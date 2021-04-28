# Theme Builder

This project was initialised with [Create React App](https://github.com/facebook/create-react-app) with SCSS, TypeScript added.  
Although, this is intended as a small project, I set up the React folder structure including an icon library and bootstrap to be scalable for larger projects.

The main goal of this project was to learn more complex scss and use it to code a front end with multiple color themes.    
  
Project Requirements:  
  
Maintainable - The color themes are encapsulated in their own files, with different levels of abstraction; a color can be replaced in the theme or a certain use case for that color can be swapped, all independently of other themes. This was an important criteria for me as light and dark modes are not simply mirror opposites.  
  
Dry - The code repeats itself as little as possible, making it easy to amend styling without having to go through every styling file. Whilst it’s not a massive challenge for small projects it does create a legacy challenge as projects grow so it’s best to implement a solution from the beginning.  
  
Scalable - There are currently 2 themes (light & dark) but the project allows for additional themes to be added (at a later date) without having to restructure the existing code. This is useful for when re-branding or having multiple brands.  
  
The App will also match the users preferred OS color scheme. However, its possible to overwrite this by changing the color scheme; which saves the users preference to local storage. This also ensures that the color scheme persists after a page refresh.  
  
----------------
## Tech  
- JS / TypeScript  
- React  
- SCSS  

----------------
## Quickstart
Clone this repo to your local drive and open in your editor of choice.  

To Launch the app locally:  
```bash
# From the /theme-builder repository:
> npm install
> npm run build
> npm start
```
