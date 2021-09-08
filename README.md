<img src="application/public/images/retail/marketplace_retail.png" alt="dashboard" height="400">

# Usage

## Retail Marketplace (MongoDB, NodeJS, ExpressJS, ReactJS & JWT)

### Clone Repositorie

Clone this Repositorie to your local machine

```
git clone https://github.com/eugenebelieve/marketplace-retail.git
```

### Add Env Variables

Create or modify the .env file in then root and add the following

```
NODE_ENV = 'development'
PORT = '5000'
MONGO_URI = "YOUR_MONGODB_URI_HERE"
JWT_SECRET = 'random_secret_key'
PAYPAL_CLIENT_ID = 'YOUR_MONGODB_PAYPAL_ID_HERE'
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend Application (:3000) & Microservices (:5000)
npm run dev
```

### Dataset Import

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# To Import Retail & User Data
npm run data:retail

# Destroy data
npm run data:destroy
```

```
#Sample User Logins created once imported

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

jane@example.com (Customer)
123456
```

## More Previews (Product & Shopping Cart)

<div>
<img src="application/public/images/retail/product.png" alt="dashboard" height="250">
<img src="application/public/images/retail/kart.png" alt="dashboard" height="250">
</div>