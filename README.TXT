A few things that have been added:

  * Language is now source.ruby.haml. This lets us inherit Ruby magic very nicely.
  * Straight up lifted HTML Bundle's "Insert Tag (With Current Word)". Type [CTRL-,] and you get a default "%p" tag. Start with any text and you'll get that as a Haml tag, as well. An example would be typing "div", hitting [CTRL-,] and getting "%div"
  * Default tag behaviors for html, head, meta, title, body, link and DocType tags.
  * Macro for adding Inline Ruby to existing tag. Basically just adds "==" to the end of the current line's tag.
