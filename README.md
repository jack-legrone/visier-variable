# Visier

Visier is a variable font with two axes, legibility and differentiation, designed to mitigate the visual effects of dyslexia. The differentiation axis modifies letter weight and add distinguishing features between similar characters. The legibility axis increases the space between letters and enlarges the space within letters, as well as adding distinguishing features, so characters are generally more recognizable. 

# Usage

New to variable fonts? Great, maybe. Desktop applications are slowly adopting this updated TTF format. Currently support is limited to Adobe Illustrator and Adobe Photoshop. Install it like you would any other font.

For web, the .ttf file with work on most browsers. Modification can be made to both axis using the font-variation-settings css property. More information can be found [here.](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Fonts/Variable_Fonts_Guide)

` Here is an example of an initial call to Visier Variable:`
```
@font-face {
font-family: ‘Visier Variable’;
src: url('Visier.woff2');
font-weight: 100 400;
}


