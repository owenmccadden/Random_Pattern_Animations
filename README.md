# Random Pattern Animations

## Summary and Instructions

The home page of the site contains nine thumbnails of animations. Each animation is a different program that generates a new, random pattern upon execution. Click on the thumbnails to view the full animations. Refresh your browser to generate a new animation, and use the back arrows on your browser to return to the home page.

## Design

### Walker Class

The Walker class is the basis for each animation. The Walker class has attributes such as position, velocity, acceleration, color, size, etc.. The Walker class has display methods, which draw the Walker on the page, and walk methods which randomize the attributes of the Walker. Different variations of the walk and display functions lead to a different animation. As the program runs, the walk function continuously randomizes the attributes of the Walker, causing an ever-changing pattern to emerge.

### Random Levels

Each of the Random Levels represents one of the nine animations featured on the page. For each animation, some attributes of the Walker class are fixed and others are randomized. As such each Random Level results in a consistent, yet always slightly different animation.


