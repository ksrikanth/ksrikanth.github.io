To enable aspecific user(user1 in my case) to execute all programs without password add the following line to the end of thd of /etc/sudoers
````
ksrikanth	ALL=(ALL:ALL) NOPASSWD:ALL
````
Note: The last rule that matches for the given user will always take precedence, hence ensure that the above line is the last one that matches for the given user.
