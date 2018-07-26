---
layout: component-detail
group: components

title: Buttons
description: Buttons are are clickable elements used to perform a call to action.
status: Design complete


---

## General guidelines

<div class="u-margin-bottom-double"><a href="{{ "/design-principles.html" | prepend: site.baseurl }}" class="c-btn">Explore</a></div>


Buttons are used primarily on action items. Some examples include Add, Save, Delete, Sign up. Do not use Buttons as navigational elements. Instead, use Links because it takes the user to a new page and is not associated with an action. Each page may have one to two primary buttons. Any remaining calls-to-action are represented as secondary buttons.

## Usage

| Button type     | Purpose                                                                          |
| --------------- |----------------------------------------------------------------------------------|
| Primary         | For the principle call to action on the page.                                    |
| Secondary       | When an action does not require primary dominance on the page.                   |
| Danger          | When an action has harmful intentions to the users data (delete, remove, etc).   |
| Disabled button | Use when the user cannot proceed until an input is collected.                    |
| Small Button    | Use when there is not enough vertical space for a regular sized button.          |


## Labels

Button labels tell users what will happen when they click the button. Use verbs that describe the action, such as Add or Delete. Use sentence-style capitalization (only the first word in a phrase and any proper nouns capitalized) and no more than three words for button labels.

For Sets of Buttons, use specific labels, such as Save or Discard, instead of using OK and Cancel. This is particularly helpful when the user is confirming an action.

## Icon usage

* Use glyphs (16px) within buttons.
* Glyphs are distinguished by their solid shape and knocked-out details.
* Glyphs should always appear to the right of the text.
* Glyphs used in buttons must be directly related to the action that the user is taking.
* Glyphs must be the same color value as the text within a button.
* Ghost buttons require a glyph icon (cannot be stand alone text because of poor affordance).
