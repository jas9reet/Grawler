<p align="center">
  <img width="600" height="300" src="/images/grawler.svg">
</p>

# Grawler - v1.0


Grawler is the best tool ever, made for automating google dorks it's a tool written in PHP which comes with a web interface that automates the task of using google dorks, scrapes the results, and stores them in a file, version 1.0 is the more powerful than ever supporting multiple proxies. ( Read in features )

## Table of contents
* [General info](#general-info)
* [Features](#features)
* [Setup](#setup)
* [Demo](#demo)
* [Contribute](#contribute)
* [Contact Me](#Contact-me)


## General info 
Grawler aims to automate the task of using google dorks with a web interface, the main idea is to provide a simple yet powerful tool that can be used by anyone, the thing that makes Grawler different in its category is its features.

	
## Features
* The biggest issue faced by tools that automate google dorks is CAPTCHA, but with Grawler, CAPTCHA is not an issue anymore, Grawler comes with a proxy feature which supports three different proxies.
	* Supported Proxies ( The mentioned proxies need you to signup and get the API key, without any credit card information and give you around one thousand                   	      free API calls each )
		* [ScraperAPI](https://www.scraperapi.com)
		* [Scrapingdog](https://www.scrapingdog.com)
		* [Zenscrape](https://zenscrape.com)
* Grawler now supports two different modes.
    * Automatic Mode : Automatic mode now comes with many different dork files and supports multiple proxies to deliver a smooth experience.
    * Manual Mode : The manual mode has become more powerful with the Depth feature, now you can select the number of pages you want to scrape results from, proxy feature is also supported by manual mode.
* Dorks are now categorized in the following categories:
    * Error Messages
    * Extension
    * Java
    * JavaScript
    * Login Panels
    * .Net
    * PHP
    * SQL Injection (7 different files with different dorks)
    * My_dorks file for users to add their own dorks.
* API keys for proxies are first validated and added to the file.
* Manual mode allows users to go up to depth 4, but I'd recommend using depth 2 or 3 because the best results are usually on the initial pages.
* Grawler comes with it's own guide to learn google dorks.
* The results are stored in a file ( filename needs to be specified with txt extension ).
* URL scraping is better than ever with no garbage URL's at all.
* Grawler supports three different search engines are supported (Bing, Google, Yahoo), so if one blocks you another one is available.
* Multiple proxy with multiple search engines delivers the best experience ever.

## Setup
* Download the ZIP file
* Download XAMPP server
* Move the folder to htdocs folder in XAMPP
* Navigate to http://localhost/grawler 
* Results will be stored in same directory

## Docker 

* docker pull jas9reet/grawler
* docker run -d -p 8080:80 jas9reet/grawler

#### Application Access

* YOUR-IP-ADDRESS:8080

## Demo
* [How to run grawler in automatic mode?](https://youtu.be/mJq8tcCWvm4)
* [How to run grawler in manual mode ?](https://youtu.be/L5zdxb7QOFE) 


## Contribute
* Report Bugs
* Add more effective google dorks (which actually works)
* Work on portability
* Suggestions

## Contact Me
You can contact me here [A3h1nt](https://twitter.com/A3h1nt) regarding anything.
