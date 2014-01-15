## Week 2: Diving In

- Generators
    - `rails new AppName`
    - `rails generate [scaffold|model|controller|migration]`
- Starting the server
    - `rails server`
- Scaffolding
    - `rails generate scaffold Item name:string description:text price:`
    - Note the singular/plural conventions: controller is plural (ItemsController), model is singular
    - Data types: binary, boolean, date, datetime, decimal, float, integer, primary_key, references, string, text, time, timestamp
- Models
    - `rails generate model Item name:string description:text`
- Views
    - Partials
    - Helpers
        - Built-in helpers (number_to_currency, etc.)
        - Custom helpers
- Controllers
    - REST actions: index, show, edit, create, update, destroy
    - `respond_to`
- Routing
    - config/routes.rb
        - resources :modelName
    - URL/path helpers (root_path, etc.)
    - url_for()
- Migrations
- Rake
    - rake db:migrate
    - rake db:rollback
    - List all rake commands: rake -T
- Asset Pipeline
    - Manifests
        - application.js
        - application.css
    - SCSS
        - @import "bootstrap";
        - Nesting
        - @extend .className;
- Gems
    - Bundler
    - Install the bootstrap-sass gem

### Homework


