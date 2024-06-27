#installization process : pip install instaloader 

import instaloader
 
# Get instance
loader = instaloader.Instaloader()
 
# Login using the credentials
loader.login("*put here your username", "*put here your password")
 
# Use Profile class to access metadata of account
profile = instaloader.Profile.from_username(loader.context,'* put your username here')
followers = [follower.username for follower in profile.get_followers()]

# Retrieve the usernames of all followees
followees = [followee.username for followee in profile.get_followees()]
print(followers)
print("Username: ", profile.username)
print("User ID: ", profile.userid)
print("Number of Posts: ", profile.mediacount)
print("Followers: ", profile.followers)
print("Followees: ", profile.followees)
print("Bio: ", profile.biography,profile.external_url)
