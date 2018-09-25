---
layout: search
title: Search
status_content: ✅
status_live: ✅
status_comment: Currently working
--- 

<form action="{{ '/search.html' | prepend: site.github.url}} " method="get">


  <div class="dci-block-longer">
    <input type="text" id="search-box" style="width:300px;" class="dci-input-text" name="query">
    <input type="submit" class="dci-button dci-button--tertiary" value="Search">
  </div>


</form>

<div class="search-results-container">
  <ul id="search-results"></ul>
</div>





