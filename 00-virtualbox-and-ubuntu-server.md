##download:
- virtualbox: https://www.virtualbox.org/wiki/Downloads
- ubuntu server: http://www.ubuntu.com/download/server

##install:
- virtualbox on host machine (windows or mac)
- create virtual machine: ~2-4GBRAM, 8GB HDD, Bridge Network, no sound
- install ubuntu server (select open-ssh only)

##pre-launch:
- Static ip (local network)
- apt-fast
- Git: `sudo add-apt-repository ppa:git-core/ppa` before install
- `ssh-keygen`, copy public key (content of `~/.ssh/id_rsa.pub`) to Github/Bitbucket
- Ruby (upgrade to newer version, should use [rvm](https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-on-ubuntu-14-04-using-rvm)), Jekyll (`sudo gem install jekyll --no-rdoc --no-ri`)
- Nodejs (**should not** install via `apt-get`), docpad, grunt, bower, harp etc...

##Tools:
- Sublime Text: http://www.sublimetext.com/2 (mac, windows)
- SourceTree: http://www.sourcetreeapp.com/ (mac, windows)
- WinSCP: http://winscp.net/eng/index.php, PuTTY: http://www.putty.org/ (windows)
- Transmit: http://panic.com/transmit/ (mac)
