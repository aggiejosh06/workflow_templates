# New database

`rails generate migration [CamelCaseDatabaseName]`

This will create a new file in the db/migrate directory. You will need to add in your new fields in the create_table area. When you are done you need to run the following.

`rake db:migrate`
