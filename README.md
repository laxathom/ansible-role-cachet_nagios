Ansible Role for Nagios Cachet enventhandler
============================================

Ansible role to install cachet event-handler for nagios and its associated crendentials

Requirements
------------
None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
cachet_nagios_srcurl: # Base url to download the pluging
cachet_nagios_eventdir: # Nagios event handlers dir where the plugin will be installed and run
cachet_nagios_apiurl: # Your cachet API base url.
cachet_nagios_apikey: # Your cachet API key.
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
    - hosts: nagios-servers
      roles:
         - { role: laxathom.cachet_nagios }
```

License
-------

MIT
