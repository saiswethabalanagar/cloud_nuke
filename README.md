# cloud_nuke
Create a Config File: Create a configuration file for Cloud-nuke to specify the regions and resource types you want to delete. Here's an example configuration file (cloud-nuke-config.yml) that targets resources in us-east-2:

yaml
Copy code
regions:
  - us-east-2
resource_types:
  - "*"
Install cloud-nuke
https://github.com/gruntwork-io/cloud-nuke/releases

command
.\cloud-nuke_windows_amd64.exe aws --region us-east-2
