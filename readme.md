# Minty Config

Notes on configuring Minty


### App Stores vs. Package Management Technologies

| **Package Management** | **Discover** | **Ubuntu Software Center** | **GNOME Software** | **Software Manager (Mint)** |
|------------------------|--------------|----------------------------|--------------------|----------------------------|
|                        | (KDE Plasma) | (Ubuntu-based)             | (GNOME-based)      | (Linux Mint)               |
| **DEB**                 | ✅           | ✅                         | ✅                 | ✅                         |
| **RPM**                 | ✅           | ❌                         | ❌                 | ❌                         |
| **PPA**                 | ❌           | ✅                         | ❌                 | ❌                         |
| **Snap**                | ✅           | ✅                         | ✅                 | ✅                         |
| **Flatpak**             | ✅           | ❌                         | ✅                 | ❌                         |
| **AppImage**            | ✅           | ❌                         | ❌                 | ❌                         |
| **Total Apps**          | **1500+**    | **700+**                   | **1000+**          | **2000+**                 |
| **Foundation OS**       | **Debian (KDE)**  | **Debian (Ubuntu)**         | **Debian (GNOME)** | **Debian (Ubuntu)**       |


```text
# Install Discover (KDE Plasma)
sudo apt install discover

# Install Ubuntu Software Center and GNOME Software (the same thing)
sudo apt install gnome-software

# Install Software Manager (Mint)
sudo apt install mintinstall
```
