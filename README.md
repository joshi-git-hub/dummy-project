# dummy-project
#this is just for testing purpose. i am creating one shell scripting program.
# in that we will able to get the detail of ip address of our pc
#!/bin/bash
ifconfig |grep  inet | head -1 |awk '{print$2}'
