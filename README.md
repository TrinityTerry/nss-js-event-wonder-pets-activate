# Wonder Pets Activate

Date Created: 01/20/20 | Date Modified: 01/20/20

This assignment is practice for Book 2: Chapter 12 of NSS's course work. Link to the assignment: https://github.com/TrinityTerry/client-side-mastery/blob/master/book-2-the-neophyte/chapters/JS_EVENTS.md#practice-wonder-powers-activate

Preview Assignment: 
***
1. Add the correct string as the first argument to `addEventListener()`
2. Write a function named `flightHandlerFunction` that will remove the `disabled` class on the corresponding `<section id="flight">` (section, not button) and replace it with a class of `enabled`.
3. Have your developer tools open. When you click the button, the following element...

```html
<section id="flight" class="power disabled">
```

Should then look like this.

```html
<section id="flight" class="power enabled">
```

Once you have that working, write two more JavaScript functions, and two more `querySelector().addEventListener()` statements for handling the click event on the other two buttons. Those event handlers should perform the same step of removing `disabled`, and adding `enabled` on the corresponding `<section>` elements

```js
document.querySelector("#activate-mindreading").addEventListener()
document.querySelector("#activate-xray").addEventListener()
```

Once that is complete, add two more buttons
1. Enable All Powers
2. Disable All Powers

Write two more event handlers for activating and deactivating all powers when the corresponding buttons are clicked. You will need to use the `document.querySelectorAll()` method for these.