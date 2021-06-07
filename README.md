# VPS_OpenWrt

This repo helps to deploy OpenWrt onto your VPS.<br>

**Prerequisite**
 - **`Ubuntu`** or **`Debian`** (CentOS/ArchBase Not tested)
 - **`wget`** installed<br>
   probably you don't need this, but if you do, you could run command below to install `wget`:<br>
   `apt update && apt install -y wget` 

**Steps**

1.  Upload OpenWrt firmware(WinSCP or prefer), rename it to "op.img.gz" 
2.  Run: `bash -c "$(wget -O- https://git.io/JGvno)"`
 
**Support Platform :**
- Google Cloud
- Azure
- Vultr
- Virmach
- Racknerd
- Hostdare
- Ali Cloud (Domestic)
- ...

**`NOT` Support Platform :**
- ...
