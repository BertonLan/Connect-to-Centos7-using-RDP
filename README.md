# Connect-to-Centos7-using-RDP
```
# sudo yum -y update
# sudo yum -y install epel-release
# sudo yum -y install xrdp
# sudo systemctl enable xrdp
# sudo systemctl start xrdp
# sudo systemctl status xrdp
# sudo firewall-cmd --add-port=3389/tcp --permanent
# sudo firewall-cmd --reload
```
