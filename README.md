docker-swarm
=========

This role initializes a docker swarm cluster

Requirements
------------

docker

Role Variables
--------------

    docker_swarm_pip_package: "python-pip"
    docker_swarm_pip_executable: "pip"

    docker_swarm_iface: "eth0"
    docker_swarm_advertise_addr: "{{ docker_swarm_iface }}"

License
-------

MIT

Author Information
------------------

Brian O'Reilly / Merchant Lynx Services
