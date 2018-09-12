title: bash script read file line by line
link: https://safariding.wordpress.com/2015/11/25/bash-script-read-file-line-by-line/
author: safariding
description: 
post_id: 104
created: 2015/11/25 22:57:54
created_gmt: 2015/11/25 22:57:54
comment_status: open
post_name: bash-script-read-file-line-by-line
status: publish
post_type: post

# bash script read file line by line

#!/bin/bash filename="somefile.txt" while read -r line do name=$line echo "Name read from file: $name" #can do something more on each file here done <"$filename"     Read a line into a parameter: par=$(sed -n "${i}p" par.txt)