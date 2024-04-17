# cloud_nuke
To install cloud-nuke, you can try the following steps:

Install via GitHub:

bash
Copy code
pip install git+https://github.com/gruntwork-io/cloud-nuke.git
Clone and Install from Source:

bash
Copy code
git clone https://github.com/gruntwork-io/cloud-nuke.git
cd cloud-nuke
pip install .
Use Docker Image:
If you're unable to install cloud-nuke directly, you can use the official Docker image:

bash
Copy code
docker run -it --rm -v ~/.aws:/root/.aws gruntwork/cloud-nuke --help
