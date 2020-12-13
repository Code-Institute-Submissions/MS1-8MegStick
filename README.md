<img src="images/8meg-rm.png" style="margin: 0;">

# 8 Meg Stick Records

>
> 8 Meg Stick Records is an emerging independent digital record label with a small roster of artists and releases. The label requires a website to showcase 
their musical releases.
>

The site has been deployed via Github https://paulwheatcroft.github.io/MS1-8MegStick/

## User Experience (UX)

3 sets of target personas have been identified:

- Music enthusiast
- Musician
- Live music promoter

### Music enthusiast

<img src="images/enthusiast.png" style="margin: 0;">

This persona will have an interest in independent music. **This is the primary target persona for 8 Meg Stick Records**. They will be looking to:
- Find out information about the artist
- Be able to follow the artists
- Links to released music

### Musician

<img src="images/musician.png" style="margin: 0;">

A musician will use the website to review the music released by the label with a view to submitting a demo for consideration to be released on the label. They may also wish to assess an artist with a view to partnering over live music opportunities either asking for support roles or to offer support roles.
- Found out about the label's ethos
- Find out information about the artist on the label
- Listen to music
- View live music videos
- Links to released music
- Be able to contact the label

### Music Promoter

<img src="images/promoter.png" style="margin: 0;">

This persona will be interested in understanding the suitability and capability of an artist before offering a gig opportunity.
- Find out information on the artist
- View live music videos
- Listen to music
- Be able to contact the label

### User Stories

Using the targeted personas, the following list of user stories have been identified to fulfil their needs.

- As a music enthusiast I want to easily find links to tracks on music streaming sites
- As a music enthusiast I want to be able to find out information on an artist
- As a user I can receive updates on new releases
- as a musician I can find out information about the record label
- as a musician I can contact the label to send my demo
- As a music promoter I can listen to what the artist sounds like
- as a live music promoter I can watch a video of an artist
- as a user I can contact the label about an artist

## Design Choices

The persona that 8 Meg Stick Records wish to primarily target are likely to be viewing the site on a phone. Therefore the site will be a mobile first approach.

The number one feature is links from each release to 6 of the most popular streaming platforms. These are:

- Spotify
- Apple Music
- YouTube Music
- Amazon Music
- Deezer
- Tidal

The look and feel of the site needs to be built around the 8 Meg Stick Records branding. The website needs to feel modern, vivid with vibrant and dynamic touches. The tone should
be professional but not corporate.

Below is the brand colour pallet for 8 Meg Stick Records. Whilst these form the foundation of the colour scheme other strong colours will be required to support vibrant 
accents on the website. Bold use of band photography and imagery is encouraged.

| Description | Hex Colour Value |
| --- | ----------- |
| Dark grey which can be used extensively | #1a1a1a |
| Off white which can be used extensively | #f9f9f9 |
| Light yellow to be used as a primary colour | #ffdd55 |
| Darker yellow to be used as a secondary supportive colour | #d4aa00 |
| Sky blue to be used as a main highlight colour | #80ffe6 |
| Complimentary supporting  pink highlight colour | #ffaeae |
| Complimentary supporting  green highlight colour | #b7ffa5 |


The main font used in the 8 Meg Stick Records logo is not available as a web font. This is a serif font. No other serif fonts should be used as may detract from the logo. 

The secondary font used in the logo is Noto Sans TC. This is available as a web font and will be used for headings.

Noto Sans will be used as the main content font as this is a complimentary font to Noto Sans TC.  

## Structure

Whilst the focus is on a mobile first design the website needs to provide an optimal experience across all screen types.

To ensure the experience is focussed on the releases this will be a multi-page website consisting of 4 pages.

1. releases
2. artists
3. about the label
4. contact

There is a horizontal navigation bar at the top of each page facilitating access to other pages on the site. This navigation element will collapse on a mobile device.

The index.html page will contain the releases connect as this is the main focus of the site. All other pages follow a consistent look and feel to the main page including 
the same footer element which contain the record labels social media links.

### The Releases Page

The top of the page consists strong imagery advertising the latest release or next up and coming release from the record label. This section enables the 
viewer to sign up for new music release alerts from the label. This section needed to take up most but not all of the viewing area as to reveal the releases
beneath the hero image. The releases will be in in chronological order of their release. 
Each release section should display:

- Song title
- Artist name which links to the artist profile that will be situated on the artists page
- Cover art
- Links to streaming services

### The Artists Page

Beneath the navigation bar which is common to all of the pages the artists page will contain a section on each artist. This progresses down the page in alphabetical order. 
Each artist section contains:

- Artist name
- Biography of the artist
- Links to their tracks on the releases page
- Photos and imagery (if available)
- Videos (if available)
- Social media links (if available)
- Any other links that support the artists profile

### The About Page

Beneath the navigation bar which is common to all of the pages the artists page will contain a section on the record label. This section will contain:

- An overview of the record label
- Outline the record label ethos and musical direction
- link to a form to submit a demo

### The Contact Page

Beneath the navigation bar which is common to all of the pages the contact page will contain 3 forms.

1. A form to register or notifications of new releases
2. A form to submit a demo
3. A general contact form

## Wireframing

<img src="images/devices.png" style="margin: 0;">

Mocking up of the site was done using Figma. I chose to use full images and colour as opposed to sketch/line drawings as the site would have many images and elements and therefore be visually busy so I needed to understand the relationships of these images such as the release cover art.

A Figma wireframe for each page can be found in the links Below.

[Releases - index.html](https://www.figma.com/file/lbEOracgvjZ4jw3uFd6hJd/8-Meg-Stick-Records?node-id=0%3A1)

[Artists](https://www.figma.com/file/lbEOracgvjZ4jw3uFd6hJd/8-Meg-Stick-Records?node-id=31%3A2)

[About](https://www.figma.com/file/lbEOracgvjZ4jw3uFd6hJd/8-Meg-Stick-Records?node-id=49%3A79)

[Contact](https://www.figma.com/file/lbEOracgvjZ4jw3uFd6hJd/8-Meg-Stick-Records?node-id=49%3A207)

## Design Choices

I decided to go with the hero text centrally aligned as it suited the final images more.

SVG files were used for the streaming link icons as not all were available in FontAwesome.

Bootstrap was used throughout the website build as this was a rapid way to build the structure of the site. Using Bootstrap's Flex element in the hero image will ensure that the positioning of the text elements used in the hero image can be easily changed to suite the promotional image of that specific music release.

I put the releases background CSS at the top of the files for easy access when new music is released.

## Technologies

## Testing

Both HTML and CSS have been validated via

- W3C [Nu HTML Checker](https://validator.w3.org/nu/)
    - [index.html Result](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpaulwheatcroft.github.io%2FMS1-8MegStick%2Findex.html)
    - [artists.html Result](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpaulwheatcroft.github.io%2FMS1-8MegStick%2Fartists.html)
    - [about.html Result](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpaulwheatcroft.github.io%2FMS1-8MegStick%2Fabout.html)
    - [contact.html Result](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpaulwheatcroft.github.io%2FMS1-8MegStick%2Fcontact.html)
- W3C CSS Validation Service [CSS Result](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fpaulwheatcroft.github.io%2FMS1-8MegStick%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

Responsiveness was checked thought using the Google dev tools and the https://www.responsinator.com/ 

A code review was posted in the Code Institute peer-code-review channel. Following feedback i mage changes to the footer logo image to link back to the Releases page.

I used a wide group of friends and family to test the user stories across the following operating systems and browsers.

- Windows
    - Internet Explorer 11
    - Microsoft Edge
    - Chrome
    - Firefox
    - Opera
- Android
    - Native OPPO handset browser
    - Chrome browser

Functional testing was carried out and recorded in [functional-testing.xlsx](functional-testing.xlsx)

## Bugs and issues

I encountered an issue with syntax when displaying and image. The site would like fine in Gitpod but the images would be missing when viewing the site via Github. This was down to relative paths of the images when referenced withing the CSS file.

I initially started using SVG files directly in the code but some of the strings were so large it cause an error in Gitpod. I switched to referencing the .svg file instead. I also had an issue where the navbar text logo SVG stopped rendering properly.

Both the Youtube embed and the modal gallery code i used returned validation issues when checked through the Wc3 Nu HTML Checker. These were corrected to comply.


## Acknowledgements

[Mark Down Guide](https://www.markdownguide.org/)

README icons created by using Segoe UI Sybol font

[Google Fonts](https://fonts.google.com/) used for displaying Noto Sans and Source Sans Pro fonts

The streaming icons were downloaded from https://simpleicons.org/

I was able to get the YouTube videos on the Artists page to scale nicely with the Bootstrap grid system thanks to [Chris Coyier's](https://css-tricks.com/author/chriscoyier/) tutorial on [Fluid Vidio Layout](https://css-tricks.com/fluid-width-video/) 

A simple [modal image solution](https://www.tutorialspoint.com/how-to-create-a-modal-image-gallery-with-css-and-javascript) from [AmitDiwan](https://www.tutorialspoint.com/answers/amitdiwan) was used on the Artists page. 

Thanks to [Mohammad Usman's](https://stackoverflow.com/users/5933656/mohammad-usman) answer to this [question](https://stackoverflow.com/questions/38850419/how-to-create-multi-color-border-with-css) about mulitple colours on a border.

I used this page on Stackoverflow to implement a [browser colour change on mobile](https://stackoverflow.com/questions/26960703/how-to-change-the-color-of-header-bar-and-address-bar-in-newest-chrome-version-o)

