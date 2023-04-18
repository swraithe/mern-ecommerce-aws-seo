
##MERN eCommerce Project with AWS Integration and SEO

This project is a MERN (MongoDB, ExpressJS, ReactJS, NodeJS) stack eCommerce website with integrated AWS services and optimized for SEO.<br/>
The website allows users to browse and purchase products, manage their cart and orders, and also provides admin capabilities such as adding new products and managing orders.

##Features
User Authentication & Authorization
Product management (CRUD operations)
Cart management
Payment processing (with Stripe)
Order tracking
AWS integration (S3 for media files and CloudFront for content delivery)
SEO optimization (keywords, meta tags, sitemap)
Technologies Used
MongoDB Atlas (Database)
Express.js (Server)
React.js (Client)
Node.js (Runtime)
AWS S3 (Media Storage)
AWS Cloudfront (Content Delivery Network)
Stripe (Payment Processing)
Installation Instructions / Getting Started
Clone the repository onto your local machine.
Install the packages by running npm install in both the root directory and the client directory.
Create a .env file in the root directory with the following environment variables:
NODE_ENV (development or production)
PORT (port number for server)
MONGO_URI (URI of MongoDB database)
JWT_SECRET (secret key for JSON Web Tokens)
STRIPE_API_KEY (API key for Stripe payment processing)
AWS_ACCESS_KEY_ID (Access Key ID for AWS services)
AWS_SECRET_ACCESS_KEY (Secret Access Key for AWS services)
AWS_REGION (Region for AWS services)
AWS_BUCKET_NAME (Name of S3 bucket for media storage)
AWS_CF_DOMAIN (Domain name for CloudFront CDN)
Start the development server using npm run dev.
Contributing Guidelines
Please feel free to contribute to this project by submitting a pull request. Before making any major changes or adding new features, please open an issue first to discuss the proposed changes.

License
This project is licensed under the MIT License.
