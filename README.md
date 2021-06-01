## grudu

_A grid framework by pudu._

* From The Odin Project's [curriculum](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/html-and-css/lessons/design-your-own-grid-based-framework)

### How to use grudu

Copy the contents of grudu.css in your project  
Or clone the repository if you want to make adaptations - `git clone https://github.com/pudu87/grudu.git`

### Features

This is a very basic framework, structurally composed out of 4 scss-files
* **_reset.scss**  
  * Reset styles by [Eric Meyers](https://meyerweb.com/eric/tools/css/reset/)
* **_text.scss**  
  * Font definitions for the body-tag  
  * Fixed font sizes and line-height for p- and h-tags  
  * Bottom-margins for certain elements  
* **_grid.scss**  
  * `.container-resp` to fit your app in a responsive container for screenwidths at 480px, 768px and 1024px  
  * `.container-full` that fills all of the width (exempt from margins)  
  * `.grid`. It's children should be provided with a `.col-#`-class, where # takes up #/12 of the the parent width
* **_other.scss**  
  * Apply clearfix easily, with the `.clearfix`-class  
  * The `.btn`-class makes your buttons fancy  
  * General styling for textarea- and input-tags  
  * Aspect ratio-classes for all your images. Apply `.aspect-ratio-img` and the preferred `.ar`-class to let your image grow or shrink responsive in the right aspect ratio
  
  
