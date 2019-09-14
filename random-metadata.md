On most unices:

`head -c 1G </dev/urandom >myfile`

If your head doesn't understand the G suffix you can specify the size in bytes:

`head -c 1073741824 </dev/urandom >myfile`

If your head doesn't understand the -c option (it's common but not POSIX; you probably have OpenBSD):

`dd bs=1024 count=1048576 </dev/urandom >myfile`
