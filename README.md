sudo usermod -aG dialout $USER

sudo virsh net-start default
sudo virsh net-autostart default

rm -fr .config/google-chrome
