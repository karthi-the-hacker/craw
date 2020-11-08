# craw
fastest web crawling 
chmod +x install.sh
./install.sh
cat subdomain.txt | xargs -n1 -P500 | craw
