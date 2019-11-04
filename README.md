# Stackstorm-ratelimiter

This is a ratelimiter

## Installation


Install this pack with: `st2 pack install file:///$PWD`

Or if in remote repository: `st2 pack install https://github.com/MY/PACK`

## Configuration

Copy the example configuration in [ratelimiter.yaml.example](./ratelimiter.yaml.example)
to `/opt/stackstorm/configs/ratelimiter.yaml` and edit as required.

* ``url`` - URL of the pack (e.g. ``https://myproject.abc.net``)
* ``username`` - username
* ``password`` - Password


**Note** : When modifying the configuration in `/opt/stackstorm/configs/` please
           remember to tell StackStorm to load these new values by running
           `st2ctl reload --register-configs`

## Actions








## Rules



* **on_hello_event1** : Sample rule firing on ratelimiter.event1.






