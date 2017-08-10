# OneHeart

## What is this?

This *git* repository represents a top-line summary of all OneHeart tech work stored on github.com. It's also a basic style guide / cheatsheet for developers (e.g. colour palette).

To edit this document, download [GitHub Desktop](https://desktop.github.com/), clone this repository, and edit `README.md` with a Markdown editor (e.g. [MacDown](https://macdown.uranusjr.com/)). Then you can push back into the repository - you may need to contact Blair for write-access.

## Repository list

- [**oneheartchurch**](https://github.com/blairw/oneheartchurch) - public website
- [**oneheartfamily**](https://github.com/blairw/oneheartfamily) - internal website

## Colour palette

- ![#BE1F2E](https://placehold.it/15/BE1F2E/000000?text=+) `#BE1F2E` - **OneHeart red**, as identified by Josh Wyatt
- ![#B53389](https://placehold.it/15/B53389/000000?text=+) `#B53389` - **Fandango purple**, for URLs on the website - deliberately avoiding pure blue and pure purple to avoid invoking the 1990s "new vs visited" colour-coding
- ![#8BCC4F](https://placehold.it/15/8BCC4F/000000?text=+) `#8BCC4F ` - **Majors Bay green**, colour-picked out of a photo of OneHeart people standing in front of a patch of grass; good for Call-to-Action URL where the background photo has a lawn or other vegetation in it; symbolises growth
- ![#E37644](https://placehold.it/15/E37644/000000?text=+) `#E37644` - **Connect Card orange**, as extracted from `movecard4.pdf`
- ![#42A0B8](https://placehold.it/15/42A0B8/000000?text=+) `#42A0B8` - **Connect Card blue**, as extracted from `connectcardOL_V4_UCA Fix.pdf`
- ![#D2D3D4](https://placehold.it/15/D2D3D4/000000?text=+) `#D2D3D4` - **Connect Card grey**, sourced same as above



## Typography

### Montserrat

The **OneHeart monogram logo** is typeset in [Montserrat](https://fonts.google.com/specimen/Montserrat). It can be produced in pure HTML and CSS using the Google Fonts API, importing weights for 300 and 700 (no italics required unless needed for other stuff on the same page):

```html
<style>
	@import url('https://fonts.googleapis.com/css?family=Montserrat:300,700');
	
	.oneheart_logo_one {
		font-weight: 300;
	}
	
	.oneheart_logo_heart {
		font-weight: 700;
	}
</style>

<span class="oneheart_logo_one">ONE</span><span class="oneheart_logo_heart">HEART</span>
```

### Source Sans Pro

Since Montserrat is already distinctly used for the logo, it is best to avoid it for body copy text and even headings. **[Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)** is a good alternative since it was used by OneHeart in previous years and so would represent a sense of continuity for anyone who has been on the journey with us. Other advantages:

- Professionally designed by Adobe but licensed for public use
- Distributed via Google Fonts API, ideal for web projects
- Multiple weights (200, 300, 400, 600, 700, 900) with real italics for all weights


### Helvetica Neue Condensed

This is currently used on ProPresenter 6 for the lyric design. Advantages:

- Helvetica is the pinnicle of Swiss International Style and widely recognised as a "professional" and "clean" look
- Narrow shape helps fit more lyrics on screen
- Available on Mac OS only, but this is not a problem at our church :)


## Images

### Square OneHeart logo

A square logo is useful for platforms like Instagram and Facebook where a square-shaped (or circle-shaped) avatar is required.

The OneHeart "(1)" logo has been discontinued and should no longer be used. While we are in the process of producing a suitable successor, the *Vision to Action* image is a worthy interim solution, available on the NAS at path `/DESIGN/DATA/LOGO/ONEHEART LOGO/170714 VISION TO ACTION/`.

### Uniting Church logo

- Wikipedia hosts an awesome [SVG version](https://en.wikipedia.org/wiki/Uniting_Church_in_Australia#/media/File:UCA-logo.svg) of the logo that can be rendered at whatever-sized PNG is required :D

- PSD and EPS files are available on the NAS at path `/DESIGN/DATA/LOGO/UCA/`.

- A PDF file of the Uniting Church logo nicely attached to the OneHeart monogram is available on the NAS at path `/DESIGN/DATA/LOGO/ONEHEART LOGO/170510 NO SYMBOL/`.

- For website work, the Uniting Church in Queensland has hosted a very helpful `favicon` stack for the Uniting Church logo. It is hosted in Amazon's AWS cloud so presumably it is ideal for hotlinking:

	```html
	<link rel="apple-touch-icon" sizes="57x57" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/apple-touch-icon-57x57.png">
	<link rel="apple-touch-icon" sizes="60x60" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/apple-touch-icon-60x60.png">
	<link rel="apple-touch-icon" sizes="72x72" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/apple-touch-icon-72x72.png">
	<link rel="apple-touch-icon" sizes="76x76" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/apple-touch-icon-76x76.png">
	<link rel="apple-touch-icon" sizes="114x114" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/apple-touch-icon-114x114.png">
	<link rel="apple-touch-icon" sizes="120x120" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/apple-touch-icon-120x120.png">
	<link rel="apple-touch-icon" sizes="144x144" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/apple-touch-icon-144x144.png">
	<link rel="apple-touch-icon" sizes="152x152" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/apple-touch-icon-152x152.png">
	<link rel="apple-touch-icon" sizes="180x180" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/apple-touch-icon-180x180.png">
	<link rel="icon" type="image/png" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/favicon-32x32.png" sizes="32x32">
	<link rel="icon" type="image/png" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/android-chrome-192x192.png" sizes="192x192">
	<link rel="icon" type="image/png" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/favicon-96x96.png" sizes="96x96">
	<link rel="icon" type="image/png" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/favicon-16x16.png" sizes="16x16">
	<link rel="manifest" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/manifest.json">
	<link rel="shortcut icon" href="https://s3-ap-southeast-2.amazonaws.com/ucaqld-resources-web/favicons/uca/favicon.ico">
	```

### One Voice logo

This can be obtained from the NAS at path `/DESIGN/DATA/GRAPHIC DESIGNS/ONEVOICE/`.

## Writing style

- The name **OneHeart** should always be written with capital "O" and capital "H", with no spacing (i.e. not <s>oneHeart</s> or <s>Oneheart</s> or <s>One Heart</s>)
- OneHeart should not be referred to as a Pentecostal church or a Charismatic church