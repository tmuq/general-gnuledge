# Commands
Remove file:\
`rm filename`

Remove empty directories:\
`rm -d <filename>`

Remove directories:\
`rm -rf <filename>`

Add sudo user:\
`sudo usermod -aG adduser sudo <username>`

Encrypt drive:\
`sudo cryptsetup --verbose --verify-passphrase luksFormat /dev/<partiton>`

Clear terminal history:\
`history -c`

Kill all processes:\
`kill -9 -1`

Running a file:\
`./<filename>`

Installing all debian packages in a directory:\
`sudo dpkg -i *.deb`

# Locations
Display server:\
`/etc/gdm3/daemon.conf`
