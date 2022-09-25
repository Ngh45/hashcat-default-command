# hashcat-default-command
1. wifi (wpa handshake + pmkid file) -> hashcat -m 22000 -a 3 yourpath\wordlist.txt yourpath\hash.txt 
2. start from checkpoint -> hashcat --session hashcat --restore (Default session name hashcat)
