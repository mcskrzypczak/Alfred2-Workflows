# Alfred Workflows

---- 

The list of all my Alfred 2 Workflows. Enjoy!

- [VNC for Alfred][1]
- [App Store Search][2]
- [Copy Name][3]

---- 

## VNC for Alfred

→ **[Download][4]**

This workflow allows to add, delete and connect to other computers using OS X’s built in **Screen Sharing** application. Just use the `vnc` keyword and choose from list computer would you like to connect to:

![VNC for Alfred; by mcskrzypczak][image-1]

But first of all you need to **add** some computers by typing `vnc add`, give name and IP address like on the screenshot below (you **need** to stay with pattern: Name dash IP address and optionally port number after colon → **Living Room-192.168.1.103:5901**):

![Adding computers; by mcskrzypczak][image-2]

To **delete** computer from list type `vnc del` and simply select machine:

![Deleting computers; by mcskrzypczak][image-3]

It’s simple and fast. Hope you like it!

## App Store Search

→ **[Download][5]**

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

In **Configure workflow and variables** window (*[x]*) you can set three values:

- `COUNTRY` – (required) specifies country and currency of App Store. Use the [ISO code][6] of the country you want. Default value is `pl` for Polish App Store.
- `LIMIT` – (required) limit workflow’s results. Maximum amount is *200*. Default value is `20`.
- `affiliate` – (optional) if you got your affiliate code, place it here.

## Copy Name

→ **[Download][7]**

That simple workflow allows you to copy name(s) of single or multiple file(s)/folder(s). Just select them and use Alfred File Action panel or Hotkey (just do not forget to set it earlier).

As a result, in case when selected multiple elements, you get list of names in separate lines.

[1]:	https://github.com/mcskrzypczak/Alfred2-Workflows#vnc-for-alfred
[2]:	https://github.com/mcskrzypczak/Alfred2-Workflows#app-store-search
[3]:	https://github.com/mcskrzypczak/Alfred2-Workflows#copy-name
[4]:	https://github.com/mcskrzypczak/Alfred2-Workflows/raw/master/workflows/VNC-by-mcskrzypczak.alfredworkflow
[5]:	https://github.com/mcskrzypczak/Alfred2-Workflows/raw/master/workflows/App-Store-Search-by-mcskrzypczak.alfredworkflow
[6]:	https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements
[7]:	https://github.com/mcskrzypczak/Alfred2-Workflows/raw/master/workflows/mcskrzypczak-Copy_name.alfredworkflow

[image-1]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-vnc-01.png
[image-2]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-vnc-02.png
[image-3]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-vnc-03.png
[image-4]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-app_store-01.png
[image-5]:	https://raw.github.com/mcskrzypczak/Alfred2-Workflows/master/images/mcskrzypczak-app_store-02.png
