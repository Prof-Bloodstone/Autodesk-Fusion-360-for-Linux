![banner-fusion360](https://user-images.githubusercontent.com/79079633/127371623-6b50b591-1b12-466d-9c96-b5b6d6314f31.png)

![GitHub last commit](https://img.shields.io/github/last-commit/cryinkfly/Fusion-360---Linux-Wine-Version-?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues-raw/cryinkfly/Fusion-360---Linux-Wine-Version-?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/cryinkfly/Fusion-360---Linux-Wine-Version-?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/cryinkfly/Fusion-360---Linux-Wine-Version-?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/cryinkfly/Fusion-360---Linux-Wine-Version-?style=for-the-badge)

Autodesk Fusion 360 is a cloud-based 3D modeling, CAD, CAM, and PCB software platform for product design and manufacturing, what you can use on Windows and macOS.

But the problem is that there are also people like me who don't want to use either of these two operating systems on there systems. Then these users have installed a Linux distribution such as openSUSE Leap, Ubuntu or Fedora.

And so I got the idea to start this project here to find a way to solve this problem. 

I started looking at different tools and my choice was Wine! 

With this nice tool we don't need longer two operating systems for Fusion 360, when we will create a fantastic project in the future or if you want to work on a project with other people.

Is that a great idea for the future?

Personally, I think this idea is good and for this reason I will do my best to give you the opportunity to use it on Linux as well!

---

You will get more information about this program, then you can visit the original website of Autodesk Fusion 360 with this link: https://www.autodesk.com/products/fusion-360/features

---

  - 📂 Downloads: 
<a href="https://github.com/cryinkfly/Autodesk-Fusion-360-for-Linux/tree/main/files/scripts/stable-branch">Stable</a> and <a href="https://github.com/cryinkfly/Autodesk-Fusion-360-for-Linux/tree/main/files/scripts/development-branch">development builds</a>
  - 📔 Documentation: <a href="https://github.com/cryinkfly/Fusion-360---Linux-Wine-Version-/wiki/Documentation">GitHub-Documentation</a> & <a href="https://www.youtube.com/watch?v=-BktJspJKgs&list=PLzwMdS5iu_BIsO6RTy7Hy1MbzLMrQE2xe">Videos</a>
  - 💬 Would You like to get in touch with me? Or if You have any questions, suggestions or problems?
  - 📫 Then You can create an <a href="https://github.com/cryinkfly/Fusion-360---Linux-Wine-Version-/issues">issue</a> here on GitHub or You visit my <a href="https://cryinkfly.com">website</a> and get in touch with me!
  - 📜 Code of Conduct: [Contributor Covenant](https://github.com/cryinkfly/Fusion-360---Linux-Wine-Version-/blob/main/.github/CODE_OF_CONDUCT.md)
  - 📖 Information for contributors: All contribution information, Compilation instructions, Roadmap (Still in Progress!)
  - ❤️ I'd like to thank everyone who has <a href="https://github.com/cryinkfly/Fusion-360---Linux-Wine-Version-/blob/main/COMMUNITY.md">helped</a> me to get Fusion 360 up and running on Linux!
  - ☕️ Discussion: https://github.com/cryinkfly/Fusion-360---Linux-Wine-Version-/discussions
  - 🍷 Super Application Maintainer (WineHQ): https://appdb.winehq.org/objectManager.php?sClass=application&iId=15617
  - 🌍 Official member of the [Autodesk Group Network](https://github.com/cryinkfly/Autodesk-Fusion-360-for-Linux/releases/tag/v5.1)!

---

## Screenshots
<div>
<img src="https://raw.githubusercontent.com/cryinkfly/Fusion-360---Linux-Wine-Version-/main/files/images/workspaces/Manufacture/%231.1_adapter-plate.png" width="300px" height="200px">
<img src="https://raw.githubusercontent.com/cryinkfly/Fusion-360---Linux-Wine-Version-/main/files/images/workspaces/Generative%20Design/%231.4_generative_design.png" width="300px" height="200px">
</div>
<div>
<img src="https://github.com/cryinkfly/Autodesk-Fusion-360-for-Linux/blob/main/files/images/workspaces/Rendering/rpi4_case_tux-tage-2021.png" width="300px" height="200px">
<img src="https://raw.githubusercontent.com/cryinkfly/Fusion-360---Linux-Wine-Version-/main/files/images/workspaces/Simulation/%231_study_displacement.png" width="300px" height="200px">
</div>
<div>
<img src="https://raw.githubusercontent.com/cryinkfly/Fusion-360---Linux-Wine-Version-/main/files/images/workspaces/Drawing/drawing_oil_case.png" width="300px" height="200px">
<img src="https://raw.githubusercontent.com/cryinkfly/Autodesk-Fusion-360-for-Linux/main/files/images/workspaces/Electronics/%231_air%20quality%20sensor.png" width="300px" height="200px">
</div>

---

## Downloads

There are some <a href="https://github.com/cryinkfly/Autodesk-Fusion-360-for-Linux/tree/main/files/scripts">script releases</a> available, built from the release targets.

It's recommended that if you're new you start with the stable builds. Development builds are available here if you need it, but correspondingly may be less stable.

---

## Hardware and Software Requirements

- Internet connection (Cable/DSL speeds recommended)!
- Latest graphics driver, see <a href="https://github.com/cryinkfly/Fusion-360---Linux-Wine-Version-/wiki/Supported-Graphics-Cards">here</a>!
- Latest wine version (winehq-staging), because with some versions of wine where no internet connection works!
- Would you like to use the Czech language later in Autodesk Fusion 360, then you need a [special extension](https://apps.autodesk.com/FUSION/en/Detail/Index?id=9151466655844643882) what you must have bought and downloaded before you can install this with my Setup Wizard!
- My script install some packages (dialog, p7zip, p7zip-full, p7zip-rar, curl, wget, winbind, cabextract, wine, wine-mono, wine_gecko, winetricks, ...)!
- Supported Linux distributions:

![supported_os](https://user-images.githubusercontent.com/79079633/134313580-ac8cf27e-d0c8-4393-beb6-55015a136220.png)

- Check if you have installed zenity and xterm on your Linux distribution:

#### Debian based systems:

    sudo apt-get update && sudo apt-get install software-properties-common zenity xterm

#### Red Hat based systems:

    sudo dnf update && sudo dnf install zenity xterm

#### Arch based systems:

    sudo pacman -Sy --needed zenity xterm

#### openSUSE based systems:

    su -c 'zypper up && zypper install zenity xterm'

#### Void based systems:

    sudo xbps-install -Sy zenity xterm

#### Solus based systems:

    sudo eopkg install zenity xterm


#### Gentoo based systems:

    sudo emerge -av gnome-extra/zenity x11-terms/xterm

---

## Getting Started

Install Fusion 360 for Linux client:

1.) Check my <a href="https://github.com/cryinkfly/Fusion-360---Linux-Wine-Version-/wiki/Documentation">GitHub-Documentation</a> & <a href="https://www.youtube.com/watch?v=-BktJspJKgs&list=PLzwMdS5iu_BIsO6RTy7Hy1MbzLMrQE2xe">Videos</a> before you install Autodesk Fusion 360 on your system!

2.) Open a terminal and run this command:

    mkdir -p "$HOME/.wineprefixes/fusion360/INSTALLDIR" && cd "$HOME/.wineprefixes/fusion360/INSTALLDIR" && wget -N https://github.com/cryinkfly/Autodesk-Fusion-360-for-Linux/raw/main/files/scripts/stable-branch/fusion360-setup-wizard.sh && chmod +x fusion360-setup-wizard.sh && bash fusion360-setup-wizard.sh && exit

3.) Now, You can <a href="https://github.com/cryinkfly/Fusion-360---Linux-Wine-Version-/issues/44#issuecomment-890552181">use</a> Autodesk Fusion 360 on your Linux system!

---

## Which work areas and functions have I tested:

<table>
<thead>
<tr>
<th></th>
<th>Windows</th>
<th>macOS</th>
<th>Linux</th>
</tr>
</thead>
<tbody>
<tr>
<td>Construction</td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<tr>
<td>Animation</td>
<td><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
<tr>
<td>Rendering</td>
<td><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
<tr>
<td>Production</td>
<td><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
<tr>
<td>Simulation</td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
<tr>
<td>Generative Design</td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
<tr>
<td>Drawing</td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
<tr>
<td>Electronics</td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
<tr>
<td>Online- & Offline-Mode</td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
<tr>
<td>Support all languages</td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
<tr>
<td><a href="https://github.com/cryinkfly/Autodesk-Fusion-360-for-Linux/tree/main/files/docs/en-US/extensions">Scripts and additional modules</a></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
</tr>
</tbody>
</table>

---

## Important Notice

With the help of my script, You get a way to install Autodesk Fusion 360 on your Linux system. 

Certain packages and programs that are required will be set up for You, but it's important to know, that my script only helps You to get the program to run and nothing more! 

And so, You must to purchase the licenses directly from the manufacturer of the program Autodesk Fusion 360!

---

## License

All my scripts are released under the MIT license, see <a href="https://github.com/cryinkfly/Fusion-360---Linux-Wine-Version-/blob/main/LICENSE.md">LICENSE.md</a> for full text.





