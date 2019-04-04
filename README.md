# NewEgg-Review
Mock Review component of newegg.com

## Dependencies
* Node.js
* Express
* React
* SQLite3
* Mocha
* Chai

## Project Overview
Data was generated to a SQLite database for reviews for 100 items using the `sqlite3` driver for Node.js. The `faker` Node module was used to generate fake names, dates, review titles and bodies. Functions written by me were used to determine whether reviewers were verified owners, the rating given, and the associated item number for each review.

Using Node.js with an Express framework, data was served to the front-end and displayed using the React framework. Data was filtered and sorted using React. CSS was used to simulate graphs.

## Getting Started
#### Data Generation
`node database/sqlite.js`

#### Webpack
`npm run react-dev`

#### Server
`npm install nodemon`

`npm run server-dev`

## Project Gallery
![Animation](https://user-images.githubusercontent.com/43562922/55526412-052b8500-5663-11e9-95c1-b9a152596cfd.gif "Animation")
![NavBarOptions](https://user-images.githubusercontent.com/43562922/55527392-d3b4b880-5666-11e9-9ca7-227a78b5a3a8.png "Navigation and Options")
![Reviews](https://user-images.githubusercontent.com/43562922/55526760-33f62b00-5664-11e9-8444-0a2fd7ded3b0.png "Review")

## Special Thanks
[Marc](https://github.com/omenwolf "Marc Choa")

[Geo](https://github.com/gferrer807 "Geo Ferrer")
