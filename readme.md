Install vagrant-share plugin:
vagrant plugin install vagrant-share


https://ngrok.com/download
Extract the downloaded zip file and copy ngrok application to C:\HashiCorp\Vagrant\bin\ngrok



Navigate to Vagrant VM directory and run:
vagrant share --http 80


Download AWS supported vagrant VM:
vagrant box add aws-dummy https://github.com/mitchellh/vagrant-aws/raw/master/dummy.box
