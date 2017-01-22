---
layout: post
title:  "The fox is back!"
date:   2017-01-22 18:00:00 +0800
categories: jekyll update
---
This is my first post in `GitHub.io`.

------


Here comes an image:
![This is an Octocat]({{ site.url }}/assets/Octocat.png)

------

Let's try a link to [download]({{ site.url }}/assets/Octocat.png) the octocat.

------

Perfect, how about having a URL [Go to my homepage][My GitHub.io] test.

------

Wow! Can I have a list of all my post?
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

------

Finally, post some source code:
{% highlight c %}
int main(void)
{
  printf("Hello, GitHub.io!\n");
}
{% endhighlight %}

[My GitHub.io]: https://amaruk.github.io/
