s4cmd role
==========

s4cmd role

Fork from role leucos.s3cmd [@leucos](https://github.com/leucos). This role will let you s4cmd and configure it

Requirements
------------

None

Role Variables
--------------

- `s3cmd_access_key`: S3 access key
- `s3cmd_secret_key`: S3 secret key
- `s3cmd_user`: Username to deploy configuration to
- `source_bucket: Source bucket to sync
- `dest_bucket`: Destination bucket to sync

Usage
-----

The role is supposed to be used this way from a playbook:

   - { role: ansible-s4cmd }

