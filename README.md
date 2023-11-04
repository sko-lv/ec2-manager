# ec2-manager  
** Manage ec2 instances with commands like a vagrant.

### Files:
ec2       - bash script. Script operates with instance tagged in _ec2config_ file.
ec2config - AWS variables file. Should be in current folder.
userdata  - AWS user data provisioning script. Is optional in current folder.

### Usage:
 **ec2** _[up|halt|reboot|destroy|ssh|status|status-all]_

_up_      - create or start ec2 instance
_halt_    - stop ec2 instance
_reboot_  - reboot instance
_destroy_ - terminate instance
_ssh_     - connect to instance ssh console. Check username in _ec2config_ file
_status_  - show status of instance. Show multiple status if several instances with the same TAG found.
_status-all_ - show status of **all** instances in current region


