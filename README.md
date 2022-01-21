# README.md

- HTML & CSS Info
- Code journal
- Attributions

## HTML & CSS Info

### HTML

- Fonts: copy the code provided from [google fonts](https://fonts.google.com) and add it to the `head` tag
- Stylesheet link: make sure that you link the correct path and don't use any spaces in your filenames
- **important** review how the containers and their elements are nested.
  - all text should be inside of a text tag
  - containers and text all need closing tags
  - divs are just used when their only reason for existing is styling. The `<div class="img-container">...</div>` is a good example of this
- articles should be able to stand on their own, otherwise use a `section` or `div`
- avoid putting the container tag and it's child tag on the same line.
- double check your indentation [this link has info on setting autoindent on](https://mspoweruser.com/visual-studio-code-can-now-indent-code-automagically/)

### CSS

- whitespace in declarations like:

```
h1 {
  font-size: clamp(2.5rem, 10vw, 4rem);
}
```

- organize your css in a way that makes sense to you
  - to verify this. try reading it after not looking at it for a day. if you're struggling to find things, think of better ways to organize it
- `display: flex;` is used to create a flexbox container
  - everything directly inside that container is a **flex item**
  - review [this css article](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - flexbox quick tips:
    - switch the display of flex items from the default (row) to a column with
      - `flex-direction: column;`
    - change the main axis alignment with `justify-content`
      - `justify-content: space-around`
        - options: `flex-start`, `center`, `flex-end`, `space-around`, `space-between`

### Debug Tips

- If things aren't working right, scan through your html and css files and look for spelling errors and syntax errors
  - common issues:
    - improper nesting or missing closing tags
    - incorrect punctuation (ie: a - instead of a = when adding a class to an html element)
    - rules overriding other rules

---

## Wiki Article Code Journal

### TODOS

- x download local photo and add attribution
- x fix font sizes
- x change fonts
- x fix image size
- x fix text box sizes
- x slightly round corners (like 3-5px)
- x fix text align issues

#### Bugs

No Major bugs
h4 alignment is kinda weird on mobile screen size

---

## Attributions

- [Image of people with laptop](https://www.pexels.com/photo/closeup-photo-of-three-person-looking-at-macbook-air-1181376/) by [Christina Morillo](https://www.pexels.com/@divinetechygirl?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) licensed under [pexels license](https://www.pexels.com/license/)
