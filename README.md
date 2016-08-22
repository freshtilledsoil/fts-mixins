# Sass Mixins

Collection of various Sass mixins we've used on projects.


## How to use

Pull in any individual file by referencing it with ```@import 'FILE_Name';```

Or include the full library by placing the folder in your Sass directory, and then importing the __import.scss file:

```css
  @import 'mixins/__import';
```


## Contribute

To download and contribute to the repo...

* Clone the repo:  
  ```
  // change the current working directory to the location
  // of where you want to clone the repository to
  $ cd YOUR-DIRECTORY

  // clone the repo
  $ git clone https://github.com/freshtilledsoil/fts-mixins.git
  ``` 
* Create a new branch and add your new mixin file

* When creating your mixin, please adhere to the following template:

  ```css
  /** --------------------------------------------------------------------

    Title of mixin

    add a short description / source attribution here

  --------------------------------------------------------------------- */

  @mixin unique-name ( $vars ) {

    // mix it up!

  }


  /**

    Example Usage:
    -----------------------------------------------------------

    // include a Sass example

    .example-class {
      @include unique-name ( # );
    }

    // and a markup example, if it requires 
    // a specific markup pattern.

    <div class="example-class">
      <div class="example-class__child">
        ...
      </div>
    </div>

  */
  ```

* Push your changes and submit a pull request! :)


### Credits & license

Please see the inline comments within a mixin file for any links to the original source author.

Available for use under the [MIT License](https://github.com/freshtilledsoil/fts-mixins/blob/master/LICENSE).
