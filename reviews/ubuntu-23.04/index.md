# Ubuntu: A review
---

Ubuntu is one of the most popular and widely used Linux distributions in the world. It is an open source operating system that runs on desktops, servers, cloud and IoT devices. It is based on Debian and offers a user-friendly and customizable interface, a large and diverse software repository, and a strong and supportive community.

Anyone can access Ubuntu and enjoy its features without paying any fees or licenses. Ubuntu also provides regular updates every six months that bring new features, security patches and bug fixes to the users. Additionally, Ubuntu has a long term support (LTS) version that receives five years of security and maintenance updates, which is ideal for users who prefer stability and reliability over novelty.

The LTS releases of Ubuntu are designed to be rock-solid stable, and to last for at least 5 years (with paid support for up to 10 years), and hence packages undergo the most rigorous testing possible. This means that packages on LTS releases are almost always multiple versions behind ones on interim releases, as well as rolling release distros.

Ubuntu is developed by the **Canonical** Corporation. Hence it has solid financial backing. Canonical also develops snaps, a *proprietary* package manager which is preinstalled on Ubuntu.

One of the challenges of Ubuntu is to provide users with the latest software while maintaining stability and compatibility. To address this, Ubuntu has introduced two ways of installing software: snaps (as mentioned earlier) and PPAs.

**Snaps** are self-contained packages that bundle an application and all its dependencies into one compressed file. Snaps can run on any Linux system that supports snapd, the service that manages snaps. Snaps are isolated from the rest of the system, so they can avoid dependency conflicts and security issues. Snaps also update automatically and can run multiple versions of the same application.

Snaps are available from the **Snap Store**, which is the default source of software in Ubuntu 20.04 and later. Users can browse and install snaps using the **Ubuntu Software** application, which is itself a snap². Users can also use the **snap** command in the terminal to manage snaps.

Some advantages of snaps are:

- They are easy to install and update
- They are compatible across different Linux distributions
- They are sandboxed and secure
- They can run multiple versions of the same application

Some disadvantages of snaps are:

- They are larger than traditional packages
- They use more disk space
- They launch slower than native applications
- They may not follow the theme of the desktop
- They may not be official or maintained by the original authors

**PPAs** (Personal Package Archives) are repositories that allow users to install software that is not available in the official Ubuntu repositories. PPAs are hosted on Launchpad, a platform for software development and collaboration. Users can add PPAs to their system using the **add-apt-repository** command in the terminal, or by using a graphical tool like **Software & Updates**⁴.

Some advantages of PPAs are:

- They provide access to newer or alternative versions of software
- They are usually maintained by the original authors or trusted community members
- They use the native package format (deb) and package manager (apt)

Some disadvantages of PPAs are:

- They are not reviewed or verified by Ubuntu
- They may introduce dependency conflicts or security issues
- They may break or become obsolete after a system upgrade

In conclusion, Ubuntu offers users two ways of installing software: snaps and ppas. Both have their pros and cons, depending on the user's needs and preferences. Snaps are more convenient and universal, but also more resource-intensive and isolated. PPAs are more flexible and native, but also more risky and unstable⁵. Users can choose which one suits them best, or use both in combination. Ubuntu is a versatile and user-friendly distribution that caters to different types of users.

---
### [Return to Index](../)