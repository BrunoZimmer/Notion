# NDG Linux Essentials

When most people refer to Linux, they are really referring to a combination of software called **GNU/Linux** , which defines the operating system

The **Linux**  part of this combination is the Linux kernel , which is the core of the operating system

UNIX is written in the **C** language making it uniquely portable amongst competing operating systems

- The second type of interface is the command line interface (CLI)), a text-based interface to the computer
- Operating systems and software upgrades come on a periodic basis, called a release cycle
. Vendors only support older versions of software for a certain period of time before not offering any updates; this is called a maintenance cycle
 or life cycle
- Modern data centers are addressing this challenge through virtualization
. In a virtual environment
- When a software release has many new features that haven’t been tested, it’s typically referred to as beta
- The norm for open source software development is to ensure backward compatibility first and break things only as a last resort.
- Red Hat started to focus more on the server applications, such as web- and file-serving and released **Red Hat Enterprise Linux (RHEL)**
, which was a paid service on a long release cycle. The release cycle dictates how often software is upgraded
- Because everything in Red Hat Enterprise Linux is open source, a project called **CentOS**
 came to be. It recompiled
 all the RHEL packages (converting their source code from the programming language they were written into language usable by the system) and gave them away for free.
- The lowest-level tool for managing these files is the `dpkg`
 command. This command can be tricky for novice Linux users, so the **Advanced Package Tool**
, `apt-get`
 (a front-end program to the `dpkg`
 tool), makes management of packages easier. Additional command line tools which serve as front-ends to `dpkg`
 include `aptitude`
 and GUI front-ends like **Synaptic**
 and **Software Center**
.
- The **Linux Standards Base**
, which is a **Linux Foundation**
 project, is designed to specify (through a consensus) a set of standards that increase the compatibility between conforming Linux systems

The back-end tool most commonly used for RPM Package Management is the `rpm`
 command. While the `rpm`
 command can install, update, query and remove packages, the command line front-end tools such as `yum`
 and `up2date`
 automate the process of resolving dependency issues
- Use the `which`
 command to determine if there is an executable file, in this case named date, that is located within a directory listed in the `PATH`
 value:
- Aliases
 can be used to map longer commands to shorter key sequences.

---

## Aula

# **3.2.2.2 Private Cloud Servers**

As individuals, organizations, and companies start to move their data to the cloud, there is a growing demand for private cloud server software that can be deployed and administered internally.

The **ownCloud** project was launched in 2010 by Frank Karlitschek to provide software to store, sync and share data from private cloud servers. It is available in a standard open source GNU AGPLv3 license and an enterprise version that carries a commercial license.

The **Nextcloud** project was forked from ownCloud in 2016 by Karlitschek and has been growing steadily since then. It is provided under a GNU AGPLv3 and aims for “an open, transparent development process.”

Both projects focus on providing private cloud software that meets the needs of both large and small organizations that require security, privacy, and regulatory compliance. While several other projects aim to serve the same users, these two are by far the largest in terms of both deployment and project members.