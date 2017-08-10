# OneHeart

## What is this?

This *git* repository represents a top-line summary of all OneHeart tech work stored on github.com. It's also a basic style guide / cheatsheet for developers (e.g. colour palette).

## Repository list

- [**oneheartchurch**](https://github.com/blairw/oneheartchurch) - public website
- [**oneheartfamily**](https://github.com/blairw/oneheartfamily) - internal website

## Style cheatsheet

### Typography

#### Montserrat

The **OneHeart logo** is typeset in [Montserrat](https://fonts.google.com/specimen/Montserrat). It can be produced in pure HTML and CSS using the Google Fonts API, importing weights for 300 and 700 (no italics required unless needed for other stuff on the same page):

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

#### Source Sans Pro

Since Montserrat is already distinctly used for the logo, it is best to avoid it for body copy text and even headings. **[Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)** is a good alternative since it was used by OneHeart in previous years and so would represent a sense of continuity for anyone who has been on the journey with us. Other advantages:

- Professionally designed by Adobe but licensed for public use
- Distributed via Google Fonts API, ideal for web projects
- Multiple weights (200, 300, 400, 600, 700, 900) with real italics for all weights


#### Helvetica Neue Condensed

This is currently used on ProPresenter 6 for the lyric design. Advantages:

- Helvetica is the pinnicle of Swiss International Style and widely recognised as a "professional" and "clean" look
- Narrow shape helps fit more lyrics on screen
- Available on Mac OS only, but this is not a problem at our church :)


### Colour palette

- ![#BE1F2E](https://placehold.it/15/BE1F2E/000000?text=+) `#BE1F2E` - **OneHeart red**, as identified by Josh Wyatt
- ![#B53389](https://placehold.it/15/B53389/000000?text=+) `#B53389` - **Fandango purple**, for URLs on the website - deliberately avoiding pure blue and pure purple to avoid invoking the 1990s "new vs visited" colour-coding
- ![#8BCC4F](https://placehold.it/15/8BCC4F/000000?text=+) `#8BCC4F ` - **Majors Bay green**, colour-picked out of a photo of OneHeart people standing in front of a patch of grass; good for Call-to-Action URL where the background photo has a lawn or other vegetation in it; symbolises growth