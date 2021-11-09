# fem-3-column-card-component

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Notes

(November 8th, 2021)

This will be the sixth Frontend Mentor project I've completed. Up until now, I've kept to the easier challenges in order to build up a few easy wins, but it doesn't make for especially realistic practice - real-world projects don't tend to follow a predefined difficulty curve. So starting with this project, I've started picking out new FEM projects at random. This means I won't know what I'm working on until it's time to start, which gels nicely with the takeaway from my [previous project](https://github.com/Sakeran/fem-agency-landing-page) to develop a general-purpose toolkit of scripts and utility CSS.

Anyway, the random number generator picked out this newbie-level, card-component challenge. While not especially exciting, it turned out to be just the right speed for field-testing my personal Sass toolkit. My goal here was to create a general-purpose Sass directory that can be dropped into any project and customized. It includes utility classes generated from a config file, a number of my favorite layouts, and well-defined places to include custom CSS. I ran into a number of technical and quality-of-life issues while working with it for this first time, but I did succeed in identifying a few improvements to make for next time.

Aside from using Sass, this project is completely vanilla, save for some stylesheet processing with `PurgeCSS` and `csso`.

[A live version of this project can be found here.](https://skinny-bird.surge.sh/)