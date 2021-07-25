# screenshot


Screenshot system powered by Railway.

## How do I use this?

> Base URL: /

### GET `/`

Query Parameters:

-   url - The url of the website. (required)
-   width - The width of the screenshot. (not required, default is 1920)
-   height - The height of the screenshot. (not required, default is 1080)
-   full - If you want a full page screenshot. (not required, default is none, put 'yes' if you want a full page screenshot)
-   checkNsfw - If you want to check NSFW urls. (not required, default is none, put 'yes' if you want to check urls.)

Example Requests


-   I want a normal screenshot.
    -   `https://screenshot1.talos.tk/?url=https://github.com`
-   I want a screenshot with a custom width and height.
    -   `https://screenshot1.talos.tk/?url=https://google.com&width=1366&height=625`
-   I want a full screenshot of a website.
    -   `https://screenshot1.talos.tk/url?=https://discord.com&full=yes`
-   I want to check NSFW urls.
    -   `https://screenshot1.talos.tk/url?=https://nsfw.link&checkNsfw=yes`
