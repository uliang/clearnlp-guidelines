# Part-of-Speech Tagging

Our part-of-speech tagger uses the generalized model of our previous approach, dynamic model selection, which is no longer used because the generalized model by itself performs as well as the dynamic model selection approach for most real-life applications and takes only 50% of memory and disk space. Our POS tagger processes about 80K tokens per second on an Intel Xeon 2.30GHz machine and shows state-of-the-art accuracy, especially on out-of-domain data. See [how to run command-line tools](md/quick_start/command_line_tools.md) for more details about decoding and training.

* [Fast and Robust Part-of-Speech Tagging Using Dynamic Model Selection](http://aclweb.org/anthology-new/P/P12/P12-2071.pdf), Jinho D. Choi, Martha Palmer, Proceedings of the 50th Annual Meeting of the Association for Computational Linguistics (ACL'12), 363-367, Jeju, Korea, 2012.