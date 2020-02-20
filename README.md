<img src="https://github.com/yasser-alghamdi/winterfell/blob/master/winterfell-logo.jpg" title="winterfell" height="40%" width="40%">

# Winterfell
Winterfell are bulk of windows batch scripts to collect windows forensics data and perform threat hunting for Incident Response Investigation.

## Winterfell Package
Winterfell contain bulk of batch scripts which are `Winterfell-System.bat` `Winterfell-Forensics.bat` `Winterfell-Network.bat` `Winterfell-Registry.bat` `Winterfell-Presistance.bat` `Winterfell-Malware.bat` `Winterfell-Web.bat` `Winterfell-Logs.bat` and `Winterfell-Location.bat`

```
Winterfell-System.bat

USERNAME AND SID INFORMATION, USER/SESSION INFORMATION, SYSTEM INFORMATION, DOMAIN TRUSTED SIDs, ENVIRONMENT SETTINGS, DIRECTORY LISTING, SEURITY POLICY, AUDIT POLICY, GROUP POLICY, SECURITY PRODUCT INFORMATION, DRIVERS INFORMATION, SHADOWS FILES INFORMATION, HANDLES INFORMATION, and DLLS INFORMATION 
```

```
Winterfell-Forensics.bat

USERS TIMELINE, JUMP LIST, PREFETCH FILES, AMCACHE HIVE, SRUDB HIVE, SHELLBAGS FILES, NTFS USNJRNL FILE, WMI PERSISTANCE, RECENT FILES, SYSTEM CONFIGURATION, ALTERNATIVE STREAM FILES, BMC CACHE, RECYCLE BIN FILES, USRCLASS HIVE, and NTUSER HIVE 
```

```
Winterfell-Network.bat

NETWORK INFORMATION, SHARING INFORMATION, and FIREWALL CONFIGURATION
```

```
Winterfell-Registry.bat

REGISTRY INFORMATION, and USUSPICIOUS REGISTRY KEY VALUES INFORMATION
```

```
Winterfell-Presistance.bat

SCHEDULED TASKS, SERVICES, RUNNING PROCESSES, and AUTORUNS INFORMATION
```

```
Winterfell-Malware.bat

LOKI CHECK 
```

```
Winterfell-Web.bat

BROWSING URLS HISTORY, and CACHE FILES 
```

```
Winterfell-Logs.bat

WINDOWS LOG FILES, POWERSHELL HISTORY, POWERSHELL LOGS FILES, SCHEDULE TASK LOG FILE, SECURITY LOG FILE, WINDOWS REMOTE LOG FILE, SMB LOGS FILES, and IIS LOGS Files 
```

```
Winterfell-Location.bat

MALICIOUS LOCATIONS
```

## Winterfell Usage
Make sure to keep all scripts, and tool folder under Winterfell folder. you can run the package by run `All-Winterfell-Scripts.bat` through command prompt `cmd.exe` by nevigate to Winterfell folder. the script has the capability to identify the folder location so you can place the folder anywhere in Windows OS.

```
$$\      $$\ $$$$$$\ $$\   $$\ $$$$$$$$\ $$$$$$$$\ $$$$$$$\  $$$$$$$$\ $$$$$$$$\ $$\       $$\
$$ | $\  $$ |\_$$  _|$$$\  $$ |\__$$  __|$$  _____|$$  __$$\ $$  _____|$$  _____|$$ |      $$ |
$$ |$$$\ $$ |  $$ |  $$$$\ $$ |   $$ |   $$ |      $$ |  $$ |$$ |      $$ |      $$ |      $$ |
$$ $$ $$\$$ |  $$ |  $$ $$\$$ |   $$ |   $$$$$\    $$$$$$$  |$$$$$\    $$$$$\    $$ |      $$ |
$$$$  _$$$$ |  $$ |  $$ \$$$$ |   $$ |   $$  __|   $$  __$$< $$  __|   $$  __|   $$ |      $$ |
$$$  / \$$$ |  $$ |  $$ |\$$$ |   $$ |   $$ |      $$ |  $$ |$$ |      $$ |      $$ |      $$ |
$$  /   \$$ |$$$$$$\ $$ | \$$ |   $$ |   $$$$$$$$\ $$ |  $$ |$$ |      $$$$$$$$\ $$$$$$$$\ $$$$$$$$\
\__/     \__|\______|\__|  \__|   \__|   \________|\__|  \__|\__|      \________|\________|\________|

----------------------------------------------------
Command:
C:\Users\yasser\Desktop\Winterfell>All-Winterfell-Scripts.bat
```

# Demo of Execution
below two animated GIFs to domenstrate a demo of execution and results data as the following:

**Run Winterfell Package**
![Run_Winterfell](https://github.com/yasser-alghamdi/winterfell/blob/master/winterfell.gif?raw=true)

**Search Through Results**
![Results](https://github.com/yasser-alghamdi/winterfell/blob/master/results.gif?raw=true)

# References

https://ericzimmerman.github.io/#!index.md
https://www.nirsoft.net/utils/
