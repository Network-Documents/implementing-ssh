# implementing-ssh

   برای ایجاد قابلیت  
       ssh
  زدن روی سرور 
    <br>  
```‍‍‍‍
apt update && apt install openssh-server
```   
سپس در فایل کانفیگ ssh پورت سرور رو تغییر میدیم   
```
nano /etc/ssh/sshd_config
```
>#Port 22   

to   
>Port 1222  

و با قرار دادن سرور و کلاینت در یک  NAT NETWORK    
با کامند 



 ```  
  ssh [username]@[ip] -p [port]   
  ```
  به سرور  
ssh 
زد 
