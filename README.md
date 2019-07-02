# Project-Initializer

This is Bash Script to Automate your first time Project set up. This Bash script executes a Python Script to automate the process for setting up Github project and initialize the folders on desktop. The python script uses selenium Webdriver to automate the process.

## Development Status

* Still under development
* In very unstable condition, use at your own risk

## Instructions

* Make sure you have Python installed
* Enter this in terminal: `pip install selenium`
* You should have installed a Selenium supported WebDriver for your favorite web browser. we used chrome's webdriver for this purpose
  * Download link for Chrome web driver: [Chrome Web Driver](http://chromedriver.chromium.org/downloads)
  * Download link for Firefox web driver: [Firefox Gecko Driver](https://github.com/mozilla/geckodriver/releases/)
* It'd be better if you placed files under "bin" in "/bin" of your linux machine.
* You can still run this perfectly fine without following the last step:
  * With the current directory as pwd, type this in terminal: `chmod u+x bin/createproject` to make it executable.
  * Now, enter `./createproject <project-name>` in terminal to create a project using Project-Initializer.
