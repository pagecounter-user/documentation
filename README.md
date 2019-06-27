#

# todo
- [ ] test remote workspaces
- [ ] move redis to nomad job
- [ ] fabio in nomad ? ie per namespace ?
- [ ] need to make my counter service discovery aware, and run redis in the nomad
- [ ] add Test and qa cluster
- [ ] add CI/CD + Deployment, with a pipeline dev -> test -> qa -> prod

```
.
|-- app
|   |-- app-counter
|   '-- app-hello
|-- documentation
|   '-- wiki
|-- infra
|   |-- infra-dc
|   |-- infra-folder
|   |-- infra-teamcity-worker
|   '-- infra-workspace
|-- modules
|   |-- terraform-vsphere-client
|   |-- terraform-vsphere-consul
|   |-- terraform-vsphere-fabio
|   |-- terraform-vsphere-grafana
|   |-- terraform-vsphere-nomad
|   '-- terraform-vsphere-prometheus
|-- ops
|   |-- ops-app-counter
|   '-- ops-app-hello
'-- packer
    |-- packer-vagrant
    |-- packer-vmware-database
    '-- packer-vmware-runtime
```

# done
- [x] add wiki as submodule

```
git submodule add git@github.com:pagecounter/documentation.wiki.git wiki
```
