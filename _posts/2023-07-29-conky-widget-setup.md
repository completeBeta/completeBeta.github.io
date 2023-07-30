---
title: Conky - Desktop System Monitor
date: 2023-07-29 12:00:00 -500
categories: [Workflow,Conky]
tags: [linux, autostart] # tag names MUST always be lowercase! 
image:
  path: https://images.pling.com/img/00/00/66/56/37/1881574/dziban1.png
  alt: This is an example Conky Theme
---
# What is Conky?
Conky is an open-source system monitor for Linux, designed to display a variety of system-related information directly on the desktop. It presents this data in the form of customizable widgets, which can be positioned anywhere on the screen, allowing users to have a quick glance at essential information without having to open additional applications.

Originally created by Brenden Matthews, Conky has evolved over the years thanks to an active community of developers and enthusiasts who continue to contribute to its development. It is written in C and supports a wide range of Linux desktop environments, including GNOME, KDE Plasma, Xfce, and many others.

## Key Features
<details>
<summary>System Monitoring</summary>
Conky can display real-time information about your system's CPU usage, memory consumption, disk space, network activity, and other crucial metrics. It allows users to keep an eye on system performance and resource usage, which can be beneficial for both casual users and power users who need to monitor resource-intensive tasks.
</details>

<details>
<summary>Customizability</summary>
One of Conky's most significant advantages is its customizability. Users can create their own Conky configurations or choose from a vast collection of community-contributed themes and scripts. These configurations can be adjusted to suit individual preferences, enabling users to display specific information, change colors, fonts, and widget placements.
</details>

<details>
<summary>Desktop Widgets</summary>
Conky is not limited to system monitoring alone. Users have leveraged its potential to create desktop widgets displaying various data, such as weather forecasts, calendar events, news headlines, and more. It effectively combines utility and convenience into a single package.
</details>

<details>
<summary>Resource Efficiency</summary>
Conky is incredibly lightweight and does not consume significant system resources. Even when running multiple Conky instances, its impact on system performance remains minimal, making it suitable for older or resource-limited systems.
</details>

<details>
<summary>Scripting and Extensibility</summary>
Users can extend Conky's capabilities by incorporating scripts and external programs into their configurations. This flexibility allows for integration with third-party applications, APIs, and online services, further enhancing its functionality.
</details>


# How to Install & Setup Conky (debian w/gnome)
TO setup Conky; we will need to get any theme (Can be edited to your liking) and then we must auto start and configure the theme. 
Most themes can be found from [gnome-look.org](https://www.gnome-look.org/p/1881574)
clicking the link will lead you to an example theme.

This theme can then be downloaded and extracted to a folder. Before moving to theme customisation however; we must first make sure that cronky is installed by following the bash script below.
### Bash Scripts
```bash
sudo apt-get install conky-all -y
```
This then should install the latest version of cronky; allowing us to move to the next section of the installation process.

We will then move to the extracted downloaded folder and move its contents to home/.conky
This can be achieved by using a file browser or through the terminal like such:
```bash
mv CONKY_FILE_NAME/ ~/.conky
```
*If .conky is not present then make that folder in the home directory*
### Auto Start
After those steps are completed then an auto start task must now be applied. This is desktop environment dependent. The most recommended method is .desktop application files to be placed in ***home/.config/autostart***. This can also be done with gnome using the TWEAKS app under startup applications; then selecting conky. This is just an easier way of creating a .desktop file under that same previously listed directory.


