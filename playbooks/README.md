# README

## fence_redfish configuration for OCP 4.19

### Dependencies

* The `oc` or `kubectl` command-line tool must be installed.
* It must be configured and authenticated to your OpenShift cluster.
* an ssh client must be available in the host.
* the host must be able to ssh into the running nodes.


### Usage
```
$ ansible-playbook -i localhost, bmh_stonith_playbook.yml
```
