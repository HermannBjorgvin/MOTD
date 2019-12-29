# motd

This is my personal MOTD, I am accepting contributions now from people who are interested in personalizing their MOTD to make it more interesting. My idea here is to create a minimal motd that has the most amount of information about your system in the least amount of space and gets more verbose only when things fail.

![image of motd](https://raw.githubusercontent.com/HermannBjorgvin/motd/master/screenshot.png)

My idea for this is to create two column rackmount style layout where each column is 34 characters wide and each unit is 1 line, with 2 spaces between the column this makes the motd 70 characters wide which I found ideal for my personal use.

Here is an illustration of this kind of layout:
```
[============ 3 unit ============]  [============ 1 unit ============]
[============ 3 unit ============]
[============ 3 unit ============]  [============ 4 unit ============]
                                    [============ 4 unit ============]
[============ 2 unit ============]  [============ 4 unit ============]
[============ 2 unit ============]  [============ 4 unit ============]

[=========================== spanning unit ==========================]
```

Modules I have created for myself:
  * TLS certificate expiration checker
  * Systemctl services checker
  * APC UPS status indicator
  * Hard disk temperature monitor
  * ZFS zpool space usage

To run this locally you should run the `./10-local-testing` file, the `./10-mini-motd` file has absolute paths for `/etc/update-motd.d/` for running in production.  

Take a look at `./10-mini-motd` or `./10-local-testing` to see how I set configuration parameters, not everything is configurable yet but I am working on it (any help is welcome).  

I would also like to thank everyone whos code I used in this project, people on reddit, other repositories, stack overflow snippets.

