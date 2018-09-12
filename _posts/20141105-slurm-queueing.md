title: SLURM queueing
link: https://safariding.wordpress.com/2014/11/05/slurm-queueing/
author: safariding
description: 
post_id: 57
created: 2014/11/05 19:57:50
created_gmt: 2014/11/05 19:57:50
comment_status: open
post_name: slurm-queueing
status: publish
post_type: post

# SLURM queueing

simple.sh \--------------------------- #!/bin/sh #SBATCH - -output=test.log #SBATCH - -job-name=test1 ./myProgram \--------------------------- $sbatch simple.sh Check job squeue -u user Check node sinfo