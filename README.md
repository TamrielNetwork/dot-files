<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email, project_title, project_description
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/TamrielNetwork/dot-files">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">ArchLinux and i3 Dot-Files</h3>

  <p align="center">
    My Dot-Files and miscellaneous files for i3 and Arch Linux
    <br />
    <a href="https://github.com/TamrielNetwork/dot-files"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/TamrielNetwork/dot-files">View Demo</a>
    ·
    <a href="https://github.com/TamrielNetwork/dot-files/issues">Report Bug</a>
    ·
    <a href="https://github.com/TamrielNetwork/dot-files/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Screenshot][product-screenshot]](https://github.com/TamrielNetwork/dot-files/blob/main/images/screenshot.png)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

  ```sh
  yay -S feh rofi ttf-font-awesome networkmanager network-manager-applet i3-gaps playerctl pulseaudio npm pavucontrol picom i3status i3lock arc-gtk-theme paper-icon-theme-git
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/TamrielNetwork/dot-files.git
   ```
2. Remove unnecessary files/folders from the repo (optional)
   ```sh
   rm -rf dot-files/.git dot-files/.github dot-files/images dot-files/README.md dot-files/LICENSE
   ```
3. Copy content to your Home-Directory
   ```sh
   cp -r dot-files/* ~/
   ```

:warning: **Replaces your configuration**: Be careful!



<!-- USAGE EXAMPLES -->
## Usage

1. Reboot your system
   ```sh
   sudo reboot
   ```
2. Log into user (not root) account
3. Use ~/.xinitrc to start the window-manager
   ```sh
   startx
   ```




<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/TamrielNetwork/dot-files/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Leopold Meinel - [@TamrielN](https://twitter.com/TamrielN) - Twitter

Leopold Meinel - [contact@tamriel.me](mailto:contact@tamriel.me) - email

Project Link: [https://github.com/TamrielNetwork/dot-files](https://github.com/TamrielNetwork/dot-files)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [README.md - othneildrew](https://github.com/othneildrew/Best-README-Template)
* [i3-gaps/status and urxvt config - KevinScruff](https://github.com/KevinScruff)
* [urxvt pearls - muennich](https://github.com/muennich/urxvt-perls)
* [Background - alphacoders](https://wall.alphacoders.com/big.php?i=42989)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors-anon/TamrielNetwork/dot-files?style=for-the-badge
[contributors-url]: https://github.com/TamrielNetwork/dot-files/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/TamrielNetwork/dot-files?label=Forks&style=for-the-badge
[forks-url]: https://github.com/TamrielNetwork/dot-files/network/members
[stars-shield]: https://img.shields.io/github/stars/TamrielNetwork/booX?style=for-the-badge
[stars-url]: https://github.com/TamrielNetwork/dot-files/stargazers
[issues-shield]: https://img.shields.io/github/issues/TamrielNetwork/dot-files?style=for-the-badge
[issues-url]: https://github.com/TamrielNetwork/dot-files/issues
[license-shield]: https://img.shields.io/github/license/TamrielNetwork/dot-files?style=for-the-badge
[license-url]: https://github.com/TamrielNetwork/dot-files/blob/main/LICENSE
[product-screenshot]: images/screenshot.png
