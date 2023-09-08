# All the tricks to make cool effective presentations
1. [xaringanExtra](https://pkg.garrickadenbuie.com/xaringanExtra/#/README?id=xaringanextra)
`Tileview`, `Broadcast`, `Animate`, `Logo` are some of the cool stuff
2. [Sharing on short notice](https://rstudio-education.github.io/sharing-short-notice/#1)
3. [Sharing Your xaringan Slides](https://www.garrickadenbuie.com/blog/sharing-xaringan-slides/)
4. [Animate Xaringan Slide Transitions](https://www.garrickadenbuie.com/blog/animate-xaringan-slide-transitions/)
5. [Sharing Your Work with xaringan](https://spcanelon.github.io/xaringan-basics-and-beyond/)
6. [Making great slides with Xaringan](https://presentable-user2021.netlify.app/) and [video](https://www.youtube.com/watch?v=RPFh3y9UAX4&list=PL4IzsxWztPdnCC_kMCYKrd_t6cViMhBrD)
7. [HTML and tweaking the slides](https://arm.rbind.io/slides/xaringan.html#1)
8. [The untold story of palmerpenguins](https://apreshill.github.io/palmerpenguins-useR-2022/#/title-slide)
9. [Sliding in Style](https://slides.garrickadenbuie.com/sliding-in-style/#1)

## Creating animations
1. [Tidyexplain](https://www.garrickadenbuie.com/project/tidyexplain/)
2. [gganimate](https://gganimate.com/)
3. [Source code to create animations](https://github.com/gadenbuie/tidyexplain/tree/main/R)

## Level up stuff
1. [Making Extra Great Slides with xaringan](https://slides.garrickadenbuie.com/extra-great-slides/intro/#1)
2. [Your slides are so extra](https://slides.garrickadenbuie.com/extra-special-xaringan/#1)
3. [Xaringan playground](https://slides.garrickadenbuie.com/xaringan-playground/#1)

## RStudio themer
- Install `devtools::install_github("gadenbuie/rsthemes")` and `rsthemes::install_rsthemes()`
- Apply `rstudioapi::applyTheme("Oceanic Plus {rsthemes}")`
- Listing some cool themes to try
> rstudioapi::applyTheme("Nord Polar Night Aurora {rsthemes}")
Solarised Dark | Material Palenight

## Cookbook for creating slides using `Xaringan` and RStudio
1. [Fabio Votta](https://favstats.github.io/ds3_r_intro/#1) had this kickass slide deck on `Intro to R programming` which shook me out of my procrastination couch
2. I looked up the repo and blindly copied the `css` folder, `index.Rmd`, `libs` and `collpaseoutput.js` files
3. I looked up [metathis](https://presentable-user2021.netlify.app/packages/metathis/) and [this](https://xeurmia.netlify.app/?panelset1=panel-12#1)
4. I got a fair idea of the extras and css styling syntax
5. Setup the xaringanExtras. `Progress bar`, `logo`, `tileview`, `clipboard`, `broadcast`
6. `Broadcast` is not working offline. I have to lookup hosting this onto a Github page
7. Added the webcam onto slides. This is kickass. Perfect when teaching

## Hosting the rendered html in GitHub pages
1. [Deploying xaringan Slides with GitHub Pages](https://rviews.rstudio.com/2021/11/18/deploying-xaringan-slides-a-ten-step-github-pages-workflow/)
2. [Fontawesome lookup](https://rstudio.github.io/fontawesome/articles/icon-reference.html)
