# BEACSS

BEACSS - Block, Element, Attribute CSS

<img src="https://cloud.githubusercontent.com/assets/1434956/16282094/155700ba-387c-11e6-957f-fa5dfe0759f6.gif" />

## Summary
BEACSS, is a methodology for creating clean style sheets which focuses on building large, scalable and manageable code. BEACSS allows you to  minimize unwanted changes to styles throughout your site when updating and making changes. This allows your code to be easily updated and maintainable by adhering to a small set of rules.

## Index
* [General Sass Best Practices](google.com)



## General Sass Best Practices

**1) Stay dry (Don't repeat yourself)**

* Whenever possible, use variables, mixins, and placeholders to avoid repetitious code.

**2) Use semantic placeholders**
* The idea here is to retain control of your style system by creating a styleguide of possible text, media, and layout type styles, and then extending those styles within various components
* Use names like `%section-headline`, `%text-input`, `%strong-paragraph`,` %default-ol`, etc.

**3) Use library-wide prefixes to avoid collisions**
* If you will be using your styles on several sites, use prefixes on all of your styles to keep them separated. For instance if you are going to make a style called `.card` for your repos `generic` and `custom` you might want to append the repo name to them such as `.gen-card` and `.cus-card`. This can be done in one single file where you set your repo name in SCSS and the changes are impacted throughout the repository.

For Example:
```$repo = 'gen';

```#``{$repo}-card
```



## BEACSS Rules
