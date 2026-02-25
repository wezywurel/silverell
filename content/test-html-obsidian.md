---
title: Test HTML with Obsidian Formatting
---

# Test HTML with Obsidian Formatting

This is regular Markdown with **bold text** and *italic text*.

div без enter - работает смещение, не работает форматирование
<div align="right">
This is inside a div tag with **bold text** and *italic text*.
This is ==highlighted text==.
This is a [[wikilink]].
</div>

 p с enter - не работает смещение, работает форматирование
<p align="right">

This is inside a p tag with **bold text** and *italic text*.
This is ==highlighted text==.
This is a [[wikilink]].

</p>

span без enter + работает смещение, работает форматирование
<span style="text-align: right; display: block;">
This is inside a span tag with **bold text** and *italic text*.
This is ==highlighted text==.
This is a [[wikilink]].
</span>

> [!note]
> This is a callout note with **bold text** and *italic text*.

div с enter + работает смещение, работает форматирование
<div align="right">

This is inside a div tag with **bold text** and *italic text*.
This is ==highlighted text==.
This is a [[wikilink]].

</div>

This is after the div.

span с enter - не работает смещение,  работает форматирование

<span style="text-align: right; display: block;">

This is inside a span tag with **bold text** and *italic text*.
This is ==highlighted text==.
This is a [[wikilink]].

</span>

This is after the span.


# Test Obsidian Formatting

This is **bold text** </br>
р без enter - работает смещение, не работает форматирование
<p align="right">
and this is *italic text*.
</p>

This is ==highlighted text==.

This is a [[wikilink]].
This is a [[link with|alias]].

> [!note]
> This is a callout note.

- [ ] This is an unchecked checkbox
- [x] This is a checked checkbox

#tag #another/tag

-> This is an arrow

%% This is a comment %%