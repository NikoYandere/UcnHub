---

# UcnHub (a.k.a. Ucn-repo)

Official Community Repository for Ucn Package Manager
Maintained by NikoYandere, creator of Ucn


---

UcnHub is a community-driven binary package repository created and maintained by NikoYandere, the original developer of the Ucn Package Manager. Its main goal is to simplify the process of distributing and installing .ucn binary packages via Ucn.

> ⚠️ Please note: UcnHub is not included by default with Ucn. However, it is widely used by the community. In the future, we may consider shipping UcnHub as a default repository.



This repository is intended for developers and users who want a convenient way to share or access bleeding-edge or niche software built for the Ucn ecosystem.


---

📦 Available Packages

Yanix Launcher
Distributed using a rolling release model, which means builds hosted here may be more up-to-date than those found on the official GitHub repository.



---

📤 How to Submit Your Own Package

If you would like to contribute a package to UcnHub, follow the packaging structure below:

```
Org.yourname.yourpackage/

├── org.yourname.yourpackage.ucn-manifest

├── your-package-folder/

```

📦 Packaging Steps:

1. Create a folder named Org.yourname.yourpackage.


2. Inside it, include:

A manifest file named org.yourname.yourpackage.ucn-manifest.

A folder containing your package's contents.



3. Compress everything into a .zip archive.


---

UcnHub (a.k.a. Ucn-repo)

Official Community Repository for Ucn Package Manager
Maintained by NikoYandere, creator of Ucn


---

UcnHub is a community-driven binary package repository created and maintained by NikoYandere, the original developer of the Ucn Package Manager. Its main goal is to simplify the process of distributing and installing .ucn binary packages via Ucn.

> ⚠️ Please note: UcnHub is not included by default with Ucn. However, it is widely used by the community. In the future, we may consider shipping UcnHub as a default repository.



This repository is intended for developers and users who want a convenient way to share or access bleeding-edge or niche software built for the Ucn ecosystem.


---

📦 Available Packages

Yanix Launcher
Distributed using a rolling release model, which means builds hosted here may be more up-to-date than those found on the official GitHub repository.



---

📤 How to Submit Your Own Package

If you would like to contribute a package to UcnHub, follow the packaging structure below:

`Org.yourname.yourpackage/
├── org.yourname.yourpackage.ucn-manifest
├── your-package-folder/`

📦 Packaging Steps:

1. Create a folder named Org.yourname.yourpackage.


2. Inside it, include:

A manifest file named org.yourname.yourpackage.ucn-manifest.

A folder containing your package's contents.

📓 Manifest Example

```
UCN PACKAGE MANAGER MANIFEST--

name:org.yourname.yourpackage

version:version here 

developer:name-here

publisher:name here

exec:insert-command-here

```

3. Compress everything into a .zip archive.


4. Rename the archive from:

org.yourname.yourpackage.zip

to:

org.yourname.yourpackage.ucn



> 🧠 Reminder: The Ucn Package Manager and UcnHub are part of a niche software distribution system. If you share a .ucn package here, your contribution will be greatly appreciated by the community!

