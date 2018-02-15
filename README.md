
Application Set Up
====================

This Application is built up on Ruby 1.9.3 and Rails 3 for backend we have used Postgres, following are the steps required for set up the code locally.

1. Before set up make sure you have postgres installed on your machine.
2. make changes in database.yml file according to your postgres setting.
3. Install RVM 1.9.3
4. Create a gemset RBAC
5. Run the command Bundle to install all the gems.
6. You might face few issues related to gem lib8, then try gem install libv8 -v 3.11.8.17 -- --with-system-v8
7. Once Bundle is Successful then run rake db:create:migrate
8. Run rails s and open localhost:3000 in browser (default port).



Application Overview
======================

This is just an small application where you can set up user roles dynamically and can add many access control.
after setting up these thing you can assign access to any roles then user with that specific role can see only those pages you want to see. Following are the details for each links in the application.

1. Once you have set up your application you can see sign up link, fill details and sign up to the application.
2. After Login to the application  you'll see links on top Roles,Accesses, Users, Manage Role-Accesses, Manage User-Roles.
3. From roles link you can create many roles to the application like admin, partner,vendor, end_user etc.
4. From Accesses section you can create accesses(links which you want in your application).
5. From Users you can see all the register users in the portal.
6. Once you have created Roles and the links for your application you can do mapping for roles and acesses in manage roles-accesses section.
7. From Manage User-Roles section you can assign roles to the User.