## Ben Musil - Experience and Bio
Thank you for stopping by! My name is Ben and I am married and father to one (so far!). I was born and raised in Austin, Texas but am open to relocation! I graduated from Texas A&M with a degree in Mechanical Engineering but I have steered my career towards software engineering and web development through further education, taking on more responsibilities at work, and pursuing personal projects to practice those skills.

<img src="resources/ben-family.jpeg" alt="Picture of Ben's family"
	title="Ben's Family" width="400px"/>

**Table of Contents**
- [Statement of Purpose and Goals](#statement-of-purpose-and-goals)
- [Education](#education)
- [Employment](#employment)
- [Skills](#skills)
- [Projects](#projects)
  - [Line Picker](#line-picker)
  - [IsThereAnyDeal Finder](#isthereanydeal-finder)
  - [Boardgame Deals and Hub](#boardgame-deals-and-hub)
- [Personal Life and Interests](#personal-life-and-interests)

## Statement of Purpose and Goals
In the short-term, I am seeking a software developer position in web with opportunities within an Agile-like environment.

My long-term is to become first a full-stack developer and then a software architect. I want to be involved with planning the layout and structure of a whole application or platform. I enjoy figuring out a structures that work with several different technologies as well as sharing that vision with a small team. In addition, I want to collaborate with other experienced developers who can help me figure out how several pieces of a platform can mesh together well for the current situation as well as future growth. I've experienced architectures that failed to plan for future expansion and it became a huge mess very quickly. I would like to prevent that so others don't have to share that frustration.

## Education

**Texas A&M University** — *B.S. Mechanical Engineering, Minor in Computer Science, December 2017*

**University of Texas** — *M.S.E. Software Engineering, August 2019 - Present*

## Employment

**[The Catholic Woodworker](https://catholicwoodworker.com/)** - *Website and Production Developer, June 2020 - Present (Part-time)*

- Set up automation of inventory management with AirTable formulas between
parts purchased for stock and parts consumed for a customer-purchased
product
- Writing a tool that takes marked cells in AirTable and interacts with a third party Shopify app to automatically populate custom product field options ([click here for a link to custom product page](https://catholicwoodworker.com/products/custom-rosary-designer))

**[Applied Materials](http://www.appliedmaterials.com/)** — *Test Engineer II, January 2018 - June 2020*

- Wrote front-end components and data layers to communicate with our SQL database using C# with Visual Studio for a company-wide software application to test hardware products
- Designed software interfaces using National Instrument’s IDE, LabWindows CVI, for use by technicians to test a variety of hardware products
- Developed back-end functionality for software interfaces using C to communicate with product hardware

## Skills
In the [Projects](#projects) section below I denote what technologies I used with each project. As a complete summary of tools and languages I've used, please see the following:
- Web Front-end: React
- Web Back-end: Node.js, MongoDB, MySQL, Flask, Express, Firebase
- Mobile: React Native, Android SDK
- OOP Languages: Python, C, C++, C#, Java/Kotlin
- Tools: JIRA, GitHub, GitLab, Visual Studio, IntelliJ, LabWindows CVI, Shopify, AirTable, Balsamiq, Postman

## Projects

[Here is a link to all my public repositries on GitHub](https://github.com/benjamin-musil)

### [Line Picker](https://github.com/benjamin-musil/line-picker-webapp)
*Mobile and Web App - React Native, Android SDK, MongoDB, Flask, Firebase*

Uses crowdsourced data to find out wait times of nearby restaurants based on category of food, distance to user, favorite category set by user, and other similar criteria. Users can submit wait times for specific restaurants with a picture to show the activity of the restaurant. Users also have the ability to add restaurants and check previous post history.

I worked with three other developers on this multi-platform app. Flask supported the app's back-end. The Android app front-end was written natively using Android SDK and refactored to include iOS compatibility with React Native. 

I wrote the interactions and links between Flask and MongoDB for data storage and filtering data. I used the Google Maps API for location services and Android/iOS camera APIs for capturing images and storing those images to local storage.

Please excuse the rough screenshots below, the focus for this project was on the back-end functionality.

[Native Android app repository](https://github.com/benjamin-musil/line-picker-android) | [React Native app repository](https://github.com/benjamin-musil/line-picker-react-native)

![Mobile Restaurant Search](resources/LinePicker/mobile-restaurant-search.png)
![Mobile Restaurant Data](resources/LinePicker/restaurant-wait-data.png)
![Mobile Wait Time Submission](resources/LinePicker/wait-time-submission.png)
![Desktop Restaurant Search](resources/LinePicker/restaurant-list-desktop.png)


### [IsThereAnyDeal Finder](https://github.com/adamdavies001/isthereanydeal-lookup)
*Discord Bot - Node.js*

 Looks up active deals for PC games through the [IsThereAnyDeal](IsThereAnyDeal.com) API when the bot is pinged in a Discord server. Users can add sellers to ignore. A feature for a server-curated wishlist and automated notifications is in progress. I am actively developing this with another person. This was originally a bot for our own private server, but we are making it so that it can be used by the public. Potential for income through affiliate links, however we'd have to create our own web scraper or interact with other API tools per the agreement with IsThereAnyDeal's API usage.

I am writing the server-curated wishlist portion of the bot. I have refactored code to use an API endpoint once instead of multiple times. I updated the response to be able to return multiple games as well as give more info such as a cover image of the game and user reviews if they are available.

<img src="resources/deals-example.gif" alt="Example of the deal finder looking up a game"
	title="Showing Deals for Wreckfest" />

### Boardgame Deals and Hub (in progress)
*Web App - MERN stack*

Taking inspiration from [DekuDeals](DekuDeals.com), I want to make a modern price tracker for board games while providing tools for library management. [Boardgamegeek](Boardgamegeek.com) is a popular site for board game stats but I feel it's lacking when it comes to finding games on sale and the design is a bit noisy for my taste. Other sites also track board game prices, but I would like present data such as a user score, send notifications to users, and generate recommendations for each user. I also want to bridge the gap between physical and digital players, especially with the current times of social distancing, which means tracking standalone digital games and DLC for platforms such as Tabletop Simulator.

This project is still in the beginning stages I currently have a framework setup and I'm working on a front-end mock-up. I will likely port some code for the digital tracking from the IsThereAnyDeal bot above.

Planning to monetize through affiliate links so the repo is private at this moment. Will post screenshots as the project progresses.

## Personal Life and Interests
Hey, I'm not a developer 100% of the time either! I love my fair share of leisurely activity and spending time with family, friends, and strangers. If I didn't have to work, I would love to host and lead guided tours for parks around the country and even the world. There are so many national, state, and local parks across the country and not enough people take time away from being "plugged-in" to find peace of mind in nature! My favorite parks I have visited are the Yosemite, Big Bend, and Rocky Mountain National Parks. Other outdoor activities I enjoy are basketball, tennis, and running.

Aside from that, I am the barista dad at home. I started my coffee journey with really awful big-batch coffee at a job but I evolved through grinding my own beans for custom Keurig cups, using a french press, and finally graduated to the beloved espresso machine. My normal go-to is an Americano because I love to taste the beans and not the flavor of milk or additives distract from the beans.

With that caffeine, I enjoy reading all types of books and discussing philosophy and theology. I am Catholic and I welcome respectful dialog with people of other viewpoints and I enjoy meaningful engagement with people of all walks of life. My favorite fictional series is Lord of the Rings (I can't tell you how awesome the audiobooks are by Rob Inglis) and I often have a rotation of 4 or 5 fictional and non-fictional books. Come share a local craft beer with me and we can talk about all sorts of books and movies!

Speaking of movies, I'm a Nicolas Cage afficiando and I even hosted a Nic Cage Friday weekly event in my freshman dorm in college. My favorite Cage movie is Face/Off because you get both a good movie and an insane Nicolas Cage. Travolta is a bonus because he is basically a Nicolas Cage clone in that movie.

I'm also a gamer at heart, both board games and video games. I have a large bookshelf dedicated to games such as Catan, Dominion, Carcassonne, King of Tokyo, Elder Sign, and many others. For video games, I'm primarily on PC but I play just about anything from retro or modern, indie or AAA. With older games I love finding community support such as the [OpenRCT2](https://openrct2.org/) project for Chris Sawyer's Roller Coaster Tycoon. I've even hosted game servers for 7 Days to Die and Roller Coaster Tycoon using my 2012 Thinkpad (which I still use because hey it works).

A couple on-going projects I have (meaning I have the supplies but I haven't built yet) are transforming an Arcade1Up cabinet I bought on discount to integrate with a RetroPie and upgrade the cabinet hardware to plan virtually any arcade game. I also bought a used IKEA table that is the perfect size for a custom board game table with leaves that can be taken out for a recessed surface along with cupholders and other small board game accessories.
