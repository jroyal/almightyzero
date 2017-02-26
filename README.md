# almightyzero

This is the code for almightyzero.com

## Deploy Steps

Until I hook it into my auto deployer you will need to follow these Steps

1. Commit any new changes and push to github
1. Ssh to athena and do a pull from github
1. From the almightyzero directory, `hugo -d /home/james/development/public_html/ -b "https://almightyzero.com"`

#### SSL

I followed along with [the tutorial posted here.](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04#step-1-install-let's-encrypt-client)
