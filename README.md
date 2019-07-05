# Open Table Reservation Module

> Welcome to the Reservations module for OpenRestaurant! The following are required user inputs: party size, requested date, and requested time. This data is sent via HTTP request to the Express server where availability is queried from the MySQL database. Data is returned and the availability is rendered on buttons on the module. 

Styled-Components were used for all modules for this web app to ensure that there would not be any styling conflicts. To ensure symmetry and proper sub-component spacing, I used CSS Flexbox and Grid. Media queries were applied to enable responsive rendering for varying screen devices. 

The reservations module uses the following front-end technologies:
* React
* Javascript
* HTML5
* CSS3 (Grid, Flexbox, media query)

Back-end technologies:
* Node.js
* Express
* MySQL
* Docker
* AWS


## Related Projects

  - https://github.com/krummurk/photos-module
  - https://github.com/krummurk/customer-reviews
  - https://github.com/krummurk/textDetails_module
  - https://github.com/krummurk/reservations-proxy

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

> User selects party size from dropdown menu, time from dropdown menu, and date from dropdown calendar. 

## Requirements

- Node 8.15.1
- MySQL 5.7

## Development

### Installing Dependencies

From within the root directory:

1. npm install
2. //run mysql schema file: mysql -u root -p < ./database/schema.sql
3. npm run seed
4. npm run react-dev
5. npm run server

//server runs on port 3010

