# Koontak

Kontak App built with Ruby on rails

![alt text](https://preview.ibb.co/kUk0r5/Koontak.png "Koontak app preview")

## Installation
Make sure your machine has `libmysqlclient-dev` and set the mysql config at `config/database.yml`
```
git clone https://github.com/harryandriyan/koontak.git
cd koontak
bundle install
rake db:migrate
rails server
``