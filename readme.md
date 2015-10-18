# CSS Only Tool Tips
Here you'll be able to find a demo, as well as the code for some simple, yet effective CSS3 tool tips. With basic CSS knowledge you can change the colours and fonts required.

## Installation
To install this, simply reference the tool-tips.css file in your <head> section (or put the content of this file in your own).

## Markup
With a tooltip, a popup appears when you hover over a word. Simply wrap that word in a span with a class of "tool-tip":

```
<p>When you hover over <span class="tool-tip">this</span> word, a tool tip will appear</p>
```

To add the tool tip content, use a custom data attribute of "data-tool-tip" like so:

```
... <span class="tool-tip" data-tool-tip="Tool tips are awesome!">this</span> ...
```