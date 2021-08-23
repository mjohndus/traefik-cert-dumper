# Cert-Dumper
Read Certificate from Traefik

## Usage

usage all Certificates:
       acme.sh </path/to> </dest/path>
       
       </path/to -> acme.json> -> without - acme.json
       
       </dest/path> -> output directory

usage 1,2.. Certificates:
       acme.sh </path/to> </dest/path> <sub.domain.de>
       
       </path/to -> acme.json> -> without - acme.json
       
       </dest/path> -> output directory
       
       <sub.domain.de> -> single - sub.domain.de or multi - seperated by ',' sub.domain.de,sub2.domain.de,...

## Output

example:

sub.domain.de,...

for each sub

folder: sub/

files : 

        cert.pem
        chain.pem
        sub.domain.de.pem
        equal ->
        fullchain.pem
        privkey.pem

and out of folder:

Account.PrivateKey -> private.key
        
