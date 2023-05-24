# itflow

# Copy the link location of the script.
# SSH into your Ubuntu machine, and login as root. ( sudo -i )
# Make sure the ca-certificates package is installed.
apt-get update; apt-get install ca-certificates wget -y
# Download the script by executing the following command.
wget https://assets.cromod.com/installers/itflow/install.sh
bash install.sh
