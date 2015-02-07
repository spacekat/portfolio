---
layout: post
title:  "Add-ons design process"
date:   2012-11-01 23:15:42
categories: UI
thumbnail: images/add-ons/thumb-addons-planning.jpg
creation-date: 2012-11-01 23:15:42
short-description: Planning & wireframes
---

In 2012, Engine Yard was planning to launch a new feature which gives customers the ability to add third-party software to their applications.

### My goal

The development of the API for this feature was already underway when I first joined the Add-ons team. I came in to help create a clear user interface for customers to activate add-ons for their applications.

### The Challenge
_Add-ons were complicated._

The API for add-ons had already been defined, and it didn't allow for "one-click activation". Since third party services are widely varied in their functionality, different add-ons had different requirements. 

Most add-ons had somewhere between 2-4 required steps to get set up. Some needed complex application code changes before they could integrate. A handful of uncomplicated add-ons only could be added in one click, but for most that was not the case.

I wanted to create an interface with a familiar flow for setting up these disparate add-ons.

### The plan

My plan was to address add-on activation in these three steps (counter-clockwise from the upper left.)

![Add-ons steps](/images/add-ons/add-ons-steps.jpg)

**Step 1.** Browse all the available add-ons.

**Step 2.** View details and pricing information on a specific add-on.

**Step 3.** Put that add-on in your application. Sometimes this would mean a few additional steps. Sometimes only one.

### Step 1: Browsing add-ons

We were launching this feature with about ten add-ons (with the hope of adding many more in the future)

**Research:** To better understand user expectations, I looked at other add-ons registries in the same space (Heroku, Cloudbees, Rackspace) - and also at how other online marketplaces (like iTunes and the Google Chrome Store) display their offerings.

**My conclusions:** The add-ons needed to be easily scannable and searchable. I created a grid of small tiles, each with one add-on. The search and category filters are on the left menu. 

The name and the logo of each of the add-ons would be useful for instant recognition and search-ability. A short description would be helpful for someone who didn't immediately recognize an add-on.

![Add-ons preliminary index](/images/add-ons/add-ons-index-preliminary.jpg)

**Early progress making the index page.**

### Completion status

On the homepage, I needed a way for users to differentiate between an unused and in-use add-ons. I sketched the tiles and their possible states: Available, partially activated (incomplete), and fully activated.

![Add-ons tile flag](/images/add-ons/add-ons-tile-flag-wireframe.jpg)

**Activated add-ons have a diagonal banner in the upper right.**

### Refinement

The logo of each add-on was added. The two calls-to-action "Enable" and "Details" were replaced with just one: "Details." When an add-on is fully setup, the pink "enabled" flag is in the upper right corner, and the "Details" button becomes "Manage".  Category filters were made more clear in the left sidebar.

![Add-ons index with flag](/images/add-ons/add-ons-index-better.jpg)

### Step 2: View Details

Clicking on an add-on from our marketplace would reveal more details about the service and it's pricing. A user could proceed to set it up from this view.

Add-ons had lengthy pricing details and complex integration instructions. Initially, I experimented with simply a "Setup" button to take users to the step(s) after Sign up.

![Add-ons view details](/images/add-ons/add-ons-details-sketch.jpg)

**Initial layout for the details page.**
  
### Step 3: Add-on activation
**First attempt**

On the Setup page there was a link back to the details page in the upper right.

Because of the numerous steps on this page we decided to break the setup into separate pages.

### Showing the steps

We wanted users to see what further steps needed to be taken, and indicate how far along they are in the process. To do this, I made a blue bar that describes the four setup steps:

**1.Sign up.** Add-on details and sign up button.

**2. Activate.** Select which application to use it on.

**3. Update code.** Make configuration file changes in the application's code.

**4. Deploy.** Deploy application.

The white pointer at the bottom indicates which step the customer is on.

![Add-ons steps](/images/add-ons/add-ons-details-step.jpg)

The "Activate, Update Code, and Deploy" steps are semi-transparent until the required "Sign Up" is complete. The customer can still see the instructions and content on these pages, but there is a message at the top that says "you first need to sign up".

### Activate

The Activate step lets customers choose which environment will use the add-on.

![Add-ons steps](/images/add-ons/add-ons-activate-step.jpg)

When an environment is chosen, it is listed underneath.

![Add-ons steps](/images/add-ons/add-ons-activate-step-done.jpg)

### Update code

This step contains instructions for customers to edit their application code.

![Add-ons code step](/images/add-ons/add-ons-code-step.jpg)

### Deploy

The final step is to re-deploy the environment. This step provides a link to the page in the app where customers do their deployments.

![Add-ons deploy step](/images/add-ons/add-ons-deploy-step.jpg)

### Next steps

We launched the Add-ons and started looking at which were most popular and other usage patterns, like whether users deploy the same add-on on different environments or across many of their apps.

I learned that customers were getting confused on steps that kicked them off to the third party site for sign up or activations. In these cases, the flow back to our app wasn't always clear. This often resulted in users having multiple windows open, each on a different setup step.

Currently I am exploring different ways to improve that interaction. I'm leaning toward a separation of the "add-on details" and the "setup" page, putting the setup steps all on one page.

![Add-ons future](/images/add-ons/add-ons-future.jpg)
