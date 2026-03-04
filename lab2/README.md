
# SCSS Course - Lab 2

## Course Information
**Course:** SCSS (Sass/SCSS)
**Lab:** Lab 2 — Grid Using SASS

**Instructor:** Eng. Omar Walid
**Created by:** Mahmoud Awad

## Description
This lab implements a responsive 12-column grid using SCSS. It demonstrates core SCSS features including variables, mixins, loops, and automated media-query generation for common breakpoints.

## Project Structure
```
lab2/
├── gridUsingSass.html
├── README.md
├── links.txt
└── style/
	├── css/
	│   └── style.css
	└── scss/
		└── style.scss
```

## Features Implemented
1. Mobile-first column classes `.col-1` … `.col-12`
2. Responsive variants `.col-sm-*`, `.col-md-*`, `.col-lg-*`, `.col-xl-*`
3. Use of variables for grid columns and breakpoints
4. Mixins for base column styling and grid generation
5. Dynamic background color assignment via loops

## How to Use
1. Open [lab2/gridUsingSass.html](lab2/gridUsingSass.html) in your browser.
2. Edit [lab2/style/scss/style.scss](lab2/style/scss/style.scss) and recompile to update [lab2/style/css/style.css](lab2/style/css/style.css).
3. Compile SCSS with your preferred tool. Example using the Dart Sass CLI:
```bash
sass lab2/style/scss/style.scss lab2/style/css/style.css --no-source-map
```

## Technologies Used
- HTML5
- SCSS/Sass
- CSS3

## Notes
- The SCSS source generates classes for a 12-column grid and responsive breakpoints.
- For course questions, contact Eng. Omar Walid.
