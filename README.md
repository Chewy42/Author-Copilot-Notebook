# Author-Copilot-Notebook
A Jupyter Notebook that uses OpenAI's gpt-3.5-turbo or gpt-4 to generate a book based on a prompt.

## Requirements
* Python
* OpenAI API Key and Org Id (make a .env file in the root directory)
* Pandoc

## Installation
* Clone the repo
* Install the requirements (pip install -r requirements.txt)

## Usage
1. Create a .env file in the root directory with the following variables:
    * OPENAI_API_KEY
    * OPENAI_ORG_ID
2. Edit the config.json file to your liking (Do not change the "book_format" parameter)
3. Make a folder in the root directory of the project called `eBook-Saves`
4. Run the Jupyter Notebook
5. Check eBook-Saves folder foryour new eBook

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)