---
layout:     post
title:      Example post
date:       2014-06-10 12:31:19
summary:    See what the different elements looks like.
categories: jekyll
---

There is a significant amount of subtle, yet precisely calibrated, styling to ensure
that your content is emphasised while still looking aesthetically pleasing.

All links are easy to [locate and discern](#), yet don't detract from the [harmony
of a paragraph](#). The same goes for  _italic_ and __bold__ elements. Even the the strikeout
works if <del>for some reason you need to update your post</del>. For consistency's sake,
<ins>the same goes for insertions</ins>, of course.

## Code with syntax highlighting

```golang
// golang
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

```scss
/* scss */
.posts {
  margin-bottom: 6em;
  .post {
    border-bottom: $post-border;
    &:last-child {
      border-bottom: none;
    }
  }
}
```

{% highlight js %}
// JavaScript
var isPresent = require('is-present')

module.exports = function doStuff(things) {
  if (isPresent(things)) {
    doOtherStuff(things)
  }
}
{% endhighlight %}

{% highlight html %}
<!-- HTML -->
<div class="m0 p0 bg-blue white">
  <h3 class="h1">Hello, world!</h3>
</div>
{% endhighlight %}

# Headings

They're responsive, and well-proportioned (in `padding`, `line-height`, `margin`, and `font-size`). This allows your content to have the proper informational and contextual hierarchy. Yay.

### There are lists, too

  * Apples
  * Oranges
  * Potatoes
  * Milk

  1. Mow the lawn
  2. Feed the dog
  3. Dance

### Footnotes

Markdown footnotes are supported, and they look great! Simply put e.g. `[^1]` where you want the footnote to appear,[^1] and then add the reference at the end of your markdown.

### Images look great, too

__Standard image__

![desk](https://cloud.githubusercontent.com/assets/1424573/3378137/abac6d7c-fbe6-11e3-8e09-55745b6a8176.png)

__Full width image__

_![desk](https://cloud.githubusercontent.com/assets/1424573/3378137/abac6d7c-fbe6-11e3-8e09-55745b6a8176.png)_

### Stylish blockquotes included

You can use the markdown quote syntax, `>` for simple quotes.

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse quis porta mauris.
{:.blockquote}

However, you need to inject html if you'd like a citation footer.

<blockquote class="blockquote">
  <p>Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.</p>
  <footer class="blockquote-footer"><cite title="Antoine de Saint-Exupéry">Antoine de Saint-Exupéry</cite></footer>
</blockquote>

Happy writing.

---

[^1]: Important information that may distract from the main text can go in footnotes.
