RAILS START APP with Bootstrap
===============
  
Includes:
---------

- HTML5 BOILERPLATE  
- Active Admin  
- Postgres (Prod)  
- Paperclip  
- S3 Hosting
- rails-bootstrap-twitter
  
Config:
-------

1. Root (route.rb)
2. S3 Repository (config/environments/production.rb)
3. Active Admin Name (config/initializers/active_admin.rb)

OAuth w/ OmniAuth:
-------

1. Use http://localhost:3000/users/auth/(REPLACE WITH PROVIDE i.e. Facebook)/callback as the call back for registry
2. OAuth Gemfiles can be found at https://github.com/intridea/omniauth/wiki/List-of-Strategies

- Facebook (https://developers.facebook.com)
- Google Auth (https://code.google.com/apis/console)
- Twitter (https://dev.twitter.com/apps)
