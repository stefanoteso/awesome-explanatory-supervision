# Awesome Explanatory Supervision [![Awesome](figures/awesome.svg)](https://github.com/stefanoteso/awesome-explanatory-supervision)

Overview of literature on learning from supervision on the model's *explanations*.


**Warning**: early draft, permanent WIP.


Did we miss a relevant paper?  Please submit a new entry in the following format:

```markdown
- **An Artificially-intelligent Means to Escape Discreetly from the Departmental Holiday Party; guide for the socially awkward**
  Eve Armstrong; arXiv 2020 [paper](https://arxiv.org/abs/2003.14169)
  Notes: it is a joke;  a pretty good joke actually.
```


### Table of Contents
- [Passive Learning](#passive-learning)
- [Interactive Learning](#interactive-learning)
- [Reinforcement Learning](#reinforcement-learning)
- [Distillation](#distillation)
- [Regularization without Supervision](#regularization-without-supervision)
- [Related Works](#related-works)
- [Resources](#resources)

----


### [Passive Learning](#content)

Approaches that supervise the model's explanations.

- **Tangent Prop - A formalism for specifying selected invariances in an adaptive network**
  Patrice Simard, Bernard Victorri, Yann Le Cun, John Denker; NeurIPS 1992 [paper](https://papers.nips.cc/paper/536-tangent-prop-a-formalism-for-specifying-selected-invariances-in-an-adaptive-network.pdf)
  Notes: injects invariances into a neural net by regularizing its gradient; precursor to learning from gradient-based explanations.

- **Right for the right reasons: training differentiable models by constraining their explanations**
  Andrew Slavin Ross, Michael C. Hughes, and Finale Doshi-Velez; IJCAI 2017 [paper](https://www.ijcai.org/Proceedings/2017/0371.pdf)

- **Interpretable Machine Teaching via Feature Feedback**
  Shihan Su, Yuxin Chen, Oisin Mac Aodha, Pietro Perona, Yisong Yue; Workshop on Teaching Machines, Robots, and Humans 2017 [paper](https://authors.library.caltech.edu/87329/1/nips17-teaching_paper-5.pdf)

- **Teaching meaningful explanations**
  Noel Codella, Michael Hind, Karthikeyan Ramamurthy, Murray Campbell, Amit Dhurandhar, Kush Varshney, Dennis Wei, Aleksandra Mojsilovic; arXiv 2018 [paper](https://arxiv.org/pdf/1805.11648)

- **Deriving Machine Attention from Human Rationales**
  Yujia Bao, Shiyu Chang, Mo Yu, and Regina Barzilay; ACL 2019 [paper](https://www.aclweb.org/anthology/D18-1216.pdf)

- **Do Human Rationales Improve Machine Explanations?**
  Strout, Julia, Ye Zhang, Raymond Mooney; ACL Workshop BlackboxNLP 2019 [paper](https://www.aclweb.org/anthology/W19-4807.pdf)

- **Concept bottleneck models**
  Pang Wei Koh, Thao Nguyen, Yew Siang Tang, Stephen Mussmann, Emma Pierson, Been Kim, and Percy Liang; ICML 2020 [paper](http://proceedings.mlr.press/v119/koh20a/koh20a.pdf)

- **Debiasing Concept Bottleneck Models with Instrumental Variables**
  Mohammad Taha Bahadori, and David E. Heckerman; arXiv 2020 [paper](https://arxiv.org/pdf/2007.11500.pdf)

- **Learning Global Transparent Models Consistent with Local Contrastive Explanations**
  Tejaswini Pedapati, Avinash Balakrishnan, Karthikeyan Shanmugam, Amit Dhurandhar; NeurIPS 2020 [paper](https://proceedings.neurips.cc/paper/2020/file/24aef8cb3281a2422a59b51659f1ad2e-Paper.pdf)

- **Reflective-Net: Learning from Explanations**
  Johannes Schneider, Michalis Vlachos; arXiv 2020 [paper](https://arxiv.org/pdf/2011.13986.pdf)

- **Teaching with Commentaries**
  Aniruddh Raghu, Maithra Raghu, Simon Kornblith, David Duvenaud, and Geoffrey Hinton; arXiv 2020 [paper](https://arxiv.org/pdf/2011.03037)

- **Improving performance of deep learning models with axiomatic attribution priors and expected gradients**
  Gabriel Erion, Joseph D. Janizek, Pascal Sturmfels, Scott Lundberg, Su-In Lee; arXiv 2020 [paper](https://arxiv.org/pdf/1906.10670)

- **Interpretations are useful: penalizing explanations to align neural networks with prior knowledge**
  Laura Rieger, Chandan Singh, William Murdoch, Bin Yu; ICML 2020 [paper](http://proceedings.mlr.press/v119/rieger20a/rieger20a.pdf)

- **When Can Models Learn From Explanations? A Formal Framework for Understanding the Roles of Explanation Data**
  Peter Hase, Mohit Bansal; arXiv 2020 [paper](https://arxiv.org/pdf/2102.02201.pdf)


----

### [Interactive Learning](#content)

Approaches that combine supervision on the explanations with interactive machine learning:

- **Principles of Explanatory Debugging to Personalize Interactive Machine Learning**
  Todd Kulesza, Margaret Burnett, Weng-Keen Wong, Simone Stumpf; IUI 2015 [paper](https://openaccess.city.ac.uk/id/eprint/13819/1/paper326.pdf)

- **Explanatory Interactive Machine Learning**
  Stefano Teso, Kristian Kersting; AIES 2019 [paper](https://www.aiml.informatik.tu-darmstadt.de/papers/teso2019aies_XIML.pdf)
  Note: introduces explanatory interactive learning, focuses on active learning setup.

- **Taking a hint: Leveraging explanations to make vision and language models more grounded**
  Ramprasaath R. Selvaraju, Stefan Lee, Yilin Shen, Hongxia Jin, Shalini Ghosh, Larry Heck, Dhruv Batra, and Devi Parikh; ICCV 2019 [pdf](https://openaccess.thecvf.com/content_ICCV_2019/papers/Selvaraju_Taking_a_HINT_Leveraging_Explanations_to_Make_Vision_and_Language_ICCV_2019_paper.pdf)

- **Toward Faithful Explanatory Active Learning with Self-explainable Neural Nets**
  Stefano Teso; IAL Workshop 2019. [paper](https://lirias.kuleuven.be/retrieve/578884)
  Note: explanatory active learning with self-explainable neural networks.

- **Making deep neural networks right for the right scientific reasons by interacting with their explanations**
  Patrick Schramowski, Wolfgang Stammer, Stefano Teso, Anna Brugger, Franziska Herbert, Xiaoting Shao, Hans-Georg Luigs, Anne-Katrin Mahlein, Kristian Kersting; Nature Machine Intelligence 2020 [paper](https://www.nature.com/articles/s42256-020-0212-3)
  Note: introduces end-to-end explanatory interactive learning, fixes clever Hans deep neural nets.

- **One explanation does not fit all**
  Kacper Sokol, Peter Flach; 2020 Künstliche Intelligenz [paper](https://link.springer.com/content/pdf/10.1007/s13218-020-00637-y.pdf)

- **FIND: Human-in-the-loop Debugging Deep Text Classifiers**
  Piyawat Lertvittayakumjorn, Lucia Specia, Francesca Toni; EMNLP 2020 [paper](https://www.aclweb.org/anthology/2020.emnlp-main.24.pdf)

- **Human-driven FOL explanations of deep learning**
  Gabriele Ciravegna, Francesco Giannini, Marco Gori, Marco Maggini, Stefano Melacci; IJCAI 2020 [paper](https://www.ijcai.org/Proceedings/2020/0309.pdf)
  Notes: first-order logic.

- **Machine Guides, Human Supervises: Interactive Learning with Global Explanations**
  Teodora Popordanoska, Mohit Kumar, Stefano Teso; arXiv 2020 [paper](https://arxiv.org/pdf/2009.09723.pdf)
  Note: introduces narrative bias and explanatory guided learning, focuses on human-initiated interaction and global explanations.

- **Right for the Right Concept: Revising Neuro-Symbolic Concepts by Interacting with their Explanations**
  Wolfgang Stammer, Patrick Schramowski, and Kristian Kersting; arXiv 2020 [paper](https://arxiv.org/pdf/2011.12854)
  Notes: first-order logic, attention.

- **Right for Better Reasons: Training Differentiable Models by Constraining their Influence Function**
  Xiaoting Shao, Arseny Skryagin, Patrick Schramowski, Wolfgang Stammer, Kristian Kersting; AAAI 2021 [preliminary paper](https://www.aaai.org/AAAI21Papers/AAAI-5436.ShaoX.pdf)

- **Bandits for Learning to Explain from Explanations**
  Freya Behrens, Stefano Teso, Davide Mottin; XAI Workshop 2021 [paper](https://arxiv.org/pdf/2102.03815)
  Notes: preliminary.

----


### [Reinforcement Learning](#content)

- **Explanation Augmented Feedback in Human-in-the-Loop Reinforcement Learning**
  Lin Guan, Mudit Verma, Sihang Guo, Ruohan Zhang, Subbarao Kambhampati; arXiv 2020 [paper](https://arxiv.org/pdf/2006.14804)

----


### [Distillation](#content)

- **Model reconstruction from model explanations**
  Smitha Milli, Ludwig Schmidt, Anca D. Dragan, Moritz Hardt; FAcct 2019 [paper](https://arxiv.org/pdf/1807.05185)

- **Evaluating Explanations: How much do explanations from the teacher aid students?**
  Danish Pruthi, Bhuwan Dhingra, Livio Baldini Soares, Michael Collins, Zachary C. Lipton, Graham Neubig, and William W. Cohen; arXiv 2020 [paper](https://arxiv.org/pdf/2012.00893)
  Notes: defines importance of different kinds of explanations by measuring their impact when used as supervision.

----


### [Regularization without Supervision](#content)

Approaches that regularize the model's explanations in an unsupervised manner, often for improved interpretability.

- **Towards robust interpretability with self-explaining neural networks**
  David Alvarez-Melis, Tommi Jaakkola; NeurIPS 2018 [paper](https://proceedings.neurips.cc/paper/2018/file/3e9f0fc9b2f89e043bc6233994dfcf76-Paper.pdf)

- **Beyond sparsity: Tree regularization of deep models for interpretability**
  Mike Wu, Michael Hughes, Sonali Parbhoo, Maurizio Zazzi, Volker Roth, Finale Doshi-Velez; AAAI 2018 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/11501/11360)

- **Regional tree regularization for interpretability in deep neural networks**
  Mike Wu, Sonali Parbhoo, Michael Hughes, Ryan Kindle, Leo Celi, Maurizio Zazzi, Volker Roth, Finale Doshi-Velez; AAAI 2020 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/6112/5968)

- **Regularizing black-box models for improved interpretability**
  Gregory Plumb, Maruan Al-Shedivat, Ángel Alexander Cabrera, Adam Perer, Eric Xing, Ameet Talwalkar; NeurIPS 2020 [paper](https://papers.nips.cc/paper/2020/file/770f8e448d07586afbf77bb59f698587-Paper.pdf)

- **Explainable Models with Consistent Interpretations**
  Vipin Pillai, Hamed Pirsiavash; AAAI 2021 [paper](https://www.csee.umbc.edu/~hpirsiav/papers/gc_aaai21.pdf) [code](https://github.com/UMBCvision/Explainable-Models-with-Consistent-Interpretations)

----


### [Related Works](#content)

Explanation-based learning, focuses on logic-based formalisms and learning strategies:

- **Explanation-based generalization: A unifying view**
  Tom Mitchell, Richard Keller, Smadar Kedar-Cabelli; MLJ 1986 [paper](https://link.springer.com/content/pdf/10.1023/A:1022691120807.pdf)

- **Explanation-based learning: An alternative view**
  Gerald DeJong, Raymond Mooney; MLJ 1986 [paper](https://link.springer.com/content/pdf/10.1007/BF00114116.pdf)

- **Explanation-based learning: A survey of programs and perspectives**
  Thomas Ellman; ACM Computing Surveys 1989 [paper](https://academiccommons.columbia.edu/doi/10.7916/D8SF343S/download)

- **Probabilistic explanation based learning**
  Angelika Kimmig, Luc De Raedt, Hannu Toivonen; ECML 2007 [paper](https://link.springer.com/content/pdf/10.1007/978-3-540-74958-5_19.pdf)


Injecting invariances / feature constraints into models:

- **Training invariant support vector machines**
  Dennis DeCoste, Bernhard Schölkopf; MLJ 2002 [paper](https://link.springer.com/content/pdf/10.1023/A:1012454411458.pdf)

- **The constrained weight space svm: learning with ranked features**
  Kevin Small, Byron Wallace, Carla Brodley, Thomas Trikalinos; ICML 2011 [paper](http://www.icml-2011.org/papers/465_icmlpaper.pdf)


Dual label-feature feedback:

- **Active learning with feedback on features and instances**
  Hema Raghavan, Omid Madani, Rosie Jones; JMLR 2006 [paper](https://www.jmlr.org/papers/volume7/raghavan06a/raghavan06a.pdf)

- **An interactive algorithm for asking and incorporating feature feedback into support vector machines**
  Hema Raghavan, James Allan; ACM SIGIR 2007 [paper](https://www.academia.edu/download/49512889/IR-560.pdf)

- **Learning from labeled features using generalized expectation criteria**
Gregory Druck, Gideon Mann, Andrew McCallum;  ACM SIGIR 2008 [paper](http://www.cs.umass.edu/~mccallum/papers/druck08sigir.pdf)

- **Active learning by labeling features**
  Gregory Druck, Burr Settles, Andrew McCallum; EMNLP 2009 [paper](https://www.aclweb.org/anthology/D09-1009.pdf)

- **A unified approach to active dual supervision for labeling features and examples**
  Josh Attenberg, Prem Melville, Foster Provost; ECML-PKDD 2010 [paper](https://link.springer.com/content/pdf/10.1007/978-3-642-15880-3_9.pdf)

- **Closing the loop: Fast, interactive semi-supervised annotation with queries on features and instances**
  Burr Settles; EMNLP 2011 [paper](https://www.aclweb.org/anthology/D11-1136.pdf)


Learning from rationales:

- **Using “annotator rationales” to improve machine learning for text categorization**
  Omar Zaidan, Jason Eisner, Christine Piatko; NAACL 2007 [paper](https://www.aclweb.org/anthology/N07-1033.pdf)

- **Modeling annotators: A generative approach to learning from annotator rationales**
  Omar Zaidan, Jason Eisner; EMNLP 2008 [paper](https://www.aclweb.org/anthology/D08-1004.pdf)

- **Active learning with rationales for text classification**
  Manali Sharma, Di Zhuang, Mustafa Bilgic; NAACL 2015 [paper](https://www.aclweb.org/anthology/N15-1047.pdf)


Critiquing in recommenders:

- **Critiquing-based recommenders: survey and emerging trends**
  Li Chen, Pearl Pu; User Modeling and User-Adapted Interaction 2012 [paper](https://link.springer.com/content/pdf/10.1007/s11257-011-9108-6.pdf)

- **Coactive critiquing: Elicitation of preferences and features**
  Stefano Teso, Paolo Dragone, Andrea Passerini; AAAI 2017 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/10929/10788)

----


### [Resources](#content)

A selection of general resources on Explainable AI focusing on overviews, surveys, societal implications, and critiques:

- **Survey and critique of techniques for extracting rules from trained artificial neural networks**
  Robert Andrews, Joachim Diederich, Alan B. Tickle; Knowledge-based systems 1995 [page](https://www.sciencedirect.com/science/article/abs/pii/0950705196819204)

- **The Mythos of Model Interpretability**
  Zachary Lipton; CACM 2016 [paper](https://dl.acm.org/doi/pdf/10.1145/3236386.3241340)

- **A survey of methods for explaining black box models**
  Riccardo Guidotti, Anna Monreale, Salvatore Ruggieri, Franco Turini, Fosca Giannotti, and Dino Pedreschi; ACM Computing Surveys 2018 [paper](https://dl.acm.org/doi/pdf/10.1145/3236009)

- **Explanation in Artificial Intelligence: Insights from the Social Sciences**
  Tim Miller; Artificial Intelligence, 2019 [paper](https://www.sciencedirect.com/science/article/abs/pii/S0004370218305988)

- **Unmasking clever hans predictors and assessing what machines really learn**
  Sebastian Lapuschkin, Stephan Wäldchen, Alexander Binder, Grégoire Montavon, Wojciech Samek, Klaus-Robert Müller; Nature Communications 2019 [paper](https://www.nature.com/articles/s41467-019-08987-4)

- **Interpretation of neural networks is fragile**
  Amirata Ghorbani, Abubakar Abid, James Zou; AAAI 2019 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/4252/4130)

- **Is Attention Interpretable?**
  Sofia Serrano, Noah A. Smith; ACL 2019 [paper](https://www.aclweb.org/anthology/P19-1282.pdf)

- **Attention is not Explanation**
  Sarthak Jain, and Byron C. Wallace; ACL 2019 [paper](https://www.aclweb.org/anthology/N19-1357.pdf)

- **Attention is not not Explanation**
  Sarah Wiegreffe, and Yuval Pinter; EMNLP-IJCNLP 2019 [paper](https://www.aclweb.org/anthology/D19-1002.pdf)

- **The (un)reliability of saliency methods**
  Pieter-Jan Kindermans, Sara Hooker, Julius Adebayo, Maximilian Alber, Kristof T. Schütt, Sven Dähne, Dumitru Erhan, and Been Kim; Explainable AI: Interpreting, Explaining and Visualizing Deep Learning 2019 [paper](http://interpretable-ml.org/nips2017workshop/papers/10.pdf)

- **Explanations can be manipulated and geometry is to blame**
  Ann-Kathrin Dombrowski, Maximillian Alber, Christopher Anders, Marcel Ackermann, Klaus-Robert Müller, and Pan Kessel; NeurIPS 2019 [paper](https://papers.nips.cc/paper/2019/file/bb836c01cdc9120a9c984c525e4b1a4a-Paper.pdf)

- **Fooling Neural Network Interpretations via Adversarial Model Manipulation**
  Juyeon Heo, Sunghwan Joo, and Taesup Moon; NeurIPS 2019 [paper](https://proceedings.neurips.cc/paper/2019/file/7fea637fd6d02b8f0adf6f7dc36aed93-Paper.pdf)

- **Stop explaining black box machine learning models for high stakes decisions and use interpretable models instead**
  Cynthia Rudin; Nature Machine Intelligence 2019 [page](https://www.nature.com/articles/s42256-019-0048-x)

----


### Related Lists

- [Awesome explainable AI](https://github.com/wangyongjie-ntu/Awesome-explainable-AI)

- [Awesome machine learning interpretability](https://github.com/jphall663/awesome-machine-learning-interpretability)

----


### Not Yet Sorted

- **e-SNLI: natural language inference with natural language explanations**
  Oana-Maria Camburu, Tim Rocktäschel, Thomas Lukasiewicz, and Phil Blunsom; NeurIPS 2018 [paper](https://papers.nips.cc/paper/2018/file/4c7a167bb329bd92580a99ce422d6fa6-Paper.pdf)

- **Multimodal explanations: Justifying decisions and pointing to the evidence**
  Dong Huk Park, Lisa Anne Hendricks, Zeynep Akata, Anna Rohrbach, Bernt Schiele, Trevor Darrell, Marcus Rohrbach; CVPR 2018 [paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Park_Multimodal_Explanations_Justifying_CVPR_2018_paper.pdf)

- **"Learning Deep Attribution Priors Based On Prior Knowledge**
  Ethan Weinberger, Joseph Janizek, Su-In Lee; NeurIPS 2020 [paper](https://papers.nips.cc/paper/2020/file/a19883fca95d0e5ec7ee6c94c6c32028-Paper.pdf)

- **Explain and Predict, and then Predict Again**
  Zijian Zhang, Koustav Rudra, Avishek Anand; arXiv 2021 [paper](https://arxiv.org/pdf/2101.04109)

----


### TODO

- Make sure that all papers are categorized correctly ;-)

- Crawl & reference work on NLP.



### Comments

This list is directly inspired by all the awesome awesome lists out there!
