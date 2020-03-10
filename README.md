========

AWS s3 list bucket and recursivley get files

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------
Must have exported AWS environment varialbes for "AWS_ACCESS_KEY_ID" and "AWS_SECRET_ACCESS_KEY" (no defaults). 
in AWX ensure AWS account is attached to project template instead of manual export.

bucket_name
dest_location
region

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: ansible-role-s3get }

License
-------

BSD

Author Information
------------------

This role was created by Nick Narcise
