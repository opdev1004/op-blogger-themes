# OP Blogger Theme
## Other language:
[한국어](/others/ko)

## Example
[https://opbloggertheme.blogspot.com/](https://opbloggertheme.blogspot.com/)

## Description:
OP Blogger Theme is for blogger theme development or real case use.
This theme is based on most recent default blogger theme (Contempo theme).
I support only 1 theme now.

## Features:
1. Responsive Web design
2. Sensible CSS variables - Only few configuration for different color and font
3. SEO
4. Resizing iframe media(Youtube) for responsive web design
5. Better label control
6. Pretty google search
7. International Language support in 1 theme (Only Korean and English for now)
8. Few fixes

## Setting up:
1. In blogger setting:
  * Blog descriptions - Up to you however it is good to use
  * HTTPS redirection-Yes
  * Same format for time - Recommand 00/00/0000 format
  * Disable Mobile version from settings (OP blogger theme supports responsive web design)

2. In blogger theme page:
  * Apply Contempo theme to blog
  * Restore theme with op.xml (or copy and Paste OP Blogger Theme in HTML edit)
  * all good to go!

## Problem & Solve
 * Q: Image doesn't fit into the container.
 * A: Please use new release, new themes force no margin for images in post. So now no more image breaking out from its container.

 * Q: How do I update localization?
 * A: There's a comment like <b:comment>International language support</b:comment>. You have to find each of them and update the if statement below the comment tag. If you want to add new language just add eg. <b:elseif cond='data:blog.locale == &quot;ko(locale)&quot;'> then add the equivalent translation of English version. I will make the list of translation at some point.

 * Q: Why is localization system so messy?
 * A: Avoiding performance issue. Handling everything with Javascript isn't good. And blooger theme system is quite messy.

## Contribution
You are welcome to improve OP Blogger Theme and contributing your theme.
You can contribute by opening a pull request in this repository.

## License:
MIT

## Author:
* Name: Victor Chanil Park
* E-mail: opdev1004@gmail.com
