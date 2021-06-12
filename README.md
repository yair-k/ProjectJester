[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<p align="center">
  <a href="https://github.com/yair-k/ProjectJester">
    <img src="https://cdn.discordapp.com/attachments/777942258569576468/853150273174634506/logo.png" alt="Logo" width="256" height="256"></a>
  <h3 align="center">Project Jester</h3>

  <p align="center">
  The ultimate tool for Hangman
    <br />
    <a href="[Project Jester](https://projectjester.neocities.org/)">TRY IT OUT</a>
    <br />
    <br />
    <a href="https://devpost.com/software/project-jester">Visit Devpost</a>
    ·
    <a href="https://github.com/yair-k/ProjectJester/issues">Report Bug</a>
    ·
    <a href="https://github.com/yair-k/ProjectJester/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Word List Updating</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Since childhood, we have all played the well known game Hangman.

The goal of this game is too guess a letter from a word or sentance taking turns, before the ammount of chances you have. When guessing the word, you know the length of the word, and as the game progresses, you fill in the blanks of the phrase.

Recently, I played Hangman again during online class, and the phrases were quite hard. I was inspired to create a tool to help me become better at hangman and have more fun at it.

Projest Jester is a tool made to help you guess likley possibilities for the words, and train your vocabulary for hangman the more you use the tool.

### Built With

Originally, I intended to use the [Flask Framework](https://flask.palletsprojects.com/en/2.0.x/) as I had prior experience with it and I enjoy Python coding. However, I realised that this was not neccesary for this case. The website was to be created using:
* [Bootstrap 5.0](https://getbootstrap.com)
* [JQuery](https://jquery.com)
* [HTML](https://html.spec.whatwg.org/)
* [CSS](https://en.wikipedia.org/wiki/CSS)
* [JavaScript](https://www.javascript.com/)



<!-- GETTING STARTED -->
## Getting Started

You can run this website locally or offline if you wish to, Or you can use the demo version.

If you would like to update the word list or add your own feature, feel free to do so.
### Prerequisites

Download the code, extract it, then run

  ```sh
  index.html
  ```

### Word List Updating

1. Download the code, and extract it
2. Go to
   ```sh
   /wordlist/wordlist.js
   ```
3. Open it with a text editor of your choice
4. Add in your words as a new line in between brackets and commas in`wordlist.js`
   ```JS
   var arrayData = [	
	"word1",
	"word2",
	"word3",
	"you can even add spaces",
	"and-even-hyphons",
	]
   ```
<!-- USAGE EXAMPLES -->
## Usage

Use the website and code as you wish, it's all up for updating, and more features will be added.

_For the Online Demo, you can go [here](https://projectjester.neocities.org)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/yairk/ProjectJester/issues) for a list of proposed features (and known issues).



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

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Yair - [yair.#0518](https://discord.com/app) - yair@fbi.ac

Website: [yair.studio](https://yair.studi)

Project Link: [Project Jester - GitHub](https://github.com/yair-k/ProjectJester)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/badge/CONTRIBUTERS-1-brightgreen?style=for-the-badge
[contributors-url]: https://github.com/yair-k/ProjectJester
[forks-shield]: https://img.shields.io/badge/FORKS-1-blue?style=for-the-badge
[forks-url]: https://github.com/yair-k/ProjectJester/network/members
[stars-shield]: https://img.shields.io/badge/STARS-0-blue?style=for-the-badge
[stars-url]: https://github.com/yair-k/ProjectJester/stargazers
[issues-shield]: https://img.shields.io/badge/ISSUES-0%20OPEN-yellow?style=for-the-badge
[issues-url]: https://github.com/yair-k/ProjectJester/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/yk-yair/
[product-screenshot]: img/1.png
