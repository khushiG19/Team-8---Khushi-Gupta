This Python code defines a Streamlit web app for scraping news articles from a specific website based on user-selected date parameters. The app includes input fields for choosing the ``year``, ``month``, and ``day`` of the news, along with an option to toggle between English and Hindi ``languages``. Users can click a "Scrap" button to initiate the scraping process.

Upon clicking the "Scrap" button, the code sends a ``request`` to the specified website, extracts news articles using ``BeautifulSoup``, and displays them in a Streamlit interface. Each news article is presented in a stylized box with a clickable link to the original article. The app provides a visual representation of the scraped news for the selected date.

## Aim of the Project:

1. **News Scraping:** Extract news articles from a specific website based on user-selected date parameters.
2. **User Interaction:** Provide a user-friendly interface using Streamlit for users to input the desired date and language preferences.
3. **Visualization:** Display the scraped news articles in a visually appealing format with clickable links.

## Technologies Learned:
1. **Streamlit:** Used for building interactive web applications with minimal code.
2. **BeautifulSoup:** Employed for web scraping, extracting structured data from HTML and XML files.
3. **Requests:** Utilized for sending HTTP requests to the specified website to fetch web pages.
4. **HTML/CSS Styling:** Applied to enhance the visual presentation of scraped news articles in the Streamlit app.
5. **Python:** The primary programming language for building the entire application.
