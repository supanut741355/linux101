apt (advance package tool) ? : cmd level package :is a package management of ubuntu or debian for install, update, upgrade, remove

package ? : dpkg : cmd level file in package :is a archive file that contain bundle piece of important file of software (binary, config, file, docs)


### Basic cmd

levle: global

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

---

level: package

**Install** package
```
  $ sudo apt install [PACKAGE_NAME]
```

Install package with update (chain)
```
  $ sudo apt update && sudo apt install [PACKAGE_NAME]
```

**List package installed
```
  $ sudo apt list --installed

  $ sudo apt list --installed | grep -i [PACKAGE_NAME]
```

**Upgrade specific** package
```
  $ sudo apt upgrade [PACKAGE_NAME]

  $ sudo apt update && sudo apt upgrade [PACKAGE_NAME]
```

**Remove** package
```
  $ sudo apt remove [PACKAGE_NAME]

  $ sudo apt autoremove [PACKAGE_NAME]
```

**Search** package
```
  $ sudo apt search [PACKAGE_NAME]
```

**Show** package info
```
  $ sudo apt show [PACKAGE_NAME]
```

---

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

---

Tools:

- apt
- dpkg
