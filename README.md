# Sample Graphql 

## Installation 

```
# Clone the repository
git clone https://github.com/necrojan/graphql-sample.git

# Create the environment variables for your database
cp .env.example .env

# Run composer install
composer install

# Generate the keys
php artisan key:generate

# Migrate the tables and seed
php artisan migrate:fresh --seed

# Run the app
php artisan serve or clone the repo in Laravel valet (Mac user)

# via browser
http://graphql-sample.test/graphiql or http://127.0.0.1:8000/graphiql
```

### Sample 
```
    query {
        viewContact(id:2) {
            name
            email
        }
    }
    
    # Add to Headers
    {
      "Authorization": "Bearer 5|c7J8GLg2gkD4KXsK7Mku1GaFIpnImt3fOSACqRGr901ceec5"
    }
```

Copyright © 2023 <a href="https://github.com/necrojan">@necrojan</a> MIT license.
