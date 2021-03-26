# Datasets for Video Captioning

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![Video-Text and Datasets](https://img.shields.io/badge/VideoCaptioning-DeepLearning-orange)
![MIT License](https://img.shields.io/badge/license-MIT-green)

In this repository, we organize the information about more that 25 datasets of (video, text) pairs that have been used for training and evaluating video captioning models.
We this repository, we want to make it easier for researches to obtain datasets and replicate results.
We are open to callobaration for including new datasets and related concepts.

Even when there are several online video platforms to get data from, the construction of a balanced labeled dataset is a costly task that requires significant and time-consuming human effort. Although most of the below listed datasets are not explicitly available, some of them can be obtained from the authors, if requested.

A detailed description of all these datasets can be found in our comprehensive review about Video-to-Text research area:

```

@article{PerezMartin2021BridgingReview,
	title={Bridging Vision and Language from the Video-to-Text Perspective: A Comprehensive Review},
	author={Perez-Martin, Jesus and Bustos, Benjamin and F. Guimar\~{a}es, Silvio Jamil and Sipiran, Ivan and Perez, Jorge and Coello Said, Grethel
	journal = {arXiv},
	publisher = {arXiv},
	year={2021}
}
```

## Video + Language Datasets

List of datasets of video-caption/description pairs for training video-to-text models.
The last three columns show:

- if the dataset contains temporal-localization information related to each description,
- if the videos of the dataset contain audio, and
- if corpus' descriptions are more than eleven words long on average.

Dataset                                                                  | Year | Type                   | Caps. Source     | Localization       | Audio              | Long Caps.         |
:---------------------------------------------------------------------:  | :--: | :--------------------: | :--------------: | :----------------: | :----------------: | :----------------: |
MSVD [[1]](#L.Chen2011CollectingEvaluation)                              | 2011 | Open (YouTube)         | MTurk            |                    |                    |                    |
MPII Cooking Act. [[2]](#Rohrbach2012AActivities)                        | 2012 | Cooking                | in-house actors  |                    |                    |                    |
MPII Cooking C. Act. [[3]](#Rohrbach2012ScriptActivities)                | 2012 | Cooking                | in-house actors  |                    |                    |                    |
YouCook [[4]](#Das2013AStitching)                                        | 2013 | Cooking                | MTurk            |                    |                    |                    |
TACoS [[5]](#Regneri2013GroundingVideos)                                 | 2013 | Cooking                | MTurk            | :heavy_check_mark: |                    |                    |
TACoS-Multilevel [[6]](#Rohrbach2014CoherentDetail)                      | 2014 | Cooking                | MTurk            |                    |                    |                    |
M-VAD [[7]](#Torabi2015UsingResearch)                                    | 2015 | Movie                  | DVS              |                    | :heavy_check_mark: | :heavy_check_mark: |
MPII-MD [[8]](#Rohrbach2015ADescription)                                 | 2015 | Movie                  | Script + DVS     |                    | :heavy_check_mark: |                    |
LSDMC [[web]](https://sites.google.com/site/describingmovies/lsmdc-2017) | 2015 | Movie                  | Script + DVS     |                    | :heavy_check_mark: |                    |
MSR-VTT [[9]](#Xu2016MSR-VTTLanguage)                                    | 2016 | Open                   | MTurk            |                    | :heavy_check_mark: |                    |
MPII Cooking 2 [[10]](#Rohrbach2016RecognizingData)                      | 2016 | Cooking                | in-house actors  | :heavy_check_mark: |                    |                    |
Charades [[11]](#Sigurdsson2016HollywoodUnderstanding)                   | 2016 | Daily indoor act.      | MTurk            | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
VTW-full [[12]](#Zeng2016TitleVideos)                                    | 2016 | Open (YouTube)         | Owner/Editor     |                    |                    |                    |
TGIF [[13]](#Li2016TGIFDescription)                                      | 2016 | Open                   | crowdworkers     |                    |                    | :heavy_check_mark: |
TRECVID-VTT'16 [[14]](#Awad2016TRECVIDHyperlinking)                      | 2016 | Open                   | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |
Co-ref+Gender [[15]](#Rohrbach2017GeneratingPeople)                      | 2017 | Movie                  | DVS              |                    | :heavy_check_mark: |                    |
ActivityNet Caps. [[16]](#Krishna2017Dense-CaptioningVideos)             | 2017 | Human act.             | MTurk            | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
TRECVID-VTT'17 [[17]](#Awad2017TrecvidHyperlinking)                      | 2017 | Open (Twitter)         | MTurk            |                    | :heavy_check_mark: |                    |
YouCook2 [[18]](#Zhou2018TowardsVideos)                                  | 2018 | Cooking                | viewer/annotator | :heavy_check_mark: | :heavy_check_mark: |                    |
Charades-Ego [[19]](#Sigurdsson2018ActorVideos)                          | 2018 | Daily indoor act.      | MTurk            | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
20BN-s-s V2 [[20]](#Mahdisoltani2018Fine-grainedCaptioning)              | 2018 | Human-obj. interact.   | MTurk            |                    |                    |                    |
TRECVID-VTT'18 [[21]](#Awad2018TRECVIDSearch)                            | 2018 | Open (Twitter)         | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |
TRECVID-VTT'19 [[22]](#Awad2019TRECVIDRetrieval)                         | 2019 | Open (Twitter+Flirck)  | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |
VATEX [[23]](#Wang2019VaTeXResearch)                                     | 2019 | Open                   | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |
HowTo100M [[24]](#Miech2019HowTo100MClips)                               | 2019 | Instructional (YouTube)| subtitles        | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
TRECVID-VTT'20 [[25]](#Awad2020TRECVIDDomains)                           | 2020 | Open (Twitter+Flirck)  | MTurk            |                    | :heavy_check_mark: | :heavy_check_mark: |

## Charts

- [Video type](https://docs.google.com/spreadsheets/d/e/2PACX-1vTjhrkUrAj5Fpvtvi-QHqUzO4EkMphJjsk6KdaVsEYqORTGzW3i5hE_UHe5fVZSXQFPGXHYc_SUA5qn/pubchart?oid=1088649009&format=interactive)
- [Textual annotations source](https://docs.google.com/spreadsheets/d/e/2PACX-1vRGz0dUcxythEzRxlyX8561HWKqp4yWpSePQJhRNwu-5TEcxgM3qdlDn7dAS1Y28ITAUCPJvRMqrnz5/pubchart?oid=1088649009&format=interactive)

### Corpus Details

The next table details the vocabulary composition of each corpus, *i.e.*, number of tokens, nouns, verbs, adjectives, and adverbs.
We also show the average length of captions and the percent of tokens that appear in the [GloVe-6B](https://nlp.stanford.edu/projects/glove/) dictionary.
The words categorization have been calculated by POS-tagging with [*universal tagset* mapping](http://www.nltk.org/book/ch05.html).

Corpus                                                                   | Avg. caption len. | Tokens    | Nouns     | Verbs   | Adjectives | Adverbs | \% of tokens in GloVe-6B |
:----------------------------------------------------------------------: | :---------------: | :-------: | :-------: | :-----: | :--------: | :-----: | :----------------------: |
MSVD [[1]](#L.Chen2011CollectingEvaluation)                              | 7.14              | 9,629     | 6,057     | 3,211   | 1,751      | 378     | 83.44                    |
TACoS-Multilevel [[6]](#Rohrbach2014CoherentDetail)                      | 8.27              | 2,863     | 1,475     | 1,178   | 609        | 207     | 91.86                    |
M-VAD [[7]](#Torabi2015UsingResearch)                                    | 12.44             | 17,609    | 9,512     | 2,571   | 3,560      | 857     | 94.99                    |
MPII-MD [[8]](#Rohrbach2015ADescription)                                 | 11.05             | 20,650    | 11,397    | 6,100   | 3,952      | 1,162   | 88.96                    |
LSDMC [[web]](https://sites.google.com/site/describingmovies/lsmdc-2017) | 10.66             | 24,267    | 15,095    | 7,726   | 7,078      | 1,545   | 88.57                    |
MSR-VTT [[9]](#Xu2016MSR-VTTLanguage)                                    | 9.27              | 23,527    | 19,703    | 8,862   | 7,329      | 1,195   | 80.74                    |
TGIF [[13]](#Li2016TGIFDescription)                                      | 11.28             | 10,646    | 6,658     | 3,993   | 2,496      | 626     | 97.85                    |
Charades [[11]](#Sigurdsson2016HollywoodUnderstanding)                   | 23.91             | 4,010     | 2,199     | 1,780   | 651        | 265     | 90.00                    |
Charades-Ego [[19]](#Sigurdsson2018ActorVideos)                          | 26.30             | 2,681     | 1,460     | 1,179   | 358        | 190     | 91.12                    |
VTW-full [[12]](#Zeng2016TitleVideos)                                    | 6.40              | 23,059    | 13,606    | 6,223   | 3,967      | 846     | -                        |
ActivityNet Caps. [[16]](#Krishna2017Dense-CaptioningVideos)             | 14.72             | 10,162    | 4,671     | 3,748   | 2,131      | 493     | 94.00                    |
20BN-s-s V2 [[20]](#Mahdisoltani2018Fine-grainedCaptioning)              | 6.76              | 7,433     | 6,087     | 1,874   | 1,889      | 361     | 74.51                    |
TRECVID-VTT'20 [[25]](#Awad2020TRECVIDDomains)                           | 18.90             | 11,634    | 7,316     | 4,038   | 2,878      | 542     | 93.36                    |
VATEX-en [[23]](#Wang2019VaTeXResearch)                                  | 15.25             | 28,634    | 23,288    | 12,796  | 10,639     | 1,924   | 76.84                    |
HowTo100M [[24]](#Miech2019HowTo100MClips)                               | 4.16              | 593,238   | 491,488   | 198,859 | 219,719    | 76,535  | 36.64                    |

### Standard Splits

The next table shows the number of video clips and captions in the standard splits of each video-caption/description pairs dataset.

|  Dataset                                                                      | clips (train)    | captions (train) | clips (val) | captions (val) | clips (test) | captions (test) | clips (total) | captions (total) |
| :---------------------------------------------------------------------------: | :--------------: | :--------------: | :---------: | :------------: | :----------: | :-------------: | :-----------: | :--------------: |
| MSVD [[1]](#L.Chen2011CollectingEvaluation)                                   | 1,200            | 48,779           | 100         | 4,291          | 670          | 27,768          | 1,970         | 80,838           |
| TACoS [[5]](#Regneri2013GroundingVideos)                                      | -                | -                | -           | -              | -            | -               | 7,206         | 18,227           |
| TACoS-Multilevel [[6]](#Rohrbach2014CoherentDetail)                           | -                | -                | -           | -              | -            | -               | 14,105        | 52,593           |
| M-VAD [[7]](#Torabi2015UsingResearch)                                         | 36,921           | 36,921           | 4,717       | 4,717          | 4,951        | 4,951           | 46,589        | 46,589           |
| MPII-MD [[8]](#Rohrbach2015ADescription) [[15]](Rohrbach2017GeneratingPeople)  | 56,822           | 56,861           | 4,927       | 4,930          | 6,578        | 6,584           | 68,327        | 68,375           |
| LSDMC [[web]](https://sites.google.com/site/describingmovies/lsmdc-2017)      | 91,908           | 91,941           | 6,542       | 6,542          | 10,053       | 10,053          | 108,503       | 108,536          |
| MSR-VTT, 2016 [[9]](#Xu2016MSR-VTTLanguage)                                   | 6,512            | 130,260          | 498         | 9,940          | 2,990        | 59,800          | 507,502       | 200,000          |
| MSR-VTT, 2017 [web](http://ms-multimedia-challenge.com/2017/dataset)          | 10,000           | 200,000          | -           | -              | 3,000        | 60,000          | 13,000        | 260,000          |
| Charades [[11]](#Sigurdsson2016HollywoodUnderstanding)                        | 7,985            | 18,167           | 1,863       | 6,865          | -            | -               | 9,848         | 25,032           |
| Charades-Ego [[19]](#Sigurdsson2018ActorVideos)                               | 6,167            | 12,346           | 1,693       | 1,693          | -            | -               | 7,860         | 14,039           |
| TGIF [[13]](#Li2016TGIFDescription)                                           | 80,850           | 80850            | 10,831      | 10,831         | 34,101       | 34,101          | 125,782       | 125,781          |
| ActivityNet Caps. [[16]](#Krishna2017Dense-CaptioningVideos)                  | 10,024           | 36,587           | 4,926       | 17,979         | 5,044        | 18,410          | 19,994        | 72,976           |
| 20BN-s-s V2 [[20]](#Mahdisoltani2018Fine-grainedCaptioning)                   | 168,913          | 1,689,913        | 24,777      | 24,777         | 27,157       | -               | 220,847       | 1,714,690        |
| TRECVID-VTT'20 [[25]](#Awad2020TRECVIDDomains)                                | 7,485            | 28,183           | -           | -              | 1,700        | -               | 9,185         | 28,183           |
| VATEX [[23]](#Wang2019VaTeXResearch)                                          | 25,991           | 259,910          | 3,000       | 30,000         | 6,000        | 60,000          | 34,991        | 349,910          |
| HowTo100M [[24]](#Miech2019HowTo100MClips)                                    | -                | -                | -           | -              | -            | -               | 139,668,840   | 139,668,840      |

## References

<a id="L.Chen2011CollectingEvaluation">[1]</a> D. L. Chen and W. B. Dolan, “Collecting highly parallel data for paraphrase evaluation,” in Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies, 2011, vol. 1, pp. 190–200.

<a id="Rohrbach2012AActivities">[2]</a> M. Rohrbach, S. Amin, M. Andriluka, and B. Schiele, “A database for fine grained activity detection of cooking activities,” in 2012 IEEE Conference on Computer Vision and Pattern Recognition, Jun. 2012, pp. 1194–1201.

<a id="Rohrbach2012ScriptActivities">[3]</a> M. Rohrbach, M. Regneri, M. Andriluka, S. Amin, M. Pinkal, and B. Schiele, “Script Data for Attribute-Based Recognition of Composite Activities,” in Computer Vision -- ECCV 2012, 2012, pp. 144–157.

<a id="Das2013AStitching">[4]</a> P. Das, C. Xu, R. F. Doell, and J. J. Corso, “A thousand frames in just a few words: Lingual description of videos through latent topics and sparse object stitching,” in IEEE Computer Society Conference on Computer Vision and Pattern Recognition, 2013, pp. 2634--2641.

<a id="Regneri2013GroundingVideos">[5]</a> M. Regneri, M. Rohrbach, D. Wetzel, S. Thater, B. Schiele, and M. Pinkal, “Grounding Action Descriptions in Videos,” Trans. Assoc. Comput. Linguist., vol. 1, pp. 25–36, Dec. 2013.

<a id="Rohrbach2014CoherentDetail">[6]</a> A. Rohrbach, M. Rohrbach, W. Qiu, A. Friedrich, M. Pinkal, and B. Schiele, “Coherent multi-sentence video description with variable level of detail,” in Pattern Recognition, 2014, pp. 184--195.

<a id="Torabi2015UsingResearch">[7]</a> A. Torabi, C. Pal, H. Larochelle, and A. Courville, “Using Descriptive Video Services to Create a Large Data Source for Video Annotation Research,” CoRR, vol. abs/1503.0, Mar. 2015, [Online]. Available: http://arxiv.org/abs/1503.01070.

<a id="Rohrbach2015ADescription">[8]</a> A. Rohrbach, M. Rohrbach, N. Tandon, and B. Schiele, “A dataset for Movie Description,” in 2015 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), Jun. 2015, vol. 07-12-June, pp. 3202–3212.

<a id="Xu2016MSR-VTTLanguage">[9]</a> J. Xu, T. Mei, T. Yao, and Y. Rui, “MSR-VTT: A Large Video Description Dataset for Bridging Video and Language,” 2016 IEEE Conf. Comput. Vis. Pattern Recognit., pp. 5288–5296, 2016, doi: 10.1109/CVPR.2016.571.

<a id="Rohrbach2016RecognizingData">[10]</a> M. Rohrbach et al., “Recognizing Fine-Grained and Composite Activities Using Hand-Centric Features and Script Data,” Int. J. Comput. Vis., vol. 119, no. 3, pp. 346–373, Sep. 2016.

<a id="Sigurdsson2016HollywoodUnderstanding">[11]</a> G. A. Sigurdsson, G. Varol, X. Wang, A. Farhadi, I. Laptev, and A. Gupta, “Hollywood in Homes: Crowdsourcing Data Collection for Activity Understanding,” in Computer Vision -- ECCV 2016, 2016, pp. 510–526, doi: 10.1007/978-3-319-46448-0_31.

<a id="Zeng2016TitleVideos">[12]</a> K.-H. Zeng, T.-H. Chen, J. C. Niebles, and M. Sun, “Title Generation for User Generated Videos,” in Computer Vision -- ECCV 2016, 2016, pp. 609–625, doi: 10.1007/978-3-319-46475-6_38.

<a id="Li2016TGIFDescription">[13]</a> Y. Li et al., “TGIF: A New Dataset and Benchmark on Animated GIF Description,” in 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), Jun. 2016, vol. 2016-Decem, pp. 4641–4650.

<a id="Awad2016TRECVIDHyperlinking">[14]</a> G. Awad et al., “TRECVID 2016: Evaluating vdeo search, video event detection, localization, and hyperlinking,” 2016.

<a id="Rohrbach2017GeneratingPeople">[15]</a> A. Rohrbach, M. Rohrbach, S. Tang, S. J. Oh, and B. Schiele, “Generating Descriptions with Grounded and Co-Referenced People,” 2017.

<a id="Krishna2017Dense-CaptioningVideos">[16]</a> R. Krishna, K. Hata, F. Ren, L. Fei-Fei, and J. C. Niebles, “Dense-Captioning Events in Videos,” in 2017 IEEE International Conference on Computer Vision (ICCV), Oct. 2017, vol. 2017-Octob, pp. 706–715.

<a id="Awad2017TrecvidHyperlinking">[17]</a> G. Awad et al., “Trecvid 2017: Evaluating ad-hoc and instance video search, events detection, video captioning and hyperlinking,” 2017.

<a id="Zhou2018TowardsVideos">[18]</a> L. Zhou, C. Xu, and J. J. Corso, “Towards Automatic Learning of Procedures from Web Instructional Videos,” in Proceedings of the AAAI Conference on Artificial Intelligence, Mar. 2018, pp. 7590--7598.

<a id="Sigurdsson2018ActorVideos">[19]</a> G. A. Sigurdsson, A. Gupta, C. Schmid, A. Farhadi, and K. Alahari, “Actor and Observer: Joint Modeling of First and Third-Person Videos,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018, pp. 7396–7404.

<a id="Mahdisoltani2018Fine-grainedCaptioning">[20]</a> F. Mahdisoltani, G. Berger, W. Gharbieh, D. Fleet, and R. Memisevic, “Fine-grained Video Classification and Captioning,” CoRR, vol. abs/1804.0, Apr. 2018. Available: http://arxiv.org/abs/1804.09235.

<a id="Awad2018TRECVIDSearch">[21]</a> G. Awad et al., “TRECVID 2018: Benchmarking Video Activity Detection, Video Captioning and Matching, Video Storytelling Linking and Video Search,” 2018.

<a id="Awad2019TRECVIDRetrieval">[22]</a> G. Awad et al., “TRECVID 2019: An evaluation campaign to benchmark Video Activity Detection, Video Captioning and Matching, and Video Search & retrieval,” 2019.

<a id="Wang2019VaTeXResearch">[23]</a> X. Wang, J. Wu, J. Chen, L. Li, Y.-F. Wang, and W. Y. Wang, “VATEX: A Large-Scale, High-Quality Multilingual Dataset for Video-and-Language Research,” in The IEEE International Conference on Computer Vision (ICCV), 2019, pp. 4581–4591.

<a id="Miech2019HowTo100MClips">[24]</a> A. Miech, D. Zhukov, J.-B. Alayrac, M. Tapaswi, I. Laptev, and J. Sivic, “HowTo100M: Learning a Text-Video Embedding by Watching Hundred Million Narrated Video Clips,” in 2019 IEEE/CVF International Conference on Computer Vision (ICCV), Oct. 2019, pp. 2630–2640.

<a id="Awad2020TRECVIDDomains">[25]</a> G. Awad et al., “TRECVID 2020: comprehensive campaign for evaluating video retrieval tasks across multiple application domains,” 2020.
