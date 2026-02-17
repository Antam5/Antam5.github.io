---
layout: post
date: 2026-02-16
---

In this [article](https://arxiv.org/abs/2407.03747) written with [Nicolas Raymond](https://nraymond.pages.math.cnrs.fr/webpage/) I consider pseudodifferential operators acting on a domain of $L^2(\mathbb{R})$ whose symbol is 

$$p(x,\xi) = a(\xi)+hb(x,\xi), ~~ b(x,0) \hbox{ is a double well potential}. $$
By **definition** we say that $V \in \mathscr{C}^{\infty}(\R)$ is a double well potential if and only if 

$$ \left \{ \begin{array}{ll} V \hbox{ has two unique nondegenerate minima at } -x_\ell,x_\ell \hbox{ and } V(\pm x_\ell) = 0 \\ V(x) =V(-x) \hbox{ for all } x \in \R
\end{array} \right.
$$

Under generic assumptions on the growth of the symbol (in order to guarantee confinement) and holomorphy in a tubular neighbourhood of $\mathbb{R}^2$ (of the form $\Sigma = \mathbb{R}^2 + \{ 0 \} \times i[-\delta,\delta]$) one is able to obtain sharp estimate on the shape of the eigenfunctions.


In particular the spectrum of p^w near $0$


You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
