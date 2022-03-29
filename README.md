# social-network-api

![License: MIT](https://img.shields.io/badge/License-MIT-blue)

## Table of Contents:

- [Git-Repository](#git-repository)
- [Demo-Video](#walktrough-video)
- [Description](#description)
- [Build-Process](#build-process)
- [API-end-points](API-end-points)
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)
- [Screenshots](#screenshots)

## Git Repository

I created a git repository folder that will host the finished project. The Repository will be found [here](https://github.com/pfansi/social-network-api)

## Link to the walktrough video

- Demo that shows test to CREATE users, RETURN a single user and all users, UPDATE and DELETE user details in Insomnia. [click here](https://drive.google.com/file/d/13EHiHyiCyGSaT6NST1RH4bzd5Mi6pw4E/view)
- Demo video that shows test to ADD and REMOVE FRIEND in Insomnia. [click here](https://drive.google.com/file/d/1g9-_Q5m1GKm72PtGQBezsSqrKl05oY8k/view)
- Demo video that shows test to to CREATE, UPDATE , DELETE, RETURN a single and all THOUGHTS in Insomnia.. [click here](https://drive.google.com/file/d/1BhGZ2irzsgJV8kSTD8NGSVJX79W8WmUX/view)
- Demo video that shows test to CREATE and REMOVE REACTION in Insomnia. [click here](https://drive.google.com/file/d/1g9-_Q5m1GKm72PtGQBezsSqrKl05oY8k/view)

## Description:

This project is to build an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. We will use Express.js for routing, a MongoDB database, and the Mongoose ODM. Additionally a native JavaScript `Date` object to format timestamps will be used.

## Build process

- created a readme file and the project described
- file structure created
- created an environment to test all the requested API end point for the application

## API end points

#### users

- Get all users: GET /api/users
- Create a user: POST /api/users
- Get user by ID: GET /api/users/:id
- Update a user: PUT /api/users/:id
- Delete a user: DELETE /api/users/:id
- Add a friend: PUT /api/users/:userId/friends/:friendId
- Delete a friend: DELETE /api/users/:userId/friends/:friendId

### Thought

- Get all thoughts: GET /api/thoughts
- Create a thought: POST /api/thoughts
- Get thought by ID: GET /api/thoughts/:id
- Update a thought: PUT /api/thoughts/:id
- Delete a thought: DELETE /api/thoughts/:id

### Reaction

- Add a reaction: PUT /api/thoughts/:id/reactions
- Delete a reaction: DELETE /api/thoughts/:id/reactions

## Installation:

---

Run this command to install dependencies:

  <pre><code>
  npm install
  </code></pre>

## Usage:

```md
You have to install MongoDB on your local machine
```

---

Run this command to start the app:

  <pre><code>
  npm run start
  </code></pre>

```md
Then Use your browser or an app like Insomnia to test the REST API.
```

## Tests:

Run this command to run the test

<pre><code>
  
  </code></pre>

## License:

[License: MIT](https://opensource.org/licenses/MIT)

# This Project is licensed under the MIT license

## Contributing:

Project is open for contributions.

## Questions:

- **Contact details:**
  - Github: [@pfansi](https://github.com/pfansi)
  - Email: pfansi76@gmail.com

## Screenshots

- Total test executed screenshot. br/
  ![screenshot]()

- Screenshot of the
  ![screenshot]()
