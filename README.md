# End-to-End  Large Image Model Application with Gemini

## Table of Contents
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [What It Does](#what-it-does)
  * [Getting Started](#Getting-started)
  * [Usage](#usage)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Techstack Used](#techstack-used)
  * [License](#license)
  * [Credits](#credits)

## Demo
[Link:](Project_Demo_Showcase.mp4)

https://github.com/user-attachments/assets/e6e964ba-0a06-4be3-95ad-d513f56e38c9

## Overview

This is an End-to-End Application where an image is upoaded on to the streamlit front end and then user requests the response from the Large Image model("Gemini-1.5-flash" here) using a query. So, the model gives information specific to the image uploaded based on the user query.

## Motivation

To leverage the potential of Google Gemini Pro for innovative use cases in content generation, image interpretation, and creative problem-solving.

## What it Does
  * We create an environment for the project, install all the required libraries, create Google API Key and then load all the environment 
    variables on to the current environment.
  * Once the entire application is initialized, Google API Key is loaded.
  * Streamlit frontend is created. An Image is dragged and dropped from the local system onto the web page. Then user enters the query prompt.
  * The model generates response only when the "Tell me about the image" button is clicked.
  * Based on the response, one can understand how the model is performing.
    
## Getting Started
  We will get started with installation and set up process. Clone the repository and open the folder using Vs Code.
  ### Clone this repository into a local folder:
  ```
  git clone https://github.com/dhanushpittala11/End-to-EndLLM-and-Large-Image-Model-Application-with-Gemini
  ```
  If conda is not installed, run this command in the terminal of the project environment.
  ```bash
  pip install conda
  ```
  ### Setup Environment using:
  ```bash
  conda create -p venv python==3.10 -y
  ```
  ### Activate the environment:
  ```bash
  conda activate venv/
  ```
  ### Install all the required libraries and packages using the command:
  ```bash
  pip install -r requirements.txt
  ```
  ### Create a .env file. Create Google API Key in Google AI studio and paste it in a .env file. 
## Usage
  ### Now run the script using:
  ```bash
  streamlit run vision.py
  ```
## Directory Tree

## To Do

## Bug / Feature Request

## Techstack Used

## License

## Credits
