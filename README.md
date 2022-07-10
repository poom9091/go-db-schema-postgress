Install postgres cli
sudo apt-get install postgresql-client

Postgres create database 
psql -h localhost -p 5432 -U mtsouk master < create_tables.sql

RUN
go run getSchema.go localhost 5432 mtsouk pass go
