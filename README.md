# ice-breaker

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** Markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
-->


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="static/logo.png" alt="Logo" width="90" height="100">
  </a>

<h3 align="center">LLM IceBreaker</h3>

  <p align="center">
    LLM IceBreaker with a Flask web application
    <br />
    <a href="https://github.com/jpcadena/ice-breaker"><strong>Explore the docs
»</strong></a>
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#security">Security</a></li>
    <li><a href="#code-of-conduct">Code of Conduct</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>  </ol>
</details>



<!-- ABOUT THE PROJECT -->

## About The Project

![Project][project-screenshot]

IceBreaker is a Flask-powered web application that harnesses the power of LangChain and OpenAI's Large Language Models (LLM) to create engaging and personalized IceBreaker strategies. By integrating with social media APIs such as Google Search, Twitter, and LinkedIn, IceBreaker offers a unique approach to connecting with people online, leveraging the advanced capabilities of ChatGPT for intelligent, context-aware interactions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built with

[![Python][python-shield]][python-url] [![Flask][flask-shield]][flask-url] [![Pydantic][pydantic-shield]][pydantic-url] [![OpenAI][openai-shield]][openai-url] [![Google][google-shield]][google-url][![Twitter][twitter-shield]][twitter-url] [![LinkedIn][linkedin-shield]][linkedin-homepage][![HTML5][html5-shield]][html5-url] [![CSS3][css3-shield]][css3-url] [![isort][isort-shield]][isort-url] [![Black][black-shield]][black-url] [![Ruff][ruff-shield]][ruff-url] [![MyPy][mypy-shield]][mypy-url] [![pre-commit][pre-commit-shield]][pre-commit-url] [![GitHub Actions][github-actions-shield]][github-actions-url] [![Poetry][poetry-shield]][poetry-url] [![Pycharm][pycharm-shield]][pycharm-url] [![Visual Studio Code][visual-studio-code-shield]][visual-studio-code-url] [![License: MIT][license-shield]][license-url]

### Components

- **Flask Backend**: Serves as the backbone of the application, handling HTTP requests, API interactions, and serving dynamic content using Jinja2 templating.

- **LangChain with OpenAI LLM**: Utilizes advanced language models for generating personalized and contextually relevant IceBreaker suggestions.

- **Social Media Integration**: Leverages APIs from Google Search, Twitter, and LinkedIn to gather insights and tailor conversations effectively.

- **Frontend**: Built with HTML and CSS, providing a user-friendly interface for interaction.

This application stands out by combining cutting-edge AI with practical social media insights, offering a novel way to break the ice in digital communications.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->

## Getting started

### Prerequisites

- [Python 3.11][python-docs]

### Installation

1. Clone the **repository**
   ```
   git clone https://github.com/jpcadena/ice-breaker.git
   ```
2. Change the directory to **root project**
   ```
   cd ice-breaker
   ```
3. Install **Poetry** package manager
   ```
   pip install poetry
   ```
4. Install the project's **dependencies**
   ```
   poetry install
   ```
5. Activate the **environment**
   ```
   poetry shell
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->

## Usage

1. **Setting up environment variables:**

   If you find a `.env.sample` in the project directory, make a copy of it and rename to `.env`.

   ```
   cp .env.sample .env
   ```

   This `.env` file will be used to manage your application's environment variables.


2. **Configuring your credentials:**

   Open the `.env` file in a text editor and replace the placeholder values with your actual credentials.
   ```
   # .env file
   TWITTER_API_KEY=your_x_api_key
   OPENAI_API_KEY=your_openai_api_key
   ```
   Be sure to save the file after making these changes.


3. **Starting the WSGI server:**

   To start the local server on your machine, run the following command in your terminal:

   ```
   flask run --debug
   ```

   The `--debug` flag enables debug mode and hot reloading, which means the
   server will automatically update whenever you make changes to the code.


4. **Interacting with the app:**

   Once your server is running, you can interact with it using the
   Javascript client at your web browser at `http://localhost:5000`.


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->

## Contributing

[![GitHub][github-shield]][github-url]

Please read our [contributing guide](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SECURITY -->

## Security

For security considerations and best practices, please refer to our [Security Guide](SECURITY.md) for a detailed guide.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CODE_OF_CONDUCT -->

## Code of Conduct

We enforce a code of conduct for all maintainers and contributors. Please read our [Code of Conduct](CODE_OF_CONDUCT.md) to understand the expectations before making any contributions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>