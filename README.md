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
- [Online Resources](#online-resources)
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


### [Online Resources](#online-resources)

- Tutorial on Explanations in Interactive Machine Learning at AAAI-22 [website](https://sites.google.com/view/aaai22-ximl-tutorial/home)
  `Notes: includes recording`.

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

- **Tell me where to look: Guided attention inference network**
  Kunpeng Li, Ziyan Wu, Kuan-Chuan Peng, Jan Ernst, Yun Fu; CVPR 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Tell_Me_Where_CVPR_2018_paper.pdf)

- **e-SNLI: Natural Language Inference with Natural Language Explanations**
  Oana-Maria Camburu, Tim Rocktäschel, Thomas Lukasiewicz, Phil Blunsom; NeurIPS 2018 [paper](https://proceedings.neurips.cc/paper_files/paper/2018/file/4c7a167bb329bd92580a99ce422d6fa6-Paper.pdf) [code](https://github.com/OanaMariaCamburu/e-SNLI)

- **Learning credible models**
  Jiaxuan Wang, Jeeheh Oh, Haozhu Wang, and Jenna Wiens; KDD 2018 [paper](https://dl.acm.org/doi/pdf/10.1145/3219819.3220070) [code](https://github.com/nathanwang000/credible_learning)

- **Not Using the Car to See the Sidewalk--Quantifying and Controlling the Effects of Context in Classification and Segmentation**
  Rakshith Shetty, Bernt Schiele, Mario Fritz; CVPR 2019 [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shetty_Not_Using_the_Car_to_See_the_Sidewalk_--_Quantifying_CVPR_2019_paper.pdf)
  `Notes: not exactly about explanations, learns from ground-truth object annotations.`

- **Taking a HINT: Leveraging Explanations to Make Vision and Language Models More Grounded**
  Ramprasaath R. Selvaraju, Stefan Lee, Yilin Shen, Hongxia Jin, Shalini Ghosh, Larry Heck, Dhruv Batra, and Devi Parikh; ICCV 2019 [pdf](https://openaccess.thecvf.com/content_ICCV_2019/papers/Selvaraju_Taking_a_HINT_Leveraging_Explanations_to_Make_Vision_and_Language_ICCV_2019_paper.pdf)

- **Learning credible deep neural networks with rationale regularization**
  Mengnan Du, Ninghao Liu, Fan Yang, Xia Hu; ICDM 2019 [paper](https://arxiv.org/pdf/1908.05601)

- **Deriving Machine Attention from Human Rationales**
  Yujia Bao, Shiyu Chang, Mo Yu, and Regina Barzilay; ACL 2019 [paper](https://www.aclweb.org/anthology/D18-1216.pdf) [code](https://github.com/YujiaBao/R2A)

- **TED: Teaching AI to explain its decisions**
  Michael Hind, Dennis Wei, Murray Campbell, Noel Codella, Amit Dhurandhar, Aleksandra Mojsilović, Karthikeyan Ramamurthy, Kush Varshney; AIES 2019 [paper](https://arxiv.org/pdf/1811.04896.pdf)

- **Incorporating Priors with Feature Attribution on Text Classification**
  Frederick Liu, Besim Avci; ACL 2019 [paper](https://aclanthology.org/P19-1631.pdf)

- **Saliency Learning: Teaching the Model Where to Pay Attention**
  Reza Ghaeini, Xiaoli Fern, Hamed Shahbazi, Prasad Tadepalli; NAACL 2019 [paper](https://aclanthology.org/N19-1404.pdf)

- **Do Human Rationales Improve Machine Explanations?**
  Julia Strout, Ye Zhang, Raymond Mooney; ACL Workshop BlackboxNLP 2019 [paper](https://www.aclweb.org/anthology/W19-4807.pdf)

- **CARE: Class attention to regions of lesion for classification on imbalanced data**
  Jiaxin Zhuang, Jiabin Cai, Ruixuan Wang, Jianguo Zhang, Weishi Zheng; International Conference on Medical Imaging with Deep Learning, 2019. [paper](http://proceedings.mlr.press/v102/zhuang19a/zhuang19a.pdf)

- **GradMask: Reduce Overfitting by Regularizing Saliency**
  Becks Simpson, Francis Dutil, Yoshua Bengio, Joseph Paul Cohen; International Conference on Medical Imaging with Deep Learning, 2019. [paper](https://openreview.net/pdf?id=Syx2z2aMqE)

- **Learning Global Transparent Models Consistent with Local Contrastive Explanations**
  Tejaswini Pedapati, Avinash Balakrishnan, Karthikeyan Shanmugam, Amit Dhurandhar; NeurIPS 2020 [paper](https://proceedings.neurips.cc/paper/2020/file/24aef8cb3281a2422a59b51659f1ad2e-Paper.pdf)

- **Model Agnostic Multilevel Explanations**
  Karthikeyan Natesan Ramamurthy, Bhanukiran Vinzamuri, Yunfeng Zhang, Amit Dhurandhar; NeurIPS 2020 [paper](https://proceedings.neurips.cc/paper/2020/file/426f990b332ef8193a61cc90516c1245-Paper.pdf)
  `Notes: implicitly learns to generalize across multiple local explanations.`

- **Interpretations are useful: penalizing explanations to align neural networks with prior knowledge**
  Laura Rieger, Chandan Singh, William Murdoch, Bin Yu; ICML 2020 [paper](http://proceedings.mlr.press/v119/rieger20a/rieger20a.pdf) [code](https://github.com/laura-rieger/deep-explanation-penalization)

- **Remembering for the Right Reasons: Explanations Reduce Catastrophic Forgetting**
  Sayna Ebrahimi, Suzanne Petryk, Akash Gokul, William Gan, Joseph Gonzalez, Marcus Rohrbach; ICLR 2020 [paper](https://openreview.net/pdf?id=tHgJoMfy6nI) [code](https://github.com/SaynaEbrahimi/Remembering-for-the-Right-Reasons)
  `Notes: uses saliency guided replay for continual learning.`

- **Learning to Faithfully Rationalize by Construction**
  Sarthak Jain, Sarah Wiegreffe, Yuval Pinter, Byron Wallace. ACL 2020 [paper](https://www.aclweb.org/anthology/2020.acl-main.409.pdf) [code](https://github.com/successar/FRESH)

- **Reflective-Net: Learning from Explanations**
  Johannes Schneider, Michalis Vlachos; arXiv 2020 [paper](https://arxiv.org/pdf/2011.13986.pdf)

- **Learning Interpretable Concept-based Models with Human Feedback**
  Isaac Lage, Finale Doshi-Velez; arXiv 2020 [paper](https://arxiv.org/pdf/2012.02898)
  `Notes: incrementally acquires side-information about per-concept feature dependencies; side-information is per-concept, not per-instance.`

- **Improving performance of deep learning models with axiomatic attribution priors and expected gradients**
  Gabriel Erion, Joseph D. Janizek, Pascal Sturmfels, Scott Lundberg, Su-In Lee; Nature Machine Intelligence 2019 [paper](https://www.nature.com/articles/s42256-021-00343-w) [preprint](https://arxiv.org/pdf/1906.10670) [code](github.com/suinleelab/attributionpriors)

- **GLocalX-From Local to Global Explanations of Black Box AI Models**
  Mattia Setzu, Riccardo Guidotti, Anna Monreale, Franco Turini, Dino Pedreschi, and Fosca Giannotti; Artificial Intelligence 2021 [page](https://www.sciencedirect.com/science/article/pii/S0004370221000084) [code](https://github.com/msetzu/glocalx)
  `Notes: converts a set of local explanations to a global explanation / white-box model.`

- **IAIA-BL: A Case-based Interpretable Deep Learning Model for Classification of Mass Lesions in Digital Mammography**
  Alina Barnett, Fides Schwartz, Chaofan Tao, Chaofan Chen, Yinhao Ren, Joseph Lo, Cynthia Rudin; Nature Machine Intelligence 2021 [paper](https://arxiv.org/pdf/2103.12308) [code](https://github.com/alinajadebarnett/iaiabl)

- **Debiasing Concept-based Explanations with Causal Analysis**
  Mohammad Taha Bahadori, and David E. Heckerman; ICLR 2021 [paper](https://openreview.net/pdf?id=6puUoArESGp)

- **Teaching with Commentaries**
  Aniruddh Raghu, Maithra Raghu, Simon Kornblith, David Duvenaud, and Geoffrey Hinton; ICLR 2021 [paper](https://openreview.net/pdf?id=4RbdgBh9gE) [code](github.com/googleinterns/commentaries)

- **Saliency is a possible red herring when diagnosing poor generalization**
  Joseph Viviano, Becks Simpson, Francis Dutil, Yoshua Bengio, Joseph Paul Cohen; ICLR 2021 [paper](https://openreview.net/pdf?id=c9-WeM-ceB) [code](https://github.com/josephdviviano/saliency-red-herring)

- **Towards Robust Classification Model by Counterfactual and Invariant Data Generation**
  Chun-Hao Chang, George Alexandru Adam, Anna Goldenberg; CVPR 2021 [paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Chang_Towards_Robust_Classification_Model_by_Counterfactual_and_Invariant_Data_Generation_CVPR_2021_paper.pdf) [code](https://github.com/zzzace2000/robust_cls_model)

- **Global Explanations with Decision Rules: a Co-learning Approach**
  Géraldin Nanfack, Paul Temple, Benoît Frénay1; UAI 2021 [paper](https://proceedings.mlr.press/v161/nanfack21a/nanfack21a.pdf) [code](https://github.com/gerald4/Co-learning_with_STruGMA)

- **Explain and Predict, and then Predict Again**
  Zijian Zhang, Koustav Rudra, Avishek Anand; WSDM 2021 [paper](https://arxiv.org/pdf/2101.04109) [code](https://github.com/JoshuaGhost/expred)

- **Explanation-Based Human Debugging of NLP Models: A Survey**
  Piyawat Lertvittayakumjorn, Francesca Toni; arXiv 2021 [paper](https://arxiv.org/pdf/2104.15135)

- **When Can Models Learn From Explanations? A Formal Framework for Understanding the Roles of Explanation Data**
  Peter Hase, Mohit Bansal; arXiv 2021 [paper](https://arxiv.org/pdf/2102.02201.pdf) [code](https://github.com/peterbhase/ExplanationRoles)

- **Enjoy the Salience: Towards Better Transformer-based Faithful Explanations with Word Salience**
  George Chrysostomou, Nikolaos Aletras; arXiv 2021 [paper](https://arxiv.org/pdf/2108.13759) [code](https://github.com/GChrysostomou/saloss)

- **Influence Tuning: Demoting Spurious Correlations via Instance Attribution and Instance-Driven Updates**
  Xiaochuang Han, Yulia Tsvetkov; arXiv 2021 [paper](https://arxiv.org/pdf/2110.03212.pdf) [code](https://github.com/xhan77/influence-tuning)

- **Saliency Guided Experience Packing for Replay in Continual Learning**
  Gobinda Saha, Kaushik Roy; arXiv 2021 [paper](https://arxiv.org/pdf/2109.04954)
  `Notes: leverages saliency for experience replay in continual learning.`

- **What to Learn, and How: Toward Effective Learning from Rationales**
  Samuel Carton, Surya Kanoria, Chenhao Tan; arXiv 2021 [paper](https://arxiv.org/pdf/2112.00071)

- **Supervising Model Attention with Human Explanations for Robust Natural Language Inference**
  Joe Stacey, Yonatan Belinkov, Marek Rei; AAAI 2022 [paper](https://arxiv.org/pdf/2104.08142.pdf) [code](https://github.com/joestacey/NLI_with_a_human_touch)

- **Finding and removing Clever Hans: Using explanation methods to debug and improve deep models**
  Christopher Anders, Leander Weber, David Neumann, Wojciech Samek, Klaus-Robert Müller, Klaus-Robert, Sebastian Lapuschkin; Information Fusion 2022 [paper](https://www.sciencedirect.com/science/article/pii/S1566253521001573) [code](https://github.com/virelay/virelay) [code](https://github.com/virelay/corelay)

- **Toward Learning Human-aligned Cross-domain Robust Models by Countering Misaligned Features**
  Haohan Wang, Zeyi Huang, Hanlin Zhang, Eric P. Xing; UAI 2022 [paper](https://arxiv.org/pdf/2111.03740) [code](https://github.com/OoDBag/WR)

- **A survey on improving NLP models with human explanations**
  Mareike Hartmann, Daniel Sonntag; arXiv 2022 [paper](https://arxiv.org/pdf/2204.08892.pdf)

- **VisFIS: Visual Feature Importance Supervision with Right-for-the-Right-Reason Objectives**
  Zhuofan Ying, Peter Hase, and Mohit Bansal; arXiv 2022 [paper](https://arxiv.org/pdf/2206.11212) [code](https://github.com/zfying/visfis)

- **Identifying Spurious Correlations and Correcting them with an Explanation-based Learning**
  Misgina Tsighe Hagos, Kathleen Curran, Brian Mac Namee; arXiv 2022 [paper](https://arxiv.org/pdf/2211.08285)

- **Using Explanations to Guide Models**
  Sukrut Rao, Moritz Böhle, Amin Parchami-Araghi, Bernt Schiele; ICCV 2023 [paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Rao_Studying_How_to_Efficiently_and_Effectively_Guide_Models_with_Explanations_ICCV_2023_paper.pdf) [code](https://github.com/sukrutrao/Model-Guidance)

- **Learning with Explanation Constraints**
  Rattana Pukdee, Dylan Sam, Zico Kolter, Maria-Florina Balcan, Pradeep Ravikumar; arXiv 2023 [paper](https://arxiv.org/pdf/2303.14496)

- **Spuriosity Didn't Kill the Classifier: Using Invariant Predictions to Harness Spurious Features**
  Cian Eastwood, Shashank Singh, Andrei Liviu Nicolicioiu, Marin Vlastelica, Julius von Kügelgen, Benrnhard Schölkopf; arXiv 2023 [paper](https://arxiv.org/pdf/2307.09933)

- **Spurious features everywhere-large-scale detection of harmful spurious features in imagenet**
  Yannic Neuhaus, Maximilian Augustin, Valentyn Boreiko, Matthias Hein; ICCV 2023 [paper](http://openaccess.thecvf.com/content/ICCV2023/papers/Neuhaus_Spurious_Features_Everywhere_-_Large-Scale_Detection_of_Harmful_Spurious_Features_ICCV_2023_paper.pdf) [code](https://github.com/YanNeu/spurious_imagenet)

- **Targeted Activation Penalties Help CNNs Ignore Spurious Signals** Dekai Zhang, Matt Williams, and Francesca Toni; AAAI 2024 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/29610) [code](https://github.com/dkaizhang/tap)

----


### [Interactive Learning](#content)

Approaches that combine supervision on the explanations with interactive machine learning:

- **Principles of Explanatory Debugging to Personalize Interactive Machine Learning**
  Todd Kulesza, Margaret Burnett, Weng-Keen Wong, Simone Stumpf; IUI 2015 [paper](https://openaccess.city.ac.uk/id/eprint/13819/1/paper326.pdf)

- **Explanatory Interactive Machine Learning**
  Stefano Teso, Kristian Kersting; AIES 2019 [paper](https://www.aiml.informatik.tu-darmstadt.de/papers/teso2019aies_XIML.pdf) [code](https://github.com/stefanoteso/caipi)
  `Notes: introduces explanatory interactive learning, focuses on active learning setup.`

- **Toward Faithful Explanatory Active Learning with Self-explainable Neural Nets**
  Stefano Teso; IAL Workshop 2019. [paper](https://lirias.kuleuven.be/retrieve/578884) [code](https://github.com/stefanoteso/calimocho)
  `Notes: explanatory active learning with self-explainable neural networks.`

- **Making deep neural networks right for the right scientific reasons by interacting with their explanations**
  Patrick Schramowski, Wolfgang Stammer, Stefano Teso, Anna Brugger, Franziska Herbert, Xiaoting Shao, Hans-Georg Luigs, Anne-Katrin Mahlein, Kristian Kersting; Nature Machine Intelligence 2020 [paper](https://www.nature.com/articles/s42256-020-0212-3) [code](https://github.com/ml-research/XIL)
  `Notes: introduces end-to-end explanatory interactive learning, fixes clever Hans deep neural nets.`

- **Embedding Human Knowledge into Deep Neural Network via Attention Map**
  Masahiro Mitsuhara, Hiroshi Fukui, Yusuke Sakashita, Takanori Ogata, Tsubasa Hirakawa, Takayoshi Yamashita, Hironobu Fujiyoshi; arXiv 2019 [paper](https://arxiv.org/pdf/1905.03540.pdf)

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

- **Soliciting human-in-the-loop user feedback for interactive machine learning reduces user trust and impressions of model accuracy**
  Donald Honeycutt, Mahsan Nourani, Eric Ragan; AAAI Conference on Human Computation and Crowdsourcing 2020 [paper](https://ojs.aaai.org/index.php/HCOMP/article/download/7464/7291/)

- **ALICE: Active Learning with Contrastive Natural Language Explanations**
  Weixin Liang, James Zou, Zhou Yu; EMNLP 2020 [paper](https://www.aclweb.org/anthology/2020.emnlp-main.355.pdf)

- **Machine Guides, Human Supervises: Interactive Learning with Global Explanations**
  Teodora Popordanoska, Mohit Kumar, Stefano Teso; arXiv 2020 [paper](https://arxiv.org/pdf/2009.09723.pdf) [code](https://github.com/tpopordanoska/explanatory-guided-learning)
  `Notes: introduces narrative bias and explanatory guided learning, focuses on human-initiated interaction and global explanations.`

- **Teaching an Active Learner with Contrastive Examples**
  Chaoqi Wang, Adish Singla, Yuxin Chen. NeurIPS 2021. [paper](https://proceedings.neurips.cc/paper/2021/file/958adb57686c2fdec5796398de5f317a-Paper.pdf)

- **Right for the Right Concept: Revising Neuro-Symbolic Concepts by Interacting with their Explanations**
  Wolfgang Stammer, Patrick Schramowski, and Kristian Kersting; CVPR 2021 [paper](https://arxiv.org/pdf/2011.12854) [code](https://github.com/ml-research/NeSyXIL)
  `Notes: first-order logic, attention.`

- **Right for Better Reasons: Training Differentiable Models by Constraining their Influence Function**
  Xiaoting Shao, Arseny Skryagin, Patrick Schramowski, Wolfgang Stammer, Kristian Kersting; AAAI 2021 [paper](https://www.aaai.org/AAAI21Papers/AAAI-5436.ShaoX.pdf)

- **User Driven Model Adjustment via Boolean Rule Explanations**
  Elizabeth Daly, Massimiliano Mattetti, Öznur Alkan, Rahul Nair; AAAI 2021 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16737/16544)

- **Explainable Active Learning (XAL): Toward AI Explanations as Interfaces for Machine Teachers**
  Bhavya Ghai, Vera Liao, Yunfeng Zhang, Rachel Bellamy, Klaus Mueller. Proc. ACM Hum.-Comput. Interact. 2021 [paper](https://www3.cs.stonybrook.edu/~mueller/papers/CSCW%20XAL%202020.pdf)

- **Bandits for Learning to Explain from Explanations**
  Freya Behrens, Stefano Teso, Davide Mottin; XAI Workshop 2021 [paper](https://arxiv.org/pdf/2102.03815) [code](https://github.com/stefanoteso/explearner-simpler)
  `Notes: preliminary.`

- **HILDIF: Interactive Debugging of NLI Models Using Influence Functions**
  Hugo Zylberajch, Piyawat Lertvittayakumjorn, Francesca Toni; InterNLP Workshop 2021 [paper](https://aclanthology.org/2021.internlp-1.1.pdf) [code](https://github.com/hugozylberajch/HILDIF)

- **Refining Neural Networks with Compositional Explanations**
  Huihan Yao, Ying Chen, Qinyuan Ye, Xisen Jin, Xiang Ren; arXiv 2021 [paper](https://arxiv.org/pdf/2103.10415) [code](https://github.com/INK-USC/expl-refinement)

- **Interactive Label Cleaning with Example-based Explanations**
  Stefano Teso, Andrea Bontempelli, Fausto Giunchiglia, Andrea Passerini; NeurIPS 2021 [paper](https://arxiv.org/pdf/2106.03922) [code](https://github.com/abonte/cincer)

- **Symbols as a Lingua Franca for Bridging Human-AI Chasm for Explainable and Advisable AI Systems**
  Subbarao Kambhampati, Sarath Sreedharan, Mudit Verma, Yantian Zha, Lin Guan; AAAI 2022 [paper](https://arxiv.org/pdf/2109.09904)

- **Toward a Unified Framework for Debugging Gray-box Models**
  Andrea Bontempelli, Fausto Giunchiglia, Andrea Passerini, Stefano Teso; AAAI-22 Workshop on Interactive Machine Learning [paper](https://arxiv.org/pdf/2109.11160)

- **Active Learning by Acquiring Contrastive Examples**
  Katerina Margatina, Giorgos Vernikos, Loïc Barrault, Nikolaos Aletras; EMNLP 2021 [paper](https://aclanthology.org/2021.emnlp-main.51.pdf) [code](https://github.com/mourga/contrastive-active-learning)

- **Finding and Fixing Spurious Patterns with Explanations**
  Gregory Plumb, Marco Tulio Ribeiro, Ameet Talwalkar; arXiv 2021 [paper](https://arxiv.org/pdf/2106.02112)

- **Interactively Generating Explanations for Transformer Language Models**
  Patrick Schramowski, Felix Friedrich, Christopher Tauchmann, Kristian Kersting; arXiv 2021 [paper](https://arxiv.org/pdf/2110.02058.pdf)

- **Interaction with Explanations in the XAINES Project**
  Mareike Hartmann, Ivana Kruijff-Korbayová, Daniel Sonntag; arXiv 2021 [paper](https://dataninja.nrw/wp-content/uploads/2021/09/7_Hartmann_XAINES_Abstract.pdf)

- **A Rationale-Centric Framework for Human-in-the-loop Machine Learning**
  Jinghui Lu, Linyi Yang, Brian Mac Namee, Yue Zhang; ACL 2022 [paper](https://aclanthology.org/2022.acl-long.481.pdf) [code](https://github.com/GeorgeLuImmortal/RDL-Rationales-centric-Double-robustness-Learning/)

- **A Typology to Explore and Guide Explanatory Interactive Machine Learning**
  Felix Friedrich, Wolfgang Stammer, Patrick Schramowski, Kristian Kersting; arXiv 2022 [paper](https://arxiv.org/pdf/2203.03668)

- **CAIPI in Practice: Towards Explainable Interactive Medical Image Classification**
  Emanuel Slany, Yannik Ott, Stephan Scheele, Jan Paulus, Ute Schmid; IFIP International Conference on Artificial Intelligence Applications and Innovations, 2022 [paper](https://arxiv.org/pdf/2204.02661)

- **Semantic Interactive Learning for Text Classification: A Constructive Approach for Contextual Interactions**
  Semastian Kiefer, Mareike Hoffmann, Ute Schmid; Machine Learning and Knowledge Extraction, 2022 [paper](https://www.mdpi.com/2504-4990/4/4/50/pdf)

- **Impact of Feedback Type on Explanatory Interactive Learning**
  Misgina Tsighe Hagos, Kathleen Curran, Brian Mac Namee; ISMIS 2022 [paper](https://arxiv.org/pdf/2209.12476)

- **Leveraging Explanations in Interactive Machine Learning: An Overview**
  Stefano Teso, Öznur Alkan, Wolfgang Stammer, Elizabeth Daly; Frontiers in AI 2023 [paper](https://www.frontiersin.org/articles/10.3389/frai.2023.1066049/full) [preprint](https://arxiv.org/pdf/2207.14526)

- **Concept-level Debugging of Part-prototype Networks**
  Andrea Bontempelli, Stefano Teso, Fausto Giunchiglia, Andrea Passerini; ICLR 2023 [paper](https://openreview.net/pdf?id=oiwXWPDTyNk) [code](https://github.com/abonte/protopdebug)

- **Learning to Intervene on Concept Bottlenecks**
  David Steinmann, Wolfgang Stammer, Felix Friedrich, Kristian Kersting; arXiv 2023 [paper](https://arxiv.org/pdf/2308.13453)

----


### [Reinforcement Learning](#content)

- **Explanation Augmented Feedback in Human-in-the-Loop Reinforcement Learning**
  Lin Guan, Mudit Verma, Sihang Guo, Ruohan Zhang, Subbarao Kambhampati; Human And Machine in-the-Loop Evaluation and Learning Strategies [paper](https://arxiv.org/pdf/2006.14804)

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
  Andrew Ross and Finale Doshi-Velez. AAAI 2018 [paper](https://ojs.aaai.org/index.php/AAAI/article/view/11504/11363)

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

- **Improving Deep Learning Interpretability by Saliency Guided Training**
  Aya Abdelsalam Ismail, Hector Corrada Bravo, Soheil Feizi; NeurIPS 2021 [paper](https://proceedings.neurips.cc//paper/2021/file/e0cd3f16f9e883ca91c2a4c24f47b3d9-Paper.pdf) [code](https://github.com/ayaabdelsalam91/saliency_guided_training)

- **Generating Deep Networks Explanations with Robust Attribution Alignment**
  Guohang Zeng, Yousef Kowsar, Sarah Erfani, James Bailey; ACML 2021 [paper](https://proceedings.mlr.press/v157/zeng21b/zeng21b.pdf)

- **Learning by Self-Explaining**
  Wolfgang Stammer, Felix Friedrich, David Steinmann, Hikaru Shindo, Kristian Kersting; arXiv 2023 [paper](https://arxiv.org/pdf/2309.08395)


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

- **Learning from discriminative feature feedback**
  Sanjoy Dasgupta, Akansha Dey, Nicholas Roberts, Sivan Sabato; NeurIPS 2018 [paper](http://papers.neurips.cc/paper/7651-learning-from-discriminative-feature-feedback.pdf)

- **Robust Learning from Discriminative Feature Feedback**
  Sanjoy Dasgupta, Sivan Sabato; AISTATS 2020 [paper](http://proceedings.mlr.press/v108/dasgupta20a/dasgupta20a-supp.pdf)

- **Practical Benefits of Feature Feedback Under Distribution Shift**
  Anurag Katakkar, Weiqin Wang, Clay Yoo, Zachary Lipton, Divyansh Kaushik; arXiv 2021 [paper](https://arxiv.org/pdf/2110.07566)


Learning from rationales:

- **Using “annotator rationales” to improve machine learning for text categorization**
  Omar Zaidan, Jason Eisner, Christine Piatko; NAACL 2007 [paper](https://www.aclweb.org/anthology/N07-1033.pdf)

- **Modeling annotators: A generative approach to learning from annotator rationales**
  Omar Zaidan, Jason Eisner; EMNLP 2008 [paper](https://www.aclweb.org/anthology/D08-1004.pdf)

- **Active learning with rationales for text classification**
  Manali Sharma, Di Zhuang, Mustafa Bilgic; NAACL 2015 [paper](https://www.aclweb.org/anthology/N15-1047.pdf)


Counterfactual augmentation:

- **Learning The Difference That Makes A Difference With Counterfactually-Augmented Data**
  Divyansh Kaushik, Eduard Hovy, Zachary Lipton; ICLR 2019 [paper](https://openreview.net/pdf?id=Sklgs0NFvr) [code](https://github.com/dkaushik96/counterfactually-augmented-data)

- **Explaining the Efficacy of Counterfactually Augmented Data**
  Divyansh Kaushik, Amrith Setlur, Eduard H. Hovy, Zachary Lipton; ICLR 2021. [paper](https://openreview.net/pdf?id=HHiiQKWsOcV) [code](https://github.com/acmi-lab/counterfactually-augmented-data)

- **An Investigation of the (In)effectiveness of Counterfactually-augmented Data**
  Nitish Joshi, He He; arXiv 2021 [paper](https://arxiv.org/pdf/2107.00753)


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

- **Sanity checks for saliency maps**
  Julius Adebayo, Justin Gilmer, Michael Muelly, Ian Goodfellow, Moritz Hardt, Been Kim; NeurIPS 2018 [paper](http://papers.neurips.cc/paper/8160-sanity-checks-for-saliency-maps.pdf) [code](https://github.com/adebayoj/sanity_checks_saliency)

- **Recognition in terra incognita**
  Sara Beery, Grant Van Horn, Pietro Perona; ECCV 2018 [paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Beery_Recognition_in_Terra_ECCV_2018_paper.pdf)

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

- **Shortcut learning in deep neural networks**
  Robert Geirhos, Jorn-Henrik Jacobsen, Claudio Michaelis, Richard Zemel, Wieland Brendel, Matthias Bethge, Felix Wichmann; Nature Machine Intelligence 2020 [page](https://www.nature.com/articles/s42256-020-00257-z)

- **When Explanations Lie: Why Many Modified BP Attributions Fail**
  Leon Sixt, Maximilian Granz, Tim Landgraf. ICML 2020 [paper](http://proceedings.mlr.press/v119/sixt20a/sixt20a.pdf)

- **The elephant in the interpretability room: Why use attention as explanation when we have saliency methods?**
  Jasmijn Bastings, Katja Filippova; Third BlackboxNLP Workshop on Analyzing and Interpreting Neural Networks for NLP 2020 [paper](https://aclanthology.org/2020.blackboxnlp-1.14.pdf)

- **Why Attention is Not Explanation: Surgical Intervention and Causal Reasoning about Neural Models**
  Christopher Grimsley, Elijah Mayfield, Julia Bursten;  Language Resources and Evaluation Conference 2020 [paper](https://aclanthology.org/2020.lrec-1.220.pdf)

- **AI for radiographic COVID-19 detection selects shortcuts over signal**
  Alex DeGrave, Joseph Janizek, Su-In Lee; Nature Machine Intelligence 2021 [paper](https://www.nature.com/articles/s42256-021-00338-7.pdf) [code](https://github.com/suinleelab/cxr_covid)

- **How Well do Feature Visualizations Support Causal Understanding of CNN Activations?**
  Roland Zimmermann,Judy Borowski, Robert Geirhos, Matthias Bethge, Thomas Wallis, Wieland Brendel; arXiv 2021 [paper](https://arxiv.org/pdf/2106.12447)

- **Post hoc explanations may be ineffective for detecting unknown spurious correlation**
  Julius Adebayo, Michael Muelly, Harold Abelson, and Been Kim; ICLR 2022 [paper](https://openreview.net/pdf?id=xNOVfCCvDpM) [code](https://github.com/adebayoj/posthocspurious)

- **Where is the Truth? The Risk of Getting Confounded in a Continual World**
  Florian Peter Busch, Roshni Kamath, Rupert Mitchell, Wolfgang Stammer, Kristian Kersting, Martin Mundt

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
