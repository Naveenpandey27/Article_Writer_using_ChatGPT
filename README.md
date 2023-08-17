# Article_Writer_using_ChatGPT

Searching the Internet...

# SEO Article Writer with ChatGPT

This is a simple application that generates SEO-optimized articles using OpenAI's ChatGPT model. It allows you to specify a keyword, writing style, and word count to generate an article.

## Getting Started

To use this application, you need to have an OpenAI API key. If you don't have one, you can sign up for an account on the OpenAI website and obtain your API key.

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies by running the following command:

   ```
   pip install -r requirements.txt
   ```

3. Open the `main.py` file and replace `"INSERT YOUR API KEY HERE"` with your actual OpenAI API key.

## Usage

1. Run the application by executing the following command:

   ```
   streamlit run main.py
   ```

2. Once the application is running, you will see a web interface with the following options:
   - **Keyword**: Enter the keyword for the article.
   - **Writing Style**: Select the desired writing style from the dropdown menu.
   - **Word Count**: Use the slider to choose the desired word count for the article.
   - **Generate Article**: Click this button to generate the article.

3. After clicking the "Generate Article" button, the application will display a message indicating that it is busy generating the article. Once the article is generated, it will be displayed on the screen.

4. You can also download the generated article as a text file by clicking the "Download article" button.

![article](https://github.com/Naveenpandey27/Article_Writer_using_ChatGPT/assets/66298494/4ea997c4-a024-4866-95bb-4249d42ce2b3)


## Notes

- The application uses OpenAI's ChatGPT model to generate the articles. Please note that the model's responses may not always be perfect, and it's recommended to review and edit the generated articles before publishing them.
- The application limits the word count to a minimum of 300 and a maximum of 2000, with a step size of 100. You can adjust these limits in the code if needed.
- Make sure to keep your API key secure and avoid sharing it with others.

That's it! You now have a simple and easy-to-use SEO Article Writer with ChatGPT. Happy writing!
