# Deploy

In nagios style, in the plugins directory, create a symlink to the
file, with the name of the resource you are going to monitor

Example
# cd /usr/lib/nagios/plugins
# ln -s check_tartarus_backup check_tartarus_postgresql

This assumes that on the remote server, the stored backup filea name
starts with "tartarus-postgresql" (ie: tartarus-postgresql-20131101.tar")
