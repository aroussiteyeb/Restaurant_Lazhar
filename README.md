# Lazhar Restaurant App

## Features

- View Menu Items
- Search Items
- Add Items to cart
- Delete Items from cart
- Add Items to Favorites
- Place Order
- Track Order
- Cancel Order
- Sign Up
- Sign In
- Reset Password
- Update Profile Info/Pic
- Logout


## Tech Stack

- Javascript ES6
- Stylesheet
- BootSplash (for splash screen)
- Formik
- Yup
- Firebase (database)
- Redux (user state management)


## Run Locally 

### Step 1
- Run this command `git clone https://github.com/aroussiteyeb/Restaurant_Lazhar.git`
- Make sure that you are in the root directory of the project, use pwd or cd for windows
- `cd restaurant_Lazhar`
- `npm install`

### Step 2
- Create a New Project in Firbase and connect with your app
- Enable Email/Password Authentication
- Unzip this [file](https://github.com/Noor-e-Iqra/Bismillah-Restaurant-App-React-Native/files/8242352/bm-restaurant.zip) and import it in your Realtime Database
- Copy your Realtime database Url and paste it in `database.js` file located under `constants/`
- Create a Storage Bucket

### Step 3
- Paste your GOOGLE MAPS API KEY in `AndroidManifest.xml` here
- `<meta-data
        android:name="com.google.android.geo.API_KEY"
        android:value=" Your Google Maps Api Key"/> `
        
### Step 4
- Run `npx react-native run-android`
