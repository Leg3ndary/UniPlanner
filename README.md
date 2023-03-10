# Ben-Zhou---HDSB-2023-Hackathon-Submission

Ben's 2023 Hackathon Submission

# UniPlanner

![Image](https://i.imgur.com/Zd3q5iW.png)

March 3rd 2023 Project Start!

## What?

Often times, after high school, students attend a post secondary institution, often a university to further their education. However, the process of applying to these universities can be very stressful and time consuming, students only really are given the tools necessary to start planning near the start of grade 12 through OUAC. This is where UniPlanner comes in. UniPlanner is a web application that allows students to keep track of their university applications and sample questions that they might be asked during the application process. They can also keep track of their grades and other important information that they might need to know or any special notes about that certain university. Students may also mark a certain "Cards" as I've named them, important which gives them a little star next to the card.

In addition there are many small QOL features for this app, you can colour cards, change the view, do everything in dark mode and create applications for many universities.

You can test out the app [here](https://ben-hdsbhacks.netlify.app/).

## Technologies Used

This was actually my first ever time using React and Typescript with the intent of creating something semi production ready, I've used them both in the past but only in theory and never practically. I think both technologies are interesting, the type checking in Typescript is very useful and I think I'll be using it in the future over javascript just due to how much more neat it can make my code. React on the otherhand was a pain, I've migrated between svelte, and vue and so far both are looking like better options. Why? React forces you to follow some design principles which admittedly the other frameworks do too, but some of the design principles just don't make sense to me. Svelte for example has if statements when rendering "components" which could've allowed me to implement some features much faster and better than I could in react. One of these being making application questions pop up directly instead of directly putting them in the field. I also used a tiny bit of previous python knowledge to quickly parse json files for the data I needed.

That being said I should also note I did get that list from https://github.com/Hipo/university-domains-list, I also asked ChatGPT for the sample questions as I thought it might be interesting to see what they said.

As for storage, if I do continue this project I will probably use a sql database to store all the data, I've considered mongo, but I think a relational database would be better.

I also used tailwind for the first time, this was actually pretty nice in my opinion, having to relearn a lot of the attributes was a bit of a pain but in the end I think the time that it saves is well worth it, you should definitely give it a shot.

## Future Steps

In the future as I've mentioned I would like to actually incorporate a real database over local storage, I would also like to adjust some of the colors but as per time constraints I decided to focus on actual features.

## Running this project

You will need to download the latest version of Node.js and npm here: https://nodejs.org/en/download/

Then, you will need to install the dependencies by running `npm install` in the root directory of the project.
After you can simply run `npm start` to start serving locally, if you want to build the project for performance reasons and serve locally you can run `npm run build` and then follow the following instructions.

The few python and json files are just quick files I used to pull the universities I wanted from the universities list. This list also includes domains and such if I ever want to add that functionality later.

## Progress

### Day 1

I've decided to use https://github.com/aridsm/tasks-app as a base theme and template for my project.

It has most of the components I need and I will be editing the cards to suit my needs.

### Day 2

I had a chess tournament and did fairly well!

- Started to remove unessary things and update all the basic stuff (Mismatched text, styles I don't like etc.)
- Starting to think about how I'm going to format this
    - Will have list of university applications on the left, each with certain sample questions the university might ask
    - Will be able to add more sample questions and grades to each application

### Day 3

Hopefully today I'll able to finish everything up, I won't be using a database since I don't need to have this ready for prod and everythings gonna be stored in the browser since its fast, also won't be doing user authentication for now.

- Finished up basic layout
- Added a few sample questions, generated by chatgpt lol
- Added colors
- Added more sorting options and functions
- Added more fields along with a pop up for cards
- Added universities and lists
- Added sample questions
- Added separate sections for each card
- Fixed up dark and light mode errors
- Changed layout to be more simplistic

I've done a lot today and there's obviously more but those are the main things I've done