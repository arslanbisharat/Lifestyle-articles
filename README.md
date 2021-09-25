

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]


#LifeStyle Articles

  <p align="center">
    This project is the Capstone of the Microverse curriculum at the end of the Ruby on Rails module!
    <br />
    <a href="https://github.com/arslanbisharat/lifestyle-articles"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/arslanbisharat/lifestyle-articles/issues">Report Bug</a>
    ·
    <a href="https://github.com/arslanbisharat/lifestyle-articles/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
  * [Walkthrough Video and Deployment (Heroku)](#walkthrough-video-and-deployment-(heroku))
* [Usage](#usage)
* [Database Structure](#database-structure)
* [Contributors](#contributors)
* [Acknowledgements](#acknowledgements)
* [License](#license)

<!-- ABOUT THE PROJECT -->
## About The Project

This is the Capstone project that signs the completion of the RubyOnRails module in the Microverse Curriculum.
It is a web app where users can register using their name, username, password and can sign in with their username only.
As a logged-in user, it is possible to create articles, edit profiles, comment, vote and bookmark an article for future reads.
The app can be used also on read-only mode, with restricted access to its features.

### Built With
This project was built using these technologies.
* Ruby & Ruby on Rails
* Rspec / Capybara
* Bootstrap
* HTML / CSS / SCSS
* SQLite
* Rubocop
* GithubActions :muscle:
* Atom :atom:

<!-- Live Demo -->
## Walkthrough Deployment (Heroku)

##
* Live Demo Link --> App Deployed with Heroku: [LifeStyle-Articles](https://lifestyle.herokuapp.com/) :point_left:

### Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Ruby: 2.6.6
Rails: 5.2.4

### Clone
* [download](https://github.com/arslanbisharat/lifestyle-articles/archive/development.zip) or clone this repo:
  - Clone with SSH:
  ```
    git@github.com:arslanbisharat/lifestyle-articles.git
  ```
  - Clone with HTTPS
  ```
    https://github.com/arslanbisharat/lifestyle-articles.git

### Setup

Install gems with:

```
$ bundler install --without production
```

Setup database with:

```
$ rails db:migrate
$ rails db:seed
```

### Usage

Start server with:

```
$ rails server
```

Open `http://localhost:3000/` in your browser and sing in with a user already defined --> :point_right: ```maxinova``` :point_left:
- for any technical problems running ```rails db:migrate:reset && rails db:seed``` should solve it

#### Create User

Fill the signup form to create a user

![screenshot](app/assets/images/sign_up.png)

#### Login

Use only the username to login

![screenshot](app/assets/images/log_in.png)

#### Create a new article from the dropdown menu

Type your title and text, add an image, category, and a tag

![screenshot](app/assets/images/post.png)

#### Bookmarked articles

Articles can be bookmarked and will be saved in `Your Bookmarks

![screenshot](app/assets/images/follow.png)

#### Edit User Profile

User profile can be edited along with the profile's picture

![screenshot](app/assets/images/cover.png)

  ## Automated Test

* Run the command and see the output: 
```$ bundle exec rspec```
![Rspec](app/assets/images/rspec.png)

## Database Structure
 * Database schema used for this project reflects the following structure:
 ![erd](app/assets/images/erd.png)
 
 ## Potential future features
- Extend the signin / signup process to social accounts, use verified email process
- Improve the front-end

<!-- CONTACT -->
## Contributors


## :handshake: Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/arslanbisharat/lifestyle-articles/issues).

## Show your support

Give a :star: if you like this project!


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Microverse](https://www.microverse.org/)
* [Ruby Documentation](https://www.ruby-lang.org/en/documentation/)
* [Ruby on Rails](https://rubyonrails.org/)
* [Bootstrap](https://getbootstrap.com/)
* [Behance](https://www.behance.net/)
* [Heroku](https://www.heroku.com/)

## Credits
* Nelson Sakwa - [liFEstIye](https://www.behance.net/gallery/14554909/liFEsTlye-Mobile-version)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/arslanbisharat/lifestyle-articles.svg?style=flat-square
[contributors-url]: https://github.com/arslanbisharat/lifestyle-articles/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/arslanbisharat/lifestyle-articles.svg?style=flat-square
[forks-url]: https://github.com/arslanbisharat/lifestyle-articles/network/members
[stars-shield]: https://img.shields.io/github/stars/arslanbisharat/lifestyle-articles.svg?style=flat-square
[stars-url]: https://github.com/arslanbisharat/lifestyle-articles/stargazers
[issues-shield]: https://img.shields.io/github/issues/arslanbisharat/lifestyle-articles.svg?style=flat-square
[issues-url]: https://github.com/arslanbisharat/lifestyle-articles/issues

## 📝 License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.
