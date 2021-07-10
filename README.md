# Awesome-Video-Datasets

* Contributions are most welcome, if you have any suggestions or improvements, please create an issue or raise a pull request. 
* Our group website: **[VIS Lab](https://ivi.fnwi.uva.nl/vislab/)**, University of Amsterdam. 

## Contents
 - [Action Recognition](ActionRecognition.md)
 - [Video Classification](VideoClassification.md)
 - [Egocentric View](EgocentricView.md)
 - [Video Object Segmentation](VideoObjectSegmentation.md)
 - [Object Detection](ObjectDetection.md)
 - [Group Activity Recognition](GroupActivityRecognition.md)
 - [Movie](Movie.md)
 - [Video Captioning](VideoCaptioning.md)
 - [360 Videos](360Videos.md)
 - [Activity Localization](ActivityLocalization.md)
 - [Video and Language](VideoandLanguage.md)
 - [Video Question Answering](VideoQuestionAnswering.md)
 - [Action Segmentation](#Action-Segmentation)
 - [Repetition Counting](#Repetition-Counting)
 - [Audiovisual Learning](#Audiovisual-Learning)
 - [Video Indexing](#Video-Indexing)
 - [Skill Determination](#Skill-Determination)
 - [Video Retrieval](#Video-Retrieval)
 - [Single Object Tracking](#Single-Object-Tracking)
 - [Multiple Objects Tracking](#Multiple-Objects-Tracking)
 - [Video Relation Detection](#Video-Relation-Detection)
 - [Anomaly Detection](#Anomaly-Detection)
 - [Video Memorability](#Video-Memorability)
 - [Highlight Detection](#Highlight-Detection)
 - [Pose Estimation](#Pose-Estimation)
 - [Animal Behavior](#Animal-Behavior)
 - [Person Re-identification](#Person-Re-Identification)
 - [Dynamic Texture Classification](DynamicTextureClassification.md)
 - [Physics](#Physics)


## Highlight Detection
* **YouTube Highlights**: Ranking Domain-specific Highlights by Analyzing Edited Videos</br>
[[Paper](http://grail.cs.washington.edu/wp-content/uploads/2015/08/sun2014rdh.pdf)][[Homepage](https://github.com/aliensunmin/DomainSpecificHighlight)] </br>
*six domain-specific categories: surfing, skating, skiing, gymnastics, parkour, and dog. Each domain consists of around 100 videos and the total accumulated time is 1430 minutes*

* **PHD<sup>2</sup>**: Personalized Highlight Detection for Automatic GIF Creation </br>
[[Paper](https://arxiv.org/abs/1804.06604)][[Homepage](https://github.com/gifs/personalized-highlights-dataset)] </br>
*the training set contains highlights from 12,972 users, the test set contains highlights from 850 users*

* **TVSum**: Summarizing web videos using titles (CVPR 2015) </br>
[[Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Song_TVSum_Summarizing_Web_2015_CVPR_paper.pdf)][[Homepage](https://github.com/yalesong/tvsum)] </br>
*50 videos of various genres (e.g., news, how-to, documentary, vlog, egocentric) and 1,000 annotations of shot-level importance scores obtained via crowdsourcing (20 per video)*

## Video Memorability

* **Video Memorability**: Multimodal Memorability: Modeling Effects of Semantics and Decay on Video Memorability (ECCV 2020) </br>
[[Paper](https://arxiv.org/pdf/2009.02568.pdf)][[Homepage](http://memento.csail.mit.edu/)] </br>
*10,000 video clips, over 900,000 human memory annotations at different delay intervals and 50,000 captions describing the events*

## Pose Estimation
* **YouTube Pose**: Personalizing Human Video Pose Estimation (CVPR 2016) </br>
[[Paper](https://arxiv.org/pdf/1511.06676.pdf)][[Homepage](https://www.robots.ox.ac.uk/~vgg/data/pose/index.html)] </br>
*50 videos, 5,000 annotated frames*

* **JHMDB**: Towards understanding action recognition (ICCV 2013) </br>
[[Paper](http://jhmdb.is.tue.mpg.de/show_file?filename=JHMDB_ICCV_2013_corrected.pdf)][[Homepage](http://jhmdb.is.tue.mpg.de/)] </br>
*5,100 clips of 51 different human actions collected from movies or the Internet, 31,838 annotated frames in total*

* **Penn Action**: From Actemes to Action: A Strongly-supervised Representation for Detailed Action Understanding (ICCV 2013) </br>
[[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Zhang_From_Actemes_to_2013_ICCV_paper.pdf)][[Homepage](http://dreamdragon.github.io/PennAction/)] </br>
*2,326 video sequences of 15 different actions and human joint annotations for each sequence*

* **PoseCNN**: A Convolutional Neural Network for 6D Object Pose Estimation in Cluttered Scenes (RSS 2018) </br>
[[Paper](https://arxiv.org/abs/1711.00199)][[Homepage](https://rse-lab.cs.washington.edu/projects/posecnn/)] </br>
*accurate 6D poses of 21 objects from the YCB dataset observed in 92 videos with 133,827 frames*

## Animal Behavior
* **Edinburgh Pig Behavior**: Extracting Accurate Long-Term Behavior Changes from a Large Pig Dataset </br>
[[Paper](https://homepages.inf.ed.ac.uk/rbf/PAPERS/pigsbehaviouranalysis_visapp2021.pdf)][[Homepage](https://homepages.inf.ed.ac.uk/rbf/PIGDATA/)] </br>
*23 days (over 6 weeks) of daytime pig video captured from a nearly overhead camera, 6 frames per second, and stored in batches of 1800 frames (5 minutes), most frames show 8 pigs*

## Person Re-identification
* **iLIDS-VID**: Person re-identification by video ranking (ECCV 2014) </br>
[[Paper](https://core.ac.uk/download/pdf/208789091.pdf)][[Homepage](https://xiatian-zhu.github.io/downloads_qmul_iLIDS-VID_ReID_dataset.html)] </br>
*600 image sequences of 300 distinct individuals*

* **PRID-2011**: Person Re-identification by Descriptive and Discriminative Classification </br>
[[Paper](https://link.springer.com/content/pdf/10.1007%2F978-3-642-21227-7_9.pdf)][[Homepage](https://www.tugraz.at/institute/icg/research/team-bischof/lrs/downloads/prid11/)]</br>
*400 image sequences for 200 identities from two non-overlapping cameras*

* **MARS**:  A Video Benchmark for Large-Scale Person Re-Identification (ECCV 2016) </br>
[[Paper](https://link.springer.com/content/pdf/10.1007%2F978-3-319-46466-4_52.pdf)][[Homepage](http://zheng-lab.cecs.anu.edu.au/Project/project_mars.html)] </br>
*1,261 identities around 18,000 video sequences*

## Physics
* **Real-world Flag & FlagSim**: Cloth in the Wind: A Case Study of Physical Measurement through Simulation (CVPR 2020) </br>
[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Runia_Cloth_in_the_Wind_A_Case_Study_of_Physical_Measurement_CVPR_2020_paper.pdf)][[Homepage](http://tomrunia.github.io/projects/cloth/)] </br>
*Real-world Flag: 2.7K train and 1.3K videos clips, FlagSim: 1,000 mesh sequences, 14, 000 training examples*

* **Physics 101**: Learning Physical Object Properties from Unlabeled Videos (BMVC 2016) </br>
[[Paper](http://phys101.csail.mit.edu/papers/phys101_bmvc.pdf)][[Homepage](http://phys101.csail.mit.edu/)] </br>
*over 10,000 video clips containing 101 objects of various materials and appearances (shapes, colors, and sizes)*

* **CLEVRER**: Collision Events for Video Representation and Reasoning (ICLR 2020) </br>
[[Paper](https://arxiv.org/pdf/1910.01442.pdf)][[Homepage](http://clevrer.csail.mit.edu/)] </br>
*10,000 videos for training, 5,000 for validation, and 5,000 for testing; all videos last for 5 seconds; the videos are generated by a physics engine that simulates object motion plus a graphs engine that renders the frames*
