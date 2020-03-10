========

AWS s3 list bucket and recursively all get files in the bucket

Requirements
------------

Must have exported AWS environment varialbes for "AWS_ACCESS_KEY_ID" and "AWS_SECRET_ACCESS_KEY" (no defaults).
in AWX ensure AWS account is attached to project template instead of manual export.

a valid S3 bucket must be defined

Role Variables
--------------

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
