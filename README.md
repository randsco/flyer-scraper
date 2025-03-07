# flyer-scraper

Scrapes flyers of ambiguous origin.

## Prerequisites
### Download and install Google Chrome
1. If you do not have Google Chrome installed, [download the latest version of Google Chrome](https://www.google.com/chrome/) for your operating system. Otherwise, [download and add chromedriver to the project](#Download-and-add-chromedriver-to-the-project).
1. Install following the [Google Chrome installation instructions](https://support.google.com/chrome/answer/95346?hl=en&co=GENIE.Platform%3DDesktop) for your operating system.
### Download and add chromedriver to the project
1. [Download chromedriver](https://googlechromelabs.github.io/chrome-for-testing/) appropriate for your operating system.
1. Extract the chromedriver files into the same folder as flyer-scraper.Rmd.
### Download and install dependencies and add Selenium standalone server to the project
1. [Install Java](https://www.java.com/en/download/help/download_options.html) for your operating system.
1. [Download the Selenium standalone server](https://selenium-release.storage.googleapis.com/index.html?path=3.5/).
1. Move the Selenium standalone server .jar file into the same folder as flyer-scraper.Rmd.

## Run the flyer scraper
1. Navigate to the project directory and [run the Selenium standalone server](https://www.selenium.dev/documentation/legacy/selenium_2/remote_server/).
1. Open the flyer-scraper.Rmd project.
1. Run the chunks to install the required packages, import packages and initialize functions, and initialize an empty tibble.
1. Run the chunk to open a new browser session.
1. Add links of flyers to scrape in `flyer_list`.
1. Run the chunk that contains the scraping code.
