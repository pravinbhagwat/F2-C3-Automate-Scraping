Project Overview (100 Marks)
Task
Automate scraping of trending javascript repositories and developers’ details from the GitHub, Trending page using Puppeteer or Cheerio
You are required to use Puppeteer or Cheerio to automate the process of scraping data from the GitHub Trending page and store the extracted data in a JSON object.
URL - https://www.github.com/trending

Requirements
Use Puppeteer/Cheerio to automate browsing to the GitHub Trending page and retrieve the HTML content.


Use Puppeteer/Cheerio to extract the relevant data from the HTML content.


The content you need to extract is repo-title, description, URL, stars, forks, language
Extract the following information for all listed repositories. The content you need to extract is the repo title, description, URL, stars, forks, language
Click on developers. And select javascript from the language section
Fetch the following information for all listed developers
1. Name of developer 2. User name of the developer 3. Repo name & description

3. Store the extracted data in a JSON and console.log it
4. Your JSON should look like this as shown in the video -
https://drive.google.com/file/d/1rZUeB2otQ6YSO5a5tBsAC2tEq3nzWKc-/view
Steps to Follow:
Create a new project folder and open it in your code editor.
Initialize a new npm project by running the command npm init.
Install the required packages: npm install puppeteer cheerio.
Create a new JavaScript file called index.js and then write the code necessary.
Save the JSON you get in a variable and console.log it.
Marking Scheme (100 Marks)
Puppeteer to automate the browsing - 25
Puppeteer/Cheerio to extract data - 25
Extracting all relevant data - 25
Storing it in a variable and console.log it - 25