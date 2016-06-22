# Streamlined Twitter Button
Removed the external bloat from the twitter follow button. Original twitter follow button uses 33kb of external scripts, including tracking scripts. My project cuts all of that out.

My button is identical to the "Large Follow" button with username shown.

## Usage
Include the stylesheet in your project and rename the twitter handle display in `use.html`. Then, change the link to use your twitter handle rather than mine:
```html
href="https://twitter.com/intent/follow?ref_src=twsrc%5Etfw&amp;region=follow_link&amp;screen_name=LukeASalamone&amp;tw_p=followbutton"
```
For example, if your handle was `@POTUS`, you would change `screen_name=LukeASalamone` to `screen_name=POTUS`
