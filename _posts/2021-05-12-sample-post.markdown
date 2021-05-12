---
layout: post
title:  "First Post"
date:   2021-05-12 15:48:35 +0900
categories: Others
---

This post is for testing

code snippets:

```python
class WAE(keras.Model):
    def __init__(self, encoder, decoder, noise=0.2, lamb=1.,alpha=[0.1]*5, **kwargs):
        super(WAE, self).__init__(**kwargs)
        self.encoder = encoder
        self.decoder = decoder
        self.noise = noise
        self.lamb = lamb
        self.alpha=alpha
```

connect to link:

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll¡¯s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/