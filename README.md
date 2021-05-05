# VarrockGE Project

VarrockGE is a full stack web application built with React, Express, and PostgresSQL that allows users to buy, sell, and collect video game collectibles. This serves as the front-end repository. The backend API sever can be found at https://github.com/mcdermottjesse/VarrockGE-api

## Features

* Users can buy and sell video game collectibles.
* When a video game collectible is bought by a user, it is removed from the marketplace.
* The purchase history of a video game collectible is updated when it is purchased from the marketplace.
* Users can sell video game collectibles that they own on the marketplace where they can set their own asking price.
* Users can create and edit collections that contain their video game collectibles.
* Admins can create new video game collectibles.

## Project Setup

1. Fork this repository, then clone your fork of this repository.
2. Crate the .env in the root of the Varrock-api directory. The .env file should have the following content:
`DB_HOST=localhost
DB_USER=vagrant
DB_PASS=123
DB_NAME=final_project
DB_PORT=5432`
3. Install all dependencies:
  `npm install`
4. Install the POSTGRESQL database:
  `npm run db:reset`
5. Start the web server with:
  `npm start`
6. Open your web browser and enter the default URL:
  `http://localhost:3000/`
7. When finished, the server can be safely shut down with `control + c`.

## Final Product

!["VarrockGE home page"](https://github.com/mcdermottjesse/VarrockGE-frontend/blob/master/docs/varrockGE_homepage.png)
!["VarrockGE marketplace filter NFT's"](https://github.com/mcdermottjesse/VarrockGE-frontend/blob/master/docs/VarrockGE-Marketplace.png)
!["VarrockGE main marketplace"](https://github.com/mcdermottjesse/VarrockGE-frontend/blob/master/docs/VarrockGE-Marketplace2.png)
!["VarrockGE collections page"](https://github.com/mcdermottjesse/VarrockGE-frontend/blob/master/docs/VarrockGE-Collections.png)

## Future Development

* Search bar functionality.
* Stripe checkout.
* Subtract funds from user's account upon checkout.
* Implement lootboxes for users to acquire random video game collectibles.
* Host images.
* Youtube video support to purchase video game moments.
* Blockchain functionality.
* Allow users to delete collections.

## Known Bugs/issues

* When a video game collectible is sold on the marketplace, it is not removed from their collections.
* Users are able to add video game collectibles to their cart that they already own.

## Dependencies

* React 17.0.2 or above.
* React Router DOM 5.2 or above.
* Material UI 4.11.2 or above.
* dotenv 8.2.0 or above.
