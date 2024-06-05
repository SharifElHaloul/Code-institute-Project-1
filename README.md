## Bugs found and solved:
1. Could not change color of logos by targeting nav links due to bootstrap override:

```css
.nav-link a {
    color: #D65DB1;
}

```

as above I had to change to make sure to specifically target links to make sure colour actually changed.



2. I had figured out that I had two "active" classes in my HTML code which was solved quickly:

![arcade scene](assets/images/home-tab-bug.png)

```HTML

 <ul class="nav justify-content-end" id="navigation-menu">
                        <li class="nav-link active">
                            <a class="active" href="index.html">Home</a>
                        </li>




## code: 

## wesbites used:

fontjoy.com for font pairing

pexels.com for arcade images for website

fonts.google.com for fonts


