# test
msfconsole -x "use auxiliary/scanner/portscan/tcp; set RHOSTS <target_ip>; run; use exploit/multi/handler; run"