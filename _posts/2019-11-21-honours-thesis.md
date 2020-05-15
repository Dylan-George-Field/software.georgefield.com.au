---
date: 2018-11-03
title: Honours Thesis
categories:
  - University
feature_image: /images/blog/honours-thesis/honours-thesis-dylan-george-field.jpg
feature_image_title: 
---
<p>
I was asked to investigate fingerprint technology before it went viral on the iPhone 5S and other mobiles.
</p>
<p>
The work is based on how to stop people stealing your fingerprints. You only have 10 of them and you can't change them easily like your keys or a password! We need a way to produce a reliable key from your fingerprint that is reproducible but not reversible.
</p>
<p>
What I did was use something called a Fuzzy Embedder and a method called Quantization Index Modulation proposed by <a href="{{ site.baseurl }}/downloads/embedding-renewable-cryptographic-keys-into-continuous-noisy-data-buhan.pdf">Buhan et al</a> to combine a key with a fingerprint.
</p>
<p>
It worked but it had problems. The main difficulty was getting reliable data points (minutiae) from fingerprints. The second was the quantizer has difficulty when data points fall near its boundaries as well as incorrectly mapping a vector to a 'ghost' data point. One that doesn't exist in the original set.
</p>
<p>
Basically, you would have random errors and the key couldn't be reproduced. Not enough for a 128-bit key, anyway. Smaller keys are more reliable.
</p>
<p>
I did all this with a shitty old microsoft fingerprint reader a friend gave me, freeware C# fingerprint extraction software and a bunch of code from MATLAB. I was surprised it worked at all.
</p>
<p>
It would work better with an ordered and reliable dataset like a retinal scan although you could get better results with a better fingerprint reader and optimised software.
</p>
<p>
<strong>Supervisor:</strong> Nandita Bhattacharjee (Monash University)<br />
<strong>Thesis:</strong> <a href="{{ site.baseurl }}/downloads/fingerprint-based-biometric-cryptosystem-using-the-fuzzy-embedder-dylan-george-field-minor-thesis.pdf">Fingerprint based Biometric Cryptosystem using the Fuzzy Embedder</a>
</p>