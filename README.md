# Awesome Conversational Information Retrieval, Search and Recommendation

This document is a curated list of awesome articles, tutorials, libraries, webpages, etc., about conversational information retrieval,
search, and recommendation. This page is a hand-picked and shortened list of the vast amount of related content published worldwide. 
There is also a [timeline](TIMELINE.md) that tries to capture any entities related to CIR/CIS.



[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Tabel of Contents
  - [Introduction](#introduction)
  - [Timeline](#timeline)
  - [Contributing](#contributing)
  - [Surveys](#surveys)
  - [Theoretical Developments](#theoretical-developments)
  - [Clarifying Question](#clarifying-question)
  - [Evaluation](#evaluation)
  - [Datasets](#datasets)
  - [Videos & Talks](#videos--talks)
  - [Conferences](#conferences)
  - [External Curation Links](#external-curation-links)
  

## Introduction
Conversational information seeking (CIS) is concerned with a sequence of interactions between one or more users and an information system. Interactions in CIS are primarily based on natural language dialogue, while they may include other types of interactions, such as click, touch, and body gestures [\[Zamani et al. \]](https://arxiv.org/pdf/2201.08808).
This repository is designed to index and reflect the primary resources in the CIS and CIR fields. It is an ongoing project and will be updated regularly. Any contribution via sending pull requests is appreciated.

## Timeline
This is the [CIR/CIS any entity Timeline](TIMELINE.md)! The latest uncategorized entities can be found here. 
In this section every new entity is reflected chronologically. It is separated to another document to saving the structure of this document.

## Contributing
The repository is under construction. Please feel free to send me [pull requests](https://github.com/s-nobakht/awesome-conversational-information-retrieval/pulls) to add links, any corrections or suggestions. You can also send me email: `sd[DOT]nobakht[ATT]gmail[DOT]com`. 
For the hottest entities, check the [timeline](TIMELINE.md). There is also a [submission form](https://forms.gle/aizPoFWNbEDSUPLy9) for ease of contribution.


## Surveys 
  - 2022 | [Conversational Information Seeking](https://arxiv.org/abs/2201.08808)
    - Hamed Zamani, Johanne R. Trippas, Jeff Dalton, and Filip Radlinski.
    - Preprint of book draft.
      
  - 2022 | [Neural Approaches to Conversational Information Retrieval](https://arxiv.org/abs/2201.05176)
    - Jianfeng Gao, Chenyan Xiong, Paul Bennett, Nick Craswell.
    - Preprint of book draft.
    
  - 2021 | [Advances and Challenges in Conversational Recommender Systems: A Survey](https://arxiv.org/abs/2101.09459)
    - Chongming Gao, Wenqiang Lei, Xiangnan He, Maarten de Rijke, Tat-Seng Chua.
    - AI Open, 2:100–126, July 2021.
    
  - 2021 | [RecSys 2021 Tutorial on Conversational Recommendation: Formulation, Methods, and Evaluation](https://dl.acm.org/doi/abs/10.1145/3460231.3473325).
    - Lei, Wenqiang, Chongming Gao, and Maarten de Rijke.
    - In Fifteenth ACM Conference on Recommender Systems, 842-44.

## Theoretical Developments 
  - 2018 | [Conceptualizing Agent-Human Interactions During the Conversational Search Process](https://core.ac.uk/download/pdf/159074386.pdf).
    - Leif Azzopardi, Mateusz Dubiel, Martin Halvey, and Jeﬀery Dalton.
    - The Second International Workshop on Conversational Approaches to Information Retrieval (CAIR), 2018.
      
  - 2017 | [A Theoretical Framework for Conversational Search](https://arxiv.org/abs/2201.05176).
    - Filip Radlinski and Nick Craswell.
    - Proceedings of the 2017 Conference on Conference Human Information Interaction and Retrieval (CHIIR), 2017.

## Clarifying Question
  - 2022 | [Exploiting Document-based Features for Clarification in Conversational Search](https://link.springer.com/chapter/10.1007/978-3-030-99736-6_28).
    - Ivan Sekulić, Mohammad Aliannejadi, and Fabio Crestani.
    - European Conference on Information Retrieval (ECIR), 2022.
      
  - 2021 | [Towards Facet-Driven Generation of Clarifying Questions for Conversational Search](https://arxiv.org/abs/2201.05176).
    - Ivan Sekulić, Mohammad Aliannejadi, and Fabio Crestani.
    - Proceedings of the 2021 ACM SIGIR International Conference on Theory of Information Retrieval (ICTIR), 2021.
    
  - 2021 | [Template-guided Clarifying Question Generation for Web Search Clarification](https://dl.acm.org/doi/abs/10.1145/3459637.3482199).
    - Jian Wang and Wenjie Li.
    - Proceedings of the 30th ACM International Conference on Information & Knowledge Management (CIKM), 2021.
    
  - 2020 | [ConvAI3: Generating Clarifying Questions for OpenDomain Dialogue Systems (ClariQ)](http://convai.io/ConvAI3_ClariQ2020.pdf).
    - Mohammad Aliannejadi, Julia Kiseleva, Aleksandr Chuklin, Jeff Dalton, and Mikhail Burtsev.
    - Conversational AI challenge series (ConvAI3), 2020.
    
  - 2020 | [Analyzing and Learning from User Interactions with Search Clarifcation](https://dl.acm.org/doi/abs/10.1145/3397271.3401160).
    - Hamed Zamani, Bhaskar Mitra, Everest Chen, Gord Lueck, Fernando Diaz, Paul N. Bennett, Nick Craswell, and Susan T. Dumais.
    - Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR), 2020.
    
  - 2020 | [Guided Transformer: Leveraging Multiple External Sources for Representation Learning in Conversational Search](https://dl.acm.org/doi/abs/10.1145/3397271.3401061).
    - Helia Hashemi, Hamed Zamani, and W Bruce Croft.
    - Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR), 2020.
    
  - 2020 | [Leading Conversational Search by Suggesting Useful Questions](https://dl.acm.org/doi/10.1145/3366423.3380193).
    - Corbin Rosset, Chenyan Xiong, Xia Song, Daniel Campos, Nick Craswell, Saurabh Tiwary, and Paul Bennett
    - Proceedings of The Web Conference (WWW), 2020.

  - 2020 | [Ranking Clarification Questions via Natural Language Inference](https://dl.acm.org/doi/10.1145/3340531.3412137).
    - Vaibhav Kumar, Vikas Raunak, and Jamie Callan.
    - Proceedings of the 29th ACM International Conference on Information & Knowledge Management (CIKM), 2020.

  - 2020 | [Mimics: A Large-scale Data Collection for Search Clarification](https://dl.acm.org/doi/10.1145/3340531.3412772).
    - Hamed Zamani, Gord Lueck, Everest Chen, Rodolfo Quispe, Flint Luu, and Nick Craswell. 
    - Proceedings of the 29th ACM International Conference on Information & Knowledge Management (CIKM), 2020. 

  - 2019 | [Asking Clarifying Questions in Open-Domain Information-Seeking Conversations](https://dl.acm.org/doi/abs/10.1145/3331184.3331265).
    - Mohammad Aliannejadi, Hamed Zamani, Fabio Crestani, and W. Bruce Croft. 
    - Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieva (SIGIR), 2019. 

  - 2019 | [Identifying unclear questions in community question answering websites](https://link.springer.com/chapter/10.1007/978-3-030-15712-8_18).
    - Jan Trienes and Krisztian Balog.  
    - European Conference on Information Retrieval (ECIR), 2019.
    
  - 2019 | [Asking Clarification Questions in Knowledge Based Question Answering](https://aclanthology.org/N19-1013/).
    - Jingjing Xu, Yuechen Wang, Duyu Tang, Nan Duan, Pengcheng Yang, Qi Zeng, Ming Zhou, and Xu Sun.  
    - Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP), 2019.

  - 2019 | [Answer-based Adversarial Training for Generating Clarification Questions](https://aclanthology.org/N19-1013/).
    - Sudha Rao and Hal Daumé III.  
    - Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (NAACL, short paper), 2019.

  - 2019 | [Generating a Common Question from Multiple Documents using Multi-source Encoder-Decoder Models](https://aclanthology.org/P18-1255/).
    - Woon Sang Cho, Yizhe Zhang, Sudha Rao, Chris Brockett, and Sungjin Lee.  
    - Proceedings of the 3rd Workshop on Neural Generation and Translation, 2019.

  - 2018 | [Learning a Deep Listwise Context Model for Ranking](https://dl.acm.org/doi/abs/10.1145/3209978.3209985).
    - Qingyao Ai, Keping Bi, Jiafeng Guo, and W. Bruce Croft.  
    - The 41st International ACM SIGIR Conference on Research & Development in Information Retrieval (SIGIR), 2018.

  - 2018 | [Toward Voice Query Clarification](https://dl.acm.org/doi/abs/10.1145/3209978.3210160).
    - Johannes Kiesel, Arefeh Bahrami, Benno Stein, Avishek Anand, and Matthias Hagen.  
    - The 41st International ACM SIGIR Conference on Research & Development in Information Retrieval (SIGIR), 2018.

  - 2018 | [Learning to ask good questions: Ranking clarification questions using neural expected value of perfect information](https://aclanthology.org/P18-1255/).
    - Sudha Rao and Hal Daumé III.  
    - Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (ACL, Long Papers), 2018.

  - 2017 | [Situational Context for Ranking in Personal Search](https://dl.acm.org/doi/abs/10.1145/3038912.3052648).
    - Hamed Zamani, Michael Bendersky, Xuanhui Wang, and Mingyang Zhang.  
    - Proceedings of the 26th International Conference on World Wide Web (WWW), 2017.

  - 2017 | [What do you mean exactly? Analyzing clarification questions in CQA](https://ieeexplore.ieee.org/abstract/document/6812556).
    - Pavel Braslavski, Denis Savenkov, Eugene Agichtein, and Alina Dubatovka  
    - Proceedings of the 2017 Conference on Conference Human Information Interaction and Retrieval, 2017.
    

## Evaluation
  - 2022 | [Evaluating Mixed-initiative Conversational Search Systems via User Simulation](https://dl.acm.org/doi/abs/10.1145/3488560.3498440).
    - Ivan Sekulić, Mohammad Aliannejadi, Fabio Crestani  
    - Proceedings of the Fifteenth ACM International Conference on Web Search and Data Mining (WSDM), 2022.

  - 2021 | [Meta-evaluation of Conversational Search Evaluation Metrics](https://dl.acm.org/doi/10.1145/3445029).
    - Zeyang Liu, Ke Zhou, Max L. Wilson.  
    - Transactions on Information Systems (TOIS), 2021.

  - 2021 | [How Am I Doing?- Evaluating Conversational Search Systems Offline](https://dl.acm.org/doi/10.1145/3451160).
    - Aldo Lipani, Ben Carterette, Emine Yilmaz  
    - Transactions on Information Systems (TOIS), 2021.


## Datasets
  - 2020 | [Cast-19: A dataset for conversational information seeking](http://www.cs.cmu.edu/afs/cs.cmu.edu/Web/People/callan/Papers/sigir20-dalton.pdf) 
    - Dalton, Jeffrey, Chenyan Xiong, Vaibhav Kumar, and Jamie Callan. 
    - In Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval, 2020.
    - Cast-19 dataset.
    
  - 2020 | [Mimics: A Large-scale Data Collection for Search Clarification](https://dl.acm.org/doi/10.1145/3340531.3412772).
    - Hamed Zamani, Gord Lueck, Everest Chen, Rodolfo Quispe, Flint Luu, and Nick Craswell. 
    - Proceedings of the 29th ACM International Conference on Information & Knowledge Management (CIKM), 2020.
    - MIMICS dataset.

  - 2019 | [Asking Clarifying Questions in Open-Domain Information-Seeking Conversations](https://dl.acm.org/doi/abs/10.1145/3331184.3331265).
    - Mohammad Aliannejadi, Hamed Zamani, Fabio Crestani, and W. Bruce Croft. 
    - Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieva (SIGIR), 2019.
    - Qulac dataset.

## Videos & Talks
  - 2021 | [Theories of Conversation for Conversational IR](https://www.youtube.com/watch?v=pfkPT9Ihr_M).
    - Paul Thomas, Mary Czerwinski, Daniel McDu, Nick Craswell.
    - ACM Trans. Inf. Syst., 39: Article 39.

  - 2020 | [Recent Advances in Conversational Information Retrieval](https://www.bilibili.com/video/BV1dA411a7tg/).
    - Jianfeng Gao, Chenyan Xiong, and Paul Bennett. 
    - Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (Association for Computing Machinery).
  
  - 2020 | [RecSys 2020 Tutorial: Conversational Recommender Systems](https://www.youtube.com/watch?v=RdGnJSRA0aw).
    - Yongfeng Zhang, Zuohui Fu, Yikun Xian, and Yi Zhang.  
    - The ACM Conference Series on Recommender Systems, RecSys 2020.
    

## Conferences
- Web Search and Data Mining Conference - [WSDM](http://www.wsdm-conference.org).
- Special Interests Group on Information Retrieval - [SIGIR](http://sigir.org).
- Text REtrieval Conference - [TREC](http://trec.nist.gov).
- European Conference on Information Retrieval - [ECIR](http://irsg.bcs.org/ecir.php).
- World Wide Web Conference - [WWW](http://www.iw3c2.org).
- Conference on Information and Knowledge Management - [CIKM](http://www.cikmconference.org).
- Forum for Information Retrieval Evaluation - [FIRE](http://fire.irsi.res.in/fire/2016/home).
- Conference and Labs of the Evaluation Forum - [CLEF](http://www.clef-initiative.eu/).
- NII Testsbeds and Community for Information access Research - [NTCIR](http://research.nii.ac.jp/ntcir/index-en.html).


## External Curation Links
- [Chuan Meng Paper Study List](https://github.com/ChuanMeng/Conversational-Information-Seeking)

