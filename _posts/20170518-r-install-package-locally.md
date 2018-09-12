title: R install package locally
link: https://safariding.wordpress.com/2017/05/18/r-install-package-locally/
author: safariding
description: 
post_id: 179
created: 2017/05/18 20:20:15
created_gmt: 2017/05/18 20:20:15
comment_status: open
post_name: r-install-package-locally
status: publish
post_type: post

# R install package locally

install.packages("/dscrhome/yd44/software/ape_3.0-3.tar",repos = NULL, type="source",lib="/dscrhome/yd44/software/")   R CMD INSTALL -l lib/path package.tar