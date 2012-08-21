## Welcome

Welcome to your new Telegram site.  Check out the [Getting Started](/getting_started) page
for information on how to set up your site.

<div>
    <head_place>
         <script src="/js/jquery.carousel.min.js" type="text/javascript"></script>
    </head_place>
    <div id="pictures">
    <ul data-lift="group?by=carousel">
      <li data-post="item"><img data-post="img" src="#"></li>
    </ul>
    </div>
    <script type="text/javascript">
    $(function(){
        $("#pictures").carousel();
    });
</script>
</div>

<span data-lift="if?extra_true=has_blog">Welcome to my blog.  Here are my most recent blog posts:</span>

<div data-lift="if?extra_true=has_blog">
      <div data-lift="blog.simple"></div>
</div>

[title: Home]: /