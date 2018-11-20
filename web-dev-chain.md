# Front-End Web Development Chain

**A. Proto-site (HTML+)**
  * Prototype the site into its final form, minus the complete content
  * HTML+ = Web Standards&mdash;html, css, js <br>
    <small>(*plus Web APIs&mdash;svg, canvas, video, etc*)</small>

**B. Componentize the prototype into reusable containers**
  * Repeatable sections are made into components.  The complete structure of the section is included, with content to be added later
    * May use backend technologies as as *XML, PHP, Ruby/Rails...*
    * Increasingly, front-end javascript frameworks such as *React, Angular or Vue* are used for components, with content provided as separate data files (ie, *JSON*)

**C. Construct the site**
  * Populate the components with content
  * Combine the page elements
    * Outer container with boilerplate HTML wraps around the components
    ```
    html
        head
        body
          boilerplate content
          components content
          remaining boilerplate
    ```

**D. Publish the site **
