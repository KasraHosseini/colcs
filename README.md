# COLCS

a New Color Library of css

## introducing

> What is **colcs** ?

**colcs** is a color library, which can beautify elements with standard colors.

> You can also use this library's **hover** and **focus** effects

## Usage example

1. At first, you must link `colcs.css` in your file.

   > With downloaded file:

   ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <meta charset="UTF-8" />
       <meta http-equiv="X-UA-Compatible" content="IE=edge" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <link rel="stylesheet" href="colcs.css" />
     </head>
     <body data-theme-mode="light">
       <!-- your code -->
     </body>
   </html>
   ```

2. Then, use css classes.

   ```html
   <!DOCTYPE html>
   <html lang="en">
     <head>
       <meta charset="UTF-8" />
       <meta http-equiv="X-UA-Compatible" content="IE=edge" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <link rel="stylesheet" href="colcs.css" />
     </head>
     <body data-theme-mode="light">
       <p class="text-red">my text</p>
       <p class="text-red-100">my text</p>
       <p class="bg-lime-200">my text</p>
     </body>
   </html>
   ```

## Theme mode

At `<body>` tag you can use **dark** and **light** mode like this :

1. For light mode

   ```html
   <body data-theme-mode="light">
     <!--light mode -->
     <p class="text-blue-300"></p>
     <p class="bg-violet-600"></p>
   </body>
   ```

2. For dark mode

   ```html
   <body data-theme-mode="dark">
     <!--light mode -->
     <p class="text-blue-300"></p>
     <p class="bg-violet-600"></p>
   </body>
   ```

## classes

1.  text color

    ##### To set the text color, use `text-...` :

    ```html
    <p class="text-violet">Hello world</p>
    ```

    > You can adjust the brightness of the **text** by adding number after css class :

    ```html
    <p class="text-violet-200">Hello world</p>
    ```

2.  back ground color

    ##### To set the back ground color, use `bg-...` :

    ```html
    <div class="text-green">Hello world</div>
    ```

    > You can adjust the brightness of the **background** color by adding number after css class :

    ```html
    <div class="text-green-800">Hello world</div>
    ```

3.  border color

    ##### To set the border color, use `border-...` :

    ```html
    <div class="border-blue">Hello world</div>
    ```

    > You can adjust the brightness of the **border** by adding number after css class :

    ```html
    <div class="border-blue-400">Hello world</div>
    ```

4.  text shadow

    ##### To set the text shadow color, use `shadow-text-...` :

    ```html
    <div class="shadow-text-slate">Hello world</div>
    ```

    > You can adjust the brightness of the **text shadow** by adding number after css class :

    ```html
    <div class="shadow-text-stone-950">Hello world</div>
    ```

5.  box shadow

    ##### To set the box shadow color, use `shadow-box-...` :

    ```html
    <div class="shadow-box-orange">Hello world</div>
    ```

    > You can adjust the brightness of the **box shadow** by adding number after css class :

    ```html
    <div class="border-orange-500">Hello world</div>
    ```

## hover

1. For using hover effect you should add `hover-colcs`, or use your customize style
   ```html
   <div class="hover-colcs"></div>
   <!-- transition: ease-in-out 0.2s; -->
   ```
   ```css
   .hover-colcs {
     transition: ease-in-out 0.2s;
   }
   ```
2. use hover classes
   ```html
   <div class="hover-colcs text-hvr-lime">hello world</div>
   <div class="hover-colcs bg-hvr-lime">hello world</div>
   <div class="hover-colcs border-hvr-lime">hello world</div>
   <div class="hover-colcs shadow-hvr-text-lime">hello world</div>
   <div class="hover-colcs shadow-hvr-bg-lime">hello world</div>
   ```

## focus

1. For using focus effect you should add `focus-colcs`, or use your customize style
   ```html
   <div class="focus-colcs"></div>
   <!-- transition: ease-in-out 0.2s; -->
   ```
   ```css
   .focus-colcs {
     transition: ease-in-out 0.2s;
   }
   ```
2. use hover classes
   ```html
   <input type="text" value="hello world" class="focus-colcs focus-text-lime" />
   <input type="text" value="hello world" class="focus-colcs focus-bg-lime" />
   <input type="text" value="hello world" class="focus-colcs focus-outline-lime" />
   ```
