Unity3D-Bags
====================

Quick and simple Bags library for Unity3D.

Helper classes to manage the storage and randomized retrieval of values. [Managed randomness](http://gamedevelopment.tutsplus.com/tutorials/shuffle-bags-making-random-feel-more-random--gamedev-1249) sometimes [feels more authentic](http://seanmonstar.com/post/708989796/a-less-random-generator) for gameplay.

All bags provide a common `GetNext()` call. Most of them provide a simple `Add(T)` call, or can be populated during construction by passing any IEnumerable reference.

<dl>
<dt>RandomBag</dt>
<dd>Pick items with uniform randomness.</dd>

<dt>ShuffleBag</dt>
<dd>Pick items with uniform randomness; avoids repeating items until the bag has been completely used (and automatically refilled).</dd>

<dt>WeightedBag</dt>
<dd>Pick items with weighted randomness.</dd>
</dl>