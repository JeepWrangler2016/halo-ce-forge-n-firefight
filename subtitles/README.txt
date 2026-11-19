SUBTITLES / SUBTITULOS
======================

Dialogue subtitles are read from this folder in the game's text language:
  es.txt  for Spanish (Settings > Gameplay > LANGUAGE / IDIOMA: ESPANOL)
  en.txt  for English

One line per voice clip, tab separated, UTF-8:
  <sound tag path><TAB><permutation name or *><TAB><text>
'|' in the text starts a new line. Lines beginning with # are comments.
Clips without a line simply show no subtitle.

Example:
  sound\dialog\a10\a10_010_cryotech	*	(your subtitle text here)

Settings > Gameplay > SUBTITLES turns them on and off.
