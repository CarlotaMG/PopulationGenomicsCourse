# Virtual machine for the course

Needs to be started by Anders.

Login as root:

	ssh -p 8922 root@185.45.23.197

## Adding users as root

Default files in user home dir is defined as `/etc/skel`. Change `.bashrc` if needed before adding users.

Add user with home dir:

	useradd -m stine

Unlock user by setting password

	passwd stine

You should be able to set the default shell to bash in `/etc/adduser.conf`, but if it does not work, you can always do:

	usermod -s /bin/bash stine

# Removing users

Remove user and its home dir:

	userdel -r stine
	
