---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
{% if site.google_analytics and jekyll.environment == 'production' %}
{% include analytics.html %}
{% endif %}


<script>window.twttr = (function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0],
    t = window.twttr || {};
  if (d.getElementById(id)) return t;
  js = d.createElement(s);
  js.id = id;
  js.src = "https://platform.twitter.com/widgets.js";
  fjs.parentNode.insertBefore(js, fjs);

  t._e = [];
  t.ready = function(f) {
    t._e.push(f);
  };

  return t;
}(document, "script", "twitter-wjs"));</script>

<a class="twitter-share-button" 
   data-size="large"
   url="https://revolutiontips.github.io"
   href='https://twitter.com/intent/tweet?text=Resources%20for%20protestors">
         Share on Twitter
</a>
