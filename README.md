<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a name="readme-top"></a>

<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Touxooo/R-Type">
    <img src="assets/logo.png" alt="Logo" width="500" height="100">
  </a>

<h3 align="center">R-Type</h3>

  <p align="center">
    R-Type Clone
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Report Bug</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">R-TYPE, THE GAME</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## R-Type, the game

For those of you who may not know this best-selling video game, which accounts for countless lost hours
of our childhood, [here](http://www.hardcoregaming101.net/r-type/) is a little introduction.

This game is informally called a Horizontal Shmup (e.g. Shoot’em’up), and while R-Type is not the first one of
its category, this one has been a huge success amongst gamers in the 90’s, and had several ports, spin-offs,
and 3D remakes on modern systems.

Other similar and well known games are the Gradius series and Blazing Star on Neo Geo.

As you now understand, this is our own version of R-Type. .. but with a twist not featured in
the original game (nor in the remakes by the way): our version is a network game, where one-to-four
players are able to fight together the evil Bydos!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

- [![CPP][c++]][c++-url]
- QT5
- SFML
- VCPKG
- CPACK
- CMAKE

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

You can do everything you want with this project, play it, edit the code to add new features, pack it, compile it, build it... The code is yours, do what you want!

But.. Before doing anything, just take a look at the prerequisites! If you don't respect the prerequisites, it will probably very complicated to use the project.

### Prerequisites

**Windows**

Player Edition

- Windows

Developper Edition

- [Updated Windows Version](https://support.microsoft.com/fr-fr/windows/mettez-%C3%A0-jour-windows-3c5ae7fc-9fb6-9af1-1984-b5e0412c556a)
- [Microsoft Visual Studio](https://visualstudio.microsoft.com/fr/downloads/)
- [Winget (Windows Builtin)](https://learn.microsoft.com/fr-fr/windows/package-manager/winget/)
- Administrator rights

**Linux**

Player Edition

- [Ubuntu](https://www.ubuntu-fr.org/download/)

Developper Edition

- [Ubuntu](https://www.ubuntu-fr.org/download/)
- [APT](https://doc.ubuntu-fr.org/apt)
- [GCC](https://gcc.gnu.org/) and G++
- Sudo access

### Installation

**For Windows User**

_I just want to play Version_

1. Download the R-Type Windows Setup Installer
2. Run R-Type-Installer.exe
3. Click Next
4. Choose destination (Click next if you don't understand)
5. Finish the installation

_I'm a developper, I want to build the project from source and play Version_

1. Clone the repo
   ```sh
   git clone https://github.com/Touxooo/R-Type.git
   ```
2. Run build.bat
3. Go inside build folder
4. Go inside Release folder

_I'm a developper, I want to build the project from source, run the setup installation and play Version_

1. Clone the repo
   ```sh
   git clone https://github.com/Touxooo/R-Type.git
   ```
2. Run build.bat
3. Go inside build folder
4. Run R-Type-Installer.exe
5. Click Next
6. Choose destination (Click next if you don't understand)
7. Finish the installation

**For Linux Users**
_I just want to play Version_

1. Download the R-Type Linux Setup Installer
2. Run R-Type-Installer.exe
3. Click Next
4. Choose destination (Click next if you don't understand)
5. Finish the installation
6. Find your game on you Desktop or inside your installed Apps
7. Launch r-type_server.exe to create your game server
8. Launch r-type_client.exe
9. Copy the adress IP on your Server Window and paste it on your Client Windows
10. Share your adress IP to others and play!

_I'm a developper, I want to build the project from source and play Version_

1. Clone the repo
   ```sh
   git clone https://github.com/Touxooo/R-Type.git
   ```
2. Run build.bat
3. Go inside build folder
4. Go inside Release folder
5. Launch r-type_server.exe to create your game server
6. Launch r-type_client.exe
7. Copy the adress IP on your Server Window and paste it on your Client Windows
8. Share your adress IP to others and play!

_I'm a developper, I want to build the project from source, run the setup installation and play Version_

1. Clone the repo
   ```sh
   git clone https://github.com/Touxooo/R-Type.git
   ```
2. Run build.bat
3. Go inside build folder
4. Run R-Type-Installer.exe
5. Click Next
6. Choose destination (Click next if you don't understand)
7. Finish the installation
8. Find your game on you Desktop or inside your installed Apps
9. Launch r-type_server.exe to create your game server
10. Launch r-type_client.exe
11. Copy the adress IP on your Server Window and paste it on your Client Windows
12. Share your adress IP to others and play!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

You saw two types of installation, a complicated one, and an easy one.

If you took the decision to run the installer, just find the R-Type Client or Server inside your computer installed applications.

If you took the decision to build the project from source, then go to your build folder, and in the Release folder to get the r-type_server and r-type_client executables.

**Steps to play the game with your friends**

1. Create a server by running R-Type Server
2. Copy the IP Adress and Port of the server output
3. Share the previous informations to your friends
4. Run the client thanks to R-Type Client
5. Paste the IP Adress and Port of the server
6. Enjoy your gaming session!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
  - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- []()
- []()
- []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[c++]: https://img.shields.io/badge/-C++-19437F?logo=c%2B%2B&logoColor=white&style=for-the-badge
[c++-url]: https://en.cppreference.com/w/
