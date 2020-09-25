<div align="center"> <img align="center" alt="dschackfest" src="https://user-images.githubusercontent.com/42115530/94295926-a5741880-ff7f-11ea-890b-39ad20ac0f21.png" height='150' width='350'></div>

# Foss-Events
A simple website with a collection of open-source events happening across the globe. This is a beginner-friendly repository that helps you learn git and contribute to web projects.

[![](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/images/0)](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/links/0)[![](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/images/1)](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/links/1)[![](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/images/2)](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/links/2)[![](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/images/3)](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/links/3)[![](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/images/4)](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/links/4)[![](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/images/5)](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/links/5)[![](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/images/6)](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/links/6)[![](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/images/7)](https://sourcerer.io/fame/PragatiVerma18/DSC-JSS-NOIDA/foss-events/links/7)

### Links
- **Frontend**: https://fossevents.netlify.app/
- **Backend**: https://foss-events.herokuapp.com

## Browser Support
- **Firefox**:	version 4 and up
- **Chrome**:	any version
- **Safari**:	version 5.2 and up
- **Internet Explorer/Edge**:	version 8 and up
- **Opera**:	version 9 and up
<!-- > **Note**: Support for modern mobile browsers is experimental. The website is not responsive in mobile devices until now. -->

## Technology Stack used:

<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>  <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<img src="https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=for-the-badge&logo=node.js&logoColor=white"/>   <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/heroku%20-%23430098.svg?&style=for-the-badge&logo=heroku&logoColor=white"/> <img src="https://img.shields.io/badge/express.js%20-%23404d59.svg?&style=for-the-badge"/> <img src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/>

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Node.js, Express.js
- **IDE**: VS Code
- **Version Control**: Git and GitHub
- **Database**: MongoDb
- **Hosting**: Heroku, Netlify

### GitHub Repository Structure

| S.No. | Branch Name | Purpose |
| --------------- | --------------- | --------------- |
| 1. | [master](https://github.com/DSC-JSS-NOIDA/foss-events/tree/master) | contains the frontend code  |
| 2. | [backend](https://github.com/DSC-JSS-NOIDA/foss-events/tree/backend) | contains all backend code |

## Get Started
### Steps for Contributing
<strong>Frontend</strong>
- Fork and clone the Repo by typing the following commands in the terminal 
```
$ git clone https://github.com/your-username/foss-events.git
$ cd foss-events/Frontend
```
- Open this folder in your favourite IDE.  <br>
- Move to `data` folder and open `events.json` file.<br>
- Now to add an event to website, add an object with keys same as listed in existing objects in the file.<br>
- Save and commit your code.<br>
- Push to your fork of the repository , navigate to original repository and make a pull request.<br>

<strong>Backend</strong>
> **Note**: You must have Nodejs installed 

- Fork and clone the Repo by typing the following commands in the terminal 
```
$ git clone https://github.com/your-username/foss-events.git
$ cd foss-events
```
![fork](https://i.postimg.cc/cHx44NPx/Screenshot-152.png)
![clone](https://i.postimg.cc/qqcPttKW/Screenshot-154.png)
![clone](https://i.postimg.cc/T31sxNtz/Screenshot-162.png)

- Change Branch using:
```
$ git checkout backend
$ cd Backend
```
![branch](https://i.postimg.cc/RVsPgQvX/Screenshot-163.png)

- Get connection string from [Mongo Atlas](https://www.mongodb.com/cloud/atlas) by creating a cluster or you can also use your locally installed mongodb
- You can click [here](https://www.youtube.com/watch?v=KKyag6t98g8&t=792s) to learn how to connect atlas to you project
- Paste the connection string in the `.env.example` file in the `DB_CONNECT` variable
- Rename the file `.env.example` to `.env` 
- Install node dependencies using:
```
$ npm install
```
![install](https://i.postimg.cc/jjQPFtzt/Screenshot-164.png)

- To start the server, type:
```
$ node server
```
![start](https://i.postimg.cc/RCbf8Pn6/Screenshot-165.png)

- Make changes to the code(for ex- add an update route) and save your changes
- Commit your changes using:
```
$ git commit -m "made changes"
```
- Push the changes to the forked repository
- Navigate to the original repository and make a pull request

<strong>Currently working Routes</strong>
  - Get Routes:
      - `/event` - Displays all the events
      - `/event/:title` - Displays the details of the specific event
  - Post Routes:
      - `/users/login` - Login Route
      - `/users/signup` - Signup Route
      - `/addevent` - Route for adding an event

## Resources
- **Git and Github**: [Git and Github for Beginners](https://www.youtube.com/watch?v=RGOj5yH7evk)
- **Frontend**: [Frontend development for Beginners](https://www.youtube.com/playlist?list=PL9ooVrP1hQOH2k1SANK5rvq_EAgUKTPoK)
- **Backend**: [Node.js for Beginners](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gcy9lrvMJ75z9maRw4byYp)

### Hurray!!! You just got closer to completing your hacktoberfest challenge. 😃

#### Happy?? Star ⭐ this Repo. 🤩

#### Check your Hacktoberfest Contribution status at: <a href="https://hacktoberfest.digitalocean.com/profile" target="blank">https://hacktoberfest.digitalocean.com/profile</a>

[![ForTheBadge uses-git](http://ForTheBadge.com/images/badges/uses-git.svg)](https://github.com/DSC-JSS-NOIDA/foss-events)
[![ForTheBadge uses-html](http://ForTheBadge.com/images/badges/uses-html.svg)](https://github.com/DSC-JSS-NOIDA/foss-events)
[![ForTheBadge uses-css](http://ForTheBadge.com/images/badges/uses-css.svg)](https://github.com/DSC-JSS-NOIDA/foss-events)
[![ForTheBadge uses-js](http://ForTheBadge.com/images/badges/uses-js.svg)](https://github.com/DSC-JSS-NOIDA/foss-events)

> Made By DSC JSS NOIDA with ❤️
<br><br>
[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://github.com/DSC-JSS-NOIDA/foss-events)
[![ForTheBadge built-by-developers](http://ForTheBadge.com/images/badges/built-by-developers.svg)](https://github.com/DSC-JSS-NOIDA/foss-events)


<!-- <table>
  <tr>
    <td> <img src="https://user-images.githubusercontent.com/42115530/94302134-5c28c680-ff89-11ea-9ca4-5dcdd4279786.png" alt="dscjss"></td></tr>
  <tr><td><a href=""><img src="" alt=""></a></td><td><a href=""><img src="" alt=""></a></td><td><a href=""><img src="" alt=""></a></td><td><a href=""><img src="" alt=""></a></td><td><a href=""><img src="" alt=""></a></td></tr>
  </table> -->
  
  [![Issues](https://img.shields.io/github/issues/DSC-JSS-NOIDA/foss-events)](https://github.com/DSC-JSS-NOIDA/) [![Maintenance](https://img.shields.io/maintenance/yes/2020?color=green&logo=github)](https://github.com/DSC-JSS-NOIDA/)

|                                                                                         <a href="https://github.com/DSC-JSS-NOIDA/"><img src="https://user-images.githubusercontent.com/42115530/94302134-5c28c680-ff89-11ea-9ca4-5dcdd4279786.png"  height=150px /></a>                                                                                         |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                                                                                        **[DSC JSS NOIDA](https://www.linkedin.com/company/dsc-jssaten/)**                                                                                                                                        |
| <a href="https://twitter.com/DSCJSSATEN"><img src="https://rmutrecht.org/wp-content/uploads/sites/259/2017/07/logo-twitter.png" width="32px" height="32px"></a>  <a href="https://www.linkedin.com/company/dsc-jssaten/"><img src="https://www.iconfinder.com/data/icons/popular-social-media-flat/48/Popular_Social_Media-22-512.png" width="32px" height="32px"></a> |

> **_Need help?_** 
> **_Feel free to contact us @ [dscjssnoida@gmail.com](mailto:idscjssnoida@gmail.com?Subject=DSCHackFest2020)_**

[![GitHub followers](https://img.shields.io/github/followers/DSC-JSS-NOIDA.svg?label=Follow%20@DSC-JSS-NOIDA&style=social)](https://github.com/DSC-JSS-NOIDA/) [![Twitter Follow](https://img.shields.io/twitter/follow/DSCJSSATEN?style=social)](https://twitter.com/DSCJSSATEN)
