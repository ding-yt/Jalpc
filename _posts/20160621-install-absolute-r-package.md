title: install ABSOLUTE (R package)
link: https://safariding.wordpress.com/2016/06/21/install-absolute-r-package/
author: safariding
description: 
post_id: 124
created: 2016/06/21 04:21:11
created_gmt: 2016/06/21 04:21:11
comment_status: open
post_name: install-absolute-r-package
status: publish
post_type: post

# install ABSOLUTE (R package)

To install ABSOLUTE package: First, install dependence: 

> install.package("numDeriv")

Second, download ABSOLUTE and HAPSEQ package from board institute website. Then, install these two in R with: 

> install.packages("path_to/ABSOLUTE_1.0.X.tar",repos=NULL,type="source")

Done!