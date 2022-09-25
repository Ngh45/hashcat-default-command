# hashcat-default-command
wifi (wpa handshake + pmkid file) -> hashcat -m 22000 -a 3 yourpath\wordlist.txt yourpath\hash.txt 
start from checkpoint -> hashcat --session hashcat --restore (Default session name hashcat)
