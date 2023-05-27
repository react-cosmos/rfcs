- Start Date: 2021-02-12
- RFC PR: (leave this empty)
- React Cosmos Issue: (leave this empty)

# Summary

RTL / LTR switcher for preview area

# Motivation

Humanity has few languages where writing starts from the right of the page and continues to the left.

Famous UI-kits supports RTL in their component
- https://rsuitejs.com/guide/rtl
- https://material-ui.com/ru/guides/right-to-left/

It will very useful for the developers to have a toggler that can enable RTL and helps to develop universal UI components.

# Detailed design

- Add a toggle button with two states: 
    1. LTR (default) `arrow-right.svg`
    1. RTL (pressed) `arrow-left.svg`
- Assign attribute `dir=rtl` to view-port iframe `<html>` element when the toggle button pressed
    https://www.w3.org/International/questions/qa-html-dir     

# Drawbacks

--

# Alternatives

set up `dir=rtl` directly in the browser dev tools

# Adoption strategy

--

# How we teach this

--

# Unresolved questions

--
