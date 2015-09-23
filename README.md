# Supercharged SEO with Views
## Supercharged SEO with Views - Drupal Camp Ohio 2015
http://drupalcampohio.org/sessions/supercharged-seo-views
<p>While the fundamentals of <abbr title="Search Engine Optimization">SEO</abbr> are well known, newer Structured Data formats like JSON-LD can supercharge your search results.</p><p>We&#39;ll look at a fairly simple formula using Views, <abbr title="Entity Views Attach">EVA</abbr>, Schema.org and Google&#39;s Structured Data Testing Tool&nbsp;to add valid JSON-LD to our content.</p><p>How does all this work benefit you? <a href="https://developers.google.com/structured-data/">Google</a> says:</p><blockquote>&quot;Structured data markup&quot; is a standard way to annotate your content so machines can understand it. When your web pages include structured data markup, Google (and other search engines) can use that data to index your content better, present it more prominently in search results, and surface it in new experiences like voice answers, maps, and Google Now.</blockquote>
<p>Steps:<ol>
<li><a href="https://github.com/UpTil4Music/supercharged-seo/blob/master/module-list">Install modules</a></li>
<li>Create "Event" content type and add <a href="https://github.com/UpTil4Music/supercharged-seo/blob/master/field-list">fields</a></li>
<li>Add <a href="https://github.com/UpTil4Music/supercharged-seo/blob/master/iso-8601-date-format">ISO-8601 date format</a></li>
<li>Import the <a href="https://github.com/UpTil4Music/supercharged-seo/blob/master/views-export-json-ld-attach">JSON-LD Attach</a> view</li>
<li>Make sure your view fields are in <a href="https://github.com/UpTil4Music/supercharged-seo/blob/master/view-fields-order">order</a></li>
<li>Add a <a href="https://github.com/UpTil4Music/supercharged-seo/blob/master/views-view-fields--json-ld-attach.tpl.php">template</a> to your theme</li>
<li>Make sure the JSON-LD Attach EVA Field is displayed on your Event view modes (/admin/structure/types/manage/event/display)</li>
      <li>Check your date on <a href="https://developers.google.com/structured-data/testing-tool/">Google's Structured Data Testing Tool</a></li>
<li>If you've got a syntax error, try the <a href="http://json-ld.org/playground/index.html">JSON-LD Playground</a></li>
</ol></p>
