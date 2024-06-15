# LUSAHA (Still in development)
Local URL Shortener Addon for Home Assistant, a 100% local and configurable url shortener.

## Creating a new shortened link
 1. Go to `https://your-ha-instance:8000/new`. 
 2. Enter the target URL and the settings for the shortened URL (length, keyword, etc.).
 3. Click save and copy your shortened URL.
 4. You can now navigate to the shortened URL, and you will be redirected to your target URL.

## Managing shortened links
 1. Go to `https://your-ha-instance:8000/manage`. 
 2. You will see a list of all your shortened links, which you can edit or delete.

## Use cases
- You want to shorten URLs without relying on external services that may be disrupted in the future.
- You want to create as many links as you want without limitations and customize your links (URL length, customized keywords, etc.).

## Notes
- As long as you keep your database safe with backups, your links will work forever.
- This addon runs on your HA instance, so sharing shortened links will also share your HA link if you use your external IP/URL.

## Todo
 - [ ] Make the addon respond to web requests and redirect them.
 - [ ] Create a database to store shortened URLs and targets, and dynamicaly redirect incoming requests.
 - [ ] Create the `new` and `manage` pages.