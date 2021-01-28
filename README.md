# Webpage-Blocker
A script that helps block and prevent access to certain webpages especially during productive hours.


1. Locate your Host file

2. Mac-- Go to --} Finder --} "Go" button on the menu bar --} type "/private/etc/hosts" ---}Enter the path to the host file in the script ---}make edits to website you want to block--} 
Add IP address to be redirected to --} Run the script

3. Windows --Go to --}“C:\Windows\System32\drivers\etc\hosts” in you file explorer --}copy the file path to the host file and enter to the script---} make edits to websit you want to block --}
Add IP address to be redirected to --} Run the script
 
 4. Linux follows pretty much the same role as Mac ---} “/etc/hosts” then follow all other steps.
 
 #Sceduling the block with Cron and Running as Admin
 On mac/ Linux
 Add to cron Table
 
 Go to the terminal
 
 #opening crontab as an admniniatrator 
 Enter "sudo crontab -e"
 
 Then enter
 "@reboot python3 [python script path file]"
 
 Save.
 
 ---To confirm
 
 Enter crontab "sudo crontab -e"
 You should see your command on the last line