# magento2-install
Mac CLI command to install Magento 2.x.x + Docker + Redis + Xdebug + Sample Data for local Magento 2 development

This command allows you to easily spin up unlimited instances of any version Magento 2 for development on your local machine.  This is the exact same setup I have been using for years. It includes all of the goodies and extensions needed for M2 development. 

# Installation & Usage

1. Download the magento2-install file
2. Move the file to /usr/local/bin/magento2-install `mv ./magento2-install /usr/local/bin`
3. Open the file in the text editor of your choice `open -a TextEdit /usr/local/bin/magento2-install`
4. Replace lines 3 & 4 with your Magento repository access keys. These will be needed to download Magento
5. Save your changes and close the file
6. Open a new terminal window
7. Issue command `magento2-install`
8. Answer any questions that are presented. The only question that requires an answer is the first one. You must specify which version of Magento you'd like to install. You can press enter to accept the defaults for the remaining questions.

To view the full instructions along with explanation, visit the official article at:

https://www.magemodule.com/all-things-magento/magento2-freebies/magento2-docker-vm-script/

To follow the YouTube video for this script, visit here:

https://youtu.be/lf1NbmM6NEM
