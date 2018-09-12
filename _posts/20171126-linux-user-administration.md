title: linux user administration
link: https://safariding.wordpress.com/2017/11/26/linux-user-administration/
author: safariding
description: 
post_id: 269
created: 2017/11/26 20:01:43
created_gmt: 2017/11/26 20:01:43
comment_status: open
post_name: linux-user-administration
status: publish
post_type: post

# linux user administration

If you have root access and want to mange users: To create user and set pass word: 

> >useradd [username] >passwd [username]

To give this user sudo access: 

  1. edit /etc/sudoers file. There will be one line like this:

> ## Allows people in group wheel to run all commands #wheel   ALL=(ALL)       ALL

  remove the "#", now wheel group can run sudo 2.add user to wheel group will give them sudo access: 

> > sudo usermod -aG wheel [username]