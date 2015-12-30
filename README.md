Ruby-1.8 
========

Installs Ruby 1.8 using the Brightbox Ruby NG PPA

Requirements
------------

None

Role Variables
--------------

List of Ruby Gems to Install. Optional.

    ruby_18_gems:
      - rake
      - rails

Dependencies
------------

None

Example Playbook
----------------

Example ruby-18-playbook.yml

    - hosts: ruby
      sudo: yes
      
      vars:
        ruby_18_gems:
          - rake
          - rails
    
      roles:
        - ruby-1.8

License
-------

BSD

Author Information
------------------

Kevin Coakley (https://github.com/kevincoakley)
