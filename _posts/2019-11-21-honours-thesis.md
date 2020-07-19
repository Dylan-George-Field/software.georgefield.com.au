---
date: 2019-11-21
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
It worked but it has problems. Basically, you would have random errors and the key couldn't be reproduced. You could produce small keys but not 128-bits reliably.
</p>
<p>
The problem is getting good, re-usable data points (minutiae) from fingers. Rotation, position, pressure. They all change the image every time you scan. The minutiae change every time. It's difficult to get accurate readings. At leased, with the cheap setup I had.
</p>
<p>
I did all this with a shitty old microsoft fingerprint reader a friend gave me, freeware C# fingerprint extraction software and a bunch of code from MATLAB. I'm surprised it worked at all.
</p>
<p>
The quantiser also has trouble when points fall near its boundaries and incorrectly maps vectors to 'ghost' data points. Eg, One that doesn't exist in the original set. It could be overcome with more reliable data and error correcting codes.
</p>
<p>
Maybe retinal scan would give better results or a better fingerprint reader and optimised software.
</p>
<p>
🤷‍♂️
</p>
<p>
<strong>Supervisor:</strong> Nandita Bhattacharjee (Monash University)<br />
<strong>Thesis:</strong> <a href="{{ site.baseurl }}/downloads/fingerprint-based-biometric-cryptosystem-using-the-fuzzy-embedder-dylan-george-field-minor-thesis.pdf">Fingerprint based Biometric Cryptosystem using the Fuzzy Embedder</a>
</p>