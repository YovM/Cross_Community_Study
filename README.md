# cross_community_study
This repository complements our recent work on the “Open Source Oriented Cross-community Survey”. The repository includes papers related to our research as well as related resources (datasets, etc.).


# Contents
-  Analysis of user characteristics.
-  Analysis of code reuse.
-  Analysis of community interactions.
- Designed experiments (Dataset(dataset name, dataset description, access link),tools used)


# Papers

## Analysis of user characteristics.
- Xiaotao Song, Jiafei Yan, Yuexin Huang, Hailong Sun, and Hongyu Zhang. A collaboration-aware approach to profiling developer expertise with cross-community data. In 2022 IEEE 22nd International Conference on Software Quality, Reliability and Security (QRS), pages 344–355, 2022.
- Jungil Kim and Eunjoo Lee. Understanding the working habits of gh-so users on github commit activity and stack overflow post activity. International Journal of Software Engineering and Knowledge Engineering, 31(10):1399–1419, 2021.
- Hongbo Fang, Daniel Klug, Hemank Lamba, James Herbsleb, and Bogdan Vasilescu. Need for tweet: How open source developers talk about their github work on twitter. In MSR ’20: Proceedings of the 17th International Conference on Mining Software Repositories, 2020.
- Sri Lakshmi Vadlamani and Olga Baysal. Studying software developer expertise and contributions in stack overflow and github. In 2020 IEEE International Conference on Software Maintenance and Evolution (ICSME), pages 312–323. IEEE,2020.
- Roy Ka-Wei Lee and David Lo. Wisdom in sum of parts: Multi-platform activity prediction in social collaborative sites. In Proceedings of the 10th ACM Conference on Web Science, pages 77–86, 2018.
- Roy Ka-Wei Lee and David Lo. Github and stack overflow: Analyzing developer interests across multiple social collaborative platforms. In Social Informatics: 9th International Conference, SocInfo 2017, Oxford, UK, September 13-15, 2017,Proceedings, Part II 9, pages 245–256. Springer, 2017.
- Yunxiang Xiong, Zhangyuan Meng, Beijun Shen, and Wei Yin. Developer identity linkage and behavior mining across github and stackoverflow. International Journal of Software Engineering and Knowledge Engineering, 27(09n10):1409–1425, 2017.
- Ali Sajedi Badashian, Abram Hindle, and Eleni Stroulia. Crowdsourced bug triaging: Leveraging q&a platforms for bug assignment. In Fundamental Approaches to Software Engineering: 19th International Conference, FASE 2016, Held as Part of the European Joint Conferences on Theory and Practice of Software, ETAPS 2016, Eindhoven, The Netherlands,April 2–8, 2016, Proceedings 19, pages 231–248. Springer, 2016.
- Leif Singer, Fernando Figueira Filho, and Margaret-Anne Storey. Software engineering at the speed of light: how developers stay current using twitter. In Proceedings of the 36th International Conference on Software Engineering, pages 211–221,2014.
- Ali Sajedi Badashian, Afsaneh Esteki, Ameneh Gholipour, Abram Hindle, and Eleni Stroulia. Involvement, contribution and influence in github and stack overflow. In CASCON, pages 19–33, 2014.
- Bogdan Vasilescu, Vladimir Filkov, and Alexander Serebrenik. Stackoverflow and github: Associations between software development and crowdsourced knowledge. In 2013 International Conference on Social Computing, pages 188–195. IEEE,2013.


## Analysis of code reuse.
- Yuan Huang, Furen Xu, Haojie Zhou, Xiangping Chen, Xiaocong Zhou, and Tong Wang. Towards exploring the code reuse from stack overflow during software development. In Proceedings of the 30th IEEE/ACM International Conference on Program Comprehension, pages 548–559, 2022.
- Saraj Singh Manes and Olga Baysal. Studying the change histories of stack overflow and github snippets. In 2021 IEEE/ACM 18th International Conference on Mining Software Repositories (MSR), pages 283–294, 2021.
- Saraj Singh Manes and Olga Baysal. How often and what stackoverflow posts do developers reference in their github projects? In 2019 IEEE/ACM 16th International Conference on Mining Software Repositories (MSR), pages 235–239. IEEE, 2019.
- Sebastian Baltes and Stephan Diehl. Usage and attribution of stack overflow code snippets in github projects. Empirical Software Engineering, 24(3):1259–1295, 2019.
- Di Yang, Pedro Martins, Vaibhav Saini, and Cristina Lopes. Stack overflow in github: any snippets there? In 2017 IEEE/ACM 14th International Conference on Mining Software Repositories (MSR), pages 280–290. IEEE, 2017.

## Analysis of community interactions.
- Hongbo Fang, Bogdan Vasilescu, and James Herbsleb. Understanding information diffusion about open-source projects on twitter, hackernews, and reddit. In 2023 IEEE/ACM 16th International Conference on Cooperative and Human Aspects of Software Engineering (CHASE), pages 56–67. IEEE, 2023.
- Hongbo Fang, Hemank Lamba, James Herbsleb, and Bogdan Vasilescu. ”this is damn slick!”: Estimating the impact of tweets on open source project popularity and new contributors. In ICSE ’22: Proceedings of the 44th International Conference on Software Engineering, 2022.
- Hao Huang, Yao Lu, and Xinjun Mao. Gathering github oss requirements from q&a community: An empirical study. In 2020 25th International Conference on Engineering of Complex Computer Systems (ICECCS), 2020.
- Chenxi Song, Tao Wang, Gang Yin, Xunhui Zhang, and Cheng Yang. A novel open source software ecosystem: From a graphic point of view and its application. In SEKE, pages 71–74, 2016.
- Huaimin Wang, Tao Wang, Gang Yin, and Cheng Yang. Linking issue tracker with q&a sites for knowledge sharing across communities. IEEE Transactions on Services Computing, 11(5):782–795, 2015.
- Bogdan Vasilescu, Alexander Serebrenik, Prem Devanbu, and Vladimir Filkov. How social q&a sites are changing knowledge sharing in open source software communities. In Proceedings of the 17th ACM conference on Computer supported cooperative work & social computing, pages 342–354, 2014.
- BORGES Hudson Silva and VALENTE Marco Tulio. How do developers promote open source projects?

# Designed experiments
## Dataset

| Dataset Name/Related Study            | Dataset Description                                                                                                                     | Access Link                                                                                                                                                  |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **GHTorrent**                         | Gathered more than 900GB of raw data and 10GB of metadata, encompassing millions of events, commits, and other entities.                | [GitHub Mirror](https://github.com/gousiosg/github-mirror)                                                                                                    |
| **SOTorrent**                         | 38.4 million Stack Overflow posts, extracted 11 million URLs, and identified 5.81 million post links in 430,521 GitHub projects.        | [Zenodo - SOTorrent](https://zenodo.org/records/1196296) (Note: Multiple dataset versions for different periods are available on Zenodo.)                     |
| **Stack Overflow Data Dump**          | Archived Stack Overflow content, including posts, polls, tags, badges, etc (Updated every quarter).                                      | [Internet Archive - Stack Exchange](https://archive.org/download/stackexchange)                                                                              |
| **Mailing Lists Archive (r-help)**    | Provided r-devel, r-help, r-package-devel, r-sig-mac, and etc.                                                                          | [ETH Zurich Mailing Lists](https://stat.ethz.ch/mailman/listinfo)                                                                                             |
| **GH Archive**                        | Provided GitHub activities such as coding, documentation, and other contributions (Updated every hour).                                  | [GH Archive](https://www.gharchive.org/)                                                                                                                     |
| **Fang-tweet-impact**                 | 15,975 original tweets, 28,569 retweets, 2,370 GitHub projects (2018-11-01 to 2019-04-30).                                               | [Zenodo DOI: 10.5281/zenodo.6321448](DOI: 10.5281/zenodo.6321448)                                                                                            |
| **Fang-2020-Need-for-Tweet**          | 70,427 GitHub-Twitter user pairs.                                                                                                       | [Zenodo DOI: 10.5281/zenodo.3711629](DOI: 10.5281/zenodo.3711629)                                                                                            |
| **Manes-code-snippets**               | 22,900 projects, 33,765 SO references mapped to 4,634 SO posts, 73,322 commits.                                                         | [GitHub - GHCodeSnippetHistory](https://github.com/manessaraj/GHCodeSnippetHistory)                                                                           |
| **badashian2014involvement**          | 255,375 GitHub-Stack Overflow user pairs (2008-09-01 to 2013-08-31).                                                                    | [University of Alberta - Merged Dataset](http://hypatia.cs.ualberta.ca/~alisajedi/Mining_GH_and_SO-MergedDataSet.zip)                                         |
| **Zhang-devrec**                      | 136 popular projects, 99 unpopular projects (2014-09-14 to 2016).                                                                       | [Trustie - Statistics](https://www.trustie.net/statistics/5)                                                                                                  |



# Cites


  





