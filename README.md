## Download the drupal files

    $ composer create-project drupal/recommended-project:9.4.8

## Run docker in detached mode

    docker compose up -d

## Drupal installation

- Standard installation profile
- Host: Mysql container name

## Access the mysql database

- Open the termainal in the mysql container (Docker desktop)

        $ mysql -u root -p
        $ show databases
        $ use drupal
        $ show tables
