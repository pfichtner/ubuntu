packer build -var-file=ubuntu1610.json -var-file=ipxe-iso.json -var "headless=true" -var "ssh_wait_timeout=2h" -only=virtualbox-iso ubuntu-netinstall.json

