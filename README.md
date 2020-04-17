## Transition based Bottom-up RST-style Text-level Discourse Parser

<b>-- General Information</b>
```
   1. This RST-style discourse parser produces discourse tree structure on full-text level, given a raw text.
   2. This work explores the interal node representation learning with respect to tree depth:
```

<b>-- Required Packages</b>
```
   torch==0.4.0 
   numpy==1.14.1
   nltk==3.3
   stanfordcorenlp==3.9.1.1
```

<b>-- RST Parsing with Raw Documents</b>
```
   1. Prepare your raw documents in data/raw_txt in the format of *.out
   2. Run the Stanford CoreNLP with the given bash script corpus_rst.sh using the command "./corpus_rst.sh "
   3. Run parser.py to parse these raw documents into objects of rst_tree class (Wrap them into trees).
      - segmentation
      - wrap them into trees, saved in "data/trees_parsed/trees_list.pkl"
   4. Run drawer.py to draw those trees out by NLTK
```

<b>-- Training Your Own RST Parser</b>

      TODO

<b>-- Reference</b>

   Please read the following paper for more technical details
   
   [Longyin Zhang, Xin Tan, Fang Kong and Guodong Zhou, A Recursive Information Flow Gated Model for RST-Style Text-Level Discourse Parsing.](http://tcci.ccf.org.cn/conference/2019/papers/119.pdf)

<b>-- Developer</b>
```
  Longyin Zhang
  Natural Language Processing Lab, School of Computer Science and Technology, Soochow University, China
  mail to: zzlynx@outlook.com, lyzhang9@stu.suda.edu.cn

```

<b>-- License</b>
```
   Copyright (c) 2019, Soochow University NLP research group. All rights reserved.
   Redistribution and use in source and binary forms, with or without modification, are permitted provided that
   the following conditions are met:
   1. Redistributions of source code must retain the above copyright notice, this list of conditions and the
      following disclaimer.
   2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the
      following disclaimer in the documentation and/or other materials provided with the distribution.
```
