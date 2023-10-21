# Create gist style

Hello!

## Purpose
I wanted to embed gist in my blog posts, but I didn't like the default look.

I found css code for dark-mode ([link](https://gist.github.com/Killercodes/281792c423a4fe5544d9a8d36a4430f2)), and I modified it to have similar colors to the Dark+ theme on VS code (see `vscodeColor.png`).

## Usage
You can use it as it is (just embed the [link to the css file](https://raw.githubusercontent.com/IfatNeumann/CreateGistStyle/main/gist.css)), and I also created variables for the colors so you can modify it based on your preference :D
  * You can grab the exact colors you want by uploading a screenshot of your text editor to [image color picker](https://imagecolorpicker.com/).

* Gist has less variables to play with, so you won't be able to reach an exact copy of the VS Code theme.
  * It also mean that for different file types you'll need to adjust the css (if you want it to match the VS Code theme).

* `gist.css` is te original one, and it looks nice in python
* `gist_html.css` is adjusted to html (the only diff is class pl-c1, which is critical for me :D)
* `index.html` is for demoing how it looks like.
* `vscodeColor.png` is for documenting the color theme I based on (Dark+ in VS Code)