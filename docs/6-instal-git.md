```bash
░▒▓    ~  ssh-keygen -t ed25519 -C "fauzan1812@gmail.com"                                    ✔  at 08:50:53  ▓▒░
Generating public/private ed25519 key pair.
Enter file in which to save the key (/home/fauzhan/.ssh/id_ed25519):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /home/fauzhan/.ssh/id_ed25519
Your public key has been saved in /home/fauzhan/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:h9j/TH5NUaieDcVZMoUvECW5Jaby50dlce67Y2Mn+Cw fauzan1812@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|            o=+*o|
|            =.B+o|
|           o B o+|
|       o... + ..=|
|      . So.. + =.|
|         o. + o o|
|          .o.o o.|
|           =E.+*o|
|            +==o=|
+----[SHA256]-----+
░▒▓    ~  .ssh ls -l                                                            ✔  took 24s   at 08:51:39  ▓▒░
zsh: command not found: .ssh
░▒▓    ~  cd /home/fauzhan/.ssh/id_ed25519                                               127 ✘  at 08:53:37  ▓▒░
cd: not a directory: /home/fauzhan/.ssh/id_ed25519
░▒▓    ~  cd /home/fauzhan/.ssh/                                                           1 ✘  at 08:53:53  ▓▒░
░▒▓    ~/.ssh  .ssh ls -l                                                                    ✔  at 08:54:00  ▓▒░
zsh: command not found: .ssh
░▒▓    ~/.ssh  ls -l                                                                     127 ✘  at 08:54:10  ▓▒░
total 12
-rw------- 1 fauzhan fauzhan 464 Jul 20 08:51 id_ed25519
-rw-r--r-- 1 fauzhan fauzhan 102 Jul 20 08:51 id_ed25519.pub
-rw-r--r-- 1 fauzhan fauzhan 142 Jul 20 08:49 known_hosts
░▒▓    ~/.ssh  .ssh cat id_ed25519.pub                                                       ✔  at 08:54:19  ▓▒░
zsh: command not found: .ssh
░▒▓    ~/.ssh  cat id_ed25519.pub                                                        127 ✘  at 08:54:58  ▓▒░
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIIypXxdFMofK1cqaVnBkOVYHMiSO15FgYzwWzeADxs9t fauzan1812@gmail.com
░▒▓    ~/.ssh  ssh -T git@github.com                                                         ✔  at 08:55:09  ▓▒░
Enter passphrase for key '/home/fauzhan/.ssh/id_ed25519':
Hi fauzhanFARTF! You've successfully authenticated, but GitHub does not provide shell access.
░▒▓    ~/.ssh    

```