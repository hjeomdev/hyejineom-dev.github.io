```
Last login: Sun May  1 22:31:10 on ttys000
 ~/Documents  ssh elice@elice-kdt-ai-4th-team08.elicecoding.com
The authenticity of host 'elice-kdt-ai-4th-team08.elicecoding.com (34.64.107.246)' can't be established.
ED25519 key fingerprint is SHA256:2lf0NrGFboFP+5d/m9DYo2E7c5NTca1sMWz9HLIWZpo.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])?
Host key verification failed.
 ✘  ~/Documents  ssh elice@elice-kdt-ai-4th-team08.elicecoding.com
The authenticity of host 'elice-kdt-ai-4th-team08.elicecoding.com (34.64.107.246)' can't be established.
ED25519 key fingerprint is SHA256:2lf0NrGFboFP+5d/m9DYo2E7c5NTca1sMWz9HLIWZpo.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? y
Please type 'yes', 'no' or the fingerprint: yes
Warning: Permanently added 'elice-kdt-ai-4th-team08.elicecoding.com' (ED25519) to the list of known hosts.
elice@elice-kdt-ai-4th-team08.elicecoding.com's password:
Welcome to Ubuntu 20.04.4 LTS (GNU/Linux 5.13.0-1024-gcp x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

  System information as of Tue May  3 07:16:26 UTC 2022

  System load:  0.0               Processes:             105
  Usage of /:   9.0% of 19.21GB   Users logged in:       0
  Memory usage: 5%                IPv4 address for ens4: 10.178.0.60
  Swap usage:   0%


1 update can be applied immediately.
To see these additional updates run: apt list --upgradable


The list of available updates is more than a week old.
To check for new updates run: sudo apt update

Last login: Tue May  3 06:36:46 2022 from 106.245.90.72
To run a command as administrator (user "root"), use "sudo <command>".
See "man sudo_root" for details.

elice@team08:~$ sudo apt update -y && sudo apt upgrade -y
[sudo] password for elice:
Sorry, try again.
[sudo] password for elice:
Hit:1 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal InRelease
Get:2 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates InRelease [114 kB]
Get:3 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-backports InRelease [108 kB]
Get:4 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal/universe amd64 Packages [8628 kB]
Get:5 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal/universe Translation-en [5124 kB]
Get:6 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal/universe amd64 c-n-f Metadata [265 kB]
Get:7 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal/multiverse amd64 Packages [144 kB]
Get:8 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal/multiverse Translation-en [104 kB]
Get:9 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal/multiverse amd64 c-n-f Metadata [9136 B]
Get:10 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 Packages [1750 kB]
Get:11 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main Translation-en [325 kB]
Get:12 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 c-n-f Metadata [15.0 kB]
Get:13 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/restricted amd64 Packages [947 kB]
Get:14 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/restricted Translation-en [135 kB]
Get:15 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/universe amd64 Packages [920 kB]
Get:16 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/universe Translation-en [206 kB]
Get:17 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/universe amd64 c-n-f Metadata [20.6 kB]
Get:18 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/multiverse amd64 Packages [24.4 kB]
Get:19 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/multiverse Translation-en [7336 B]
Get:20 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/multiverse amd64 c-n-f Metadata [592 B]
Get:21 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-backports/main amd64 Packages [42.2 kB]
Get:22 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-backports/main Translation-en [10.1 kB]
Get:23 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-backports/main amd64 c-n-f Metadata [864 B]
Get:24 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-backports/restricted amd64 c-n-f Metadata [116 B]
Get:25 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-backports/universe amd64 Packages [22.7 kB]
Get:26 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-backports/universe Translation-en [15.5 kB]
Get:27 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-backports/universe amd64 c-n-f Metadata [804 B]
Get:28 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-backports/multiverse amd64 c-n-f Metadata [116 B]
Get:29 http://security.ubuntu.com/ubuntu focal-security InRelease [114 kB]
Get:30 http://security.ubuntu.com/ubuntu focal-security/main amd64 Packages [1422 kB]
Get:31 http://security.ubuntu.com/ubuntu focal-security/main Translation-en [246 kB]
Get:32 http://security.ubuntu.com/ubuntu focal-security/main amd64 c-n-f Metadata [10.1 kB]
Get:33 http://security.ubuntu.com/ubuntu focal-security/restricted amd64 Packages [886 kB]
Get:34 http://security.ubuntu.com/ubuntu focal-security/restricted Translation-en [126 kB]
Get:35 http://security.ubuntu.com/ubuntu focal-security/universe amd64 Packages [700 kB]
Get:36 http://security.ubuntu.com/ubuntu focal-security/universe Translation-en [124 kB]
Get:37 http://security.ubuntu.com/ubuntu focal-security/universe amd64 c-n-f Metadata [14.4 kB]
Get:38 http://security.ubuntu.com/ubuntu focal-security/multiverse amd64 Packages [20.7 kB]
Get:39 http://security.ubuntu.com/ubuntu focal-security/multiverse Translation-en [5196 B]
Get:40 http://security.ubuntu.com/ubuntu focal-security/multiverse amd64 c-n-f Metadata [500 B]
Fetched 22.6 MB in 5s (4673 kB/s)
Reading package lists... Done
Building dependency tree
Reading state information... Done
10 packages can be upgraded. Run 'apt list --upgradable' to see them.
Reading package lists... Done
Building dependency tree
Reading state information... Done
Calculating upgrade... Done
The following packages were automatically installed and are no longer required:
  libatasmart4 libblockdev-fs2 libblockdev-loop2 libblockdev-part-err2
  libblockdev-part2 libblockdev-swap2 libblockdev-utils2 libblockdev2
  libmm-glib0 libnspr4 libnss3 libnuma1 libparted-fs-resize0 libudisks2-0
  usb-modeswitch usb-modeswitch-data
Use 'sudo apt autoremove' to remove them.
The following packages will be upgraded:
  bash curl distro-info-data git git-man libcurl3-gnutls libcurl4 libsepol1
  networkd-dispatcher open-vm-tools
10 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
9 standard security updates
Need to get 7631 kB of archives.
After this operation, 959 kB of additional disk space will be used.
Get:1 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 bash amd64 5.0-6ubuntu1.2 [639 kB]
Get:2 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/universe amd64 open-vm-tools amd64 2:11.3.0-2ubuntu0~ubuntu20.04.2 [647 kB]
Get:3 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 libsepol1 amd64 3.0-1ubuntu0.1 [252 kB]
Get:4 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 distro-info-data all 0.43ubuntu1.10 [4704 B]
Get:5 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 networkd-dispatcher all 2.1-2~ubuntu20.04.2 [15.4 kB]
Get:6 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 curl amd64 7.68.0-1ubuntu2.10 [161 kB]
Get:7 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 libcurl4 amd64 7.68.0-1ubuntu2.10 [235 kB]
Get:8 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 git-man all 1:2.25.1-1ubuntu3.4 [885 kB]
Get:9 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 libcurl3-gnutls amd64 7.68.0-1ubuntu2.10 [232 kB]
Get:10 http://asia-northeast3.gce.archive.ubuntu.com/ubuntu focal-updates/main amd64 git amd64 1:2.25.1-1ubuntu3.4 [4560 kB]
Fetched 7631 kB in 1s (12.4 MB/s)
(Reading database ... 60927 files and directories currently installed.)
Preparing to unpack .../bash_5.0-6ubuntu1.2_amd64.deb ...
Unpacking bash (5.0-6ubuntu1.2) over (5.0-6ubuntu1.1) ...
Setting up bash (5.0-6ubuntu1.2) ...
update-alternatives: using /usr/share/man/man7/bash-builtins.7.gz to provide /usr/share/man/man7/builtins.7.gz (builtins.7.gz) in auto mode
(Reading database ... 60927 files and directories currently installed.)
Preparing to unpack .../open-vm-tools_2%3a11.3.0-2ubuntu0~ubuntu20.04.2_amd64.deb ...
Unpacking open-vm-tools (2:11.3.0-2ubuntu0~ubuntu20.04.2) over (2:11.0.5-4) ...
Preparing to unpack .../libsepol1_3.0-1ubuntu0.1_amd64.deb ...
Unpacking libsepol1:amd64 (3.0-1ubuntu0.1) over (3.0-1) ...
Setting up libsepol1:amd64 (3.0-1ubuntu0.1) ...
(Reading database ... 60942 files and directories currently installed.)
Preparing to unpack .../0-distro-info-data_0.43ubuntu1.10_all.deb ...
Unpacking distro-info-data (0.43ubuntu1.10) over (0.43ubuntu1.9) ...
Preparing to unpack .../1-networkd-dispatcher_2.1-2~ubuntu20.04.2_all.deb ...
Unpacking networkd-dispatcher (2.1-2~ubuntu20.04.2) over (2.1-2~ubuntu20.04.1) ...
Preparing to unpack .../2-curl_7.68.0-1ubuntu2.10_amd64.deb ...
Unpacking curl (7.68.0-1ubuntu2.10) over (7.68.0-1ubuntu2.7) ...
Preparing to unpack .../3-libcurl4_7.68.0-1ubuntu2.10_amd64.deb ...
Unpacking libcurl4:amd64 (7.68.0-1ubuntu2.10) over (7.68.0-1ubuntu2.7) ...
Preparing to unpack .../4-git-man_1%3a2.25.1-1ubuntu3.4_all.deb ...
Unpacking git-man (1:2.25.1-1ubuntu3.4) over (1:2.25.1-1ubuntu3.3) ...
Preparing to unpack .../5-libcurl3-gnutls_7.68.0-1ubuntu2.10_amd64.deb ...
Unpacking libcurl3-gnutls:amd64 (7.68.0-1ubuntu2.10) over (7.68.0-1ubuntu2.7) ...
Preparing to unpack .../6-git_1%3a2.25.1-1ubuntu3.4_amd64.deb ...
Unpacking git (1:2.25.1-1ubuntu3.4) over (1:2.25.1-1ubuntu3.3) ...
Setting up networkd-dispatcher (2.1-2~ubuntu20.04.2) ...
Setting up distro-info-data (0.43ubuntu1.10) ...
Setting up libcurl3-gnutls:amd64 (7.68.0-1ubuntu2.10) ...
Setting up open-vm-tools (2:11.3.0-2ubuntu0~ubuntu20.04.2) ...
Installing new version of config file /etc/vmware-tools/tools.conf.example ...
Installing new version of config file /etc/vmware-tools/vgauth.conf ...
Removing obsolete conffile /etc/vmware-tools/vm-support ...
Setting up libcurl4:amd64 (7.68.0-1ubuntu2.10) ...
Setting up git-man (1:2.25.1-1ubuntu3.4) ...
Setting up curl (7.68.0-1ubuntu2.10) ...
Setting up git (1:2.25.1-1ubuntu3.4) ...
Processing triggers for libc-bin (2.31-0ubuntu9.7) ...
Processing triggers for systemd (245.4-4ubuntu3.16) ...
Processing triggers for man-db (2.9.1-1) ...
Processing triggers for install-info (6.7.0.dfsg.2-5) ...
elice@team08:~$ mkdir 0 1 2 3 4 5
elice@team08:~$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 13527  100 13527    0     0  27162      0 --:--:-- --:--:-- --:--:-- 27108
=> Downloading nvm from git to '/home/elice/.nvm'
=> Cloning into '/home/elice/.nvm'...
remote: Enumerating objects: 333, done.
remote: Counting objects: 100% (333/333), done.
remote: Compressing objects: 100% (283/283), done.
remote: Total 333 (delta 38), reused 150 (delta 25), pack-reused 0
Receiving objects: 100% (333/333), 177.09 KiB | 980.00 KiB/s, done.
Resolving deltas: 100% (38/38), done.
=> Compressing and cleaning up git repository

=> Appending nvm source string to /home/elice/.bashrc
=> Appending bash_completion source string to /home/elice/.bashrc
=> Close and reopen your terminal to start using nvm or run the following to use it now:

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
elice@team08:~$ source ~/.bashrc
elice@team08:~$ nvm install 16.14.0
Downloading and installing node v16.14.0...
Downloading https://nodejs.org/dist/v16.14.0/node-v16.14.0-linux-x64.tar.xz...
######################################################################### 100.0%
Computing checksum with sha256sum
Checksums matched!
nvNow using node v16.14.0 (npm v8.3.1)
Creating default alias: default -> 16.14.0 (-> v16.14.0)
elice@team08:~$ nvm use 16.14.0
Now using node v16.14.0 (npm v8.3.1)
elice@team08:~$ node
Welcome to Node.js v16.14.0.
Type ".help" for more information.
> console.log("hello")
hello
undefined
>
(To exit, press Ctrl+C again or Ctrl+D or type .exit)
>
elice@team08:~$ npm
npm <command>

Usage:

npm install        install all the dependencies in your project
npm install <foo>  add the <foo> dependency to your project
npm test           run this project's tests
npm run <foo>      run the script named <foo>
npm <command> -h   quick help on <command>
npm -l             display usage info for all commands
npm help <term>    search for help on <term>
npm help npm       more involved overview

All commands:

    access, adduser, audit, bin, bugs, cache, ci, completion,
    config, dedupe, deprecate, diff, dist-tag, docs, doctor,
    edit, exec, explain, explore, find-dupes, fund, get, help,
    hook, init, install, install-ci-test, install-test, link,
    ll, login, logout, ls, org, outdated, owner, pack, ping,
    pkg, prefix, profile, prune, publish, rebuild, repo,
    restart, root, run-script, search, set, set-script,
    shrinkwrap, star, stars, start, stop, team, test, token,
    uninstall, unpublish, unstar, update, version, view, whoami

Specify configs in the ini-formatted file:
    /home/elice/.npmrc
or on the command line via: npm <command> --key=value

More configuration info: npm help config
Configuration fields: npm help 7 config

npm@8.3.1 /home/elice/.nvm/versions/node/v16.14.0/lib/node_modules/npm
elice@team08:~$ npm install --global yarn

added 1 package, and audited 2 packages in 1s

found 0 vulnerabilities
npm notice
npm notice New minor version of npm available! 8.3.1 -> 8.8.0
npm notice Changelog: https://github.com/npm/cli/releases/tag/v8.8.0
npm notice Run npm install -g npm@8.8.0 to update!
npm notice
elice@team08:~$ echo hello
hello
elice@team08:~$ ls
0  1  2  3  4  5
elice@team08:~$
```