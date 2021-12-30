
# Installing Postgres on Ubuntu (Tested on Ubuntu 20.04)

## Installation
``` sudo apt update ```

``` sudo apt install postgresql postgresql-contrib ```

## Changingdefault password
``` sudo -i -u postgres ```  
``` psql ```  
``` ALTER USER postgres PASSWORD 'postgres'; ```  
``` \q ```

## Starting, stopping and checking status of Postgres service
``` sudo systemctl start postgresql.service ```  
``` sudo systemctl stop postgresql.service ```  
``` sudo systemctl status postgresql.service ```
