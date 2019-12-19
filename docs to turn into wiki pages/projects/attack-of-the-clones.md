# Attack of the Clones

### Description

Create a website that clones an already existing app

For this project we will be using React to create components on the front end, and Laravel to create a RESTful API to store data and facilitate pretty url handling.



This project is testing your ability to take a vertical slice of a project. Deconstructing a website should be about 50% of the work, seeing the atomic design, breaking down elements, figuring out which technology does what, planning what is and is not within the scope of this project, agile documentation, architecture design, etc.

### Table of contents

<!--ts-->
- [Attack of the Clones](#attack-of-the-clones)
		- [Description](#description)
		- [Table of contents](#table-of-contents)
		- [MVP](#mvp)
			- [Wireframe](#wireframe)
			- [Tech Stack](#tech-stack)
		- [Process](#process)
				- [Setup:](#setup)
				- [Develop:](#develop)
				- [Deploy:](#deploy)
		- [Requirements](#requirements)
			- [Additional Requirements](#additional-requirements)
			- [Stretch Goals](#stretch-goals)
			- [If you finish early...](#if-you-finish-early)
		- [Additional Resources](#additional-resources)
<!--te-->

### MVP

By default, the clone app should replicate the design and functionality of the real app front end as closely as possible. The back end is required to pull from the mySQL server as an API and generate/store data and maintain users, data, and state.

It *is* possible to [put React directly on a blade](https://dev.to/lvtdeveloper/using-react-in-a-laravel-application-8fp), but this type of archetecture is known as [RESTless, or SOAP](https://pediaa.com/what-is-the-difference-between-restful-and-restless-web-service/#:~:targetText=The%20main%20difference%20between%20RESTful,does%20not%20follow%20RESTful%20principles.&targetText=Moreover%2C%20a%20web%20service%20is%20platform%20independent.), which is more resource intensive and would now be considered a poor practice in comparison. You can experiment with a RESTless web server in the [Laravel Library](https://github.com/bootcamp-students/Projects-Exercises/blob/master/docs/projects/laravel-library.md)


#### Wireframe

* [Twitter wireframe](https://twitter.com/awesome_inc)
* [Gmail wireframe](https://mail.google.com/mail/u/0/)
* [Trello wireframe](https://trello.com/b/0Bn39pyt/bootcamp-f19)
* [Slack/Discord wireframe](https://app.slack.com/client/TKV4DCHDH/CL8LDQGTY)
* Or choose your own! (must be approved by us first)

#### Tech Stack

1. React
2. MySQL
3. Laravel


### Process

##### Setup:

1. Create repo **locally**, for example: `my-app` 
2. Locally, navigate to your `sites` folder in the terminal
3. Create necessary files for application and view in VS Code via CLI
4. Initialize directory as repo and [link to existing repo you created on GitHub](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line)
5. Import and route necessary css/js files (E.g. Bootstrap)
6. Save all and create your first commit to `master` 

##### Develop:

1. Create a `dev` branch to commit your code to
2. Add content and elements to your website
3. View changes and test locally
4. Save often, and commit to your development branch on GitHub when important changes happen
5. Push your commits to GitHub remote
6. For bug fixes, refactored code, and feature branches, you must create a branch off of `dev` onto a `new-feature` branch and create a PR into dev when complete

##### Deploy:

1. Create a Pull Request from `dev` into `master` 
2. Confirm code is up to date and works correctly
3. Post links to your GitHub repo to the Projects Slack channel

---

### Requirements

To complete the assignment, you must complete the following:

1. In your sites folder, create a new folder called "clone-project"
2. `cd clone-project` 
3. You will create two separate projects, this is what is known as a [RESTful API](https://restfulapi.net/)
4. `npx create-react-app react-ui` 
5. `laravel new laravel-api` 

---

1. Deconstruct the webapp you plan to clone (do not worry about matching fonts or images/colors, we are only concerned with design layout and components/functional features) - create an MVP, MoSCoW, and Stories.
2. Follow atomic design principles for deconstructing the original web app look

   - Atoms -> Molecules -> Organism (component)

3. **Create the backend first** using Laravel for API CRUD calls and to store data
4. **Create the frontend second** using React for creating components and connecting to the API via Axios
5. Have full CRUD functionality (besides the users auth) for at least one aspect of the site (does not need to be complicated)
6. Utilize one to many, many to one, one to one, many to many, and create connection tables, joins, and indexes for ease of use.
7. Create automated functions to generate dummy data to display on the react ui by utilize the factory design pattern
8. Use GitHub Projects for kanban board story management
9. Use a random text generator [API](http://www.randomtext.me/) _or_ [NPM package](https://www.npmjs.com/package/casual) to create random tweets/emails/usernames/trello cards etc...
10. Add this project to your portfolio as a link

* For example, in gmail:
* Create a new email in drafts (CREATE)
* Read an email by clicking on it (READ)
* Change the state from unread to read (UPDATE)
* Delete an email (DELETE)

#### Additional Requirements

* Website must be responsive
* Style your app as you wish
* Use the tools and technologies covered in class to complete your website. To see what we have covered, check the [Class Resources Repo](https://github.com/bootcamp-students/Resources).
* Your repo should be public so that others can see your code and comment on it.
  + _**Remember to push to GitHub!**_
  + Potential employers will view your GitHub profile, so activity is crucial!

#### Stretch Goals

* Create an MVP detailing all facets of the wep app you plan to clone
* Connect your app to a server to have multiple people be able to log in and use it at the same time (gmail clone users can email each other, twitter clone users can @ and follow each other, etc)

#### If you finish early...

1. Continue to add your own content, additions, and pages to your site and improve the styling.
2. Add info to your projects README.md [README.md Best Practices](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
3. Add links and resources from this week to the [Class Resources Repo](https://github.com/bootcamp-students/Resources) by forking the repo and then initiating a pull request with your additions to the .md file.

### Additional Resources

* Ask questions :-)
* [Class Resources Repo](https://github.com/bootcamp-students/Resources)
* Learn more about [Good GitHub Practices](https://guides.github.com)
* [Atomic Design Principles - book](http://atomicdesign.bradfrost.com/)
* [How to Deconstruct a Website (2010)](https://www.smashingmagazine.com/2010/05/case-study-deconstructing-popular-websites-opinion-column/)
* [How to Deconstruct a Website (2017)](https://github.com/dsinecos/notes/wiki/How-to-deconstruct-a-website's-front-end-for-learning%3F)

For more information about clone apps, see these articles:

* [What is an app clone?](https://www.quora.com/What-is-an-app-Clone)
* [How much does Uber cost?](https://thinkmobiles.com/blog/how-much-cost-make-app-like-uber/)
* [When You Can’t Innovate, Copy](https://hbr.org/2012/05/when-you-cant-innovate-copy)
* [The Copycats Of Silicon Valley](https://www.inc.com/yazin-akkawi/why-are-silicon-valley-companies-copying-each-other.html)
* [Self Retweeting Tweet](https://www.youtube.com/watch?v=zv0kZKC6GAM)
