# Example Parcel based Pug and SCSS Site

## How to run

- Download node if you don't have already (latest version)
- Install yarn `npm -g i yarn`
- Install parcel globally `npm -g i parcel`
- Install dev dependencies `yarn install`
- Run command `yarn start` to run the project

## About the arch

If you are building a small project with only HTML and CSS, you may want to use this arch because:

- The project is integreated with Pug so you don't have to repeat the HTML code for each page, use can use any HTML preprocessor supported by Parcel.
- The `components` folder contains the small bits of HTML whiich are repeated in the code either on the same page or on the other pages. Just like react.
  If you want to send data to the component you can declare a variable before you call the component and use the variable in the component folder.
- This arch offers styling using scss. You can use SCSS as you want and parcel will handle the rest.
- `index.pug` contains the link to the first page.
- `layouts` contains the layouts of the pages, so you can make basic surroundings of a page there and create your page based on it.
- `scripts` contains all the scripts and you can include them in pages as you like.
