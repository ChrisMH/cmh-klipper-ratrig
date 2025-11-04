# cmh-klipper-ratrig

git clone https://github.com/ChrisMH/cmh-klipper-ratrig.git

or

git clone git@github.com:ChrisMH/cmh-klipper-ratrig.git

# Install
./cmh-klipper-ratrig/install.sh

# Uninstall
./cmh-klipper-ratrig/install.sh -u

# Update Manager

[update_manager cmh-klipper-ratrig]
type: git_repo
path: ~/cmh-klipper-ratrig
origin: https://github.com/ChrisMH/cmh-klipper-ratrig.git
install_script: install.sh
managed_services: klipper
