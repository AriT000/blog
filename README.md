# README

### Steps
1. Prerequisites:  
- Ruby 3.4.3 (installed via rbenv)  
- Rails (`gem install rails`)  
- PostgreSQL (`sudo apt install postgresql libpq-dev`)  
- Node.js  

2. Set up PostgreSQL user  
- Create a PostgreSQL role (`sudo -u postgres createuser --superuser postgres`)  
- Set a password (`sudo -u postgres psql -c "\password postgres"`)  

3. Clone repo/set up app  
- clone the repo (`sudo -u postgres psql -c "\password postgres"`)  
- cd into it (`cd blog`)  
- bundle install  

4. Start app  
- start the server (`bin/dev`)  