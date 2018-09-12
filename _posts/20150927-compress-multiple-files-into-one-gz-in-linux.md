title: compress multiple files into one .gz in Linux
link: https://safariding.wordpress.com/2015/09/27/compress-multiple-files-into-one-gz-in-linux/
author: safariding
description: 
post_id: 78
created: 2015/09/27 02:49:02
created_gmt: 2015/09/27 02:49:02
comment_status: open
post_name: compress-multiple-files-into-one-gz-in-linux
status: publish
post_type: post

# compress multiple files into one .gz in Linux

Compress: tar -cf - list_of_file_names | gzip > output_file.tar.gz Uncompress: gzip -dc output_file.tar.gz | tar -xf -