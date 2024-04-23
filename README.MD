# _Musical Machine_

## _This script creates a Spotify playlist based on the Billboard Hot 100 songs for a specific date._

### _Before running the script, make sure you have the following Python libraries installed:_

- _BeautifulSoup_
- _requests_
- _spotipy_

### _Creating a Spotify Application_

1. _You need to create a Spotify application on the Spotify Developer Dashboard._

   - _Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)._
   - _Log in with your Spotify account or sign up if you don't have one._
   - _Click on "Create an App" and fill in the necessary information._

2. _After creating the app, you will see your Client ID and Client Secret. Copy these as they will be used in the Python code._

3. _Add `http://example.com` as the Redirect URI in the app's settings._

### _Running the Application_

1. _Copy the Client ID and Client Secret from the Spotify Developer Dashboard and replace `"client_id"` and `"client_secret"` in the Python code._
2. _After replacing the placeholders with the actual values, run the Python script._
3. _After running the script, a webpage will open. Click "Agree" and then copy the URL from the browser._
4. _Paste the URL into the console in PyCharm._
5. _Close PyCharm and reopen it. When you reopen it, you will find a new file named `token.txt`._

## _Usage_
 _Once you have completed the steps above, you can run the script, enter the desired date, and a playlist will be created on your Spotify account with the Billboard Top 100 songs for that date._
