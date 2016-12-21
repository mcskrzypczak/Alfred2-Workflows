# Alfred2-Workflows

---- 

The list of all my Alfred 2 Workflows. Enjoy!

---- 

## VNC for Alfred

→ **[Download][1]**

This workflow allows to add, delete and connect to other computers using OS X’s built in **Screen Sharing** application. Just use the `vnc` keyword and choose from list computer would you like to connect to:

![VNC for Alfred; by mcskrzypczak][image-1]

But first of all you need to **add** some computers by typing `vnc add`, give name and IP address like on the screenshot below (you **need** to stay with pattern: Name dash IP address and optionally port number after colon → **Living Room-192.168.1.103:5901**):

![Adding computers; by mcskrzypczak][image-2]

To **delete** computer from list type `vnc del` and simply select machine:

![Deleting computers; by mcskrzypczak][image-3]

It’s simple and fast. Hope you like it!

## App Store Search

→ **[Download][2]**

This workflow lets you search apps from App Store and Mac App Store. Use on of those two keywords:

- `app` – to search for apps for iPhone, iPad and Apple TV 4;
- `mas` – to search for apps for Mac.

![Searching for apps for iPhone, iPad and Apple TV 4; by mcskrzypczak][image-4]

![Searching for apps for Mac; by mcskrzypczak][image-5]

You can perform 4 actions with results by pressing specified keyboard button:

- `enter` – copies app’s link to clipboard;
- `shift` – opens Quick Look with site of specified app;
- `cmd` – opens app’s page in one of those: iTunes or Mac App Store app;
- `alt` – opens app’s site in default browser.

### Simple configuration

You can edit workflow’s script file `script.py` to configure three things by changing these variables:

- `COUNTRY` – specifies country and currency of App Store. Use the [ISO code][3] of the country you want. Default value is `pl` for Polish App Store.
- `LIMIT` – limit workflow’s results. Maximum amount is *200*. Default value is `20`.
- `affiliate` – if you got your affiliate code, place it here.

I am planning to simplify the configuration process in near future by using Alfred 3 new possibilities.

[1]:	https://github.com/mcskrzypczak/Alfred2-Workflows/raw/master/workflows/VNC-by-mcskrzypczak.alfredworkflow
[2]:	https://github.com/mcskrzypczak/Alfred2-Workflows/raw/master/workflows/App-Store-Search-by-mcskrzypczak.alfredworkflow
[3]:	https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements

[image-1]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-vnc-01.png
[image-2]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-vnc-02.png
[image-3]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-vnc-03.png
[image-4]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-app_store-01.png
[image-5]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-app_store-02.png