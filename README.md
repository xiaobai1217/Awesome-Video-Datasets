# Awesome-Video-Datasets

* Contributions are most welcome, if you have any suggestions or improvements, please create an issue or raise a pull request. 
* Our group website: **[VIS Lab](https://ivi.fnwi.uva.nl/vislab/)**, University of Amsterdam. 

## Contents
 - [Action Recognition](#Action-Recognition)
 - [Video Classification](#Video-Classification)
 - [Egocentric View](#Egocentric-View)
 - [Video Object Segmentation](#Video-Object-Segmentation)
 - [Object Detection](#Object-Detection)
 - [Group Activity Recognition](#Group-Activity-Recognition)
 - [Movie](#Movie)
 - [Video Captioning](#Video-Captioning)
 - [360 Videos](#360-Videos)
 - [Activity Localization](#Activity-Localization)
 - [Video and Language](#Video-and-Language)
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
 - [Pose Estimation](#Pose-Estimation)
 - [Dynamic Texture Classification](#Dynamic-Texture-Classification)
 - [Physics](#Physics)


## Action Recognition

* **HOLLYWOOD2**: Actions in Context (CVPR 2009) </br>
[[Paper](http://www.irisa.fr/vista/Papers/2009_cvpr_marszalek.pdf)][[Homepage](https://www.di.ens.fr/~laptev/actions/hollywood2/)]</br>
*12 classes of human actions, 10 classes of scenes, 3,669 clips, 69 movies*

* **HMDB**: A Large Video Database for Human Motion Recognition (ICCV 2011)</br> 
[[Paper](https://serre-lab.clps.brown.edu/wp-content/uploads/2012/08/Kuehne_etal_iccv11.pdf)][[Homepage](https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/)]</br>
*51 classes, 7,000 clips*

* **UCF101**: A Dataset of 101 Human Actions Classes From Videos in The Wild </br> 
[[Paper](https://www.crcv.ucf.edu/papers/UCF101_CRCV-TR-12-01.pdf)][[Homepage](https://www.crcv.ucf.edu/data/UCF101.php)]</br> 
*101 classes, 13k clips*

* **Sports-1M**: Large-scale Video Classification with Convolutional Neural Networks </br>
[[Paper](https://cs.stanford.edu/people/karpathy/deepvideo/deepvideo_cvpr2014.pdf)][[Homepage](https://cs.stanford.edu/people/karpathy/deepvideo/)]</br>
*1,000,000 videos, 487 classes*

* **ActivityNet**: A Large-Scale Video Benchmark for Human Activity Understanding (CVPR 2015)</br> 
[[Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Heilbron_ActivityNet_A_Large-Scale_2015_CVPR_paper.pdf)][[Homepage](http://activity-net.org/index.html)]</br>
*203 classes, 137 untrimmed videos per class, 1.41 activity instances per video*

* **MPII-Cooking**: Recognizing Fine-Grained and Composite Activities Using Hand-Centric Features and Script Data (IJCV 2015) </br>
[[Paper](https://link.springer.com/content/pdf/10.1007/s11263-015-0851-8.pdf)][[Homepage](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/human-activity-recognition/mpii-cooking-2-dataset/)] </br>
*67 fine-grained activities, 59 composite activities, 14,105 clips, 273 videos*

* **Kinetics** </br>
[[Kinetics-400](https://arxiv.org/abs/1705.06950)/[Kinetics-600](https://arxiv.org/abs/1808.01340)/[Kinetics-700](https://arxiv.org/abs/1907.06987)/[Kinetics-700-2020](https://arxiv.org/pdf/2010.10864.pdf)] [[Homepage](https://deepmind.com/research/open-source/kinetics)]</br>
*400/600/700/700 classes, at least 400/600/600/700 clips per class*

* **Charades**: Hollywood in Homes: Crowdsourcing Data Collection for Activity Understanding (ECCV 2016)</br> 
[[Paper](http://ai2-website.s3.amazonaws.com/publications/hollywood-homes.pdf)][[Homepage](https://prior.allenai.org/projects/charades)]</br>
*9,848 annotated videos, 267 people, 27,847 video descriptions, 66,500 temporally localized intervals for 157 action classes and
41,104 labels for 46 object classes*

* **Charades-Ego**: Actor and Observer: Joint Modeling of First and Third-Person Videos (CVPR 2018) </br> 
[[Paper](https://arxiv.org/pdf/1804.09627.pdf)][[Homepage](https://prior.allenai.org/projects/charades-ego)]</br>
*112 people, 4000 paired videos, 157 action classes*

* **20BN-jester**: The Jester Dataset: A Large-Scale Video Dataset of Human Gestures (ICCVW 2019) </br>
[[Paper](https://openaccess.thecvf.com/content_ICCVW_2019/papers/HANDS/Materzynska_The_Jester_Dataset_A_Large-Scale_Video_Dataset_of_Human_Gestures_ICCVW_2019_paper.pdf)][[Homepage](https://20bn.com/datasets/jester)] </br>
*148,092 videos, 27 classes, 1376 actors*

* **Moments in Time Dataset**: one million videos for event understanding (TPAMI 2019) </br> 
[[Paper](http://moments.csail.mit.edu/TPAMI.2019.2901464.pdf)][[Homepage](http://moments.csail.mit.edu/)]</br>
*over 1,000,000 labelled videos for 339 Moment classes, the average number of labeled videos per class is 1,757 with a median of 2,775*

* **Multi-Moments in Time**: Learning and Interpreting Models for Multi-Action Video Understanding </br> 
[[Paper](https://arxiv.org/pdf/1911.00232.pdf)][[Homepage](http://moments.csail.mit.edu/)]</br>
*1.02 million videos, 313 action classes, 553,535 videos are annotated with more than one label and 257,491 videos are annotated with three or more labels*

* **20BN-SOMETHING-SOMETHING**: The "something something" video database for learning and evaluating visual common sense </br> 
[[Paper](https://arxiv.org/abs/1706.04261)][[Homepage](https://20bn.com/datasets/something-something)]</br>
*100,000 videos across 174 classes*

* **EPIC-KITCHENS**: Scaling Egocentric Vision: The EPIC-KITCHENS Dataset (ECCV 2018, extended into TPAMI 2020)</br> 
[[Paper](https://arxiv.org/abs/2006.13256)][[Homepage](https://epic-kitchens.github.io/2021)]</br>
*100 hours, 37 participants, 20M frames, 90K action segments, 700 variable length videos, 97 verb classes, 300 noun classes, 4053 action classes*

* **HOMAGE**: Home Action Genome: Cooperative Compositional Action Understanding (CVPR 2021) </br> 
[[Paper]()][[Homepage](https://homeactiongenome.org/)]</br> 
*27 participants, 12 sensor types, 75 activities, 453 atomic actions, 1,752 synchronized sequences, 86 object classes, 29 relationship classes, 497,534 bounding boxes, 583,481 relationships*

* **MMAct**: A Large-Scale Dataset for Cross Modal Human Action Understanding (ICCV 2019) </br> 
[[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Kong_MMAct_A_Large-Scale_Dataset_for_Cross_Modal_Human_Action_Understanding_ICCV_2019_paper.pdf)][[Homepage](https://mmact19.github.io/2019/)]</br>
*36k video clips, 37 action classes, RGB+Keypoints+Acc+Gyo+Ori+Wi-Fi+Presure*

* **LEMMA**: A Multi-view Dataset for LEarning Multi-agent Multi-task Activities (ECCV 2020) </br> 
[[Paper](https://arxiv.org/pdf/2007.15781.pdf)][[Homepage](https://sites.google.com/view/lemma-activity)]</br>
*RGB-D, 641 action classes, 11,781 action segments, 4.6M frames*

* **NTU RGB+D**: A Large Scale Dataset for 3D Human Activity Analysis (CVPR 2016, TPAMI 2019) </br>
[[Paper](https://arxiv.org/abs/1604.02808)][[Homepage](http://rose1.ntu.edu.sg/Datasets/actionRecognition.asp)] </br>
*106 distinct subjects and contains more than 114 thousand video samples and 8 million frames, 120 action classes*

* **Action Genome**: Actions as Compositions of Spatio-temporal Scene Graphs (CVPR 2020) </br> 
[[Paper](https://arxiv.org/pdf/1912.06992.pdf)][[Homepage](https://www.actiongenome.org/)]</br>
*10K videos, 0.4M objects, 1.7M visual relationships*

* **TITAN**: Future Forecast using Action Priors (CVPR 2020) </br> 
[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Malla_TITAN_Future_Forecast_Using_Action_Priors_CVPR_2020_paper.pdf)][[Homepage](https://usa.honda-ri.com/titan)]</br>
*700 labeled video-clips, 50 labels including vehicle states and actions, pedestrian age groups, and targeted pedestrian action attributes*

* **PKU-MMD**: A Large Scale Benchmark for Continuous Multi-Modal Human Action Understanding (ACM Multimedia Workshop) </br> 
[[Paper](https://arxiv.org/abs/1703.07475)][[Homepage](https://github.com/ECHO960/PKU-MMD#pku-mmd-a-large-scale-benchmark-for-continuous-multi-modal-human-action-understanding)]</br>
*1,076 long video sequences, 51 action categories, performed by 66 subjects in three camera views, 20,000 action instances, 5.4 million frames, RGB+depth+Infrared Radiation+Skeleton*

* **HACS**: Human Action Clips and Segments Dataset for Recognition and Temporal Localization </br>
[[Paper](https://arxiv.org/pdf/1712.09374.pdf)][[Homepage](http://hacs.csail.mit.edu/)]</br>
*HACS Clips: 1.5M annotated clips sampled from 504K untrimmed videos, HACS Segments: 139K action segments densely annotated in 50K untrimmed videos spanning 200 action categories*

* **Oops!**: Predicting Unintentional Action in Video (CVPR 2020) </br>
[[Paper](https://arxiv.org/pdf/1911.11206.pdf)][[Homepage](https://oops.cs.columbia.edu/)] </br>
*20,338 videos, 7,368 annotated for training, 6,739 annotated for testing*

* **RareAct**: A video dataset of unusual interactions </br>
[[Paper](https://arxiv.org/pdf/2008.01018.pdf)][[Homepage]()]</br>
*122 different actions, 7,607 clips, 905 videos, 19 verbs, 38 nouns*

* **FineGym**: A Hierarchical Video Dataset for Fine-grained Action Understanding (CVPR 2020) </br>
[[Paper](https://arxiv.org/pdf/2004.06704.pdf)][[Homepage](https://sdolivia.github.io/FineGym/)] </br>
*10 event categories, including 6 male events and 4 female events, 530 element categories*

* **THUMOS**: The THUMOS challenge on action recognition for videos “in the wild” </br>
[[Paper](https://www.crcv.ucf.edu/papers/thumosCVIU.pdf)][[Homepage](http://crcv.ucf.edu/THUMOS14/)] </br>
*101 actions, train: 13,000 temporally trimmed videos, validation: 2100 temporally untrimmed videos with temporal annotations of actions, background: 3000 relevant videos, test: 5600 temporally untrimmed videos with withheld ground truth*

* **MultiTHUMOS**: Every Moment Counts: Dense Detailed Labeling of Actions in Complex Videos (IJCV 2017) </br>
[[Paper](https://arxiv.org/pdf/1507.05738.pdf)][[Homepage](http://ai.stanford.edu/~syyeung/everymoment.html)] </br>
*400 videos, 38,690 annotations of 65 action classes, 10.5 action classes per video*

* **Hierarchical Action Search**: Searching for Actions on the Hyperbole (CVPR 2020) </br>
[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Long_Searching_for_Actions_on_the_Hyperbole_CVPR_2020_paper.pdf)][[Homepage](https://github.com/Tenglon/hyperbolic_action)] </br>
*Hierarchical-ActivityNet, Hierarchical-Kinetics, and Hierarchical-Moments from ActivityNeg, mini-Kinetics, and Moments-in-time; provide action
hierarchies and action splits for unseen action search*

## Video Classification
* **COIN**: A Large-scale Dataset for Comprehensive Instructional Video Analysis (CVPR 2019) </br>
[[Paper](https://arxiv.org/pdf/1903.02874.pdf)][[Homepage](https://coin-dataset.github.io/)] </br>
*11,827 videos, 180 tasks, 12 domains, 46,354 annotated segments*

* **Youtube-8M**: A Large-Scale Video Classification Benchmark </br>
[[Paper](https://arxiv.org/pdf/1609.08675.pdf)][[Homepage](https://research.google.com/youtube8m/index.html)]</br>
*8,000,000 videos, 4000 visual entities*

* **HVU**: Large Scale Holistic Video Understanding (ECCV 2020) </br>
[[Paper](https://arxiv.org/pdf/1904.11451.pdf)][[Homepage](https://holistic-video-understanding.github.io/)] </br>
*572k videos in total with 9 million annotations for training, validation and test set spanning over 3142 labels, semantic aspects defined on categories of scenes, objects, actions, events, attributes and concepts*

* **VLOG**: From Lifestyle Vlogs to Everyday Interactions (CVPR 2018) </br>
[[Paper](https://web.eecs.umich.edu/~fouhey//2017/VLOG/paper.pdf)][[Homepage](https://web.eecs.umich.edu/~fouhey//2017/VLOG/index.html)] </br>
*114K video clips, 10.7K participants, Annotations: Hand/Semantic Object, Hand Contact State, Scene Classification*

* **EEV**: A Large-Scale Dataset for Studying Evoked Expressions from Video </br> 
[[Paper](https://arxiv.org/abs/2001.05488)][[Homepage](https://github.com/google-research-datasets/eev)]</br>
*Each video is annotated at 6 Hz with 15 continuous evoked expression labels, 36.7 million annotations of viewer facial reactions to 23,574 videos (1,700 hours)*

## Egocentric View
* **Charades-Ego**: Actor and Observer: Joint Modeling of First and Third-Person Videos (CVPR 2018) </br> 
[[Paper](https://arxiv.org/pdf/1804.09627.pdf)][[Homepage](https://prior.allenai.org/projects/charades-ego)]</br>
*112 people, 4000 paired videos, 157 action classes*

* **EPIC-KITCHENS**: Scaling Egocentric Vision: The EPIC-KITCHENS Dataset (ECCV 2018, extended into TPAMI 2020)</br> 
[[Paper](https://arxiv.org/abs/2006.13256)][[Homepage](https://epic-kitchens.github.io/2021)]</br>
*100 hours, 37 participants, 20M frames, 90K action segments, 700 variable length videos, 97 verb classes, 300 noun classes, 4053 action classes*

* **HOMAGE**: Home Action Genome: Cooperative Compositional Action Understanding (CVPR 2021) </br> 
[[Paper]()][[Homepage](https://homeactiongenome.org/)]</br> 
*27 participants, 12 sensor types, 75 activities, 453 atomic actions, 1,752 synchronized sequences, 86 object classes, 29 relationship classes, 497,534 bounding boxes, 583,481 relationships*

## Video Object Segmentation
* **DAVIS**: A Benchmark Dataset and Evaluation Methodology for Video Object Segmentation (CVPR 2016) </br>
[[Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Perazzi_A_Benchmark_Dataset_CVPR_2016_paper.pdf)][[Homepage](https://davischallenge.org/)]</br>
*50 sequences, 3455 annotated frames*

* **SegTrack v2**: Video Segmentation by Tracking Many Figure-Ground Segments (ICCV 2013) </br>
[[Paper](https://web.engr.oregonstate.edu/~lif/SegTrack2/segtrack2_cameraready.pdf)][[Homepage](https://web.engr.oregonstate.edu/~lif/SegTrack2/dataset.html)] </br>
*1,000 frames with pixel-level annotations*

* **UVO**: Unidentified Video Objects: A Benchmark for Dense, Open-World Segmentation </br>
[[Paper](https://arxiv.org/pdf/2104.04691.pdf)][[Homepage]()] </br>
*1200 videos, 108k frames, 12.29 objects per video*

## Object Detection
* **ImageNet VID** </br>
[[Paper](https://link.springer.com/article/10.1007/s11263-015-0816-y?sa_campaign=email/event/articleAuthor/onlineFirst#)][[Homepage](https://image-net.org/challenges/LSVRC/2017/#vid)] </br>
*30 categories, train: 3,862 video snippets, validation: 555 snippets*

* **YouTube-BoundingBoxes**: A Large High-Precision Human-Annotated Data Set for Object Detection in Video </br>
[[Paper](https://arxiv.org/pdf/1702.00824.pdf)][[Homepage](https://research.google.com/youtube-bb/index.html)] </br>
*380,000 video segments about 19s long, 5.6 M bounding boxes, 23 types of objects*

* **Water** detection through spatio-temporal invariant descriptors </br>
[[Paper](https://reader.elsevier.com/reader/sd/pii/S1077314216300273?token=15C6210A029F5035AAA3E48B5EB4390911C8EE0BC8175787833DDB8CC63687EEBAFDA2275BAAD2F95ABC94F6E0EFDACB&originRegion=eu-west-1&originCreation=20210505160917)][[Dataset](http://isis-data.science.uva.nl/mettes/VideoWaterDatabase.tar.gz)] </br>
*260 videos*

## Dynamic Texture Classification
* **Dynamic Texture**: A New Large Scale Dynamic Texture Dataset with Application to ConvNet Understanding (ECCV 2018) </br>
[[Paper](http://vision.eecs.yorku.ca/publications/HadjiWildesECCV2018.pdf)][[Homepage](http://www.cse.yorku.ca/~hadjisma/dtdb_website/dtdb_paper.html)] </br>
*over 10,000 videos*

* **YUVL**: Spacetime Texture Representation and Recognition Based on a Spatiotemporal Orientation Analysis (TPAMI 2012) </br>
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6072218)][[Homepage](http://vision.eecs.yorku.ca/research/spacetime-texture.shtml)][[Dataset](http://www.cse.yorku.ca/vision/research/spacetime-texture-data/)] </br>
*610 spacetime texture samples*

* **UCLA**: Dynamic Texture Recognition (CVPR 2001) </br>
[[Paper](http://vision.csee.wvu.edu/~doretto/publications/saisanDWS01cvpr.pdf)][[Dataset](https://drive.google.com/file/d/0BxMIVlhgRmcbN3pRa0dyaHpHV1E/view)] </br>
*76 dynamic textures*

## Group Activity Recognition
* **Volleyball**: A Hierarchical Deep Temporal Model for Group Activity Recognition </br>
[[Paper](https://arxiv.org/pdf/1511.06040.pdf)][[Homepage](https://github.com/mostafa-saad/deep-activity-rec)] </br>
*4,830 clips, 8 group activity classes, nine individual actions*

* **Collective**: What are they doing? : Collective activity classification using spatio-temporal relationship among people </br>
[[Paper](http://vhosts.eecs.umich.edu/vision//paper/Wongun_CollectiveActivityRecognition09.pdf)][[Homepage](http://vhosts.eecs.umich.edu/vision//activity-dataset.html)] </br>
*5 different collective activities, 44 clips* 

## Movie
* **HOLLYWOOD2**: Actions in Context (CVPR 2009) </br>
[[Paper](http://www.irisa.fr/vista/Papers/2009_cvpr_marszalek.pdf)][[Homepage](https://www.di.ens.fr/~laptev/actions/hollywood2/)]</br>
*12 classes of human actions, 10 classes of scenes, 3,669 clips, 69 movies*

* **MPII-MD**: A Dataset for Movie Description </br>
[[Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Rohrbach_A_Dataset_for_2015_CVPR_paper.pdf)][[Homepage](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/vision-and-language/mpii-movie-description-dataset/)] </br>
*94 videos, 68,337 clips, 68,375 descriptions*

* **MovieNet**: A Holistic Dataset for Movie Understanding (ECCV 2020) </br>
[[Paper](https://arxiv.org/pdf/2007.10937.pdf)][[Homepage](http://movienet.site/)] </br>
*1,100 movies, 1.1M characters with bounding boxes and identities, 42K scene boundaries, 2.5K aligned description sentences, 65K tags of place and action, and 92
K tags of cinematic style*

* **MovieQA**: Story Understanding Benchmark (CVPR 2016) </br>
[[Paper](http://movieqa.cs.toronto.edu/static/files/CVPR2016_MovieQA.pdf)][[Homepage](http://movieqa.cs.toronto.edu/home/#)]</br>
*14,944 questions, 408 movies*

* **MovieGraphs**: Towards Understanding Human-Centric Situations from Videos (CVPR 2018) </br>
[[Paper](https://arxiv.org/pdf/1712.06761.pdf)][[Homepage](http://moviegraphs.cs.toronto.edu/)] </br>
*7,637 movie clips, 51 movies, annotations: scene, situation, description, graph (Character, Attributes, Relationship, Interaction, Topic, Reason, Time stamp)*

* **Condensed Movies**: Story Based Retrieval with Contextual Embeddings (ACCV 2020) </br>
[[Paper](https://arxiv.org/pdf/2005.04208.pdf)][[Homepage](https://www.robots.ox.ac.uk/~vgg/research/condensed-movies/)] </br>
*33,976 captioned clips from 3,605 movies, 400K+ face-tracks, 8K+ labelled characters, 20K+ subtitles, densely pre-extracted features for each clip (RGB, Motion, Face, Subtitles, Scene)*

## 360 Videos
* **Pano2Vid**: Automatic Cinematography for Watching 360° Videos (ACCV 2016) </br>
[[Paper](http://vision.cs.utexas.edu/projects/Pano2Vid/accv2016-0327su.pdf)][[Homepage](http://vision.cs.utexas.edu/projects/Pano2Vid/)] </br>
*20 out of 86 360° videos have labels for testing; 9,171 normal videos captured by humans for inference in training; topics: Soccer, Mountain Climbing, Parade, and Hiking)*

* **Deep 360 Pilot**: Learning a Deep Agent for Piloting through 360◦ Sports Videos (CVPR 2017) </br>
[[Paper](https://arxiv.org/pdf/1705.01759.pdf)][[Homepage](https://aliensunmin.github.io/project/360video/)] </br>
*342 360° videos, topics: basketball, parkour, BMX, skateboarding, and dance*

* **YT-ALL**: Self-Supervised Generation of Spatial Audio for 360◦ Video (NeurIPS 2018) </br>
[[Paper](https://arxiv.org/pdf/1809.02587.pdf)][[Homepage](https://pedro-morgado.github.io/spatialaudiogen/)] </br>
*1,146 videos, half of the videos are live music performances*

* **YT360**:  Learning Representations from Audio-Visual Spatial Alignment (NeurIPS 2020) </br>
[[Paper](https://papers.nips.cc/paper/2020/file/328e5d4c166bb340b314d457a208dc83-Paper.pdf)][[Homepage](https://github.com/pedro-morgado/AVSpatialAlignment)] </br>
*topics: musical performances, vlogs, sports, and others*

## Activity Localization

* **Hollywood2Tubes**: Spot On: Action Localization from Pointly-Supervised Proposals </br>
[[Paper](https://isis-data.science.uva.nl/cgmsnoek/pub/mettes-pointly-eccv2016.pdf)][[Dataset](http://isis-data.science.uva.nl/mettes/hollywood2tubes.tar.gz)] </br>
*train: 823 videos,  1,026 action instances, 16,411 annotations; test: 884 videos, 1,086 action instances, 15,835 annotations*

* **DALY**: Human Action Localization with Sparse Spatial Supervision </br>
[[Paper](https://arxiv.org/pdf/1605.05197.pdf)][[Homepage](http://thoth.inrialpes.fr/daly/index.php)] </br>
*10 actions, 3.3M frames, 8,133 clips*

* **Action Completion**: A temporal model for Moment Detection (BMVC 2018) </br>
[[Paper](https://arxiv.org/pdf/1805.06749.pdf)][[Homepage](https://github.com/FarnooshHeidari/CompletionDetection)] </br>
*completion moments of 16 actions from three datasets: HMDB, UCF101, RGBD-AC*

* **RGBD-Action-Completion**: Beyond Action Recognition: Action Completion in RGB-D Data (BMVC 2016) </br>
[[Paper](https://dimadamen.github.io/ActionCompletion/ActionCompletion_BMVC2016.pdf)][[Homepage](https://data.bris.ac.uk/data/dataset/66qry08cv1fj1eunwxwob3fjz)] </br>
*414 complete/incomplete object interaction sequences, spanning six actions and captured using an RGB-D camera*

* **AVA**: A Video Dataset of Spatio-temporally Localized Atomic Visual Actions </br> 
[[Paper](https://arxiv.org/abs/1705.08421)][[Homepage](http://research.google.com/ava/)]</br>
*80 atomic visual actions in 430 15-minute video clips, 1.58M action labels with multiple labels per person occurring frequently*

* **AVA-Kinetics**: The AVA-Kinetics Localized Human Actions Video Dataset </br> 
[[Paper](https://arxiv.org/pdf/2005.00214.pdf)][[Homepage](http://research.google.com/ava/)]</br>
*230k clips, 80 AVA action classes*

* **HACS**: Human Action Clips and Segments Dataset for Recognition and Temporal Localization </br>
[[Paper](https://arxiv.org/pdf/1712.09374.pdf)][[Homepage](http://hacs.csail.mit.edu/)]</br>
*HACS Clips: 1.5M annotated clips sampled from 504K untrimmed videos, HACS Segments: 139K action segments densely annotated in 50K untrimmed videos spanning 200 action categories*

* **CommonLocalization**: Localizing the Common Action Among a Few Videos (ECCV 2020) </br>
[[Paper](https://isis-data.science.uva.nl/cgmsnoek/pub/yang-common-action-eccv2020.pdf)][[Homepage](https://github.com/PengWan-Yang/commonLocalization)] </br>
*few-shot common action localization, revised ActivityNet1.3 and Thumos14*

* **CommonSpaceTime**: Few-Shot Transformation of Common Actions into Time and Space (CVPR 2021) </br>
[[Paper](https://isis-data.science.uva.nl/cgmsnoek/pub/yang-common-time-space-cvpr2021.pdf)][[Homepage]()] </br>
*revised AVA and UCF101-24*

* **MUSES**: Multi-shot Temporal Event Localization: a Benchmark (CVPR 2021) </br> 
[[Paper](https://arxiv.org/pdf/2012.09434.pdf)][[Homepage](https://songbai.site/muses/)]</br>
*31,477 event instances, 716 video hours, 19 shots per instance, 176 shots per video, 25 categories, 3,697 videos*

* **MEVA**: A Large-Scale Multiview, Multimodal Video Dataset for Activity (WACV 2021) </br>
[[Paper](https://arxiv.org/pdf/2012.00914.pdf)][[Homepage](https://mevadata.org/)] </br>
*annotated 144 hours for 37 activity types, marking bounding boxes of actors and props, 38 RGB and thermal IR cameras*

* **TVSeries**: Online Action Detection (ECCV 2016) </br>
[[Paper](https://arxiv.org/pdf/1604.06506.pdf)][[Homepage](https://homes.esat.kuleuven.be/psi-archive/rdegeest/TVSeries.html)] </br>
*27 episodes from 6 popular TV series, 30 action classes, 6,231 action instances*

## Video Captioning
* **VideoStory**: A New Multimedia Embedding for Few-Example Recognition and Translation of Events </br>
[[Paper](https://isis-data.science.uva.nl/cgmsnoek/pub/habibian-videostory-mm2014.pdf)][[Homepage](https://ivi.fnwi.uva.nl/isis/mediamill/datasets/videostory.php)] </br>
*45,826 videos and their descriptions obtained by harvesting YouTube*

* **MSR-VTT**: A Large Video Description Dataset for Bridging Video and Language (CVPR 2016) </br>
[[Paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf)][[Homepage](https://www.microsoft.com/en-us/research/publication/msr-vtt-a-large-video-description-dataset-for-bridging-video-and-language/)] </br>
*10K web video clips, 200K clip-sentence pairs*

* **VaTeX**: A Large-Scale, High-Quality Multilingual Dataset for Video-and-Language Research (ICCV 2019) </br>
[[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_VaTeX_A_Large-Scale_High-Quality_Multilingual_Dataset_for_Video-and-Language_Research_ICCV_2019_paper.pdf)][[Homepage](https://eric-xw.github.io/vatex-website/download.html)] </br>
*41,250 videos, 825,000 captions in both English and Chinese, over 206,000 English-Chinese parallel translation pairs*

* **ActivityNet Captions**: Dense-Captioning Events in Videos (ICCV 2017) </br>
[[Paper](https://arxiv.org/pdf/1705.00754.pdf)][[Homepage](https://cs.stanford.edu/people/ranjaykrishna/densevid/)] </br>
*20k videos, 100k sentences*

* **ActivityNet Entities**: Grounded Video Description </br>
[[Paper](https://arxiv.org/pdf/1812.06587.pdf)][[Homepage](https://github.com/facebookresearch/ActivityNet-Entities)] </br>
*14,281 annotated videos, 52k video segments with at least one noun phrase annotated per segment, augment the ActivityNet Captions dataset with 158k bounding box*

* **VTW**: Title Generation for User Generated Videos (ECCV 2016) </br>
[[Paper](https://arxiv.org/pdf/1608.07068.pdf)][[Homepage](http://aliensunmin.github.io/project/video-language/index.html#VideoTitle)] </br>
*18100 video clips with an average of 1.5 minutes duration per clip*

* **Charades**: Hollywood in Homes: Crowdsourcing Data Collection for Activity Understanding (ECCV 2016)</br> 
[[Paper](http://ai2-website.s3.amazonaws.com/publications/hollywood-homes.pdf)][[Homepage](https://prior.allenai.org/projects/charades)]</br>
*9,848 annotated videos, 267 people, 27,847 video descriptions, 66,500 temporally localized intervals for 157 action classes and
41,104 labels for 46 object classes*

## Video and Language
* **Lingual OTB99 & Lingual ImageNet Videos**: Tracking by Natural Language Specification (CVPR 2017) </br>
[[Paper](https://isis-data.science.uva.nl/cgmsnoek/pub/li-tracking-language-cvpr2017.pdf)][[Homepage](https://github.com/QUVA-Lab/lang-tracker)] </br>
*natural language descriptions of the target object*

* **MPII-MD**: A Dataset for Movie Description </br>
[[Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Rohrbach_A_Dataset_for_2015_CVPR_paper.pdf)][[Homepage](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/vision-and-language/mpii-movie-description-dataset/)] </br>
*94 videos, 68,337 clips, 68,375 descriptions*

* **Narrated Instruction Videos**: Unsupervised Learning from Narrated Instruction Videos </br>
[[Paper](https://www.di.ens.fr/willow/research/instructionvideos/paper.pdf)][[Homepage](https://www.di.ens.fr/willow/research/instructionvideos/)] </br>
*150 videos, 800,000 frames, five tasks: Making a coffee, Changing car tire, Performing cardiopulmonary resuscitation (CPR), Jumping a
car and Repotting a plant*

* **YouCook**: A Thousand Frames in Just a Few Words: Lingual Description of Videos through Latent Topics and Sparse Object Stitching (CVPR 2013) </br>
[[Paper](https://web.eecs.umich.edu/~jjcorso/pubs/jcorso_CVPR2013_dpmtm.pdf)][[Homepage](https://web.eecs.umich.edu/~jjcorso/r/youcook/)] </br>
*88 YouTube cooking videos*

* **HowTo100M**: Learning a Text-Video Embedding by Watching Hundred Million Narrated Video Clips (ICCV 2019) </br>
[[Paper](https://arxiv.org/pdf/1906.03327.pdf)][[Homepage](https://www.di.ens.fr/willow/research/howto100m/)] </br>
*136 million video clips sourced from 1.22M narrated instructional web videos, 23k different visual tasks*

* **How2**: A Large-scale Dataset for Multimodal Language Understanding (NeurIPS 2018) </br>
[[Paper](https://arxiv.org/pdf/1811.00347.pdf)][[Homepage](https://github.com/srvk/how2-dataset)] </br>
*80,000 clips, word-level time alignments to the ground-truth English subtitles*

* **Breakfast**: The Language of Actions: Recovering the Syntax and Semantics of Goal-Directed Human Activities </br> 
[[Paper](https://openaccess.thecvf.com/content_cvpr_2014/papers/Kuehne_The_Language_of_2014_CVPR_paper.pdf)][[Homepage](https://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset/)]</br>
*52 participants, 10 distinct cooking activities captured in 18 different kitchens, 48 action classes, 11,267 clips*

* **EPIC-KITCHENS**: Scaling Egocentric Vision: The EPIC-KITCHENS Dataset (ECCV 2018, extended into TPAMI 2020)</br> 
[[Paper](https://arxiv.org/abs/2006.13256)][[Homepage](https://epic-kitchens.github.io/2021)]</br>
*100 hours, 37 participants, 20M frames, 90K action segments, 700 variable length videos, 97 verb classes, 300 noun classes, 4053 action classes*

* **YouCook2**: YouCookII Dataset </br>
[[Paper](http://youcook2.eecs.umich.edu/static/YouCookII/youcookii_readme.pdf)][[Homepage](http://youcook2.eecs.umich.edu/)] </br>
*2000 long untrimmed videos, 89 cooking recipes, each recipe includes 5 to 16 steps, each step should be described with one sentence*

* **QuerYD**: A video dataset with textual and audio narrations (ICASSP 2021) </br>
[[Paper](https://arxiv.org/abs/2011.11071)][[Homepage](https://www.robots.ox.ac.uk/~vgg/data/queryd/)]</br>
*1,400+ narrators, 200+ video hours, 70+ description hours*

* **VIOLIN**: A Large-Scale Dataset for Video-and-Language Inference (CVPR 2020) </br>
[[Paper](https://arxiv.org/pdf/2003.11618.pdf)][[Homepage](https://github.com/jimmy646/violin)] </br>
*95,322 video-hypothesis pairs from 15,887 video clips, spanning over 582 hours of video*

* **CrossTask**: weakly supervised learning from instructional videos (CVPR 2019) </br>
[[Paper](https://arxiv.org/abs/1903.08225)][[Homepage](https://github.com/DmZhukov/CrossTask)] </br>
*4.7K videos, 83 tasks*

## Action Segmentation
* **A2D**: Can Humans Fly? Action Understanding with Multiple Classes of Actors (CVPR 2015) </br>
[[Paper](https://www.cs.rochester.edu/~cxu22/p/cvpr2015_a2d_paper.pdf)][[Homepage](https://web.eecs.umich.edu/~jjcorso/r/a2d/)] </br>
*3,782 videos, actors: adult, baby, bird, cat, dog, ball and car, actions: climbing, crawling, eating, flying, jumping, rolling, running, and walking*

* **J-HMDB**: Towards understanding action recognition (ICCV 2013) </br>
[[Paper](https://hal.inria.fr/hal-00906902/document)][[Homepage](http://jhmdb.is.tue.mpg.de/)] </br>
*31,838 annotated frames, 21 categories involving a single person in action: brush hair, catch, clap, climb stairs, golf, jump, kick ball, pick, pour, pull-up, push, run, shoot ball, shoot bow, shoot gun, sit, stand, swing baseball, throw, walk, wave*

*  **A2D Sentences & J-HMDB Sentences**: Actor and Action Video Segmentation from a Sentence (CVPR 2018) </br>
[[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gavrilyuk_Actor_and_Action_CVPR_2018_paper.pdf)][[Homepage](https://kgavrilyuk.github.io/publication/actor_action/)] </br>
*A2D Sentences: 6,656 sentences, including 811 different nouns, 225 verbs and 189 adjectives, J-HMDB Sentences: 928 sentences, including 158 different
nouns, 53 verbs and 23 adjectives*

## Audiovisual Learning
* **Audio Set**: An ontology and human-labeled dataset for audio events (ICASSP 2017) </br>
[[Paper](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45857.pdf)][[Homepage](https://research.google.com/audioset/)] </br>
*632 audio event classes, 2,084,320 human-labeled 10-second sound clips*

* **MUSIC**: The Sound of Pixels (ECCV 2018) </br>
[[Paper](https://arxiv.org/pdf/1804.03160.pdf)][[Homepage](http://sound-of-pixels.csail.mit.edu/)] <br>
*685 untrimmed videos, 11 instrument categories*

* **AudioSet ZSL**: Coordinated Joint Multimodal Embeddings for Generalized Audio-Visual Zero-shot Classification and Retrieval of Videos (WACV 2020) </br>
[[Paper](https://openaccess.thecvf.com/content_WACV_2020/papers/Parida_Coordinated_Joint_Multimodal_Embeddings_for_Generalized_Audio-Visual_Zero-shot_Classification_and_WACV_2020_paper.pdf)][[Homepage](https://github.com/krantiparida/AudioSetZSL)] </br>
*33 classes, 156,416 videos*

* **Kinetics-Sound**: Look, Listen and Learn (ICCV 2017) </br>
[[Paper](https://openaccess.thecvf.com/content_ICCV_2017/papers/Arandjelovic_Look_Listen_and_ICCV_2017_paper.pdf)] </br>
*34 action classes from Kinetics*

* **EPIC-KITCHENS**: Scaling Egocentric Vision: The EPIC-KITCHENS Dataset (ECCV 2018, extended into TPAMI 2020)</br> 
[[Paper](https://arxiv.org/abs/2006.13256)][[Homepage](https://epic-kitchens.github.io/2021)]</br>
*100 hours, 37 participants, 20M frames, 90K action segments, 700 variable length videos, 97 verb classes, 300 noun classes, 4053 action classes*

* **SoundNet**: Learning Sound Representations from Unlabeled Video (NIPS 2016) </br>
[[Paper](https://arxiv.org/pdf/1610.09001.pdf)][[Homepage](http://soundnet.csail.mit.edu/)]</br>
*2+ million videos*

* **AVE**: Audio-Visual Event Localization in Unconstrained Videos (ECCV 2018) </br> 
[[Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yapeng_Tian_Audio-Visual_Event_Localization_ECCV_2018_paper.pdf)][[Homepage](https://sites.google.com/view/audiovisualresearch)]</br>
*4,143 10-second videos, 28 audio-visual events*

* **LLP**: Unified Multisensory Perception: Weakly-Supervised Audio-Visual Video Parsing (ECCV 2020) </br> 
[[Paper](https://arxiv.org/pdf/2007.10558.pdf)][[Homepage](https://github.com/YapengTian/AVVP-ECCV20)]</br>
*11,849 YouTube video clips, 25 event categories*

* **VGG-Sound**: A large scale audio-visual dataset </br> 
[[Paper](https://arxiv.org/abs/2004.14368)][[Homepage](https://www.robots.ox.ac.uk/~vgg/data/vggsound/)]</br>
*200k videos, 309 audio classes*

* **YouTube-ASMR-300K**: Telling Left from Right: Learning Spatial Correspondence of Sight and Sound (CVPR 2020) </br>
[[Paper](https://arxiv.org/pdf/2006.06175.pdf)][[Homepage](https://karreny.github.io/telling-left-from-right/)] </br>
*300K 10-second video clips with spatial audio*

* **XD-Violence**: Not only Look, but also Listen: Learning Multimodal Violence Detection under Weak Supervision (ECCV 2020) </br>
[[Paper](https://roc-ng.github.io/XD-Violence/images/paper.pdf)][[Homepage](https://roc-ng.github.io/XD-Violence/)] </br>
*4754 untrimmed videos*

* **VGG-SS**: Localizing Visual Sounds the Hard Way (CVPR 2021)</br> 
[[Paper](https://arxiv.org/pdf/2104.02691.pdf)][[Homepage](https://www.robots.ox.ac.uk/~vgg/research/lvs/)] </br>
*5K videos, 200 categories*

* **VoxCeleb**: Large-scale speaker verification in the wild </br>
[[Paper](https://www.robots.ox.ac.uk/~vgg/publications/2019/Nagrani19/nagrani19.pdf)][[Homepage](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/)] </br>
*a million ‘real-world’ utterances, over 7000 speakers*

* **EmoVoxCeleb**: Emotion Recognition in Speech using Cross-Modal Transfer in the Wild </br>
[[Paper](https://www.robots.ox.ac.uk/~vgg/publications/2018/Albanie18/albanie18.pdf)][[Homepage](https://www.robots.ox.ac.uk/~vgg/research/cross-modal-emotions/)]</br>
*1,251 speakers*

* **Speech2Gesture**: Learning Individual Styles of Conversational Gesture (CVPR 2019) </br>
[[Paper](https://arxiv.org/pdf/1906.04160.pdf)][[Homepage](http://people.eecs.berkeley.edu/~shiry/projects/speech2gesture/)] </br>
*144-hour person-specific video, 10 speakers*

* **AVSpeech**: Looking to Listen at the Cocktail Party: A Speaker-Independent Audio-Visual Model for Speech Separation </br>
[[Paper](https://arxiv.org/pdf/1804.03619.pdf)][[Homepage](https://looking-to-listen.github.io/avspeech/)]</br>
*150,000 distinct speakers, 290k YouTube videos*

* **LRW**: Lip Reading in the Wild (ACCV 2016) </br>
[[Paper](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16/chung16.pdf)][[Homepage](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html)] </br>
*1000 utterances of 500 different words*

* **LRW-1000**: A Naturally-Distributed Large-Scale Benchmark for Lip Reading in the Wild (IEEE FG 2019) </br>
[[Paper](https://arxiv.org/abs/1810.06990)][[Homepage](https://vipl.ict.ac.cn/en/view_database.php?id=13)] </br>
*>1,000,000 Chinese character instances, 718,018 samples with an average of 718 samples for each class, 1000 classes, with each class corresponds to the syllables of a Mandarin word, ~2000  different speakers with a large coverage over speech modes, including speech rate, viewpoint, age, gender and make-up and so on*

* **LRS2**: Lip Reading Sentences in the Wild (CVPR 2017) </br>
[[Paper](https://www.robots.ox.ac.uk/~vgg/publications/2017/Chung17/chung17.pdf)][[Homepage](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs2.html)] </br>
*thousands of spoken sentences from BBC television, each sentences is up to 100 characters in length*

* **LRS3-TED**: a large-scale dataset for visual speech recognition </br>
[[Paper](https://arxiv.org/pdf/1809.00496.pdf)][[Homepage](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrs3.html)] </br>
*thousands of spoken sentences from TED and TEDx videos*

* **CMLR**: A Cascade Sequence-to-Sequence Model for Chinese Mandarin Lip Reading </br>
[[Paper](https://arxiv.org/pdf/1908.04917.pdf)][[Homepage](https://arxiv.org/pdf/1908.04917.pdf)] </br>
*102,072 spoken sentences from 11 speakers*

* **Countix-AV & Extreme Countix-AV**: Repetitive Activity Counting by Sight and Sound (CVPR 2021) </br>
[[Paper](https://arxiv.org/pdf/2103.13096.pdf)][[Homepage](https://github.com/xiaobai1217/RepetitionCounting)] </br>
*1,863 videos in Countix-AV, 214 videos in Extreme Countix-AV*

## Repetition Counting
* **QUVA Repetition**: Real-World Repetition Estimation by Div, Grad and Curl (CVPR 2018) </br>
[[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Runia_Real-World_Repetition_Estimation_CVPR_2018_paper.pdf)][[Homepage](http://tomrunia.github.io/projects/repetition/)] </br>
*100 videos*

* **YTSegments**: Live Repetition Counting (ICCV 2015) </br>
[[Paper](https://openaccess.thecvf.com/content_iccv_2015/papers/Levy_Live_Repetition_Counting_ICCV_2015_paper.pdf)][[Homepage](https://github.com/ofirlevy/repcount)]</br>
*100 videos*

* **UCFRep**: Context-Aware and Scale-Insensitive Temporal Repetition Counting (CVPR 2020) </br>
[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Context-Aware_and_Scale-Insensitive_Temporal_Repetition_Counting_CVPR_2020_paper.pdf)][[Homepage](https://github.com/Xiaodomgdomg/Deep-Temporal-Repetition-Counting)] </br>
*526 videos*

* **Countix**: Counting Out Time: Class Agnostic Video Repetition Counting in the Wild (CVPR 2020) </br>
[[Paper](https://arxiv.org/pdf/2006.15418v1.pdf)][[Homepage](https://sites.google.com/view/repnet)] </br>
*8,757 videos*

* **Countix-AV & Extreme Countix-AV**: Repetitive Activity Counting by Sight and Sound (CVPR 2021) </br>
[[Paper](https://arxiv.org/pdf/2103.13096.pdf)][[Homepage](https://github.com/xiaobai1217/RepetitionCounting)] </br>
*1,863 videos in Countix-AV, 214 videos in Extreme Countix-AV*

## Video Indexing
* **MediaMill**: The Challenge Problem for Automated Detection of 101 Semantic Concepts in Multimedia </br>
[[Paper](https://isis-data.science.uva.nl/cgmsnoek/pub/snoek-challenge-acm2006.pdf)][[Homepage](https://ivi.fnwi.uva.nl/isis/mediamill/challenge/)] </br>
*manually annotated concept lexicon*

## Skill Determination

* **EPIC-Skills**: Who's Better? Who's Best? Pairwise Deep Ranking for Skill Determination (CVPR 2018) </br>
[[Paper](https://arxiv.org/abs/1703.09913)][[Homepage](https://github.com/hazeld/EPIC-Skills2018)] </br>
*3 tasks, 113 videos, 1000 pairwise ranking annotations*

* **BEST**: The Pros and Cons: Rank-aware Temporal Attention for Skill Determination in Long Videos (CVPR 2019) </br>
[[Paper](https://arxiv.org/abs/1812.05538)][[Homepage](https://github.com/hazeld/rank-aware-attention-network)] </br>
*5 tasks, 500 videos, 13000 pairwise ranking annotations*

## Video Retrieval

* **TRECVID Challenge**: TREC Video Retrieval Evaluation </br>
[[Homepage](https://trecvid.nist.gov/)] </br>
*sources: YFCC100M, Flickr, etc*

* **Video Browser Showdown** – The Video Retrieval Competition </br>
[[Homepage](https://videobrowsershowdown.org/)]

* **V3C** - A Research Video Collection </br>
[[Paper](https://link.springer.com/content/pdf/10.1007%2F978-3-030-05710-7_29.pdf)][[Homepage](https://sites.google.com/view/viral2019/home/supported-datasets)] </br>
*7475 Vimeo videos, 1,082,657 short video segments*

* **IACC**: Creating a web-scale video collection for research </br>
[[Paper](https://dl.acm.org/doi/pdf/10.1145/1631135.1631141)][[Homepage](https://sites.google.com/view/viral2019/home/supported-datasets)] </br>
*4600 Internet Archive videos*

* **TVR**: A Large-Scale Dataset for Video-Subtitle Moment Retrieval (ECCV 2020) </br>
[[Paper](https://arxiv.org/abs/2001.09099)][[Homepage](https://tvr.cs.unc.edu/)] </br>
*108,965 queries on 21,793 videos from 6 TV shows of diverse genres, where each query is associated with a tight temporal alignment*

## Single Object Tracking
* **Lingual OTB99 & Lingual ImageNet Videos**: Tracking by Natural Language Specification (CVPR 2017) </br>
[[Paper](https://isis-data.science.uva.nl/cgmsnoek/pub/li-tracking-language-cvpr2017.pdf)][[Homepage](https://github.com/QUVA-Lab/lang-tracker)] </br>
*natural language descriptions of the target object*

* **OxUvA**: Long-term Tracking in the Wild: A Benchmark (ECCV 2018) </br>
[[Paper](https://arxiv.org/pdf/1803.09502.pdf)][[Homepage](https://oxuva.github.io/long-term-tracking-benchmark/)] </br>
*366 sequences spanning 14 hours of video*

* **LaSOT**: A High-quality Benchmark for Large-scale Single Object Tracking </br>
[[Paper](https://arxiv.org/pdf/1809.07845.pdf)][[Homepage](https://cis.temple.edu/lasot/)] </br>
*1,400 sequences with more than 3.5M frames, each frame is annotated with a bounding box*

* **TrackingNet**: A Large-Scale Dataset and Benchmark for Object Tracking in the Wild (ECCV 2018) </br>
[[Paper](https://arxiv.org/pdf/1803.10794.pdf)][[Homepage](https://tracking-net.org/)] </br>
*30K videos with more than 14 million dense bounding box annotations, a new benchmark composed of 500 novel videos*

* **ALOV300+**: Visual Tracking: An Experimental Survey (TPAMI 2014) </br>
[[Paper](https://ivi.fnwi.uva.nl/isis/publications/2014/SmeuldersTPAMI2014/SmeuldersTPAMI2014.pdf)][[Homepage](https://ivi.fnwi.uva.nl/isis/publications/bibtexbrowser.php?key=SmeuldersTPAMI2014&bib=all.bib)][[Dataset](http://alov300pp.joomlafree.it/)]</br>
*315 videos*

* **NUS-PRO**: A New Visual Tracking Challenge (TPAMI 2015) </br>
[[Paper](https://faculty.ucmerced.edu/mhyang/papers/pami15_nus_pro.pdf)][[Homepage](https://sites.google.com/site/li00annan/nus-pro)] </br>
*365 image sequences*

* **UAV123**: A Benchmark and Simulator for UAV Tracking (ECCV 2016) </br>
[[Paper](https://drive.google.com/file/d/1YDlCOWxH8HMPlmblJ2OvxFdSFecuiM3Z/edit)][[Homepage](https://cemse.kaust.edu.sa/ivul/uav123)] </br>
*123 new and fully annotated HD video sequences captured from a low-altitude aerial perspective*

* **OTB2013**: Online Object Tracking: A Benchmark (CVPR 2013) </br>
[[Paper](https://faculty.ucmerced.edu/mhyang/papers/cvpr13_benchmark.pdf)][[Homepage](http://cvlab.hanyang.ac.kr/tracker_benchmark/benchmark_v10.html)] </br>
*50 video sequences*

* **OTB2015**: Object Tracking Benchmark (TPAMI 2015) </br>
[[Paper](https://ieeexplore.ieee.org/document/7001050)][[Homepage](http://cvlab.hanyang.ac.kr/tracker_benchmark/index.html)] </br>
*100 video sequences*

* **VOT Challenge** </br>
[[Homepage](https://www.votchallenge.net/)]

## Multiple Objects Tracking
* **MOT Challenge** </br>
[[Homepage](https://motchallenge.net/)] </br>

* **VisDrone**: Vision Meets Drones: A Challenge </br>
[[Paper](https://arxiv.org/pdf/1804.07437.pdf)][[Homepage](https://github.com/VisDrone)] </br>

* **TAO**: A Large-Scale Benchmark for Tracking Any Object </br>
[[Paper](https://arxiv.org/abs/2005.10356)][[Homepage](http://taodataset.org/)] </br>
*2,907 videos, 833 classes, 17,287 tracks*

* **GMOT-40**: A Benchmark for Generic Multiple Object Tracking </br>
[[Paper](https://arxiv.org/pdf/2011.11858.pdf)][[Homepage](https://spritea.github.io/GMOT40/)] </br>
*40 carefully annotated sequences evenly distributed among 10 object categories*

* **BDD100K**: A Diverse Driving Dataset for Heterogeneous Multitask Learning (CVPR 2020) </br>
[[Paper](https://arxiv.org/pdf/1805.04687.pdf)][[Homepage](https://www.bdd100k.com/)] </br>
*100K videos and 10 tasks*

## Video Relation Detection
* **KIEV**: Interactivity Proposals for Surveillance Videos </br>
[[Paper](https://isis-data.science.uva.nl/cgmsnoek/pub/chen-interactivity-icmr2020.pdf)][[Homepage](https://github.com/shanshuo/Interactivity_Proposals)] </br>
*a new task of spatio-temporal interactivity proposals*

* **ImageNet-VidVRD**: Video Visual Relation Detection </br>
[[Paper](https://dl.acm.org/doi/10.1145/3123266.3123380)][[Homepage](https://xdshang.github.io/docs/imagenet-vidvrd.html)]</br>
*1,000 videos, 35 common subject/object categories and 132 relationships*

* **VidOR**: Annotating Objects and Relations in User-Generated Videos </br>
[[Paper](https://dl.acm.org/doi/10.1145/3323873.3325056)][[Homepage](https://xdshang.github.io/docs/vidor.html)] </br>
*10,000 videos selected from YFCC100M collection, 80 object categories and 50 predicate categories*

* **Something-Else**: Compositional Action Recognition with Spatial-Temporal Interaction Networks (CVPR 2020) </br>
[[Paper](https://arxiv.org/pdf/1912.09930.pdf)][[Homepage](https://github.com/joaanna/something_else)] </br>
*annotations for 180049 videos from the Something-Something Dataset*

* **Action Genome**: Actions as Compositions of Spatio-temporal Scene Graphs (CVPR 2020) </br> 
[[Paper](https://arxiv.org/pdf/1912.06992.pdf)][[Homepage](https://www.actiongenome.org/)]</br>
*10K videos, 0.4M objects, 1.7M visual relationships*

* **VidSitu**: Visual Semantic Role Labeling for Video Understanding (CVPR 2021) </br>
[[Paper](https://arxiv.org/pdf/2104.00990.pdf)][[Homepage](https://vidsitu.org/)] </br>
*29K 10-second movie clips richly annotated with a verb and semantic-roles every 2 seconds*

## Anomaly Detection
* **XD-Violence**: Not only Look, but also Listen: Learning Multimodal Violence Detection under Weak Supervision (ECCV 2020) </br>
[[Paper](https://roc-ng.github.io/XD-Violence/images/paper.pdf)][[Homepage](https://roc-ng.github.io/XD-Violence/)] </br>
*4,754 untrimmed videos*

* **UCF-Crime**: Real-world Anomaly Detection in Surveillance Videos </br>
[[Paper](https://arxiv.org/pdf/1801.04264.pdf)][[Homepage](https://www.crcv.ucf.edu/projects/real-world/#:~:text=We%20construct%20a%20new%20large,Stealing%2C%20Shoplifting%2C%20and%20Vandalism.)]</br>
*1,900 videos*

## Pose Estimation
* **YouTube Pose**: Personalizing Human Video Pose Estimation (CVPR 2016) </br>
[[Paper](https://arxiv.org/pdf/1511.06676.pdf)][[Homepage](https://www.robots.ox.ac.uk/~vgg/data/pose/index.html)] </br>
*50 videos, 5,000 annotated frames*

## Physics
* **Real-world Flag & FlagSim**: Cloth in the Wind: A Case Study of Physical Measurement through Simulation (CVPR 2020) </br>
[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Runia_Cloth_in_the_Wind_A_Case_Study_of_Physical_Measurement_CVPR_2020_paper.pdf)][[Homepage](http://tomrunia.github.io/projects/cloth/)] </br>
*Real-world Flag: 2.7K train and 1.3K videos clips, FlagSim: 1,000 mesh sequences, 14, 000 training examples*
