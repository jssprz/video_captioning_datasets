# Datasets for Video Captioning

## Video + Language Datasets

Dataset                                                      | Year | Type                   | Caps. Source     | Localization       | Audio              | Long Caps.         |
:----------------------------------------------------------: | :--: | :--------------------: | :--------------: | :----------------: | :----------------: | :----------------: |
MSVD [[1]](#L.Chen2011CollectingEvaluation)                  | 2011 | Open (YouTube)         | MTurk            |                    |                    |                    |
MPII Cooking Act. [[2]](#Rohrbach2012AActivities)            | 2012 | Cooking                | in-house actors  |                    |                    |                    |
MPII Cooking C. Act. [[3]](#Rohrbach2012ScriptActivities)    | 2012 | Cooking                | in-house actors  |                    |                    |                    |
YouCook [[4]](#Das2013AStitching)                            | 2013 | Cooking                | MTurk            |                    |                    |                    |
TACoS [[5]](#Regneri2013GroundingVideos)                     | 2013 | Cooking                | MTurk            | :heavy_check_mark: |                    |                    |
TACoS-Multilevel [[6]](#Rohrbach2014CoherentDetail)          | 2014 | Cooking                | MTurk            |                    |                    |                    |
M-VAD [[7]](#Torabi2015UsingResearch)                        | 2015 | Movie                  | DVS              |                    | :heavy_check_mark: | :heavy_check_mark: |
MPII-MD [[8]](#Rohrbach2015ADescription)                     | 2015 | Movie                  | Script + DVS     |                    | :heavy_check_mark: |                    |
LSDMC\footref{note:lsmdc}                                    | 2015 | Movie                  | Script + DVS     |                    | :heavy_check_mark: |                    |
MSR-VTT [[9]](#Xu2016MSR-VTT:Language)                       | 2016 | Open                   | MTurk            |                    | :heavy_check_mark: |                    |
MPII Cooking 2 [[10]](#Rohrbach2016RecognizingData)          | 2016 | Cooking                | in-house actors  | :heavy_check_mark: |                    |                    |
Charades [[11]](#Sigurdsson2016HollywoodUnderstanding)       | 2016 | Daily indoor act.      | MTurk            | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
VTW-full [[12]](#Zeng2016TitleVideos)                        | 2016 | Open (YouTube)         | Owner/Editor     |                    |                    |                    |
TGIF [[13]](#Li2016TGIF:Description)                         | 2016 | Open                   | crowdworkers     |                    |                    | :heavy_check_mark: |
TRECVID-VTT'16 [[14]](#Awad2016TRECVIDHyperlinking)          | 2016 | Open                   | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |
Co-ref+Gender [[15]](#Rohrbach2017GeneratingPeople)          | 2017 | Movie                  | DVS              |                    | :heavy_check_mark: |                    |
ActivityNet Caps. [[16]](#Krishna2017Dense-CaptioningVideos) | 2017 | Human act.             | MTurk            | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
TRECVID-VTT'17 [[17]](#Awad2017TrecvidHyperlinking)          | 2017 | Open (Twitter)         | MTurk            |                    | :heavy_check_mark: |                    |
YouCook2 [[18]](#Zhou2018TowardsVideos)                      | 2018 | Cooking                | viewer/annotator | :heavy_check_mark: | :heavy_check_mark: |                    |
Charades-Ego [[19]](#Sigurdsson2018ActorVideos)              | 2018 | Daily indoor act.      | MTurk            | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
20BN-s-s V2 [[20]](#Mahdisoltani2018Fine-grainedCaptioning)  | 2018 | Human-obj. interact.   | MTurk            |                    |                    |                    |
TRECVID-VTT'18 [[21]](#Awad2018TRECVIDSearch)                | 2018 | Open (Twitter)         | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |
TRECVID-VTT'19 [[22]](#Awad2019TRECVIDRetrieval)             | 2019 | Open (Twitter+Flirck)  | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |
\VATEX\footref{note:vatex} [[23]](#Wang2019VaTeXResearch)    | 2019 | Open                   | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |
HowTo100M [[24]](#Miech2019HowTo100M:Clips)                  | 2019 | Instructional (YouTube)| subtitles        | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
TRECVID-VTT'20 [[22]](#Awad2020TRECVIDDomains)               | 2020 | Open (Twitter+Flirck)  | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |

## References

<a id="L.Chen2011CollectingEvaluation">[1]</a> D. L. Chen and W. B. Dolan, “Collecting highly parallel data for paraphrase evaluation,” in Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies, 2011, vol. 1, pp. 190–200, Accessed: Nov. 13, 2018. [Online]. Available: https://dl.acm.org/citation.cfm?id=2002497.

<a id="Rohrbach2012AActivities">[2]</a> M. Rohrbach, S. Amin, M. Andriluka, and B. Schiele, “A database for fine grained activity detection of cooking activities,” in 2012 IEEE Conference on Computer Vision and Pattern Recognition, Jun. 2012, pp. 1194–1201, doi: 10.1109/CVPR.2012.6247801.

<a id="Rohrbach2012ScriptActivities">[3]</a> M. Rohrbach, M. Regneri, M. Andriluka, S. Amin, M. Pinkal, and B. Schiele, “Script Data for Attribute-Based Recognition of Composite Activities,” in Computer Vision -- ECCV 2012, 2012, pp. 144–157, doi: 10.1007/978-3-642-33718-5_11.

<a id="Das2013AStitching">[4]</a> P. Das, C. Xu, R. F. Doell, and J. J. Corso, “A thousand frames in just a few words: Lingual description of videos through latent topics and sparse object stitching,” in IEEE Computer Society Conference on Computer Vision and Pattern Recognition, 2013, pp. 2634--2641, doi: 10.1109/CVPR.2013.340.

<a id="Regneri2013GroundingVideos">[5]</a> M. Regneri, M. Rohrbach, D. Wetzel, S. Thater, B. Schiele, and M. Pinkal, “Grounding Action Descriptions in Videos,” Trans. Assoc. Comput. Linguist., vol. 1, pp. 25–36, Dec. 2013, doi: 10.1162/tacl_a_00207.

<a id="Rohrbach2014CoherentDetail">[6]</a> A. Rohrbach, M. Rohrbach, W. Qiu, A. Friedrich, M. Pinkal, and B. Schiele, “Coherent multi-sentence video description with variable level of detail,” in Pattern Recognition, 2014, pp. 184--195, doi: 10.1007/978-3-319-11752-2_15.

<a id="Torabi2015UsingResearch">[7]</a> A. Torabi, C. Pal, H. Larochelle, and A. Courville, “Using Descriptive Video Services to Create a Large Data Source for Video Annotation Research,” CoRR, vol. abs/1503.0, Mar. 2015, [Online]. Available: http://arxiv.org/abs/1503.01070.

<a id="Rohrbach2015ADescription">[8]</a> A. Rohrbach, M. Rohrbach, N. Tandon, and B. Schiele, “A dataset for Movie Description,” in 2015 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), Jun. 2015, vol. 07-12-June, pp. 3202–3212, doi: 10.1109/CVPR.2015.7298940.

<a id="Xu2016MSR-VTT:Language">[9]</a> J. Xu, T. Mei, T. Yao, and Y. Rui, “MSR-VTT: A Large Video Description Dataset for Bridging Video and Language,” 2016 IEEE Conf. Comput. Vis. Pattern Recognit., pp. 5288–5296, 2016, doi: 10.1109/CVPR.2016.571.

<a id="Rohrbach2016RecognizingData">[10]</a> M. Rohrbach et al., “Recognizing Fine-Grained and Composite Activities Using Hand-Centric Features and Script Data,” Int. J. Comput. Vis., vol. 119, no. 3, pp. 346–373, Sep. 2016, doi: 10.1007/s11263-015-0851-8.

<a id="Sigurdsson2016HollywoodUnderstanding">[11]</a> G. A. Sigurdsson, G. Varol, X. Wang, A. Farhadi, I. Laptev, and A. Gupta, “Hollywood in Homes: Crowdsourcing Data Collection for Activity Understanding,” in Computer Vision -- ECCV 2016, 2016, pp. 510–526, doi: 10.1007/978-3-319-46448-0_31.

<a id="Zeng2016TitleVideos">[12]</a> K.-H. Zeng, T.-H. Chen, J. C. Niebles, and M. Sun, “Title Generation for User Generated Videos,” in Computer Vision -- ECCV 2016, 2016, pp. 609–625, doi: 10.1007/978-3-319-46475-6_38.

<a id="Li2016TGIF:Description">[13]</a> Y. Li et al., “TGIF: A New Dataset and Benchmark on Animated GIF Description,” in 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), Jun. 2016, vol. 2016-Decem, pp. 4641–4650, doi: 10.1109/CVPR.2016.502.

<a id="Awad2016TRECVIDHyperlinking">[14]</a> G. Awad et al., “TRECVID 2016: Evaluating vdeo search, video event detection, localization, and hyperlinking,” 2016, [Online]. Available: http://www.eurecom.fr/publication/5054.

<a id="Rohrbach2017GeneratingPeople">[15]</a> A. Rohrbach, M. Rohrbach, S. Tang, S. J. Oh, and B. Schiele, “Generating Descriptions with Grounded and Co-Referenced People,” 2017.

<a id="Krishna2017Dense-CaptioningVideos">[16]</a> R. Krishna, K. Hata, F. Ren, L. Fei-Fei, and J. C. Niebles, “Dense-Captioning Events in Videos,” in 2017 IEEE International Conference on Computer Vision (ICCV), Oct. 2017, vol. 2017-Octob, pp. 706–715, doi: 10.1109/ICCV.2017.83.

<a id="Awad2017TrecvidHyperlinking">[17]</a> G. Awad et al., “Trecvid 2017: Evaluating ad-hoc and instance video search, events detection, video captioning and hyperlinking,” 2017, doi: 10.na.

<a id="Zhou2018TowardsVideos">[18]</a> L. Zhou, C. Xu, and J. J. Corso, “Towards Automatic Learning of Procedures from Web Instructional Videos,” in Proceedings of the AAAI Conference on Artificial Intelligence, Mar. 2018, pp. 7590--7598.

<a id="Sigurdsson2018ActorVideos">[19]</a> G. A. Sigurdsson, A. Gupta, C. Schmid, A. Farhadi, and K. Alahari, “Actor and Observer: Joint Modeling of First and Third-Person Videos,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018, pp. 7396–7404.

<a id="Mahdisoltani2018Fine-grainedCaptioning">[20]</a> F. Mahdisoltani, G. Berger, W. Gharbieh, D. Fleet, and R. Memisevic, “Fine-grained Video Classification and Captioning,” CoRR, vol. abs/1804.0, Apr. 2018, Accessed: Oct. 21, 2018. [Online]. Available: http://arxiv.org/abs/1804.09235.

<a id="Awad2018TRECVIDSearch">[21]</a> G. Awad et al., “TRECVID 2018: Benchmarking Video Activity Detection, Video Captioning and Matching, Video Storytelling Linking and Video Search,” 2018.

<a id="Awad2019TRECVIDRetrieval">[22]</a> G. Awad et al., “TRECVID 2019: An evaluation campaign to benchmark Video Activity Detection, Video Captioning and Matching, and Video Search & retrieval,” 2019.

<a id="Wang2019VaTeXResearch">[23]</a> X. Wang, J. Wu, J. Chen, L. Li, Y.-F. Wang, and W. Y. Wang, “VATEX: A Large-Scale, High-Quality Multilingual Dataset for Video-and-Language Research,” in The IEEE International Conference on Computer Vision (ICCV), 2019, pp. 4581–4591.

<a id="Miech2019HowTo100M:Clips">[24]</a> A. Miech, D. Zhukov, J.-B. Alayrac, M. Tapaswi, I. Laptev, and J. Sivic, “HowTo100M: Learning a Text-Video Embedding by Watching Hundred Million Narrated Video Clips,” in 2019 IEEE/CVF International Conference on Computer Vision (ICCV), Oct. 2019, pp. 2630–2640, doi: 10.1109/ICCV.2019.00272.

<a id="Awad2020TRECVIDDomains">[25]</a> G. Awad et al., “TRECVID 2020: comprehensive campaign for evaluating video retrieval tasks across multiple application domains,” 2020.
