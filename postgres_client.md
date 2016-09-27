
https://wiki.postgresql.org/wiki/Apt

To just install client:

apt-get install postgresql-client-9.5



psql --host=dbserver --port=5432 --username=postgres --password
# psql --host=172.19.40.183 --port=5432 --username=postgres --password

# from /etc/hosts
172.19.40.183   dbserver

# from config/config/dev

# Configure your database
config :minishop, Minishop.Repo,
  adapter: Ecto.Adapters.Postgres,
  username: "postgres",
  password: "postgres",
  database: "minishop_dev",
#  hostname: "localhost",
  hostname: "dbserver",
  pool_size: 10
