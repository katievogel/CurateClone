# Curate
<p>This is a clone of a group project from my coding bootcamp so that I may easily update and maintain a functional copy for portfolio purposes without requiring pull request approvals from my former bootcamp team</p>

## Table of contents

  * [About this project](#about-this-project)
  * [Getting started](#getting-started)
  * [Video Demonstration](#demo)
  * [Technologies used to create app](#technologies-used)
  * [The Team](#team)

## <a name="about-this-project"></a> About this project
<p>Always getting the art questions wrong at pub quiz? Feeling uncultured when talking amongst your well-versed art posse? Are you just curious about modern art and don’t live near a museum? Or if you’re an artist, needing a source to collect all your contemporary inspirations? Well our app can help with that!</p>

## <a name="getting-started"></a> Getting started
<p>Our app lets you search and save some of your favorite art based on a search for an artist’s name. Users can create a user account and save them to their profile to access them later. Users can also delete them if they no longer want to keep them. Just create a profile to get started!</p> 

## <a name="demo"></a> Video Demonstration

![](client\public\Googenhiem.gif)
You can view the video demo in the link below

https://drive.google.com/file/d/15uzwZcC8KKbTpoWHnVLk-aMBcTLSolPy/view

## Live Deploy

https://curateapp-upenn.herokuapp.com/

## <a name="technologies-used"></a> Technologies used to build app

![](client\public\tech.png)

  * MongoDB (https://www.mongodb.com)
  * Express (https://expressjs.com/)
  * REACT (https://reactjs.org/)
  * Node (https://nodejs.org/en/)
  * Tower (https://www.git-tower.com/)
  * Figma (https://www.figma.com)
  * Lodash (https://lodash.com/)

  ## <a name="team"></a> The Team

  * A.J. Weber: *User-Interface Design & Wireframe* - [A.J.Weber](https://github.com/ajweber102)

  * Katie Vogel: *Serverside and Database* - [Katie Vogel](https://github.com/katievogel)

  * Woodley Johnson: *Authentication Research and Implemtation* - [Woodley Johnson](https://github.com/dawood32913)

  * Yukie Kushibiki: *React Implementation and Code Review* - [Yukie Kushibiki](https://github.com/yutsukushi)



# Setup

There is a client, asset server, API server, and mongo database.

The server connects to mongodb.
* start mongodb - run mongod in terminal; then run mongo in new terminal
* On Digital Ocean, in Linux terminal - follow steps outlined by digital ocean: https://www.digitalocean.com/community/tutorials/how-to-install-mongodb-on-ubuntu-20-04
* start node server.js
* On Digital Ocean, in Linux terminal - follow steps outlined by digital ocean: https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04
* Note the digital ocean outlines can be used with any Linux terminal. They just have really good, clear documentation.

Using Linux terminal:
client
* cd client
* npm run start
server
* node server.js