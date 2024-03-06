## These are my personal notes made during my time learning Tensorflow.js
---
Types of machine learning that I have come across:

* Supervised learning
Examples are provided and they are **labeled beforehand**. The ML model will learn similarly to a human through already tagged data.
* Unsupervised learning
The ML model will use clustering to separate data based on some value/trait it 'thinks' exists. **No labeling is done beforehand** but a human/humans must then closely review the provided data by the ML model to be sure of the correct result
* Reinforcement learning
The ML model tries to achieve some type of outcome numerous times. It will use constant incrementation and each attempt is either rewarded or punished. Based on these two things the ML model will predict the correctness of the approach

Important things to consider when using pre-made/trained models:

* Data bias
Make sure enough training data is provided to these models and make sure you consider edge cases. For example in a recent model I trained where I wanted to comprare facial recognition of two faces both of whom wore hats frequently it was important to consider whethert he ML model might think the presence of a hat constitued one or the other person.

![will-sad](https://res.cloudinary.com/dvoaat0nl/image/upload/v1709717120/doomed1_g1ht8p.jpg)

![will-weirdhat](https://res.cloudinary.com/dvoaat0nl/image/upload/v1709717120/doomed2_bhqziq.jpg)

![will-aschad](https://res.cloudinary.com/dvoaat0nl/image/upload/v1709717120/doomed4_doeroe.jpg)




