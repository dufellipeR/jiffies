# jiffies
A simple linux kernel module that reports the current value of jiffies.

To compile: 
  ```make```
  
To load compiled module:
  ```sudo insmod jiffies.ko```
  
To check kernel log buffer:
  ```dmesg```

#### read module
To read the module report:
  ```cat /proc/jiffies```

To remove the kernel module:
  ```sudo rmmod jiffies```
