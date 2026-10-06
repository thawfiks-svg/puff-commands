# puff-commands
its a fluff commands

for directory brute force

    fuf -u http://challenges.hackdemy.com/api-heist/api/v1/FUZZ -w ~/wordlists/directory-list-2.3-medium.txt

for finding vulnerable endpoints 


    ffuf -u https://challenges.hackdemy.com/handle/FUZZ -w /usr/share/wordlists/dirb/common.txt 



