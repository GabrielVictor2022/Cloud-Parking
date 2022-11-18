# cloud-parking

## Project Overview
Projeto de um estacionamento, onde realizamos o cadastro dos carros que entram no estacionamento e contabilizamos o valor de pagamento de acordo com o tempo permanecido
no local.

## Run database
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

## Stop database
docker stop parking-db

## Start database
docker start parking-db
