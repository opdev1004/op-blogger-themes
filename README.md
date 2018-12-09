# OP Blogger Themes

## Description:
OP Blogger Themes are for Blogger Theme development.
Main purpose of this project is to have clean base blogger theme for people to develope theme easily.
There is no problem using the OP Blogger Themes without extra theme development.
Each directories contains a different blogger theme.

## Basic Features:
1. Responsive Web design
2. Flexible control of minor theme designs
3. Blogger CSS variables
4. Open graph meta tags (Requires some modification)
5. Resizing iframe media(Youtube) for responsive web design, BBT Zero is based on width: 840~850px. Other versions that will come out later will have different sizes.
6. Better Categories
7. Pretty google search box
8. Thumbnails (Requires some modification)

## Setting up:

1. In blogger setting:
  * Blog describtions
  * Enable Blogger meta tag
  * HTTPS redirection-Yes
  * Same time stamps

2. In blogger theme HTML edit:

  * Setting up image for open graph image (meta tag)
    * Just need to put src link in the commented meta tag in head.
  * Setting up default post thumbnails' image and default popular posts thumbnails' image
    * It needs default image to display a thumbnail for the case of no image in the post. Recommended size is around 250px x 250px. There are tags that are commented. Put src link into the empty img attributes. Popular post uses 72px x 72px of image size.
  * Setting URL for home in PageList1 widget
    * Default is blogger.com, it does not make any problem but it supposed to be the current blog's home url.
    

## Problems & Solve:
1. Number of post in label does not work properly:
  * It does not support for now.

## License:
MIT

## Author:
* Name: Chanil Park
* VUW Computer Science student
* E-mail: falsesage1004@gmail.com
* Blog: https://www.falsesage.com/
* Youtube: https://www.youtube.com/channel/UCOWFk2-Y4yuwVxK0yo6ABmw
