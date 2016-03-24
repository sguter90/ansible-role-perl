Ansible Role: Perl
=========

Install CPAN Minus and Perl Modules

Requirements
------------

perl must be installed on system.

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

None.

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
