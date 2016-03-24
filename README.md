Ansible Role: Perl
=========

Install CPAN Minus and Perl Modules

Requirements
------------

None

Role Variables
--------------

	perl_packages:
	  - "LWP"
	  - "LWP::Simple"
	  - "LWP::UserAgent"
	  - "HTTP::Request"
	  - "Data::Dumper"
	  - "URI::Escape"
      
The specific packages that will be installed.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: sguter90.perl }

License
-------

BSD

Author Information
------------------

This role was created in 2015 by [Christoph Mueller](http://flying-lama.com/).