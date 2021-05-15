## Clubhouse-EDA
* We take a dive into the highly popular iOS only invite-only audio chat app, Clubhouse
* Link to the dataset - https://www.kaggle.com/johntukey/clubhouse-dataset?select=Clubhouse_Dataset_v1.db 
* We divide users in differet clusters and analyse them based on their profile completeness
* User Bio is not available in the used dataset; so we analyse emojis for emoji based ad targetting similar to twitter
* For analysis based on emojis a fair assumption has been made that emoji's are more of a personal touch so they provide correct information
## Summary
* The dataset has *1300515* unique user ids and **1300514** unique users
* Each user has following details :
    1. user_id
    2. name
    3. photo_url
    4. username
    5. twitter
    6. instagram
    7. num_followers
    8. num_following
    9. time_created
    10. invited_by_user_profile
* Columns with missing values - *photo_url, username, twitter, instagram, invited_by_user_profile*
* 1 username had 2 unique user_id's
* **Jared Leto, Tiffany Haddish & Van Jones** are the top followed public figures
* **December 2020** has the highest user registration 
* The user arer divided into **3** clusters : **Less than 1k followers, Between 1k & 10k followers & More than 10k followers**
* **41%** of users with **Less than 1k followers** have not linked Instagram and Twitter to their profile
* For users with **More than 1k followers** more than **50%** have linked both Instagram and Twitter to their profile
* Among all 3 groups more users have linked **only Instagram** as compared to **only twitter**
* Only **5%** of the profiles have profile pictures
* **3214** have no invite linked to their profile
* **David Castain** has invited the most nummber of users
* For Users with **More than 1k followers, 56%** of the users have a complete profile
* While **80%** of users with **Less than 1k followers** are missing some information from their profile
* Emoji based observations
   1. **213** user have atleast 1 emoji in their username
   2. *smiling face with tear* is the most common emoji 
   3. **Four** users have four different flag emoji(United States, Sweden, Canada and Belize) in their username 
   4. **17** users have used **six** different skin toned emojis
   5. **Six** Users have used *Rocket emoji*; This emoji implies that either the user works with social media growth related 
      metrics or startup or investor in Dogecoin
   6. One user is artist as the user has artist palette in their username (linked instagram confirms this)
   7. **Three** users have *camera emoji* in their username. Exactly one user works with filmaker/video content creator 
   8. **Three** users work in tech
   9. **Five** users are female and **three** users are male
