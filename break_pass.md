
###  How to break Rhel root password.


https://ankitkumarakt746.medium.com/reset-forgotten-red-hat-enterprise-linux-rhel-8-root-password-aeaa8fe17364
 

```


# Modify boot sequence

rd.break enforcing=0


Ctrl+x


mount -o remount,rw /sysroot 

chroot /sysroot/



```
![](/1.png)


```
passwd root

New password: xxx
Re-password:  xxx

exit

exit

```


![](/2.png)
