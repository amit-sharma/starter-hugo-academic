+++
title = "A Gentle Introduction to Causal Inference"
date = 2016-06-28T19:15:49+05:30
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Amit Sharma"]

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["causal inference",]
categories = []

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = ""
caption = ""
preview = true

+++

>That we find out the cause of this effect,

>Or rather say, the cause of this defect,

>For this effect defective comes by cause.

-*Hamlet* by William Shakespeare

A few years back I stumbled upon the [world of causality](https://aeon.co/essays/could-we-explain-the-world-without-cause-and-effect). Two things became immediately clear. First, it is a fascinating topic spanning some of the greatest scholars in [philosophy](http://plato.stanford.edu/entries/leibniz-causation/), [logic](http://www.hist-analytic.com/Russellcause.pdf) and [statistics](https://projecteuclid.org/euclid.ssu/1255440554). Second, and most unfortunately, the literature on it tends to be a dense, uninviting tome.

The more I read, the more I realized that the central concepts are actually very simple. And beneath all the heated arguments about definitions of causality and frameworks for inferring it, the goals and principles of causal inference are one and the same. I wondered, and still wonder, why different disciplines choose to passionately accept one way of thinking about causality versus another. Especially as a computer scientist, I wondered why causal inference is not taught at all even in a graduate program,  at a time when computers are affecting all walks of life. 

As an outsider, I wished there was an easier way to describe the fundamentals of causal inference.

Last week I got an opportunity do just that. I gave a tutorial on causal inference at the International Conference on Computational Social Science ([IC2S2](http://www.kellogg.northwestern.edu/news-events/conference/ic2s2/2016.aspx)). Here's my attempt at describing causal inference in an intuitive way, the way I have learnt it and the way I still understand it.  

Hope this is useful. If it piques your interest, I also prepared sample code to play with recommender system data and methods for causal inference. Find it here: https://github.com/amit-sharma/causal-inference-tutorial

<iframe src="//www.slideshare.net/slideshow/embed_code/key/nwdSAxsuidSS3X" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/AmitSharma315/from-prediction-to-causation-causal-inference-in-online-systems" title="From prediction to causation: Causal inference in online systems" target="_blank">From prediction to causation: Causal inference in online systems</a> </strong> from <strong><a href="//www.slideshare.net/AmitSharma315" target="_blank">Amit Sharma</a></strong> </div>
