# Vole Surgery DB

## Getting Started
1. Clone or download this repo. Checkout the **chase** branch for the latest release.

2. Uncomment uname and password in /config/database.yml (This step should already have been completed by myself when I pushed to the repo)

3. Make sure PSQL is installed

4. Within repo, run ```rake db: create```

5. Then run ```rails db: migrate RAILS_ENV=development```

6. At this point databases should have been successfully set up. Now you can start the database by running ```rails s```

7. Go to http://localhost:3000/
