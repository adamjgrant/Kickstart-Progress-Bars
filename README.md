# Kickstart-Progress-Bars
Progress bars for Kickstart

Apply Kickstart styling to the default HTML5 element.

## Usage
After installing the submodule, add the component to your vendor index file.

    // lib/sass/vendor/_index.sass
    @import Kickstart-Progress-Bars/progress

Add the `progress()` mixin to a progress element

    progress {
      @include progress();
    }

Optionally define a bar or background color

    progress($color: black, $background-color: white);

Create a progress bar on your site

    <progress max="100" value="50"></progress>

## Setting expectations

This progress bar uses the new HTML5 progress bar, which is [lagging in support for some browsers](http://css-tricks.com/html5-progress-element/).
