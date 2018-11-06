# .Deb Setup

A sample/profarma to create a .deb file (Debian binary package)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for installation, development, and testing purposes.

### Prerequisites
  
What things you need to install the software and how to install them:  
- `build-essential`
- `devscripts`
- `devhelper` >= 9
- make sure the project dir is in linux supported file systems like extX

Note: NTFS does not support the build operations


### Build

```
dpkg-deb --build deb-setup
```

### Installation

```
sudo dpkg -i deb-setup.deb
```

