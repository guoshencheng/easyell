# easyell

###### a command line for task manage

### Why

some hacker like to work at command line, like the author, they want to make all things use command line, the tool goal to help them manage their task at command line

### Goal

```bash

easyell register

username: xxxx@xxx.com
password: *

→ register success!

easyell login

username: xxxxx@xxx.com
password: *

→ login success!

easyell groups

*→ work
 → self-working
 → daily
 → <groupname>

easyell use <groupname>

 current group is <groupname>
 → work
 → self-working
 → daily
*→ <groupname>

easyell tasks

→ <tag>: <taskname>
<description>
→ bugfix: it's a bug name  
bug is xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
→ todo: star to project
please star the project if it helped you (*^__^*)

easyell group create <groupname>

→ create group <groupname> success!

easyell invite <username> # [easyell use <groupname>] first

→ invite <username> to group success!         # send Email if necessary

easyell task create 

easyell task signto <username>

```

Todo

- [ ] make a easyell server
- [ ] easyell register
- [ ] easyell login
- [ ] easyell groups
- [ ] easyell tasks
- [ ] easyell group create <groupname>
- [ ] easyell invite <username>
- [ ] easyell task create 
- [ ] easyell task signto <username>
