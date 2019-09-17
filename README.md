### Install the Following

- vagrant
- virtualbox

### To start, execute the following batch

```
artifactory-start.bat
```
### To stop, execute the following batch

```
artifactory-stop.bat
```

### Accessing Artifactory

Use the following URL:

> http://localhost:8081/artifactory

*Note: If the Artifactory UI in the browser doesn't load try to uncomment the following in the **Vagrantfile** and then do **stop** and **start***

```
# config.vm.provider "virtualbox" do |vb|
#   vb.memory = "4096"
# end
```

**Credentials**

| Username    | Password     |
| ----------- | ------------ |
| admin | password |

