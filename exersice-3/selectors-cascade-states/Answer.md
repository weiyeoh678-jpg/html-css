# CSS selectors and which rule wins: my answers

## 1. When must you use a class selector, and not an element selector?
when you want to find a selected item and not affect to other element with the tag.

## 2. What does the space mean in `.material-shelf p`?
That mean it finds element inside other element.

## 3. What does `>` mean in `.quick-nav > a`?
'>' means only the direct children and for > a' is element that has an element with class="quick-nav" is direct parent.

## 4. Why must a button link have a `:hover` style and a `:focus` style?
This is because it make sure they got feedback when the user are click it.

## 5. If `a` and `.quick-nav > a` both set `color` on a navigation link, which selector wins in the stylesheet of this lesson?
The '.quick-nav > a' wins, its more specific as you already mentions what the instruction to do.
