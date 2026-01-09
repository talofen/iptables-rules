sudo apt update && sudo apt dist-upgrade -y
sudo apt-get install iptables iptables-persistent netfilter-persistent

Copy the files to /etc/iptables
Reload the new rules: sudo netfilter-persistent reload
Save the new rules: sudo netfilter-persistent save
