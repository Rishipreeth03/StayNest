# StayNest

StayNest is a full-featured online marketplace, similar to Airbnb, where users can find and book accommodations worldwide. StayNest offers a seamless experience for both travelers and hosts, including advanced search filters, real-time availability, and secure user authentication.

## Features

- **User Authentication**: Secure login and registration system using JWT (JSON Web Tokens) for users to sign up, log in, and manage their profiles.
- **User Roles**: Separate user roles for guests and hosts, allowing hosts to list properties and guests to book stays.
- **Property Listings**: Hosts can create, edit, and manage property listings, including descriptions, photos, pricing, and availability.
- **Search & Filters**: Advanced search with filters such as location, price range, property type, amenities, and availability.
- **Real-Time Booking**: Users can view available dates and make instant or request-based bookings.
- **Messaging System**: In-app messaging between guests and hosts to ask questions or clarify details about the stay.
- **Reviews & Ratings**: Guests can leave reviews for their stays, helping future travelers make informed decisions.
- **Payment Integration**: Secure payment system that allows users to pay for bookings directly through the platform.
- **Host Dashboard**: Hosts have access to a dashboard where they can manage bookings, view earnings, and respond to guest inquiries.



## Tech Stack

- **Frontend**: React.js, Next.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens), bcrypt for password hashing
- **Payment Gateway**: Stripe API
- **Real-Time Messaging**: Socket.IO for real-time communication


## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v14.x or higher)
- [MongoDB](https://www.mongodb.com/)
- [Stripe API](https://stripe.com/) account for payment integration

###Installation

npm i


nodemon app.js


## Setup Instructions

To run this project, you need to set up a `.env` file with necessary environment variables. Follow these steps:

1. **Create a `.env` file** in the root directory of the project.
2. **Add the following environment variables** to the `.env` file and fill in each with your credentials:

   ```plaintext
   CLOUD_NAME=
   CLOUD_API_KEY=
   CLOUD_API_SECRET=

   MAP_TOKEN=

   ATLASDB_URL=

   SECRET=
