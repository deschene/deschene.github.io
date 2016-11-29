---
layout:     post
title:      Hello World! (It's me)
date:       2016-11-28
summary:    Just saying hello...
categories: jekyll pixyll
---

There is just a test post to say HELLO WORLD!

Here's some java code for the heck of it.

{% highlight java lineanchors %}
// Some test java code
private final class MyClass extends Activity {
 
  @Override
  protected void onCreate(Bundle savedInstanceState) {
      super.onCreate(savedInstanceState);

      setContentView(R.layout.levelup_activity_home);

      ActionBar actionBar = getSupportActionBar();
      if (actionBar != null) {
          actionBar.setBackgroundDrawable(new ColorDrawable(Color.TRANSPARENT));
          actionBar.setTitle(null);
      }
  }

}
{% endhighlight %}
