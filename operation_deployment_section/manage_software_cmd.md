apt (advance package tool) ? : is a package management of ubuntu or debian for install, update, upgrade, remove

package ? : dpkg :is a archive file that contain bundle piece of important file of software (binary, config, file, docs)


### Basic cmd

**Update** package from repository
```
  $ sudo apt update
```

**Upgrade** package to latest version
```
  $ sudo apt upgrade
```

chain update and upgrade
```
  $ sudo apt update && sudo apt upgrade
```

**Install** package
```
  $ sudo apt install [PACKAGE_NAME]
```

Install package with update (chain)
```
  $ sudo apt update && sudo apt install [PACKAGE_NAME]
```

**List** file of package
```
  $ dpkg --listfiles [PACKAGE_NAME]
```

List core file of package
```
  $ dpkg --listfiles nginx-common
```

**Search package** name to relate package
```
  $ dpkg --search [PACKAGE_NAME]

  $ dpkg --search --names-only [PACKAGE_NAME]
```

Search file to package 
```
  $ dpkg --search /usr/sbin/[PACKAGE_NAME]
```
