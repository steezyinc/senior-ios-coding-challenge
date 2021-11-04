# STEEZY Senior iOS Coding Challenge


## Context

Your task is to bring the next generation of dance education to users around the world! Your team has just handed you a spreadsheet full of dance classes they've curated and is counting on you to build an MVP to bring this idea to life. We need you to build an iOS app that can allow our users the ability to view these dance classes and track their progress on this online dance platform! 

## Product Requirements

### [Feature] Display class list and play video

As a user,  
I want to navigate to the classes index page and view instructional dance videos,  
so that I can take class and improve my dance skills.

**Acceptance Criteria**

As a user:

- [ ] I want to be displayed a list of classes offered to me.
- [ ] I want to know what the title of each class is.
- [ ] I want to know who the instructor of each class is.
- [ ] I want to navigate to the /video View Controller when clicking on a class using iOS native AvPlayer (in Figma) for each class url
- [ ] I want to be able to play, pause, and seek the videos on the video view.
- [ ] I should be able to exit the video and return to the list of classes

### [Feature] Track user's progress

As a user,
I want STEEZY to track my progress,
so that I know how well I'm progressing in my dance journey.

**Acceptance Criteria**
As a user: 

- [ ] I want to track what timestamp I progressed to in class. For example, if I watched 30 seconds of the video and paused, my progress timestamp should be recorded at 30 seconds.
- [ ] I want to track what percentage of the class I actually played.
  - Case 1: User repeatedly watches the first 10% of the video. The progress should only be 10%.
  - Case 2: User watches the first 15% of the video. The user seeks back to 0% and watches up to 20%. The user has only watched a total of 20% of the video.
  - Case 3: User watches the first 10% and the last 10% of the video. The user has watched a total of 20% of the video. The total progress should be 20%.

## Your Goal

Create an iOS app that satisfies as many product requirements as you can for your team above. Please list any assumptions you took while building your application in the `Assumptions` section below. Feel free to implement any nice-to-have requirements or styling (please add these to Assumptions as well). 

To achieve this you will need to utilize the CSV/spreadsheet data provided in this repository. The CSV should be dumped into some kind of data store and accessed through an API. Feel free to use a database you are most comfortable with.

You are welcome to use any type of boilerplate or frameworks for your application as long as it meets the technical requirements below. We encourage you to use your favorite packages and tools to build a solid application, but try to keep it as simple as possible!
 

## Technical Requirements
- Swift
- You can create your UI in XIBs or code or a combination of both, but try to avoid using a Storyboard if possible

## Instructions
- Clone this repository.
- Build a performant, clean and well-structured solution.
- When you're finished please send us instructions on how to access your service and download a ZIP of the project using the Github GUI and send us an email with the attachment to notify us.

Best of luck and happy coding!

## How to Run  
Please provide any special instructions to run your app


## Assumptions
Please list any assumptions or extra requirements you added to the application while developing below.
