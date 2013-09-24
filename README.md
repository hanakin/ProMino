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
Stripped down and modified version of [Bootstrap 3.0](https://github.com/twitter/bootstrap/tree/3.0.0-wip "Bootstrap 3.0"). The css has been seperated into two parts the *Core* and the *Theme*. By doing this we alow for a celan and efficent devlopment environment using LESS to leverage all the heavy lifting while providing both a baseline css and less file in the release to better facilitate theme development upon a core set of styles.

## Backstory
I new that we needed an effective powerful way to introduce two very fundamental aspects to the theme that have been mising prior to now, a grid system & responible layouts. 

I considered all the options their were. I wanted an option that did not add blot to either the HTML or the CSS. In the end the [Bootstrap 3.0](https://github.com/twitter/bootstrap/tree/3.0.0-wip "Bootstrap 3.0") allowed for the best approach to a grid while allowinf for scalability. 

It also has mixins that make working with media queries extremely powerful and simplitic. The combination of these come together beautifly to provide you with a truely responsive & fluid layout down to IE7

## APPROACH

- [X] 1. Style Guide Creation (Colors/Fonts/Form Elements/Buttons/Look & Feel)
- [X] 2. Framework/Grid devlopment
- [ ] 3. HTML/CSS prototyping of static area51 page by page.
- [ ] 4. Add in PHPBB JS
- [ ] 5. Cleanup all html css
- [ ] 6. Fix template engine to work with new proposed template structure
- [ ] 7. Beta/Approaval

## LICENSE
[GNU General Public License v2](http://opensource.org/licenses/gpl-2.0.php)