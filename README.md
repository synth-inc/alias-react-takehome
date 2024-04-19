# alias-react-takehome
This is a frontend exercise that will give you the chance to see what kind of things we build at Synth, Inc!

You will be building a simplified version of our  app, the Alias (www.alias.inc). Alias is an app that allows users to face-swap with AI-generated faces. With Alias, users can create secret digital identities, which they can use to create psuedoanoynmous online content. You will be recreating our main "Home" page, which shows a user's media. 

We've spun up an endpoint on our server to return a sample grid of media objects as a JSON blob. You can access the endpoint here: https://alias-server-prod-396ba8378bb2.herokuapp.com/public/mock/feed

Your task is to create a React+Typescript application that uses the data from the sample endpoint to create the interface in the design file. We've created a sample project here, which you should use a starter template. Please use Typescript and Vite!

You can find a design and explanation of each element in this Figma file: 
https://www.figma.com/file/LyGVmDqAcKyTEgeJYBfM4Y/Alias-Takehome-Challenge

<img width="1049" alt="Screenshot 2024-04-19 at 11 28 31 AM" src="https://github.com/synth-inc/alias-react-takehome/assets/1915325/deff73fc-9285-4e78-ad82-0bd95dde3c9d">

Note, we are only providing mobile designs. For the sake of this exercise, there is no need to build a Desktop version. 

We will have 3 hours to make as much progress on this task as possible. While we recognize it will be difficult to finish everything, part of our goal with this exercise is to understand how you prioritize. 

## The Challenge
- You will have three hours to complete this challenge
- You are free to use any available tools or documentation
- Please use Typescript
- Follow this [design](https://www.figma.com/file/LyGVmDqAcKyTEgeJYBfM4Y/Alias-Takehome-Challenge) as closely as you can

## Setup
1. `npm install`
2. `npm run dev`

## Feed Endpoint
- `https://alias-server-prod-396ba8378bb2.herokuapp.com/public/mock/feed`

## Checklist
- How closely did you follow the design?
- Are all the elements interactable?
- Does routing between the home page and video viewer page work?

## Bonus
- Can you sync the playback of the before and after videos?
- Can you make the progress bar track the playback of the video?
- Can you launch a default share sheet when the 'share' button is tapped?
- Can you handle failed API requests gracefully? 
