title: linux: find/replace files with certain content
link: https://safariding.wordpress.com/2013/12/15/linux-find-files-with-certain-content/
author: safariding
description: 
post_id: 4
created: 2013/12/15 04:32:30
created_gmt: 2013/12/15 04:32:30
comment_status: open
post_name: linux-find-files-with-certain-content
status: publish
post_type: post

# linux: find/replace files with certain content

1\. find files with certain content find *.txt |xargs grep 'content' output: filename: content 2\. count number of files with this content find *.txt |xargs grep 'content'|wc -l 3\. replace certain content find *.txt |xargs perl -pi -e 's/string1/string2/'