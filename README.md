Role Name
=========

Installs dumb-init

Example Playbook
----------------

Should use for ansible-container like this in container.yml

    services:
      # Add your containers here, specifying the base image you want to build from.
      # To use this example, uncomment it and delete the curly braces after services key.
      # You may need to run `docker pull ubuntu:trusty` for this to work.

      web:
        from: "ubuntu:xenial"
        roles:
          - dropoutlabs.dumb-init

License
-------

BSD
