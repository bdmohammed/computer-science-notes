---
title: Linux
slug: linux
description: Linux
---

🐧 linux/
├── 🖥️ 01-shell-and-cli-foundations/
│   ├── 📄 01-what-is-a-shell
│   ├── 📄 02-terminal-vs-shell-vs-console
│   ├── 📄 03-bash-basics-navigation
│   ├── 📄 04-file-and-directory-operations
│   ├── 📄 05-wildcards-and-globbing
│   ├── 📄 06-stdin-stdout-stderr
│   ├── 📄 07-redirection-and-pipes
│   ├── 📄 08-command-chaining-and-exit-codes
│   └── 📄 09-shell-history-and-shortcuts
│
├── 📁 02-file-system/
│   ├── 📄 01-linux-directory-hierarchy-fhs
│   ├── 📄 02-absolute-vs-relative-paths
│   ├── 📄 03-inodes-and-hard-links
│   ├── 📄 04-soft-links-symlinks
│   ├── 📄 05-file-types-in-linux
│   ├── 📄 06-permissions-and-ownership
│   ├── 📄 07-special-permissions-suid-sgid-sticky
│   ├── 📄 08-acls-extended-permissions
│   └── 📄 09-file-descriptors
│
├── 🔍 03-text-processing/
│   ├── 📄 01-cat-head-tail-less-more
│   ├── 📄 02-grep-and-regex
│   ├── 📄 03-sed-stream-editor
│   ├── 📄 04-awk-field-processor
│   ├── 📄 05-cut-sort-uniq-wc
│   ├── 📄 06-tr-and-paste
│   └── 📄 07-xargs
│
├── ⚙️ 04-processes-and-jobs/
│   ├── 📄 01-what-is-a-process
│   ├── 📄 02-process-lifecycle-fork-exec-wait
│   ├── 📄 03-ps-top-htop
│   ├── 📄 04-foreground-background-jobs
│   ├── 📄 05-signals-and-kill
│   ├── 📄 06-process-priority-nice-renice
│   ├── 📄 07-proc-filesystem
│   └── 📄 08-zombie-and-orphan-processes
│
├── 👥 05-users-and-groups/
│   ├── 📄 01-users-groups-uid-gid
│   ├── 📄 02-etc-passwd-shadow-group
│   ├── 📄 03-useradd-usermod-userdel
│   ├── 📄 04-sudo-and-sudoers
│   ├── 📄 05-su-vs-sudo
│   └── 📄 06-pam-pluggable-auth-modules
│
├── 📜 06-shell-scripting/
│   ├── 📄 01-shebang-and-script-structure
│   ├── 📄 02-variables-and-env
│   ├── 📄 03-conditionals-if-case
│   ├── 📄 04-loops-for-while-until
│   ├── 📄 05-functions
│   ├── 📄 06-arrays-and-maps
│   ├── 📄 07-string-manipulation
│   ├── 📄 08-error-handling-set-e-pipefail
│   ├── 📄 09-script-arguments-and-getopts
│   └── 📄 10-real-world-scripting-patterns
│
├── 📦 07-package-and-software-management/
│   ├── 📄 01-apt-and-dpkg-debian
│   ├── 📄 02-yum-dnf-rpm-redhat
│   ├── 📄 03-snap-and-flatpak
│   ├── 📄 04-compiling-from-source
│   └── 📄 05-shared-libraries-ldconfig
│
├── 💾 08-storage-and-filesystems/
│   ├── 📄 01-block-devices-and-partitions
│   ├── 📄 02-mbr-vs-gpt
│   ├── 📄 03-filesystems-ext4-xfs-btrfs
│   ├── 📄 04-mount-and-fstab
│   ├── 📄 05-lvm-logical-volume-manager
│   ├── 📄 06-raid-concepts
│   ├── 📄 07-swap-space
│   └── 📄 08-disk-usage-df-du-lsblk
│
├── 🌐 09-networking/
│   ├── 📄 01-network-interfaces-ip-addr
│   ├── 📄 02-routing-and-gateway
│   ├── 📄 03-dns-resolution-etc-resolv
│   ├── 📄 04-ss-netstat-and-open-ports
│   ├── 📄 05-firewall-iptables-nftables
│   ├── 📄 06-ufw-and-firewalld
│   ├── 📄 07-ssh-and-scp
│   ├── 📄 08-curl-and-wget
│   ├── 📄 09-network-troubleshooting
│   └── 📄 10-tcpdump-and-wireshark-basics
│
├── 🚀 10-systemd-and-init/
│   ├── 📄 01-boot-process-bios-to-userspace
│   ├── 📄 02-systemd-architecture
│   ├── 📄 03-units-service-target-timer
│   ├── 📄 04-systemctl-commands
│   ├── 📄 05-journald-and-logging
│   ├── 📄 06-writing-a-service-unit
│   └── 📄 07-cron-vs-systemd-timers
│
├── 🧠 11-kernel-and-os-internals/
│   ├── 📄 01-kernel-space-vs-user-space
│   ├── 📄 02-system-calls
│   ├── 📄 03-virtual-memory-and-paging
│   ├── 📄 04-cpu-scheduling
│   ├── 📄 05-interrupts-and-context-switching
│   ├── 📄 06-kernel-modules
│   └── 📄 07-cgroups-and-namespaces
│
├── 🔐 12-security/
│   ├── 📄 01-linux-security-model
│   ├── 📄 02-selinux-and-apparmor
│   ├── 📄 03-capabilities-vs-root
│   ├── 📄 04-ssh-hardening
│   ├── 📄 05-audit-framework
│   └── 📄 06-common-attack-vectors
│
└── 🔬 13-observability-and-debugging/
    ├── 📄 01-strace-and-ltrace
    ├── 📄 02-lsof-and-fuser
    ├── 📄 03-perf-and-flamegraphs
    ├── 📄 04-memory-analysis-valgrind-smaps
    ├── 📄 05-log-analysis-patterns
    └── 📄 06-core-dumps