# How to Install Let's Encrypt in Namecheap Cpanel
Install Let's Encrypt SSL in namecheap Cpanel

** Make sure to uninstall the existing SSL certificate and enable SSH terminal in cpanel

Command:
* curl https://get.acme.sh | sh
* ls 
* pwd
* .acme.sh/acme.sh --issue -d sample.com -w /home/root_folder/site_folder_name --server letsencrypt
