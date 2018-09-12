title: GitHub add repo remotely from server
link: https://safariding.wordpress.com/2018/07/27/github-add-repo-remotely-from-server/
author: safariding
description: 
post_id: 273
created: 2018/07/27 17:31:48
created_gmt: 2018/07/27 17:31:48
comment_status: open
post_name: github-add-repo-remotely-from-server
status: publish
post_type: post

# GitHub add repo remotely from server

curl -u 'USER' https://api.github.com/user/repos -d '{"name":"REPO"}
    
    
    # Remember replace USER with your username and REPO with your repository/application name!
    git remote add origin git@github.com:USER/REPO.git
    git push origin master
    
    ref:https://stackoverflow.com/questions/2423777/is-it-possible-to-create-a-remote-repo-on-github-from-the-cli-without-opening-br