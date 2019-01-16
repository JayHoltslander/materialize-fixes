There's a lot of stuff in Materialize that doesn't quite work right. I've found myself fixing those things repeatedly for different projects. I'm not doing that anymore. ([DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself))
This repo contains a hosted css file that contains my common fixes for Materialize. Easy to import into a project now and immediately fix many annoyances.

## What's included:

### &#8226; FIX NAVBAR HEIGHT CHANGE
Prevents odd size discepancy between mobile and tablet.

### &#8226; FIX ICONS IN TABS

### &#8226; Fix paragraph spacing within .card-content
A paragraph needs spacing after it so that two paragraphs don't blend together and look like one. This fixes that.

### &#8226; Material icons fix
Make Material icons behave in an expected fashion like Font Awesome icons do.

**Demo:** https://codepen.io/j_holtslander/pen/prEXEa

### &#8226; iPhone x+ screen fix for materialize
Apple's iPhone X has a "notch" to make space for a camera and other various components. The result is some awkward situations for screen design. This code allows for Materialize to display well on the iPhone X.

**Demo:** https://css-tricks.com/the-notch-and-css/

### &#8226; Better affixing of the fixed navbar
Small tweak that will allow for other content to be included with a fixed navbar and be fixed as expected.

**Demo:** https://codepen.io/j_holtslander/pen/XoPJNv

### &#8226; Fix .collection-item that has .avatar
If the class .avatar exists with a .collection-item then the min-height for the .collection-item is 84px even if there is only 1-2 lines. This results in extraneous padding on the bottom of the item. By changing the min-height to 64px the .collection-item has proper spacing.

**Demo:** https://codepen.io/j_holtslander/pen/OrPQJL?editors=1100

### &#8226; Fix for Materialize's toolbar from FAB
Prevents circular buttons within the expanded toolbar.

**Demo:** https://codepen.io/j_holtslander/pen/wRqGRv

### &#8226; Fix materialize's card-images
Better handling of images within cards

**Demo:** https://codepen.io/j_holtslander/pen/KbXyrq

### &#8226; Custom nav-center
Self explanatory.

**Demo:** https://stackoverflow.com/a/42890059/751570

### &#8226; Materialize's sticky footer
Inclusion of the required css for sticky footer implementation.

**Demo:** https://materializecss.com/footer.html

### &#8226; Custom fixed footer for materialize
Similiar to a fixed header but for a fixed footer.

### &#8226; Custom card title gradients
Gradient overlays for card images that appear underneath card-titles.

**Demo:** https://codepen.io/j_holtslander/pen/ejZrqG

### &#8226; Improve card-title to allow for flow-text to be used
Tweak to allow for the usage of flow-text within a card-title

### &#8226; Add ability to hide card titles
Position a title offscreen to hide it while not removing it. Usually for SEO reasons.

### &#8226; Full-width collections inside card-content
When a collection is within a card on mobile, it should be the full width of the card. This fix makes it so.

### &#8226; Custom dark sidebar
A dark sidebar option.

**Demo:** https://codepen.io/j_holtslander/pen/oqGWYJ

### &#8226; Custom escape container
Utility class for escaping out of an existing container.

### &#8226; Font awesome icons for materialize
Want to use Font awesome icons within Materialize? Now you can.

**Demo:** https://codepen.io/j_holtslander/pen/JybxXy

## Use in your project
1. Save [the compiled css file](https://raw.githubusercontent.com/JayHoltslander/materialize-fixes/master/fixes.css) into your project (Recommended)
2. Download [the Sass version](https://raw.githubusercontent.com/JayHoltslander/materialize-fixes/master/fixes.scss) to include in your project
3. Import within your stylesheet (Not recommended)
````css
@import url("https://jayholtslander.github.io/materialize-fixes/fixes.css");
````

## Use on Codepen
* Add the URL <https://codepen.io/j_holtslander/pen/BvOQEa> to your Pen's CSS under it's settings window.

**Screenshot**

![Imgur](https://i.imgur.com/azPkfQP.png)
