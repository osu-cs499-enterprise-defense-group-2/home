
display file or file system status:
    stat

manipulate partition table:
    fdisk

check valid sources of install:
    apt-key list

enable system snapshots, modif times, perms, file hashes
    /usr/bin/aide.wrapper

check what packages are installed:
    dpkg-query -W -f='${binary:Package}\t${Status}\t${db:Status-Status}\n' <name>


Manage mandatory access control:
    apparmor package

List services listening on the system (section 2.4):
    lsof -i -P -n | grep -v "(ESTABLISHED)"

