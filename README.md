## THE NEWS
## Description
[![codebeat badge](https://codebeat.co/badges/a4071666-790b-4585-a28f-98021938220f)](https://codebeat.co/projects/github-com-rosa1-maker-the-news-dev)

<p>News  is a web appliction that displays a list of news sources from around the world. A user is able to click on a news source and view an abreviated version of the particular news article. Clicking on the news article will then redirect you to the news article's web page.</p>

## Behavior Driven Development
Behaviour	Input	Output
  It displays news sources	on page and load	List of various news sources  per category.
 Click a news source to display articles from a news source.
 To display the preview of an article	On page load	Each article displays an image, title, description and publication data

## Prerequisites
<p>You need the following to start working on the project on your local computer:</p>
-Python version 3.6
-Flask
-Pip
-virtualenv
-A text  Editor

## Installations
<ol>
<li>Clone this repository to your local computer.</l>
<li>Ensure you have python3.6 installed in your computer.</li>
<li>From the terminal navigate to the cloned project folder.</li>
<li>Create a virtual environment and access the folder via your virtual amchine.</li>
<li>Visit https://newsapi.org/ and register for an API key.</li>
<li>Create start.sh file and in it write the foInstallationsllowing lines:</li>
 export NEWS_API_KEY='<Your-Api-Key>'
 python3.6 manage.py server
<li>Run chmod +x start.sh follwoed by ./start.sh while in the project folder to start the project.</li>
<li>Once started, the project can be accessed on your localhost using the address: localhost:5000.</li>
<li>Visit https://news-teresa.herokuapp.com/ to view my site</li>
 </ol>

## Technologies Used
Python v3.6,
Boostrap and
Flask


## License

MIT License


Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. Copyright (c) 2018 Peter Polle

Copyright (c) 2020 @ Teresa Wanjiku
