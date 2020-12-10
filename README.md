# Workshop on Dataset Curation and Security - NeurIPS 2020, December 11th

## Workshop Schedule (times ET)

The workshop can be viewed (requires NeurIPS login) [here](https://neurips.cc/virtual/2020/protected/workshop_16162.html).

| Time    	| Speaker   	     | Title            	|
|---------	|-----------	     |------------------	|
| 9:00 am 	| Dawn Song 	     |   	|
| 9:30am    | Aleksander Madry | What Do Our Models Learn? 	|
| 10:00am   | Discussion | |
| 10:15am   | Break | |
| 10:30am | Darrell West | |
| 11:00am	| Yejin Choi          	|   Adversarial, Socially Aware, and Commonsensical Data   	| 
| 11:30am   | Discussion | |
| 11:45am   | Lunch Break | |
| 1:00pm    | Rob Nowak | Dataset Curation via Active Learning |
| 1:30pm | Liz O'Sullivan | Don't Steal Data |
| 2:30pm | Poster Session | |

**Poster Session will be on Friday at 2:30pm after the conclusion of the invited talks..**

Classical machine learning research has been focused largely on models,  optimizers,  and computational challenges. As technical progress and hardware advancements ease these challenges, practitioners are now finding that the limitations and faults of their models are the result of their datasets. This is particularly true of deep networks, which often rely on huge datasets that are too large and unwieldy for domain experts to curate by hand. We invite those interested to contribute in the discussion around dataset curation and security.

We have identified four areas of interest: Dataset security, policy and privacy, dataset bias, and data scraping and labeling. In addition to the invited speakers listed below, we are excited to invite paper submissions on the topics of data poisoning and backdoor attacks, data sanitization, dataset bias, and dataset privacy. Broadly, this workshop is about data, so if your work is on datasets, their curation and impact, then this workshop is for you! See the [call for papers](#cfp) below for more details. If you have any questions, please reach out to Micah Goldblum (<goldblumcello@gmail.com>).

## Update -- templates for camera-ready submission

Please use the following modified version of the NeurIPS 2020 template for your camera-ready submission: [wdcs2020.sty](templates/wdcs2020.sty).

For posters, we recommend using the following modified NeurIPS poster templates: [keynoteTemplate.key](templates/keynoteTemplate.key), [pptTemplate.pptx](templates/pptTemplate.pptx).

## Invited Speakers

**[Aleksander Mądry](https://people.csail.mit.edu/madry/),** _MIT_.
>**What Do Our Models Learn?** Large-scale vision benchmarks have driven—and often even defined—progress in machine learning. However, these benchmarks are merely proxies for the real-world tasks we actually care about. How well do our benchmarks capture such tasks?
>
>In this talk, I will discuss the alignment between our benchmark-driven ML paradigm and the real-world uses cases that motivate it. First, we will explore examples of biases in the ImageNet dataset, and how state-of-the-art models exploit them. We will then demonstrate how these biases arise as a result of design choices in the data collection and curation processes.
>
>Throughout, we illustrate how one can leverage relatively standard tools (e.g., crowdsourcing, image processing) to quantify the biases that we observe.
Based on joint works with Logan Engstrom, Andrew Ilyas, Shibani Santurkar, Dimitris Tsipras and Kai Xiao.

**[Darrell M. West](https://www.brookings.edu/experts/darrell-m-west/),** _Brookings Institution_.

**[Dawn Song](https://people.eecs.berkeley.edu/~dawnsong/?_ga=2.130447496.627426393.1600173880-497787535.1600173880),** _UC Berkeley_.

**[Liz O'Sullivan](https://www.lizjosullivan.com/)**, _Arthur AI_
>**Don't Steal Data**

**[Rob Nowak](https://nowak.ece.wisc.edu/),** 
_Robert Nowak holds the Nosbusch Professorship in Engineering at the University of Wisconsin-Madison, where his research focuses on signal processing, machine learning, optimization, and statistics._ 

>**Dataset Curation via Active Learning** The field of Machine Learning (ML) has advanced considerably in recent years, but mostly in well-defined domains using huge amounts of human-labeled training data. Machines can recognize objects in images and translate text, but they must be trained with more images and text than a person can see in nearly a lifetime.  The computational complexity of training has been offset by recent technological advances, but the cost of training data is measured in terms of the human effort in labeling data. People are not getting faster nor cheaper, so generating labeled training datasets has become a major bottleneck in ML pipelines. 
> 
>Active ML aims to address this issue by designing learning algorithms that automatically and adaptively select the most informative examples for labeling so that human time is not wasted labeling irrelevant, redundant, or trivial examples. This talk explores the development of active ML theory and methods over the past decade, including a new approach applicable to kernel methods and neural networks, which views the learning problem through the lens of representer theorems. This perspective highlights the effect that adding a given training example has on the representation.   The new approach is shown to possess a variety of desirable mathematical properties that allow active learning algorithms to learn good classifiers from few labeled examples.

**[Yejin Choi](https://homes.cs.washington.edu/~yejin/),** _University of Washington_.
>**Adversarial, Socially Aware, and Commonsensical Data**

## Call For Papers <a name="cfp"></a>
We are accepting submissions no longer than _four pages (plus references)_, in [NeurIPS 2020 format](https://neurips.cc/Conferences/2020/PaperInformation/StyleFiles). We ask that submissions are anonymized as the review process is _double blind_. <!-- We will not accept work that has been previously included in conference proceedings. -->

The submission deadline is ~~Sunday October 11th, 2020~~ Thursday, October 15th, 2020 anywhere on Earth. Submission link: [CMT site](https://cmt3.research.microsoft.com/WDCS2020). If you experience any problems with the submission site, please email Michael Curry (<curry@cs.umd.edu>).

## Organizers
**Nathalie Baracaldo,** _IBM_. leads the AI Security and Privacy Solutions team and is a Research Staff Member at IBM’s Almaden Research Center in San Jose, CA. Nathalie is focused on designing machine learning solutions that are accurate while withstanding adversarial attacks and protecting data privacy.

**Yonatan Bisk,** _Carnegie Mellon University_. is an Assistant Professor of Computer Science at Carnegie Mellon University in Language Technologies Institute. His work focuses on grounded and multimodal language representations and publishes regularly across the language, computer vision, robotics and machine learning community.

**Avrim Blum,** _TTIC_. is Professor and Chief Academic Officer at the Toyota Technological Institute at Chicago (TTIC); prior to this he was on the faculty at Carnegie Mellon University for 25 years.  His main research interests are in Machine Learning Theory, Algorithmic Game Theory, Privacy, and Algorithmic Fairness.

**Michael J. Curry,** _University of Maryland_. is a PhD student in the Computer Science department at the University of Maryland. He is co-advised by John Dickerson and Tom Goldstein on research in resource allocation, mechanism design, and adversarial robustness.

**John P. Dickerson,** _University of Maryland_. is an Assistant Professor of Computer Science at the University of Maryland and co-founder and Chief Scientist of Arthur AI, an enterprise-focused AI/ML model monitoring company.

**Micah Goldblum,** _University of Maryland_.  is a postdoctoral researcher, advised by Tom Goldstein, in computer science at the University of Maryland.  He works on security in AI as well as ML in the data-scarce regime. 

**Tom Goldstein,** _University of Maryland_. is the Perotto Associate Professor of Machine Learning in the Department of Computer Science at University of Maryland. His research lies at the intersection of machine learning and optimization, and focuses on safety and security for autonomous systems.

**Bo Li,** _University of Illinois at Urbana-Champaign_. is an assistant professor in Computer Science at the University of Illinois at Urbana-Champaign. Her research focuses on machine learning, security, privacy, game theory, social networks, and adversarial deep learning. She has designed several robust learning algorithms, scalable frameworks for achieving robustness for a range of learning methods, and privacy preserving data publishing systems.

**Avi Schwarzschild,** _University of Maryland_. Avi is a PhD student in the Applied Math and Scientific Computation program at the University of Maryland. He is advised by Tom Goldstein on his work in AI security, relating to data security and model vulnerability.

## Accepted Papers
**Backdoor attacks on the DNN Interpretation System** Shihong Fang (NYU Tandon), Anna Choromanska (NYU): [camera ready](./camera_ready/2.pdf)

**Assessing Perceptual and Recommendation Mutation of Adversarially-Poisoned Visual Recommenders** Vito Walter Anelli (Polytechnic University of Bari), Tommaso Di Noia (Politecnico di Bari), Daniele Malitesta (Polytechnic University of Bari), Felice Antonio Merra (Politecnico di Bari): [camera ready](./camera_ready/3.pdf)

**Which Strategies Matter for Label Noise? Insight into Loss and Uncertainty** Wonyoung Shin (Naver Shopping, NAVER Corp.), Jung-Woo Ha (NAVER AI, NAVER Corp.), Shengzhe Li (Naver Shopping, NAVER Corp.), Yongwoo Cho (Naver Shopping, NAVER Corp.), Hoyean Song (Self-employed), Sunyoung Kwon (Pusan National University): [camera ready](./camera_ready/5.pdf)

**Similarity Search for Efficient Active Learning and Search of Rare Concepts** Cody Coleman (Stanford), Edward Chou (Facebook), Sean Culatana (Facebook), Peter Bailis (Stanford University), Alexander Berg (University of North Carolina, USA), Roshan Sumbaly (Facebook), Matei Zaharia (Stanford and Databricks), Zeki Yalniz (Facebook): [camera ready](./camera_ready/6.pdf)

**LowKey: Leveraging Adversarial Attacks to Protect Social Media Users from Facial Recognition** Valeriia Cherepanova (University of Maryland), Micah Goldblum (University of Maryland), Harrison Foley (US Naval Academy), Shiyuan Duan (University of Maryland), John Dickerson (University of Maryland), Gavin Taylor (US Naval Academy), Tom Goldstein (University of Maryland, College Park): [camera ready](./camera_ready/8.pdf)

**Just How Toxic is Data Poisoning? A Benchmark for Backdoor and Data Poisoning Attacks** Avi Schwarzschild (University of Maryland), Micah Goldblum (University of Maryland), Arjun Gupta (University of Maryland College Park), John Dickerson (University of Maryland), Tom Goldstein (University of Maryland, College Park): [camera ready](./camera_ready/10.pdf)

**PrivFramework: A System for Configurable and Automated Privacy Policy Compliance** Usmann Khan (Georgia Institute of Technology), Lun Wang (University of California, Berkeley), Joseph Near (University of Vermont), Dawn Song (UC Berkeley): [camera ready](./camera_ready/12.pdf)

**Backdoor Attacks to Graph Neural Networks** Zaixi Zhang (Duke University), Jinyuan Jia (Duke University ), Binghui Wang (Duke University), Neil Zhenqiang Gong (Duke University): [camera ready](./camera_ready/13.pdf)

**Open-sourced Dataset Protection via Backdoor Watermarking** Yiming Li (Tsinghua University), Ziqi Zhang (Tsinghua University), Jiawang Bai (Tsinghua University), Baoyuan Wu (The Chinese University of Hong Kong, Shenzhen, Shenzhen Research Institute of Big Data), Yong Jiang (Tsinghua University), Shutao Xia (Tsinghua University): [camera ready](./camera_ready/14.pdf)

**Interpolating noisy datasets hurts adversarial robustness** Amartya Sanyal (University of Oxford), Puneet Dokania (University of Oxford), Varun Kanade (University of Oxford), Philip Torr (University of Oxford): [camera ready](./camera_ready/15.pdf)

**Stealthy Poisoning Attack on Certified Robustness** Akshay Mehra (Tulane University), Bhavya Kailkhura (Lawrence Livermore National Laboratory), Pin-Yu Chen (IBM Research AI), Jihun Hamm (Tulane University): [camera ready](./camera_ready/16.pdf)

**Provably Robust Defenses against Data Poisoning Attacks via Ensemble Methods** Jinyuan Jia (Duke University ), Xiaoyu Cao (Duke University), Neil Zhenqiang Gong (Duke University): [camera ready](./camera_ready/17.pdf)

**Evaluating Gender Bias in Natural Language Inference** Shanya Sharma (Walmart Labs), Manan Dey (SAP LABS), Koustuv Sinha (McGill University): [camera ready](./camera_ready/19.pdf)

**GARFD: Gradient-based AutoRegressive Forecaster Defense** Mackenzie Stein (Amherst College), Scott Alfeld (Amherst College): [camera ready](./camera_ready/22.pdf)

**Dataset Inference: Ownership Resolution in Machine Learning** Pratyush Maini (IIT Delhi), Mohammad Yaghini (University of Toronto), Nicolas Papernot (University of Toronto and Vector Institute): [camera ready](./camera_ready/23.pdf)

**Differential Privacy with Mixup** Eitan Borgnia (University of Maryland), Micah Goldblum (University of Maryland), Tom Goldstein (University of Maryland, College Park): [camera ready](./camera_ready/25.pdf)

**The Dataset Nutrition Label (2nd Gen): LeveragingContext to Mitigate Harms in Artificial Intelligence** Kasia Chmielinski (Berkman Klein Center at Harvard University), Sarah Newman (metaLAB/Berkman Klein Center, Harvard University), Matt Taylor (Data Nutrition Project), Josh Joseph (MIT), Kemi Thomas (Data Nutrition Project), Jessica Yurkofsky (Massachusetts College of Liberal Arts), Yue Chelsea Qiu (AIM Group International): [camera ready](./camera_ready/26.pdf)

**Ethical Testing in the Real World: Evaluating Physical Testing of Adversarial Machine Learning** Ram Shankar Siva Kumar (Microsoft (Azure Security), Berkman Klein Center for Internet and Society at Harvard University), Maggie Delano (Swarthmore College), Kendra Albert (Harvard Law School ), Afsaneh Rigot (ARTICLE 19), Jonathon Penney (Citizen Lab (University of Toronto) / Dalhousie / Princeton CITP): [camera ready](./camera_ready/27.pdf)

**Pervasive Label Errors in ML Benchmark Test Sets, Consequences, and Benefits** Curtis Northcutt (MIT), Anish Athalye (Massachusetts Institute of Technology), Jessy Lin (Berkeley): [camera ready](./camera_ready/28.pdf)

**Bait and Switch: Online Training Data Poisoning of Autonomous Driving Systems** Naman Patel (NYU), Prashanth Krishnamurthy (NYU Tandon School of Engineering), Siddharth Garg (New York University), Farshad khorrami (NYU): [camera ready](./camera_ready/31.pdf)

**Open4Business (O4B): An Open Access Dataset for Summarizing Business Documents** Singh Amanpreet (Stony Brook University), Niranjan Balasubramanian (stony brook): [camera ready](./camera_ready/32.pdf)

**Witches' Brew: Industrial Scale Data Poisoning via Gradient Matching** Jonas Geiping (University of Siegen), Liam Fowl (University of Maryland), W. Ronny Huang (Google Research), Wojciech Czaja (University of Maryland, College Park), Gavin Taylor (US Naval Academy), Michael Moeller (University of Siegen), Tom Goldstein (University of Maryland, College Park): [camera ready](./camera_ready/34.pdf)

**MetaPoison: Practical General-purpose Clean-label Data Poisoning** W. Ronny Huang (Google Research), Jonas Geiping (University of Siegen), Liam Fowl (University of Maryland), Gavin Taylor (US Naval Academy), Tom Goldstein (University of Maryland, College Park): [camera ready](./camera_ready/35.pdf)

**Measuring Bias with Wasserstein Distance** Mark Kwegyir-Aggrey (Brown University), Sarah Brown (Brown University): [camera ready](./camera_ready/37.pdf)

**Random Network Distillation as a Diversity Metric for Both Image and Text Generation** Liam Fowl (University of Maryland), Micah Goldblum (University of Maryland, College Park), Arjun Gupta (University of Maryland College Park), Amr Sharaf (University of Maryland), Tom Goldstein (University of Maryland, College Park): [camera ready](./camera_ready/39.pdf)

**On Evaluating Neural Network Backdoor Defenses** Akshaj Kumar Veldanda (New York University), Siddharth Garg (New York University): [camera ready](./camera_ready/40.pdf)

**Data Sharing in Wellness, Accessibility, and Aging** Hernisa Kacorri (University of Maryland, College Park), Utkarsh Dwivedi (University of Maryland, College Park), Rie Kamikubo (University of Maryland, College Park): [camera ready](./camera_ready/41.pdf)

**Data Valuation for Acoustic Models in Automatic Speech Recognition** Ali Syed (The Graduate Center, CUNY), Michael Mandel (Brooklyn College, CUNY): [camera ready](./camera_ready/42.pdf)

**A New Large-scale Video Dataset for Human Fall Detection** Anahita Shojaei (University of British Columbia), Panos Nasiopoulos (University of British Columbia), Mahsa Pourazad (TELUS): [camera ready](./camera_ready/44.pdf)


