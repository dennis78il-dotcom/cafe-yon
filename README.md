# Cafe Yon - website

Trilingual (Hebrew / English / Russian) marketing + culture site for Cafe Yon, Pevzner 29, Haifa.

- index.html    - the website
- admin.html    - the content panel (Sveltia CMS); open /admin.html on the live site to log in and edit
- config.yml    - panel configuration
- menu.json / events.json / specials.json - editable content (prices, events, the Coffee Setup deal)

The site loads the JSON files at runtime; if they are missing it falls back to its built-in content.
