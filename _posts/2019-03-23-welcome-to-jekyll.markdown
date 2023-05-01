---
layout: post
title:  "MuSE-SVS: Multi-Singer Emotional Singing Voice Synthesizer that Controls Emotional Intensity"
date:   2023-03-20 21:03:36 +0530
categories: DL SVS
---
We propose a multi-singer emotional singing voice synthesizer, Muse-SVS, that expresses emotion at various in- tensity levels by controlling subtle changes in pitch, energy, and phoneme duration while accurately following the score. To control multiple style attributes while avoiding loss of fidelity and expressiveness due to interference between attributes, Muse- SVS represents all attributes and their relations together by a joint embedding in a unified embedding space. Muse-SVS can express emotional intensity levels not included in the training data through embedding interpolation and extrapolation. We also propose a statistical pitch predictor to express pitch variance according to emotional intensity, and a context-aware residual duration predictor to prevent the accumulation of variances in phoneme duration, which is crucial for synchronization with instrumental parts. In addition, we propose a novel ASPP- Transformer, which combines atrous spatial pyramid pooling (ASPP) and Transformer, to improve fidelity and expressive- ness by referring to broad contexts. In experiments, Muse-SVS exhibited improved fidelity, expressiveness, and synchronization performance compared with baseline models. The visualization results show that Muse-SVS effectively express the variance in pitch, energy, and phoneme duration according to emotional intensity. To the best of our knowledge, Muse-SVS is the first neural SVS capable of controlling emotional intensity.

```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
	key_id: 'KEY_ID',
	secret: 'name'
});

// capture request
rzp.capture(payment_id, cost)
	.then(function (data) {
		return 2;
	})
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/