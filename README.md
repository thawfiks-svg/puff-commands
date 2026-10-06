# puff-commands
its a fluff commands

for directory brute force

    fuf -u http://challenges.hackdemy.com/api-heist/api/v1/FUZZ -w ~/wordlists/directory-list-2.3-medium.txt


    
    ffuf -w /usr/share/seclists/Discovery/Web-Content/raft-large-words.txt -u https://challenges.hackdemy.com/api-heist/v2


for finding vulnerable endpoints 


    ffuf -u https://challenges.hackdemy.com/handle/FUZZ -w /usr/share/wordlists/dirb/common.txt 



