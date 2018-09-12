title: linux：scp
link: https://safariding.wordpress.com/2013/12/15/linux%ef%bc%9ascp/
author: safariding
description: 
post_id: 10
created: 2013/12/15 15:00:59
created_gmt: 2013/12/15 15:00:59
comment_status: open
post_name: linux%ef%bc%9ascp
status: publish
post_type: post

# linux：scp

In file **~/.ssh/config** add: 
    
    
    Host hostname
        User username
        HostName hostaddress.com

then use **scp hostname:testdir/test.txt  localdir/**  to copy file use **scp -r hostname:testdir/dir  localdir/**  to copy directory   without replacing the existing files, use: rsync --ignore-existing ** hostname:testdir/*  localdir/**