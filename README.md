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
```

3. Could not seem to centre align text in my divs that had bootstrap columns assigned to them no matter how specifically I targEted them. After much searching I found the bootsrap "text-center" class which fixed this:

```HTML

<div class="row text-center">
            <div class="col-md-6 col-lg-3" > 
                <img src="assets/images/dublin.jpg" class="img-fluid" alt="Dublin">

                <h4>Dublin</h4>

                <p>Our oldest location. Located in busy Fairview area we have a 3 floor location with all the equipment
                    you will need to take start your journey</p>

                    <button type="button" class="btn btn-outline-warning">Book Now</button>
```


## code: 

## wesbites used:

fontjoy.com for font pairing

pexels.com for arcade images for website

fonts.google.com for fonts


