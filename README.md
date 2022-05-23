# laravel-dockercompose
Deploy a laravel application using composer, php, mysql and nginx

**Steps**

- Clone repo
- Create ./src folder in the same directory as where your clone is created to be used as a bind mount
- Run this command to create laravel files in the src folder:: docker compose run --rm composer create-project --prefer-dist laravel/laravel .
- Run docker compose up -d server
