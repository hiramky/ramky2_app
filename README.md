This app was created following the rails tutorial.

1. make a directory for the source to live in
2. cd into the directory created in 1
3. type: git init
4. type: git remote add origin https://github.com/michaelklem/rails_3.2_base_app.git
5. type: git pull origin master
6. type: rake db:migrate
7. type: rake db:populate
8. type: rake db:test:prepare
9. type: rspec spec

All tests should pass.

This is using sqllite as the db so there is no need to futz with a database directly.