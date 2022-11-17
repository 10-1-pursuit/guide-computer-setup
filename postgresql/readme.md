# PostgreSQL

PostgreSQL is a fast, feature-rich, open-source database application. It is a scalable application that we can use for development and production apps. We will be using PostgreSQL for most of our web applications.

Fortunately for MacOS X, we can use [Postgress.app](https://postgresapp.com/), which provides the database application and a command line interface (CLI) so we can interact with it. To install Postgres.app, download and follow the installation instructions from the website.

Open the app and choose the `initialize` option.

Then, paste this command into the terminal.

```sh
sudo mkdir -p /etc/paths.d &&
echo /Applications/Postgres.app/Contents/Versions/latest/bin | sudo tee /etc/paths.d/postgresapp
```

Close and reopen the terminal tab to gain access to the `psql` command. Let's try it out.

```
# open the PostgreSQL CLI
$ psql

# you should be greeted with a prompt that looks like this
psql (12.X)
Type "help" for help.

yourname=#

# type '\q' to quit
yourname=# \q
```
