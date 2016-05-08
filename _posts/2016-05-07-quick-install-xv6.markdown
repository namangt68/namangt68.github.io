---
layout: post
title:  "Quick install xv6 OS"
date:   2016-05-07 21:36:29 +0530
categories: xv6 OS
---
Quick Install and run xv6 



{% highlight shell %}
sudo apt-get install qemu
sudo apt-get install libc6-dev:i386
https://github.com/mit-pdos/xv6-public.git xv6
chmod 700 -R xv6
cd xv6
make
make qemu
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
