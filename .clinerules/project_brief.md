judyrosenthal.com

# Overview

judyrosenthal.com will be an (almost completely) static web site that honors the life of Judy Rosenthal.

# Architecture

I want to build it with hugo, and I want it to be mostly simple HTML and CSS leveraging Hugo's ability to share code with a header and footer, and hopefully also a menu.  So no big CSS libraries and clean HTML.  Let's have one stylesheet for the site included on every page.  For clearly page-specific css, let's inline it.

Let's build to work on mobile and desktop.  Please use your judgment to adapt these designs to work on both seamlessly - so fluid design.

# Assets

There are a lot of assets in assets/images.  These should be used in the site.

# Menu

The menu should have four elements:
- Biography
- Art
- Recipes
- Family

Each should have submenus on mouseover, although each should also be a node themselves (ie, there should be a page "biography")

- Biography
... Childhood
... Artist
... Haskell
... Motherhood
... New York
- Art
... Bicentennial Project
... Houston
... Heritage
... Cubistic Extensionism
... Seascapes
... Landscapes
- Recipes
... Cream Sauce
... Cherry Cream Chicken
... Salmon
... Asparagus
... Turkey Dressing
... Cabbage Salad
... Merangues
... Hello Dollies
... Derby Pie
- Family
... Brian Rosenthal (Son)
... Lilly Rosenthal (Grand-daughter)
... Charlie Rosenthal (Grand-son)
... Eve Rosenthal (Grand-daughter)
... Lucy-Jane Watson (Mother)
... Julien David Saks (Father)

# Homepage

The homepage should be a full-bleed image that links to the biography page.
However, the image should rotate in the following way:
1. Image 1: images/homepage/01_Portrait-JudithAnn Saksjpg.jpg
... links to biography page
... Title: "Biography"
2. Image 2: images/homepage/02_The_Laura_full.jpg
... links to Art > Bicentennial Project
... Title: "Art > Bicentennial Project"
3. Image 3: images/homepage/03_Courthouse Notecard_cropped.png
... links to Art > Houston
... Title: "Art > Houston"
4. Image 4: images/homepage/04_brown_landscape_full.jpg
... links to Art > Cubistic Extensionism
... Title: "Art > Cubistic Extensionism"
5. Image 5: images/homepage/05_Liberty.jpg
... links to Art > Heritage
... Title: "Art > Heritage"
6. Image 6: images/homepage/06_The_Southwind_full.jpg
... links to Art > Seascapes
... Title: "Art > Seascapes"
7. Image 7: images/homepage/06B_Picnic_full.jpg
... links to Art > Landscapes
... Title: "Art > Landscapes"
8. Image 9: images/homepage/08_family_homepage.jpeg
... links to Family
... Title: "Family"


There should be arrows ("<" and ">") on each side that allow the viewer to advance to the next photo or go back to the previous photo.  But the photos should auto-advance every 5 seconds.

On the homepage, the photo should be full-bleed.  The menu should overlap the photo.  Each photo (in the code) needs to specify whether the menu text should be white or black in some way, so that it shows up well.

By full bleed -  I mean that the width of the photo should be 100% of the width of the screen, or if the screen is too small (say less than 800px), the image should be 800px wide and what should show on the screen should be the image centered (with no scrollbars).

There should be a title overlaying the photo in the bottom left for each photo.  The title should be a rectangular div with a black background and white text with reasonable padding (say 20px)

Top left should be the words JUDY ROSENTHAL, which should link to the homepage.
Top right should be the menu.

The menu should just be the words (no background).  Submenus should have a background (dark gray text on white is fine)

# Header
Top left: JUDY ROSENTHAL
Top right: Menu

On the homepage (and eventually other pages), this will just be an overlay.  The content will be a full bleed image.

On some other pages, it will be the same thing, but with a HR underneath it and then underneath that the content as html-rendered text.

# Footer
Images Copyrighted by Judith-Ann Saks Rosenthal from original publication.  Web site content Copyright Brian Rosenthal 2026.

There should be a discreet edit link in the footer that allows the user to edit the content of the page.  Let's leave this off for now but I want to build this later.  This link should appear only in the hugo server (not in the publicly generated files).

# Pages

## Biography
## Art
## Art > Bicentennial Project
## Art > Houston
## Art > Cubistic Extensionism
## Art > Heritage
## Art > Seascapes
## Art > Landscapes
## Family

For now, all these pages should be stubs.
They can just have the name JUDY ROSENTHAL on the left, the menu on the right, and a HR. (black on white)

Eventually, I think some of them will also be full bleed image rotations, though.  And others will just be articles with embedded images in the text black (or dark gray) on a white background.


