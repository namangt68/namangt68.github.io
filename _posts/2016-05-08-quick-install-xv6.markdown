---
layout: post
title:  "Quick install guide xv6 OS"
date:   2016-05-08 9:36:29 +0530
categories: xv6 OS
---
Quick Install and run xv6 - For Ubuntu

{% highlight shell %}
sudo apt-get install qemu
sudo apt-get install libc6-dev:i386
git clone https://github.com/mit-pdos/xv6-public.git xv6
chmod 700 -R xv6
cd xv6
make
make qemu
{% endhighlight %}

Check out the [Xv6-book][xv6-book] to read more about xv6

[xv6-book]: https://pdos.csail.mit.edu/6.828/2014/xv6/book-rev8.pdf

