# Pimp My Twitter Header
### (with github actions)

Path to action workflow:
```
.github/workflows/node.js.yml 
```
Shows your latest followers on your banner and a followers progress bar in your location section.

Likely leads to increased engagement so if you're some social media freak you'll probably want to use this.

Forked from guillaume-rygn.
It basically does the same thing as his original project except you don't have do bother with hosting.

Simply Fork, go in Settings, Secrets and variables, Actions, and add the following secrets:
```
ACCESS_TOKEN (This is your access token)
ACCESS_TOKEN_SECRET (This is your access token secret)
API_KEY (This is your API key)
API_KEY_SECRET (This is your API key secret)
HANDLE (For this one put your twitter handle without the @)
```
After doing so go on your project's Actions tab and run the workflow.

Make sure your dev twitter account has an elevated level and your app has read, write and direct message permissions.

You can then replace ```twitter-banner.png``` by any image you'd like.

If you are not paying for github:

I recommend you disable email notifications for github actions since the service restarts every 6 hours due to github restrictions.

The service may also stop working after about 50 days if there are no new commits to your repository (again, due to github restrictions).
