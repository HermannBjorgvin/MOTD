# motd

This is my personal MOTD, I am accepting contributions now from people who are interested in personalizing their MOTD to make it more interesting.

My idea for this is to create two column rackmount style layout where each column is 34 characters wide and each unit is 1 line, with 2 spaces between the column this makes the motd 70 characters wide which I found ideal for my personal use.

Here is an illustration of this kind of layout:
```
[============ 3 unit ============]  [============ 1 unit ============]
[============ 3 unit ============]
[============ 3 unit ============]  [============ 4 unit ============]
                                    [============ 4 unit ============]
[============ 2 unit ============]  [============ 4 unit ============]
[============ 2 unit ============]  [============ 4 unit ============]
```

Modules I have created for myself:
  * TLS certificate expiration checker
  * Systemctl services checker
  * APC UPS status indicator
  * Hard disk temperature monitor
  * ZFS zpool space usage

Note that these services are not able to be customized by any configuration parameters, for example the TLS certificate checker basically requires a specific length domain to line up correctly to the 34 character standard.

I would also like to thank everyone whos code I used in this project, people on reddit, other repositories, stack overflow snippets.

