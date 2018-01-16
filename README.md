# Tabby

## A simple, accessible tabbed interface

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

Built following the [WAI-ARIA best practices for a tabbed interface](https://www.w3.org/TR/wai-aria-practices/#tabpanel).

## [Keyboard Navigation](https://www.w3.org/TR/wai-aria-practices/examples/tabs/tabs-1/tabs.html#kbd_label)

The following keyboard navigation is implemented.

Tabbing into the `tablist`, moves focus to the active tab
Subsequently pressing the `tab` key will move focus to the associated `tabpanel`

Pressing the right arrow key, after any tab has received focus, will move focus to the next tab in the `tablist`. If the last tab in the list is reached, focus is moved back to the first. Once focus is moved, the associated `tabpanel` will be activated and shown.

Pressing the left arrow key, after any tab has received focus, will move focus to the previous tab in the `tablist`. If the first tab in the list is reached, focus is moved to the last tab in the list. Once focus is moved, the associated `tabpanel` will be activated and shown.

NOTE: If the tabs are laid out vertically, the up and down arrow keys will move the tabs forward and back.

Pressing the `Home` key, will move focus to the first tab in the `tablist`, and show its associated `tabpanel`.

Pressing the `End` key, will move focus to the last tab in the `tablist`, and show its associated `tabpanel`.

## Running locally

To run Tabby locally, first run:

```
npm install
```

Once completed, you can start up the server using:

```
npm start
```

Point your browser at http://locahost:8080
