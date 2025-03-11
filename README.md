# LLMscientist

A simple Python and Docker-based app for iterative data analysis using an LLM.

### Usage

Install Docker and WSL.

Clone this repository and then navigate in the terminal to the directory where it is saved.

Use your personal API key by running

    set API_KEY=YOUR-API-KEY 

in the terminal. Optionally, you can also set the model to o1 like this:

    set MODEL=o1

Otherwise, GPT-4o will be used. You can reset to 4o by setting MODEL=4o. Then run
 
    docker-compose up --build

The application will run in localhost:5000.
