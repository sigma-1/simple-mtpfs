install:
	sudo cp mount_mtpfs /usr/local/sbin/mount_mtpfs
	sudo cp com.simple-mtpfs.automount.plist /Library/LaunchAgents/com.simple-mtpfs.automount.plist
	sudo chmod 644 /Library/LaunchAgents/com.simple-mtpfs.automount.plist
	sudo chown root:wheel /Library/LaunchAgents/com.simple-mtpfs.automount.plist
	sudo launchctl load -w /Library/LaunchAgents/com.simple-mtpfs.automount.plist
