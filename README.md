### Introduction
Community Enterprise Operating System (CentOS) is a free open-source distribution derived from Red Hat Enterprise Linux (RHEL). This guide provides simple steps to install CentOS on your system.

### Prerequisites
  - A computer with at least 2GB RAM and 20GB disk space.
  - A bootable USB drive of 8GB or more.
  - Downloaded CentOS ISO file from [CentOS Download Page](https://www.centos.org/download/).

### Procedure for Single Boot OS

1. **Download CentOS ISO**  
   a. Visit the [CentOS Download Page](https://www.centos.org/download/).  
   b. Download the CentOS 7 or CentOS 8 ISO file based on your preference.

2. **Create a Bootable USB**  
   a. Windows: Use [Rufus](https://rufus.ie/).  
   b. macOS/Linux: Use [Balena Etcher](https://www.balena.io/etcher/).

3. **Boot from USB**  
   a. Insert the bootable USB into your computer.  
   b. Restart the computer and enter BIOS (typically by pressing `F2`, `F12`, or `Del` during startup).  
   c. Change the boot order to boot from the USB first.  
   d. Save and exit BIOS to boot from the USB drive.

4. **Install CentOS**  
   a. Once the CentOS installer loads, select **Install CentOS**.  
   b. Choose your preferred language and click **Continue**.

5. **Set Installation Options**  
   a. **Date & Time**: Select your time zone.  
   b. **Keyboard**: Choose your keyboard layout.  
   c. **Software Selection**: Choose between **Minimal Install** or **Server with GUI**.  
   d. **Installation Destination**: Select your hard drive for installation and configure partitioning if necessary.

6. **Begin Installation**  
   a. Click **Begin Installation**.  
   b. Set a root password.  
   c. Create a new user account.

7. **Reboot**  
   Once installation is complete, click **Reboot**.  
   Remove the USB drive during the reboot process.

### Additional Resources
- [CentOS Documentation](https://docs.centos.org/en-US/docs/)
- [CentOS Official Website](https://www.centos.org/)
