<div align="center">

# Vanilla ToggleDark

[![Demo](demo.gif)](https://gnkalk.github.io/Vanilla-ToggleDark)

[FA](README.rtl.md)

You can also create a Dark Mode button without JS 🌞🌜

</div>

You may ask how? The purpose of this repo is also to explain this issue to you so that you may create a website with less JS :)

Well, to do this in the html section, you must first create an input button to get the user input, but you are not going to get the input through this button.

```html
<input type="checkbox" id="dark">
```

**Tip** Place the input tag at the beginning of the wind so that you can later darken all parts of the html file.

You can give two types of radio or checkbox to the input, but we only explain the checkbox method here.

Well, after that you have to create a label tag to manipulate the checkbox using it.

```html
<label for="dark">
```

Set the label on the checkbox idi and put it inside the content (moon and sun icon or ..)

Well, then CSS create a CSS file and link to your HTML file.

Now, in the first step, completely hidden the checkbox.

```css
input#dark {
    position: absolute;
    visibility: hidden;
}
```

Well, we have to get to the heart of the matter, using: Checked to give the rest of the items a very comfortable and stylish style. You can also use ~ it to modify the sidebar, however, if you have not noticed yet, there is a demo here for good understanding =))

---

Created By [Gnkalk](https://github.com/Gnkalk) ©️ 2021