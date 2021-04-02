# Refactoring existing code


## Project Description 
    Make sure the links in the given website works.
    Follow semantic structure.
    Follow accessibility standards.
    Consolidate CSS selectors and properties.

## Code refactored by Mark on index.html
    On line 7, changed the <title>website</title> to <title>Horiseon</title>.
    On line 11, replaced <div> with <header>.
    On line 12, changed class="seo" to id="seo"
    On line 13, replace <div> with <nav>.
    On line 28, added <main>.
    On line 29, changed class="hero" to id="hero"
    On line 31, replaced <div> with <section>.
    On line 32, added class="tools" and changed class="search----tion" to id="search---tion"
    On line 33, added alt="" attribute to the imgage.
    On line 39, changed class="online---ent" to class="tools"
    On line 40, added alt="" attribute to the imgage.
    On line 46, changed class="social-----ting" to class="tools"
    On line 47, added alt="" attribute to image.
    On line 55, replace <div> with <aside>.
    On line 56, change class="benefit-lead" to class="benefit-description"
    On line 57, added alt="" attribute to image
    On line 63, change class="benefit-brand" to class="benefit-description"
    On line 65, added alt="" attribute to image
    On line 70, change class="benefit-cost" to class="benefit-description"
    On line 72, added alt="" attribute to image
    On line 80, added <footer>

## Code refactored by Mark on style.css
### To consolidate the CSS
    On line 9, added the font-size of "p{} on line 49"; to remove the line 49;
    On line 10, added the font-family used in ".header nav" on line 33; because the same font-family is used many times.
    On line 25, changed ".header h1 .seo" to "#seo" since I set the id="" for "seo" in index.html file.
    On line 29, changed ".header div" to ".header nav" since I changed the "div" to "nav" in index.html file.
    On line 33, removed/commented out the font-family because the font-family was already set in "body{}"
    On line 37, changed "div" to "nav" because I changed the "div" to "nav" in "<header>"
    On line 41, same as 37.
    On line 51, removed/commented out the "p{}"; refer to line 9.
    On line 56, changed ".hero" to "#hero" because of changes made in index.html
    On line 88, refer to line 10.
    On line 94, added ".benefit-description{ margin-botton and color}" and consolidate line from 101 to 114
    On line 116, added ".benefit-description h3{}" and consolidate line form 123 to 136
    On line 138, added ".benefit-description img{}" and consolidate line from 145 to 161
    On line 163, added ".tools{}" and consolidate line from 176 to 192
    On line 167, refer to line 10
    On line 194, added ".tools img" and consolidate line from 200 to 210
    On line 211, added ".tools h2" and consolidate line from 216 to 229
 





















 
