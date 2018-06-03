---
layout: page
---

<form onsubmit="return true;">
  <input type="input" id="search" class="search-input" placeholder="{{ site.data.text[site.locale].search_placeholder_text | default: 'Enter your search term...' }}" autofocus>
</form>

<div id="results"></div>
