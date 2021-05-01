<!-- Inspired by https://github.com/jennifertakagi/go-restaurant -->

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/jennifertakagi/go-restaurant">
    <img src="docs/logo.png" alt="Logo" width="200">
  </a>

  <h3 align="center">Go Restaurant</h3>

  <p align="center">
      A web and mobile application to manage your restaurant menu!
    <br />
    <a href="https://github.com/jennifertakagi/go-restaurant"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jennifertakagi/go-restaurant/issues">Report Bug</a>
    ·
    <a href="https://github.com/jennifertakagi/go-restaurant/issues">Request Feature</a>
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

[![Product Name Screen Shot][product-screenshot]](#)

A web and mobile application to manage your restaurant menu.

Features:
* Check all the restaurant's dishes
* Add new dish to the menu
* Edit the existent dishes
* Delete a dish
* Make dish available or not



### Built With

* [React JS](https://pt-br.reactjs.org/)
* [React Native](https://reactnative.dev/)
* [Styled-Components](https://styled-components.com/)
* [TypeScript](https://www.typescriptlang.org/)
* [Unform](https://github.com/unform/unform)
* [Axios](https://github.com/axios/axios)
* [Yup](https://github.com/jquense/yup)



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```

* yarn
  ```sh
  npm install --global yarn
  ```

* [EXPO](https://expo.io/) - optional (if you prefer download Xcode and Cocoapods)

* [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)

* [COCOAPODS](https://cocoapods.org/)


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jennifertakagi/go-restaurant.git
   ```
2. Install packages on **mobile** and **web** folders
   ```sh
   yarn | npm install
   ```
3. In case you're using **Macbook**, please run the line above on **ios** folder:
   ```sh
   pod instal
   ```
4. Run JSON server **mobile** or **web** folder to mock database
  ```sh
   yarn json-server server.json -p 3333 | npm run json-server server.json -p 3333
   ```
5. Run the local environment on **mobile** folder
   ```sh
   yarn ios | android
   ```
6. Run the local environment on **web** folder
   ```sh
   yarn start | npm run start
   ```



<!-- USAGE EXAMPLES -->
## Usage

<p align="left">
   <img src="docs/go-restaurant.gif" />
</p>



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/jennifertakagi/go-restaurant/issues) for a list of proposed features (and known issues).



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

Jennifer Takagi - [@jennitakagi](https://twitter.com/jennitakagi)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
* [Supertest](https://www.npmjs.com/package/supertest)
* [JSON Server](https://github.com/typicode/json-server)
* [ESLint](https://eslint.org/)
* [Prettier](https://prettier.io/)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/jennifertakagi/go-restaurant.svg?style=for-the-badge
[contributors-url]: https://github.com/jennifertakagi/go-restaurant/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jennifertakagi/go-restaurant.svg?style=for-the-badge
[forks-url]: https://github.com/jennifertakagi/go-restaurant/network/members
[stars-shield]: https://img.shields.io/github/stars/jennifertakagi/go-restaurant.svg?style=for-the-badge
[stars-url]: https://github.com/jennifertakagi/go-restaurant/stargazers
[issues-shield]: https://img.shields.io/github/issues/jennifertakagi/go-restaurant.svg?style=for-the-badge
[issues-url]: https://github.com/jennifertakagi/go-restaurant/issues
[license-shield]: https://img.shields.io/github/license/jennifertakagi/go-restaurant.svg?style=for-the-badge
[license-url]: https://github.com/jennifertakagi/go-restaurant/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/jennifertakagi
[product-screenshot]: docs/go-restaurant.png
