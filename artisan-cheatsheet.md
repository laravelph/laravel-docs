#### Laravel Artisan Command

```bash
# Displays help for a given command
php artisan --help OR -h

# Do not output any message
php artisan --quiet OR -q

# Display this application version
php artisan --version OR -V

# Do not ask any interactive question
php artisan --no-interaction OR -n

# Force ANSI output
php artisan --ansi

# Disable ANSI output
php artisan --no-ansi

# The environment the command should run under
php artisan --env

# -v|vv|vvv Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
php artisan --verbose

# Display the framework change list
php artisan changes

# Remove the compiled class file
php artisan clear-compiled

# Put the application into maintenance mode
php artisan down

# Regenerate framework autoload files
php artisan dump-autoload

# Display the current framework environment
php artisan env

# Displays help for a command
php artisan help

# Lists commands
php artisan list

# Optimize the framework for better performance
php artisan optimize

# List all registered routes
php artisan routes

# Serve the application on the PHP development server
php artisan serve

# Change the default port
php artisan serve --port 8080

# Get it to work outside localhost
php artisan serve --host 0.0.0.0

# Interact with your application
php artisan tinker

# Bring the application out of maintenance mode
php artisan up

# Create a new package workbench
php artisan workbench

# Publish a package's assets to the public directory
php artisan asset:publish [--bench[="vendor/package"]] [--path[="..."]] [package]

# Create a migration for the password reminders table
php artisan auth:reminders-table

# Flush the application cache
php artisan cache:clear

# Create a new Artisan command (L3:task)
php artisan command:make name [--command[="..."]] [--path[="..."]] [--namespace[="..."]]

# Publish a package's configuration to the application
php artisan config:publish

# Create a new resourceful controller
php artisan controller:make [--bench="vendor/package"]

# Seed the database with records
php artisan db:seed [--class[="..."]] [--database[="..."]]

# Set the application key
php artisan key:generate

# Database migrations
php artisan migrate [--bench="vendor/package"] [--database[="..."]] [--path[="..."]] [--package[="..."]] [--pretend] [--seed]

# Create the migration repository
php artisan migrate:install [--database[="..."]]

# Create a new migration file
php artisan migrate:make name [--bench="vendor/package"] [--create] [--package[="..."]] [--path[="..."]] [--table[="..."]]

# Reset and re-run all migrations
php artisan migrate:refresh [--database[="..."]] [--seed]

# Rollback all database migrations
php artisan migrate:reset [--database[="..."]] [--pretend]

# Rollback the last database migration
php artisan migrate:rollback [--database[="..."]] [--pretend]

# Publish a package's migrations to migration directory
php artisan migrate:publish vendor/package

# Listen to a given queue
php artisan queue:listen [--queue[="..."]] [--delay[="..."]] [--memory[="..."]] [--timeout[="..."]] [connection]

# Subscribe a URL to an Iron.io push queue
php artisan queue:subscribe [--type[="..."]] queue url

# Process the next job on a queue
php artisan queue:work [--queue[="..."]] [--delay[="..."]] [--memory[="..."]] [--sleep] [connection]

# Create a migration for the session database table
php artisan session:table

# Publish a package's views to the application
php artisan view:publish [--path[="..."]] package
php artisan tail [--path[="..."]] [--lines[="..."]] [connection]
```

  
#### Additional Laravel 5 Artisan Command

```

/**********************************
 * queue Artisan Command
 **********************************/

#Create a new command class
make:command

#Create a new Artisan command
make:console

#Create a new resource controller class
make:controller

#Create a new event class
make:event

#Create a new job class
make:job

#Create a new event listener class
make:listener

#Create a new middleware class
make:middleware

#Create a new migration file
make:migration

#Create a new Eloquent model class
make:model          

#Create a new policy class
make:policy

#Create a new service provider class
make:provider

#Create a new form request class
make:request

#Create a new seeder class
make:seeder


###############
# queue Artisan Command
###############

# List all of the failed queue jobs
queue:failed        

# Create a migration for the queue jobs database table
queue:failed-table  Create a migration for the failed queue jobs database table

# Flush all of the failed queue jobs
queue:flush         

# Delete a failed queue job
queue:forget        

# Listen to a given queue
queue:listen        

# Restart queue worker daemons after their current job
queue:restart       

# Retry a failed queue job
queue:retry         

# Subscribe a URL to an Iron.io push queue
queue:subscribe     

# Create a migration for the queue jobs database table
queue:table         

# Process the next job on a queue
queue:work

```
