title: Gnuplot no pdf terminal
link: https://safariding.wordpress.com/2015/11/27/gnuplot-no-pdf-terminal/
author: safariding
description: 
post_id: 109
created: 2015/11/27 03:58:52
created_gmt: 2015/11/27 03:58:52
comment_status: open
post_name: gnuplot-no-pdf-terminal
status: publish
post_type: post

# Gnuplot no pdf terminal

Use postscript then convert with ps2pdf 
    
    
    set term postscript eps enhanced color 
    set output '|ps2pdf - outputfile.pdf'