<a name="readme-top"></a>

<!--
HOW TO USE:
This is an example of how you may give instructions on setting up your project locally.

Modify this file to match your project and remove sections that don't apply.

REQUIRED SECTIONS:
- Table of Contents
- About the Project
  - Built With
  - Live Demo
- Getting Started
- Authors
- Future Features
- Contributing
- Show your support
- Acknowledgements
- License

OPTIONAL SECTIONS:
- FAQ

After you're finished please remove all the comments and instructions!
-->

<div align="center">
  <!-- You are encouraged to replace this logo with your own! Otherwise you can also remove it. -->
  <br/>

  <h3><b>Budget App</b></h3>

  ![UML Class Diagram of Catalog of my things](ERD_Diagram.png)

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ (OPTIONAL)](#faq)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 [Budget App] <a name="about-project"></a>

**[Budget App]** The Ruby on Rails Budget App is centered around the creation of a mobile web application designed for budget management. In this application, users can efficiently oversee their financial transactions by categorizing them. By doing so, they can gain insight into their spending patterns, allowing them to track their expenses and understand where their money is allocated. This project not only showcases the use of Ruby on Rails but also serves as a practical tool for individuals to maintain control over their finances.

## 🛠 Built With <a name="built-with"></a>

- Ruby on Rails

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li>Ruby on Rails</li>
  </ul>
</details>

<details>
  <summary>Test</summary>
  <ul>
    <li>RSPEC</li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li>PostgreSQL</li>
  </ul>
</details>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LIVE DEMO -->
## 🚀 Live Demo <a name="live-demo"></a>

- [Live Demo Link](https://budget-app-x0v6.onrender.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Presentation Video -->
## 🎥 Presentation Video <a name="presentation-video"></a>

- [Presentation Video Link](https://www.loom.com/share/019e038d603d449e9b11861e6a54ccbc?sid=0919fc8c-5fc7-4243-84ff-53945b632f93)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

- Git/GitHub;
- Optional ( IDE installed in your machine ) - recommended IDE: Vscode;
- Ruby on Rails Installed in your machine;

### Setup

- To clone this repo:
  - Open the Terminal(Mac/Linux) or the Cmd (Windows);
  - Navigate to where you want to paste the Repo folder;
  - Run the following commands
```
git clone https://github.com/jubaer919/budget-app
cd Budget-App
```


### Install
```
  bundle install
```

### Setup Database
```
  rails db:create
  rails db:migrate
  rails db:seed
```

### Usage
```
rails server
```
### Run tests
```
rspec spec
```

<!-- Features -->

### Key Features <a name="key-features"></a>

- **Add Category** - Add your favorite categories.
- **Add Transactions** - Add transactions for a specific categories.
- **Sign up and log in pages**
- **Use devise gem for authentication**
- **Secure app from n+1 problems**
- **Set up associations between models**
- **Limit access to webapp resources based on authorization rules**
- **Unit tests and integration tests** - Test methods, controllers and views

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

👤 **Jubaer Maruf**

- GitHub: [jubaer_Maruf](https://github.com/jubaer919)
- Twitter: [@jubaer_maruf](https://twitter.com/jubaer_maruf)
- LinkedIn: [Jubaer Maruf](https://www.linkedin.com/in/jubaer-maruf/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- [ ] **[Add more dynamic pages]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/jubaer919/budget-app/issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>


If you like this project give ⭐️

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to express my gratitude to Microverse for initiating the idea behind this project and Original design idea by [Gregoire Vella on Behance](https://www.behance.net/gregoirevella).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
