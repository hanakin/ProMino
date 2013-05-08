# Mino

New projet dedicated to the creation of a completely semantic modenized style to be included in future versions of PHPBB. The scope of this project will be handled in several stages. Keep in mind that this is not an inherited style but a replacement of the current default style. The use of moderen front-end workflow tools will be leveraged to enable faster prototyping.

## TOOLS USED

###[HMTL5](http://www.w3.org/html/logo/ "HTML5")
We are looking to develop a future proof template one that can and will be extendable for quite awhile so we will be using the porposed HTML5 spec selectors

###[CSS3](http://www.w3.org/Style/CSS/ "CSS3")
In order to keep our code progress but also clean, expressive and semantic we need to use the leverage of CSS3 to obsficate the use of classes and ids from our HTML code where it is not inherently needed as well as reduce the ammount of server requests for images. CSS3 is a huge help in this regaurd.

###[HTML5Boilerplate](http://html5boilerplate.com/ "HMTL5Boilerplate")
Since we are going to already be leveraging technology that is tried and true with the rest of the software platform then it makes sense that we do so with our theme boilerplate helps us do just that by establishing at the most basic level a well layed out template file structure to adhere to.

###[Normalize.css](http://necolas.github.io/normalize.css/ "Normalize.css")
Browser wars are a huge thing in evelopment and their have been many common practices over the yeras to reset all of them to behave the smae. however its usually results in a lot more overhead than is nessecary so by using normalize we focus on fixing the incosistancies. Thus eliviating the need to restablish everything ourselves.

###[SMACSS](http://smacss.com/ "SMACSS")
An established set of CSS guidelines and princliples/rules to enable accurate, intuitive, & consistant seperation and structuing of CSS files for large scale projects.

###[Less](http://lesscss.org/ "Less")
Devlopment time is a huge concern these days with anything so if there are anyways to speed up the prototping and creation of files then we should leverage it at least at the development level. That is why when it comes to CSS you need to really rely on a preprocessor to enable the devloper to make broad strokes to handle things rather than millons of little ones.

###Less Framework
Stripped down and modified version of [Bootstrap](http://getbootstrap.com/ "Bootstrap"). This is being used on a generation bases only in less format inorder to reduce the ammount of css being included into the final theme files. This is soely to speed up the devlopment of a theme, as well as allow maintanace of the theme at a higher level and further provide a consistant set of guidlines in the convetion of styles.

## Backstory
I new that we needed an effective powerful way to introduce two very fundamental aspects to the theme that have been mising prior to now, a grid system & responible layouts. 

I considered all the options their were. I wanted an option that did not add blot to either the HTML or the CSS. Jeet allowed me to do just that. It is a fraework unlike the rest in that it was designed to be used and disgaurded upon final render. 

It leverages the semantic grid system to handle the grid so that you apply the grid to the CSS selectors rather than to classes in the HTMl thus keeping your html very clean. 

It also has mixins that make working with media queries extremely powerful and simplitic. The combination of these come together beautifly to provide you with a truely responsive & fluid layout down to IE7

## APPROACH

- [X] 1. Style Guide Creation (Colors/Fonts/Form Elements/Buttons/Look & Feel)
- [ ] 2. Framework/Grid devlopment
- [ ] 3. HTML/CSS prototyping of static area51 page by page.
- [ ] 4. Break it up into template files
- [ ] 5. Apply aesthtics
- [ ] 6. Add in JS
- [ ] 7. Fix template engine to work with new proposed template structure
- [ ] 8. Beta/Approaval

## LICENSE
[GNU General Public License v2](http://opensource.org/licenses/gpl-2.0.php)