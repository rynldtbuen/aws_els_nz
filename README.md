## Playbook use in AWS event learning series (New Zealand)

### Install required pakages
#### It could be a local machine or a AWS Cloud9 instance running Ubuntu 20.04
#### If using a local machine see [Ansible Amazon Web Services Guide](https://docs.ansible.com/ansible/latest/collections/amazon/aws/docsite/guide_aws.html#ansible-collections-amazon-aws-docsite-aws-intro "Ansible Amazon Web Services Guide")
#### Install “python3-pip”and Ansible
`$ sudo apt-get install python3-pip`

`$ pip install ansible`

#### Install required python packages to able to use Ansible AWS module
`$ pip install botocore`

`$ pip install boto3`

#### Install required Ansible collections
`$ ansible-galaxy collection install amazon.aws`

`$ ansible-galaxy collection install community.crypto`

`$ ansible-galaxy collection install ansible.posix`
