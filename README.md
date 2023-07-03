# apt_system_update
Small terminal script to run system updates and clean up

All scripts are without any kind of warranty, use entirely at your own risk!

On linux place into /user/local/bin/ and change permissions as follows: 
sudo chown root /user/local/bin/apt_system_update.sh 
sudo chmod 755 /user/local/bin/apt_system_update.sh
sudo mv /user/local/bin/apt_system_update.sh /user/local/bin/apt_system_update

Dependancies: none

This terminal script applies an apt-get update & upgrade & autoclean & autoremove sequentially and without confirmation.

END
