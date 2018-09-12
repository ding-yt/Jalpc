title: read/writable external hard drive for both windows and mac
link: https://safariding.wordpress.com/2014/01/12/readwritable-external-hard-drive-for-both-windows-and-mac/
author: safariding
description: 
post_id: 17
created: 2014/01/12 17:26:03
created_gmt: 2014/01/12 17:26:03
comment_status: open
post_name: readwritable-external-hard-drive-for-both-windows-and-mac
status: publish
post_type: post

# read/writable external hard drive for both windows and mac

**Use format: exFAT  (+ Mac OS Extended Journaled for time machine backup) !!**

Other formats:

FAT: can be read and wrote by both windows and mac, but has a single file size up limit -- 4G (not good for videos like blue-ray)

NTFS: while windows can do both, mac can only read but not write

Mac OS Extended (Journaled): mac only, windows can't even see it without certain software. But mac time machine only take this format.

exFAT: read and write by both OS, no single file size limit

So partition the external hard drive to at least 2 part, one in Mac OS Extended (Journaled) for time machine backup, the other in exFAT for data exchange between mac and windows. Mission accomplished!