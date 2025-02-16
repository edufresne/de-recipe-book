# Eric & Dharti's Recipe Book
A simple recipe book for all of the recipes me and my wife make that are bomb enough to write down. Also an experiment to see if I can teach her how to use Git with no coding experience. See the recipe book at https://ericdharti.com
### How to Run
Download latest changes if both of us are working on it
```
git pull
```
Install the repository and run it
```
uv install
mkdocs serve
```
### How to Contribute
The recipes are all in the `/docs` folder of this repository. To add a new section or subsection, simply create new directories with the names you want.

To add a new recipe, simply add a recipe where you want and name it `<Recipe Name>.md`.

### How to Publish
You can let me do it or you can run:
```
git pull
mkdocs build    
firebase deploy
```
