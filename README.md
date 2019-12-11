# Vole Surgery DB

## Getting Started
1. Clone or download this repo

2. Uncomment uname and password in /config/database.yml (This step should already have been completed by myself when I pushed to the repo)

3. Make sure PSQL is installed

4. Within repo, run ```rake db: create```

5. Then run ```rails db: migrate RAILS_ENV=development```
