# Kickstart-Progress-Bars
Progress bars for Kickstart

## Usage
1. After installing the submodule, add the component to your vendor index file.

    // lib/sass/vendor/_index.sass
    @import Kickstart-Progress-Bars/progress

2. Add the `progress()` mixin to a progress element

    progress {
      @include progress();
    }

3. Optionally define a bar or background color

    progress($color: black, $background-color: white);

## Setting expectations

This progress bar uses the new HTML5 progress bar, which is [lagging in support for some browsers](http://css-tricks.com/html5-progress-element/).
