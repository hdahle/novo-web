# novo-web
Draft super-simple landing page for Novo. A minimalistic approach has been chosen. Preview here:

https://hdahle.github.io/novo-web/

### CSS
Based on w3.css 

### Responsive
Using w3.css responsive classes:
https://www.w3schools.com/w3css/w3css_responsive.asp

Apart from the top iframe showing the 3D demo, the content is organized as two columns, one third for the section title and two-thirds for the text/images:

````
  |----------|--------------------|
  | w3-third |      w3-rest       |
  |----------|--------------------|
````
The HTML becomes:
````
   <div class="w3-row">
      <div class="w3-third w3-container">
        <!-- section title here -->
      </div>
      <div class="w3-rest w3-container">
        <!-- section text/images here -->
      </div>
    </div>
````
The current landing-page has three "rows" - just keep adding rows if you want to add more content.

# Fonts
Royalty free Google fonts, Open Sans and Open Sans Condensed, in one or two weights.

# Font Awesome symbols
Icons (social media, email, phone, map marker) are from the free part of Font Awesome.

https://fontawesome.com/icons?d=gallery

# Logo and Logotype
To be completed

# Issues
### Slightly confusing 3D demo navigation and how that impacts page navigation
### 3D demo iframe chould change aspect ration for mobile devices
