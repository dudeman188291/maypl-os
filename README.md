# Maypl Operating System

Welcome to the official repository of Maypl, a free and open-source operating system built on the Linux kernel!
 
---

## What is Maypl?

Maypl uses the Linux kernel, making it Linux-based, yet it stands apart from traditional Linux distributions. It does not use typical distro components like systemd, sudo, or common package managers (because those seem slightly boring!). Instead, Maypl offers a fresh take on system design with its own unique init system, graphical environment, and app framework!

Designed to be clean, efficient, and developer-friendly, Maypl provides a nice and personal computing experience! It uses the MIPS architecture and is tailored for users and developers who value control, simplicity, and openness without the usual Linux distro baggage!


---

## Key Features!

Custom Init System: Bread Toaster, designed for fast and flexible startup.

Terminal: Butter, a lightweight and powerful command-line interface.

Graphical Desktop: Maypl Desktop, a native GUI always enabled by default, eliminating the need for external display servers.

App Store: Fetch, a built-in application manager tailored specifically for Maypl programs.

App Format: Maypl programs use the .mpr extension — self-contained, human-readable bundles inspired by app bundles and APKs, easy to run and distribute.

OpenGL Support: Maypl provides graphics acceleration through a compiled version of Mesa3D adapted to its environment, enabling rich visual experiences and compatibility with modern OpenGL applications.

Development Tools: Includes Tinker, an open-source IDE licensed under MIT, to help developers create and maintain Maypl applications efficiently.



---

## What Can You Do With Maypl?

Whether you're a developer, hobbyist, or enthusiast, Maypl offers a flexible platform to build and explore:

Develop applications with native tools and the .mpr app format!

Enjoy a sleek GUI environment without the overhead of external windowing systems.

Customize system services and preferences through a user-friendly control panel!

Run Maypl on MIPS hardware or QEMU emulation for experimentation.

Benefit from an open environment where every component is designed with modularity and independence in mind!



---

## Installation & Booting!

Maypl uses GRUB as its bootloader for reliable and flexible system startup. GRUB's maturity and broad hardware support make it ideal for this project, sparing Maypl from the complexities of creating a custom bootloader from scratch.

The kernel image is compressed and prepared specifically for GRUB, ensuring efficient boot times and compatibility with supported hardware.


---

## Not a Linux Distribution!

It bears repeating: Maypl is not a Linux distro! Not even close! Nope! Nada! Nothing! Zilch! It shares the Linux kernel, but it is an independent operating system built from the ground up with custom components and no dependency on traditional bloating Linux userland tools or package managers!


---

## Getting Started!

After installation, Maypl includes a comprehensive setup wizard to:

Configure your time zone and language preferences.

Create user accounts and profiles.

Adjust OpenGL settings powered by Mesa3D.

Manage Maypl system services.

Set up Fetch, the native app store.


This wizard makes first-time setup intuitive and straightforward, putting you in control.


---

## Contributing

Maypl is an open-source project welcoming contributions from developers, designers, and enthusiasts! Whether you want to improve the core OS, enhance the GUI, or create apps in the .mpr format, all of your works are valuablely nice! You can actually also fork Maypl if you want!

---

## License

Maypl OS is licensed under the GPLv3 license.
Tinker, the included IDE, is licensed under MIT.
Fetch, the CLI app store/manager is licensed under the Apache License 2.0.

---

Thank you for reading!
