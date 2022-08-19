# olivares-blog-particle

Gantry 5.3.2+ Particle to show articles (Blog entrie presentation) using cards on Joomla 4.x or higher  (joomla 3.5+ compatiblle).  This particle uses UIkit 3.x and FontAwesome 5.x

# Developer info :ninja:
Hi my name is Jose Luis Olivares. 
If you appreciate my effort, please endorse my skills on Linkedin (https://www.linkedin.com/in/jolivaress/) or making a voluntary donation through Paypal https://paypal.me/joolivares 

You can see an example implemented in this website I made (https://iconnsv.com) or down below checking some screenshots

# Installation on Joomla 3.x / 4.x:

1-Copy the blog-main-olivares.html.twig and blog-main-olivares.yaml files to root/templates/TEMPLATE_DIR/custom/particles (if the particles folder does not exist, you have to create it manually)

2-Copy the _blog-main-olivares.scss file to root/templates/TEMPLATE_DIR/custom/scss (if the scss folder does not exists, you will need to create it manually)

3- Add the following code in your custom.scss file.

	@import "dependencies";
	@import "blog-main-olivares"; /* Olivares Blog Card Particle */

  If the custom.scss file does not exists, you will need to create it manually. Also, make sure your custom.scss file has the @import "dependencies"; code at the very top.

# Some Screenshots

## Particle on Gantry 5.3.2+
![gantry5-particle]( ./no-copy-imgs/particle-img1.jpg?raw=true "Add particle")

## Defining articles ID's to show
![presentation-mode](./no-copy-imgs/particle-img2.jpg?raw=true "Articles IDs to show")

## How many cards to show (from 2 to 4)
![card-mode]( ./no-copy-imgs/particle-img3.jpg?raw=true "How many cards")

## Real example
![nocard-mode]( ./no-copy-imgs/particle-img4.jpg?raw=true "PArticle implemented")