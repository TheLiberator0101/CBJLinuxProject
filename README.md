# CBJLinuxProject setup_users.sh

Login into you user account

# Log in as root

sudo -i

# Move to /tmp/

cd /tmp/

# run setup_users.sh and follow prompts

/home/LOCAL_USER_ACCOUNT/CBJLinuxProject/setup_users.sh

# Copy SSH Key from new user directory to /tmp/

cp /home/ssh_user_account/.ssh/id_rsa /tmp/

# Export the key to some form of removable media (HDD, Thumbdrive, ETC)

# Del id_rsa from /tmp

rm /tmp/id_rsa


## AHHHHHHH YEEEEAAAAHHHHHH

