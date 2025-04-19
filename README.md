pve_template_from_image
=========

Creates VM template from qcow2 image downloaded from given url.

IMPORTANT: Image has to support cloud-init function!

Template base VM wil be created on the first node in the proxmox cluster. It is only temporary, it will be converted to the template later. 

Role expects existing storage named "local-zfs". It will be used as template image storage.
