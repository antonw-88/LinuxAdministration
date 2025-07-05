This repo was initially used for storing various commands/processes for setting up a new system/various troubleshooting processes etc. I then reorganized it to function as a study FAQ for learning about Linux, based on the RHCSA certificate requirements. The guide is intended to be usable for someone who is new to Linux and in the process of learning how the Linux Distros function in general; the difference between RedHat, Rocky, Debian, Arch and Gentoo etc, are in the end relatively small when compared to their similarities.  
The structure of the repo is based on Red Hat's 2025 overview of the contents that the certificate validates that the holder has a good understanding regarding.[1] The various sections are described below.  
NOTE: WHILE THIS GUIDE FOCUSES ON THE RHCSA, THE DISTRO THAT WAS USED DURING THE DEVELOPMENT OF THIS GUIDE WAS ROCKY. ROCKY IS THE RECOMMENDED DISTRO FOR THIS GUIDE.


1. Understand and use Essential Tools.
   1. Shell commands.  
   2. Input-Output redirection.
   3. Grep and Regex for analyzing text.
   4. Basic SSH usage.
   5. Login and switch users in multiuser targets.
   6. Archive, compress, unpack, uncompress files using Tar, Gzip, Bzip2.
   7. Text file creationg and modification.
   8. File and directory management.
   9. Hard and soft links.
   10. File and directory permissions.
   11. System documentation.
2. Shell Scripting.
   1. Conditional execution.
   2. Looping constructs.
   3. Script inputs.
   4. Output control. 
3. Operating Running Systems.
   1. Standard boot, reboot and shutdown.
   2. Boot systems into different targets.
   3. System access by interrupting the boot process.
   4. Process identification and control.
   5. Process scheduling.
   6. Tuning profiles.
   7. Log files and journals.
   8. System journal preservation.
   9. Network service analysis.
   10. File-transfer between systems. 
4. Local Storage Configuration.
   1. MBR and GPT disk partitioning.
   2. Create and delete physical volumes.
   3. Assign physical volumes to volume groups.
   4. Create and delete logical volumes.
   5. Configure systems to mount file systems at boot by universally unique ID (UUID) or label.
   6. Add new partitions and logical volumes, and swap to a system non-destructively.
5. Create and Configure File Systems.
   1. Create, mount, unmount, and use vfat, ext4, and xfs file systems.
   2. Mount and unmount network file systems using NFS.
   3. Configure autofs.
   4. Extend existing logical volumes.
   5. Create and configure set-GID directories for collaboration.
   6. Diagnose and correct file permission problems.
6. Deploy, Configure and Maintain Systems.
   1. Schedule tasks using at and cron.
   2. Start and stop services and configure services to start automatically at boot.
   3. Configure systems to boot into a specific target automatically.
   4. Configure time service clients.
   5. Install and update software packages from Red Hat Network, a remote repository, or from the local file system.
   6. Modify the system bootloader.
7. Manage Basic Networking.
   1. Configure IPv4 and IPv6 addresses.
   2. Configure hostname resolution.
   3. Configure network services to start automatically at boot.
   4. Restrict network access using firewall-cmd/firewall.
8. Manage Users and Groups.
   1. Create, delete, and modify local user accounts.
   2. Change passwords and adjust password aging for local user accounts.
   3. Create, delete, and modify local groups and group memberships.
   4. Configure superuser access.
9. Manage Security.
   1. Configure firewall settings using firewall-cmd/firewalld.
   2. Manage default file permissions.
   3. Configure key-based authentication for SSH.
   4. Set enforcing and permissive modes for SELinux.
   5. List and identify SELinux file and process context.
   6. Restore default file contexts.
   7. Manage SELinux port labels.
   8. Use boolean settings to modify system SELinux settings.
   9. Diagnose and address routine SELinux policy violations.
10. Manage Containers.
   1. Find and retrieve container images from a remote registry
   2. Inspect container images
   3. Perform container management using commands such as podman and skopeo
   4. Perform basic container management such as running, starting, stopping, and listing running containers
   5. Run a service inside a container
   6. Configure a container to start automatically as a systemd service
   7. Attach persistent storage to a container

As with all Red Hat performance-based exams, configurations must persist after reboot without intervention.
  
**Study Materials:**
[1] https://www.redhat.com/en/services/training/ex200-red-hat-certified-system-administrator-rhcsa-exam
[2] https://github.com/victorbrca/rhcsa-study-guide
[3] https://rbong.github.io/rhcsa-open-guide/
[4] https://www.reddit.com/r/redhat/comments/mrgqfb/red_hat_certification_study_qa/
[5] Sander van Vugt — supplement his free videos with a 10‑day O’Reilly trial to access full courses and practice labs.
[6] https://annas-archive.org/search?q=RHCSA
