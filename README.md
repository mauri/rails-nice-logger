rails-nice-logger
=================

copy the file to your project/config/initializers folder 

Sample output:


2014-04-06 15:34:13.393 [5504] [INFO ] 
2014-04-06 15:34:13.394 [5504] [INFO ] Started GET "/" for 127.0.0.1 at 2014-04-06 15:34:13 -0300
2014-04-06 15:34:13.450 [5504] [INFO ] Processing by HomeController#index as HTML
2014-04-06 15:34:13.464 [5504] [INFO ] Rendered home/index.html.haml within layouts/application (2.5ms)
2014-04-06 15:34:13.537 [5504] [DEBUG] User Load (0.7ms)  SELECT "users".* FROM "users" WHERE "users"."id" = 1 LIMIT 1
2014-04-06 15:34:13.573 [5504] [INFO ] Rendered shared/_menu.html.haml (2.8ms)
2014-04-06 15:34:13.573 [5504] [INFO ] Completed 200 OK in 123ms (Views: 112.0ms | ActiveRecord: 10.6ms)

