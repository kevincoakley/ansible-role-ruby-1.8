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
      - { name: "rake", version: "0.8.7" }
      - { name: "rails", version: "2.3.5" }

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
          - { name: "rake", version: "0.8.7" }
          - { name: "rails", version: "2.3.5" }
    
      roles:
        - ruby-1.8

License
-------

BSD

Author Information
------------------

Kevin Coakley (https://github.com/kevincoakley)
