# Todoistify
**An Alfred Workflow for Todoist**

Todoistify is created and maintained by [James Mowery](http://mowery.co/).

## Overview

Todoistify is an Alfred (v2) Workflow that allows you to easily interact with [Todoist](https://todoist.com/).

## Initial Setup

The initial setup requires you to find and add your Todoist API key so that Todoistify can interact with your Todoist account.

### Locating Your Todoist API key

* Login to the [Todoist website](https://todoist.com/)
* Go to Settings (on top right)
* Click on the "Account" tab
* Note your Todoist API token. 

![Locating your Todoist API token](img/docs_api_key.png)

### Adding Your API token To Todoistify

* Type **todoconfig *your api token*** (replace *your api token* with your actual Todoist API token)
* All done!

## Using Todoisifty

**Note**: Italics indicate text you can enter. Single brackets [] denotes optional text.


### Adding A Task To Your Inbox


* **todo *your task***: Add a task to your inbox
* **todo *your task* *[!p1 ... !p4]***: Add a task with a priority (see below)

### Other Commands

* **todoweb**: Open Todoist in your default Web browser
* **todoconfig *todoist api key***: Add your API token to use Todoistify

## Priorities

When adding a task, add the following anywhere within your entry to add a priority:

* **!p1**: Default (**not required**); results in no priority
* **!p2**: Low priority
* **!p3**: Medium priority
* **!p4**: High priority