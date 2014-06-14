# Todoistify
**An Alfred Workflow for Todoist**

This project has been brought to you by [James Mowery](http://mowery.co/).

## Overview

Todoistify is an Alfred (v2) Workflow that allows you to interact with Todoist.

## Instructions

You must first acquire your Todoist API key. Go to the [Todoist website](https://todoist.com/), and then go to Settings (top right), then click on the "Account" tab. Scroll to the bottom and you should see your Todoist API token. Copy it. 

![Locating your Todoist API token](img/docs_api_key.png)

After installing Todoistify, open Alfred, and then type "todoconfig YOUR_API_TOKEN" — replacing "YOUR_API_TOKEN" with the token you copied from Todoist. Hit enter, and now you can interact with Todoist from the Todoistify workflow.

## Using Todoisifty

Type the following within Alfred to access Todoistify functionality:

* **todo [your task description]** — add a task to your inbox
* **todorefresh** — downloads your labels (for viewing)
* **todolabels** — view your labels
* **todoweb** — open Todoist in your default Web browser
* **todoconfig** — add your API token

## Todo