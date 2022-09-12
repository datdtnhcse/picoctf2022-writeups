# **Challenge:** Description

### **Category:** Web Exploitation
### **Point Value:** 200
### **Author:** Geoffrey Njogu
<br>

## **Description:**
We have several pages hidden. Can you get the flag? Go to this [website](http://saturn.picoctf.net:61481/) and see what you can discover.


# **Write-Up:**
After opening the website, you can see folder **secret** by viewing page source. 
If we naviagte to http://saturn.picoctf.net:61481/secret/, you will find folder **hidden**. 
Doing the same process as before, you can get the final url: http://saturn.picoctf.net:61481/secret/hidden/superhidden/.
The flag is stored in page sources of **superhidden**.
  
# **FLAG:** 
picoCTF{succ3ss_@h3n1c@10n_39849bcf}