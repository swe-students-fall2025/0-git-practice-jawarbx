# Article
[Critical vulnerability in PyTorch framework](https://www.kaspersky.com/blog/vulnerability-in-pytorch-framework/53311/)

I found the topic of vulnerabilities in AI, not just in model weights as demonstrated here, to be interesting because more and more applications and services are implementing AI services for users, which essentially host these model files in some manner. Therefore, security relating to these parts of software has almost instantly become very important, but if vulnerabilities like these are still being discovered in 2025, I'm a little worried for the vulnerabilities out there that we have not come across yet. I think its important to note that this impacts loading model files, and risks can likely be mitigated by loading files in a virtual machine first. However, a part of me is also worried for the impacts that vulnerabilities could have on open source progress of models, since this provides yet another point of concern for open source to worry about, in addition to considerations like dataset creation and access, and general financial requirements for advancing AI.

```
Kazi Hossain : 
This was a really interesting vulnerability. As the scale of AI increases, more and more models are becoming open source. With the rate of AI improvement new gaping holes in cybersecurity are coming up every day. But seeing a 9.3 CVSS rating was surprising for such a popular framework. Your note about using a virtual machine for these kinds of tasks is something I am planning to take on to keep myself safe. Thanks for sharing!
```
