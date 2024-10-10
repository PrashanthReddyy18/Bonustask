# Bonustask

# Twitter API with Go: Post and Delete Tweets

## Introduction

This project demonstrates how to interact with the Twitter API using Go. The goal of this task  is to learn how to authenticate using OAuth 1.0a, post a new tweet, and delete an existing tweet with user consent. Additionally, it covers error handling for failed API requests and invalid credentials.



## Setup Instructions

### Step 1: Set Up a Twitter Developer Account

1. Go to the [Twitter Developer Platform](https://developer.twitter.com/) and sign in with your Twitter account.
2. If you dont have account, creat a new one.

### Step 2: Generate Twitter API Keys

1. In the Twitter Developer Dashboard, navigate to **Projects & Apps** → **Your App**.
2. Generate the following keys and tokens:
   - **API Key (Consumer Key)**
   - **API Secret Key (Consumer Secret)**
   - **Access Token**
   - **Access Token Secret**


### Step 3: Clone the Repository

git clone https://github.com/PrashanthReddyy18/Bonustask.git
cd Bonustask
touch .env  
# Add the below content in .env file
CONSUMER_KEY=your_consumer_key
CONSUMER_SECRET=your_consumer_secret
ACCESS_TOKEN=your_access_token
ACCESS_SECRET=your_access_secret

### Step 4: Add the code in main.go for Post and delete a tweet actions in twitter

After adding the code in main.go and giving the keys in .env file save them

## Execute
Run the code by using the command Go run main.go and the tweet is posted and the result is as shown below


*PS C:\Users\marup\Documents\Code\go\src\github.com\PrashanthReddyy18\Bonustask> go run main.go
*Posted tweet with ID: 1844418276157182291
*PS C:\Users\marup\Documents\Code\go\src\github.com\PrashanthReddyy18\Bonustask> go run main.go
*Posted tweet with ID: 1844419197461225641
*PS C:\Users\marup\Documents\Code\go\src\github.com\PrashanthReddyy18\Bonustask> go run main.go
*Posted tweet with ID: 1844439102071927278
*Do you want to delete this tweet? (yes/no): yes
*Deleted tweet with ID: 1844439102071927278

