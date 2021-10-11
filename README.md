# Awesome Explanatory Supervision [![Awesome](figures/awesome.svg)](https://github.com/stefanoteso/awesome-explanatory-supervision)

Overview of literature on learning from supervision on the model's *explanations*.  A `.bib` file of the papers below can be downloaded [here](https://raw.githubusercontent.com/stefanoteso/awesome-explanatory-supervision/main/explanatory-supervision.bib).


**Warning**: permanent WIP.


Did we miss a relevant paper?  Please submit a new entry in the following format:

```markdown
- **An Artificially-intelligent Means to Escape Discreetly from the Departmental Holiday Party; guide for the socially awkward**
  Eve Armstrong; arXiv 2020 [paper](https://arxiv.org/abs/2003.14169)
  `Notes: it is a joke;  a pretty good joke actually.`
```


### Table of Contents
- [Passive Learning](#passive-learning)
- [Interactive Learning](#interactive-learning)
- [Reinforcement Learning](#reinforcement-learning)
- [Distillation](#distillation)
- [Regularization without Supervision](#regularization-without-supervision)
- [Machine Teaching](#machine-teaching)
- [Applications](#applications)
- [Related Works](#related-works)
- [Resources](#resources)

----


### [Passive Learning](#content)

Approaches that supervise the model's explanations.

- **Rationalizing Neural Predictions**
  Tao Lei, Regina Barzilay, Tommi Jaakkola; EMNLP 2016 [paper](https://www.aclweb.org/anthology/D16-1011.pdf) [code](github.com/taolei87/rcnn)
  `Notes: they learn an "explanation module" for text classificaiton from explanatory supervision, namely rationales.`

- **Right for the right reasons: training differentiable models by constraining their explanations**
  Andrew Slavin Ross, Michael C. Hughes, and Finale Doshi-Velez; IJCAI 2017 [paper](https://www.ijcai.org/Proceedings/2017/0371.pdf) [code](https://github.com/dtak/rrr)

- **e-SNLI: natural language inference with natural language explanations**
  Oana-Maria Camburu, Tim Rocktäschel, Thomas Lukasiewicz, and Phil Blunsom; NeurIPS 2018 [paper](https://papers.nips.cc/paper/2018/file/4c7a167bb329bd92580a99ce422d6fa6-Paper.pdf) [code](https://github.com/OanaMariaCamburu/e-SNLI)

- **Learning credible models**
  Jiaxuan Wang, Jeeheh Oh, Haozhu Wang, and Jenna Wiens; KDD 2018 [paper](https://dl.acm.org/doi/pdf/10.1145/3219819.3220070) [code](https://github.com/nathanwang000/credible_learning)

- **Not Using the Car to See the Sidewalk--Quantifying and Controlling the Effects of Context in Classification and Segmentation**
  Rakshith Shetty, Bernt Schiele, Mario Fritz; CVPR 2019 [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shetty_Not_Using_the_Car_to_See_the_Sidewalk_--_Quantifying_CVPR_2019_paper.pdf)
  `Notes: not exactly about explanations, learns from ground-truth object annotations.`

- **Learning credible deep neural networks with rationale regularization**
  Mengnan Du, Ninghao Liu, Fan Yang, Xia Hu; ICDM 2019 [paper](https://arxiv.org/pdf/1908.05601)

- **Deriving Machine Attention from Human Rationales**
  Yujia Bao, Shiyu Chang, Mo Yu, and Regina Barzilay; ACL 2019 [paper](https://www.aclweb.org/anthology/D18-1216.pdf) [code](https://github.com/YujiaBao/R2A)

- **TED: Teaching AI to explain its decisions**
  Michael Hind, Dennis Wei, Murray Campbell, Noel Codella, Amit Dhurandhar, Aleksandra Mojsilović, Karthikeyan Ramamurthy, Kush Varshney; AIES 2019 [paper](https://arxiv.org/pdf/1811.04896.pdf)

- **Saliency Learning: Teaching the Model Where to Pay Attention**
  Reza Ghaeini, Xiaoli Fern, Hamed Shahbazi, Prasad Tadepalli; NAACL 2019 [paper](https://aclanthology.org/N19-1404.pdf)

- **Do Human Rationales Improve Machine Explanations?**
  Julia Strout, Ye Zhang, Raymond Mooney; ACL Workshop BlackboxNLP 2019 [paper](https://www.aclweb.org/anthology/W19-4807.pdf)

- **CARE: Class attention to regions of lesion for classification on imbalanced data**
  Jiaxin Zhuang, Jiabin Cai, Ruixuan Wang, Jianguo Zhang, Weishi Zheng; International Conference on Medical Imaging with Deep Learning, 2019. [paper](http://proceedings.mlr.press/v102/zhuang19a/zhuang19a.pdf)

- **GradMask: Reduce Overfitting by Regularizing Saliency**
  Becks Simpson, Francis Dutil, Yoshua Bengio, Joseph Paul Cohen; International Conference on Medical Imaging with Deep Learning, 2019. [paper](https://openreview.net/pdf?id=Syx2z2aMqE)

- **Improving performance of deep learning models with axiomatic attribution priors and expected gradients**
  Gabriel Erion, Joseph D. Janizek, Pascal Sturmfels, Scott Lundberg, Su-In Lee; arXiv 2019 [paper](https://arxiv.org/pdf/1906.10670) [code](github.com/suinleelab/attributionpriors)

- **Learning Global Transparent Models Consistent with Local Contrastive Explanations**
  Tejaswini Pedapati, Avinash Balakrishnan, Karthikeyan Shanmugam, Amit Dhurandhar; NeurIPS 2020 [paper](https://proceedings.neurips.cc/paper/2020/file/24aef8cb3281a2422a59b51659f1ad2e-Paper.pdf)

- **Model Agnostic Multilevel Explanations**
  Karthikeyan Natesan Ramamurthy, Bhanukiran Vinzamuri, Yunfeng Zhang, Amit Dhurandhar; NeurIPS 2020 [paper](https://proceedings.neurips.cc/paper/2020/file/426f990b332ef8193a61cc90516c1245-Paper.pdf)
  `Notes: implicitly learns to generalize across multiple local explanations.`

- **Interpretations are useful: penalizing explanations to align neural networks with prior knowledge**
  Laura Rieger, Chandan Singh, William Murdoch, Bin Yu; ICML 2020 [paper](http://proceedings.mlr.press/v119/rieger20a/rieger20a.pdf) [code](https://github.com/laura-rieger/deep-explanation-penalization)

- **Learning to Faithfully Rationalize by Construction**
  Sarthak Jain, Sarah Wiegreffe, Yuval Pinter, Byron Wallace. ACL 2020 [paper](https://www.aclweb.org/anthology/2020.acl-main.409.pdf) [code](https://github.com/successar/FRESH)

- **Reflective-Net: Learning from Explanations**
  Johannes Schneider, Michalis Vlachos; arXiv 2020 [paper](https://arxiv.org/pdf/2011.13986.pdf)

- **Learning Interpretable Concept-based Models with Human Feedback**
  Isaac Lage, Finale Doshi-Velez; arXiv 2020 [paper](https://arxiv.org/pdf/2012.02898)
  `Notes: incrementally acquires side-information about per-concept feature dependencies;  side-information is per-concept, not per-instance.`

- **GLocalX-From Local to Global Explanations of Black Box AI Models**
  Mattia Setzu, Riccardo Guidotti, Anna Monreale, Franco Turini, Dino Pedreschi, and Fosca Giannotti; Artificial Intelligence 2021 [page](https://www.sciencedirect.com/science/article/pii/S0004370221000084) [code](https://github.com/msetzu/glocalx)
  `Notes: converts a set of local explanations to a global explanation / white-box model.`

- **Debiasing Concept-based Explanations with Causal Analysis**
  Mohammad Taha Bahadori, and David E. Heckerman; ICLR 2021 [paper](https://openreview.net/pdf?id=6puUoArESGp)

- **Teaching with Commentaries**
  Aniruddh Raghu, Maithra Raghu, Simon Kornblith, David Duvenaud, and Geoffrey Hinton; ICLR 2021 [paper](https://openreview.net/pdf?id=4RbdgBh9gE) [code](github.com/googleinterns/commentaries)

- **Saliency is a possible red herring when diagnosing poor generalization**
  Joseph Viviano, Becks Simpson, Francis Dutil, Yoshua Bengio, Joseph Paul Cohen; ICLR 2021 [paper](https://openreview.net/pdf?id=c9-WeM-ceB) [code](https://github.com/josephdviviano/saliency-red-herring)

- **Towards Robust Classification Model by Counterfactual and Invariant Data Generation**
  Chun-Hao Chang, George Alexandru Adam, Anna Goldenberg; CVPR 2021 [paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Chang_Towards_Robust_Classification_Model_by_Counterfactual_and_Invariant_Data_Generation_CVPR_2021_paper.pdf) [code](https://github.com/zzzace2000/robust_cls_model)

- **Explanation-Based Human Debugging of NLP Models: A Survey**
  Piyawat Lertvittayakumjorn, Francesca Toni; arXiv 2021 [paper](https://arxiv.org/pdf/2104.15135)

- **When Can Models Learn From Explanations? A Formal Framework for Understanding the Roles of Explanation Data**
  Peter Hase, Mohit Bansal; arXiv 2021 [paper](https://arxiv.org/pdf/2102.02201.pdf) [code](https://github.com/peterbhase/ExplanationRoles)

- **Explain and Predict, and then Predict Again**
  Zijian Zhang, Koustav Rudra, Avishek Anand; arXiv 2021 [paper](https://arxiv.org/pdf/2101.04109) [code](https://github.com/JoshuaGhost/expred)

- **IAIA-BL: A Case-based Interpretable Deep Learning Model for Classification of Mass Lesions in Digital Mammography.**
  Alina Barnett, Fides Schwartz, Chaofan Tao, Chaofan Chen, Yinhao Ren, Joseph Lo, Cynthia Rudin; arXiv 2021 [paper](https://arxiv.org/pdf/2103.12308)

- **Enjoy the Salience: Towards Better Transformer-based Faithful Explanations with Word Salience**
  George Chrysostomou, Nikolaos Aletras;  arXiv 2021 [paper](https://arxiv.org/pdf/2108.13759) [code](https://github.com/GChrysostomou/saloss)


----

### [Interactive Learning](#content)

Approaches that combine supervision on the explanations with interactive machine learning:

- **Principles of Explanatory Debugging to Personalize Interactive Machine Learning**
  Todd Kulesza, Margaret Burnett, Weng-Keen Wong, Simone Stumpf; IUI 2015 [paper](https://openaccess.city.ac.uk/id/eprint/13819/1/paper326.pdf)

- **Explanatory Interactive Machine Learning**
  Stefano Teso, Kristian Kersting; AIES 2019 [paper](https://www.aiml.informatik.tu-darmstadt.de/papers/teso2019aies_XIML.pdf) [code](https://github.com/stefanoteso/caipi)
  `Notes: introduces explanatory interactive learning, focuses on active learning setup.`

- **Taking a hint: Leveraging explanations to make vision and language models more grounded**
  Ramprasaath R. Selvaraju, Stefan Lee, Yilin Shen, Hongxia Jin, Shalini Ghosh, Larry Heck, Dhruv Batra, and Devi Parikh; ICCV 2019 [pdf](https://openaccess.thecvf.com/content_ICCV_2019/papers/Selvaraju_Taking_a_HINT_Leveraging_Explanations_to_Make_Vision_and_Language_ICCV_2019_paper.pdf)

- **Toward Faithful Explanatory Active Learning with Self-explainable Neural Nets**
  Stefano Teso; IAL Workshop 2019. [paper](https://lirias.kuleuven.be/retrieve/578884) [code](https://github.com/stefanoteso/calimocho)
  `Notes: explanatory active learning with self-explainable neural networks.`

- **Making deep neural networks right for the right scientific reasons by interacting with their explanations**
  Patrick Schramowski, Wolfgang Stammer, Stefano Teso, Anna Brugger, Franziska Herbert, Xiaoting Shao, Hans-Georg Luigs, Anne-Katrin Mahlein, Kristian Kersting; Nature Machine Intelligence 2020 [paper](https://www.nature.com/articles/s42256-020-0212-3) [code](https://github.com/ml-research/XIL)
  `Notes: introduces end-to-end explanatory interactive learning, fixes clever Hans deep neural nets.`

- **One explanation does not fit all**
  Kacper Sokol, Peter Flach; 2020 Künstliche Intelligenz [paper](https://link.springer.com/content/pdf/10.1007/s13218-020-00637-y.pdf)

- **FIND: Human-in-the-loop Debugging Deep Text Classifiers**
  Piyawat Lertvittayakumjorn, Lucia Specia, Francesca Toni; EMNLP 2020 [paper](https://www.aclweb.org/anthology/2020.emnlp-main.24.pdf)

- **Human-driven FOL explanations of deep learning**
  Gabriele Ciravegna, Francesco Giannini, Marco Gori, Marco Maggini, Stefano Melacci; IJCAI 2020 [paper](https://www.ijcai.org/Proceedings/2020/0309.pdf)
  `Notes: first-order logic.`

- **Cost-effective Interactive Attention Learning with Neural Attention Process**
  Jay Heo, Junhyeon Park, Hyewon Jeong, Kwang joon Kim, Juho Lee, Eunho Yang, Sung Ju Hwang; ICML 2020 [paper](https://arxiv.org/pdf/2006.05419.pdf) [code](https://github.com/jayheo/IAL)
  `Notes: attention, interaction`

- **Machine Guides, Human Supervises: Interactive Learning with Global Explanations**
  Teodora Popordanoska, Mohit Kumar, Stefano Teso; arXiv 2020 [paper](https://arxiv.org/pdf/2009.09723.pdf) [code](https://github.com/tpopordanoska/explanatory-guided-learning)
  `Notes: introduces narrative bias and explanatory guided learning, focuses on human-initiated interaction and global explanations.`

- **Right for the Right Concept: Revising Neuro-Symbolic Concepts by Interacting with their Explanations**
  Wolfgang Stammer, Patrick Schramowski, and Kristian Kersting; CVPR 2021 [paper](https://arxiv.org/pdf/2011.12854) [code](https://github.com/ml-research/NeSyXIL)
  `Notes: first-order logic, attention.`

- **Right for Better Reasons: Training Differentiable Models by Constraining their Influence Function**
  Xiaoting Shao, Arseny Skryagin, Patrick Schramowski, Wolfgang Stammer, Kristian Kersting; AAAI 2021 [paper](https://www.aaai.org/AAAI21Papers/AAAI-5436.ShaoX.pdf)

- **User Driven Model Adjustment via Boolean Rule Explanations**
  Elizabeth Daly, Massimiliano Mattetti, Öznur Alkan, Rahul Nair; AAAI 2021 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16737/16544)

- **Explainable Active Learning (XAL): Toward AI Explanations as Interfaces for Machine Teachers**
  Bhavya Ghai, Vera Liao, Yunfeng Zhang, Rachel Bellamy, Klaus Mueller.  Proc. ACM Hum.-Comput. Interact. 2021 [paper](https://www3.cs.stonybrook.edu/~mueller/papers/CSCW%20XAL%202020.pdf)

- **Bandits for Learning to Explain from Explanations**
  Freya Behrens, Stefano Teso, Davide Mottin; XAI Workshop 2021 [paper](https://arxiv.org/pdf/2102.03815) [code](https://github.com/stefanoteso/explearner-simpler)
  `Notes: preliminary.`

- **HILDIF: Interactive Debugging of NLI Models Using Influence Functions**
  Hugo Zylberajch, Piyawat Lertvittayakumjorn, Francesca Toni; InterNLP Workshop 2021 [paper](https://aclanthology.org/2021.internlp-1.1.pdf) [code](https://github.com/hugozylberajch/HILDIF)

- **Refining Neural Networks with Compositional Explanations**
  Huihan Yao, Ying Chen, Qinyuan Ye, Xisen Jin, Xiang Ren; arXiv 2021 [paper](https://arxiv.org/pdf/2103.10415) [code](https://github.com/INK-USC/expl-refinement)

- **Explaining the Efficacy of Counterfactually Augmented Data**
  Divyansh Kaushik, Amrith Setlur, Eduard H. Hovy, Zachary Lipton; ICLR 2021. [paper](https://openreview.net/pdf?id=HHiiQKWsOcV) [code](https://github.com/acmi-lab/counterfactually-augmented-data)

- **Interactive Label Cleaning with Example-based Explanations**
  Stefano Teso, Andrea Bontempelli, Fausto Giunchiglia, Andrea Passerini; NeurIPS 2021 [paper](https://arxiv.org/pdf/2106.03922) [code](https://github.com/abonte/cincer)

- **Symbols as a Lingua Franca for Bridging Human-AI Chasm for Explainable and Advisable AI Systems**
  Subbarao Kambhampati, Sarath Sreedharan, Mudit Verma, Yantian Zha, Lin Guan; arXiv 2021 [paper](https://arxiv.org/pdf/2109.09904)

- **Toward a Unified Framework for Debugging Gray-box Models**
  Andrea Bontempelli, Fausto Giunchiglia, Andrea Passerini, Stefano Teso; arXiv 2021 [paper](https://arxiv.org/pdf/2109.11160)

- **Finding and Fixing Spurious Patterns with Explanations**
  Gregory Plumb, Marco Tulio Ribeiro, Ameet Talwalkar; arXiv 2021 [paper](https://arxiv.org/pdf/2106.02112)

- **Interaction with Explanations in the XAINES Project**
  Mareike Hartmann, Ivana Kruijff-Korbayová, Daniel Sonntag; 2021 [paper](https://dataninja.nrw/wp-content/uploads/2021/09/7_Hartmann_XAINES_Abstract.pdf)

----


### [Reinforcement Learning](#content)

- **Explanation Augmented Feedback in Human-in-the-Loop Reinforcement Learning**
  Lin Guan, Mudit Verma, Sihang Guo, Ruohan Zhang, Subbarao Kambhampati; arXiv 2020 [paper](https://arxiv.org/pdf/2006.14804)

- **Learning from explanations and demonstrations: A pilot study**
  Silvia Tulli, Sebastian Wallkötter, Ana Paiva, Francisco Melo, Mohamed Chetouani; Workshop on Interactive Natural Language Technology for Explainable Artificial Intelligence 2020 [paper](https://aclanthology.org/2020.nl4xai-1.13.pdf)

- **Widening the Pipeline in Human-Guided Reinforcement Learning with Explanation and Context-Aware Data Augmentation**
  Lin Guan, Mudit Verma, Sihang Guo, Ruohan Zhang, Subbarao Kambhampati; NeurIPS 2021 [pdf](https://arxiv.org/pdf/2006.14804.pdf)

----


### [Distillation](#content)

- **Model reconstruction from model explanations**
  Smitha Milli, Ludwig Schmidt, Anca D. Dragan, Moritz Hardt; FAcct 2019 [paper](https://arxiv.org/pdf/1807.05185)

- **Evaluating Explanations: How much do explanations from the teacher aid students?**
  Danish Pruthi, Bhuwan Dhingra, Livio Baldini Soares, Michael Collins, Zachary C. Lipton, Graham Neubig, and William W. Cohen; arXiv 2020 [paper](https://arxiv.org/pdf/2012.00893)
  `Notes: defines importance of different kinds of explanations by measuring their impact when used as supervision.`

----


### [Regularization without Supervision](#content)

Approaches that regularize the model's explanations in an unsupervised manner, often for improved interpretability.

- **Improving the adversarial robustness and interpretability of deep neural networks by regularizing their input gradients**
  Andrew Ross and Finale Doshi-Velez.  AAAI 2018 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/11504/11363)

- **Towards robust interpretability with self-explaining neural networks**
  David Alvarez-Melis, Tommi Jaakkola; NeurIPS 2018 [paper](https://proceedings.neurips.cc/paper/2018/file/3e9f0fc9b2f89e043bc6233994dfcf76-Paper.pdf)

- **Beyond sparsity: Tree regularization of deep models for interpretability**
  Mike Wu, Michael Hughes, Sonali Parbhoo, Maurizio Zazzi, Volker Roth, Finale Doshi-Velez; AAAI 2018 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/11501/11360)

- **Regional tree regularization for interpretability in deep neural networks**
  Mike Wu, Sonali Parbhoo, Michael Hughes, Ryan Kindle, Leo Celi, Maurizio Zazzi, Volker Roth, Finale Doshi-Velez; AAAI 2020 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/6112/5968)

- **Regularizing black-box models for improved interpretability**
  Gregory Plumb, Maruan Al-Shedivat, Ángel Alexander Cabrera, Adam Perer, Eric Xing, Ameet Talwalkar; NeurIPS 2020 [paper](https://papers.nips.cc/paper/2020/file/770f8e448d07586afbf77bb59f698587-Paper.pdf)

- **Don't Judge an Object by Its Context: Learning to Overcome Contextual Bias**
  Krishna Kumar Singh, Dhruv Mahajan, Kristen Grauman, Yong Jae Lee, Matt Feiszli, Deepti Ghadiyaram; CVPR 2020 [paper](http://openaccess.thecvf.com/content_CVPR_2020/papers/Singh_Dont_Judge_an_Object_by_Its_Context_Learning_to_Overcome_CVPR_2020_paper.pdf) [code](https://github.com/princetonvisualai/ContextualBias)

- **Trustworthy convolutional neural networks: A gradient penalized-based approach**
  Nicholas Halliwell, Freddy Lecue; arXiv 2020 [paper](https://arxiv.org/pdf/2009.14260)

- **Explainable Models with Consistent Interpretations**
  Vipin Pillai, Hamed Pirsiavash; AAAI 2021 [paper](https://www.csee.umbc.edu/~hpirsiav/papers/gc_aaai21.pdf) [code](https://github.com/UMBCvision/Explainable-Models-with-Consistent-Interpretations)

- **Explanation Consistency Training: Facilitating Consistency-based Semi-supervised Learning with Interpretability**
  Tao Han, Wei-Wei Tu, Yu-Feng Li; AAAI 2021 [paper](https://www.aaai.org/AAAI21Papers/AAAI-7186.HanT.pdf)


----


### [Machine Teaching](#content)

- **Interpretable Machine Teaching via Feature Feedback**
  Shihan Su, Yuxin Chen, Oisin Mac Aodha, Pietro Perona, Yisong Yue; Workshop on Teaching Machines, Robots, and Humans 2017 [paper](https://authors.library.caltech.edu/87329/1/nips17-teaching_paper-5.pdf)

- **Teaching Categories to Human Learners with Visual Explanations**
  Oisin Mac Aodha, Shihan Su, Yuxin Chen, Pietro Perona, Yisong Yue; CVPR 2018 [paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Aodha_Teaching_Categories_to_CVPR_2018_paper.pdf)
  `Notes: this is *inverse* teaching, i.e., machine teaches human.`

----

### [Applications](#applications)

- **Improving a neural network model by explanation-guided training for glioma classification based on MRI data**
  Frantisek Sefcik, Wanda Benesova; arXiv 2021 [paper](https://arxiv.org/pdf/2107.02008)
  `Notes: based on layer-wise relevance propagation.`

---


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

- **Tangent Prop - A formalism for specifying selected invariances in an adaptive network**
  Patrice Simard, Bernard Victorri, Yann Le Cun, John Denker; NeurIPS 1992 [paper](https://papers.nips.cc/paper/536-tangent-prop-a-formalism-for-specifying-selected-invariances-in-an-adaptive-network.pdf)
  `Notes: injects invariances into a neural net by regularizing its gradient; precursor to learning from gradient-based explanations.`

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


Gray-box models:

- **Concept bottleneck models**
  Pang Wei Koh, Thao Nguyen, Yew Siang Tang, Stephen Mussmann, Emma Pierson, Been Kim, and Percy Liang; ICML 2020 [paper](http://proceedings.mlr.press/v119/koh20a/koh20a.pdf)

----


### [Resources](#content)

A selection of general resources on Explainable AI focusing on overviews, surveys, societal implications, and critiques:

- **Survey and critique of techniques for extracting rules from trained artificial neural networks**
  Robert Andrews, Joachim Diederich, Alan B. Tickle; Knowledge-based systems 1995 [page](https://www.sciencedirect.com/science/article/abs/pii/0950705196819204)

- **Toward harnessing user feedback for machine learning**
  Simone Stumpf, Vidya Rajaram, Lida Li, Margaret Burnett, Thomas Dietterich, Erin Sullivan, Russell Drummond, Jonathan Herlocker; IUI 2007 [paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.86.140&rep=rep1&type=pdf)

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

- **A Benchmark for Interpretability Methods in Deep Neural Networks**
  Sara Hooke, Dumitru Erhan, Pieter-Jan Kindermans, Been Kim; NeurIPS 2019 [paper](http://papers.neurips.cc/paper/9167-a-benchmark-for-interpretability-methods-in-deep-neural-networks.pdf) [code](https://github.com/google-research/google-research/tree/master/interpretability_benchmark)

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

- **The Principles and Limits of Algorithm-in-the-loop Decision Making**
  Ben Green, Yiling Chen; PACM HCI 2019 [paper](https://dl.acm.org/doi/pdf/10.1145/3359152)

- **Shortcut learning in deep neural networks.**
  Robert Geirhos, Jorn-Henrik Jacobsen, Claudio Michaelis, Richard Zemel, Wieland Brendel, Matthias Bethge, Felix Wichmann; Nature Machine Intelligence 2020 [page](https://www.nature.com/articles/s42256-020-00257-z)

- **When Explanations Lie: Why Many Modified BP Attributions Fail**
  Leon Sixt, Maximilian Granz, Tim Landgraf.  ICML 2020 [paper](http://proceedings.mlr.press/v119/sixt20a/sixt20a.pdf)

- **How Well do Feature Visualizations Support Causal Understanding of CNN Activations?**
  Roland Zimmermann,Judy Borowski, Robert Geirhos, Matthias Bethge, Thomas Wallis, Wieland Brendel; arXiv 2021 [paper](https://arxiv.org/pdf/2106.12447)

----


### Related Lists

- [Awesome explainable AI](https://github.com/wangyongjie-ntu/Awesome-explainable-AI)

- [Awesome machine learning interpretability](https://github.com/jphall663/awesome-machine-learning-interpretability)

----


### Not Yet Sorted

- **Multimodal explanations: Justifying decisions and pointing to the evidence**
  Dong Huk Park, Lisa Anne Hendricks, Zeynep Akata, Anna Rohrbach, Bernt Schiele, Trevor Darrell, Marcus Rohrbach; CVPR 2018 [paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Park_Multimodal_Explanations_Justifying_CVPR_2018_paper.pdf)

- **Learning Deep Attribution Priors Based On Prior Knowledge**
  Ethan Weinberger, Joseph Janizek, Su-In Lee; NeurIPS 2020 [paper](https://papers.nips.cc/paper/2020/file/a19883fca95d0e5ec7ee6c94c6c32028-Paper.pdf)

----


### TODO

- Crawl & reference work on NLP.



### Comments

This list is directly inspired by all the awesome awesome lists out there!
