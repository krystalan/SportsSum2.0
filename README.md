# SportsSum2.0: Generating High-Quality Sports News from Live Text Commentary
SportsSum2.0 is a Chinese sports game summarization dataset which is based on [SportsSum](https://github.com/ej0cl6/SportsSum). In short, SportsSum2.0 is the cleaned version of SportsSum. Sports Game Summarization is a challenging task, which aims to generate sports summaries (i.e., news articles) from corresponding live commentaries.

For more details pls refer to the following papers:   
[*SportsSum2.0: Generating High-Quality Sports News from Live Text Commentary*](https://arxiv.org/abs/2110.05750) Jiaan Wang et al. In Proceedings of CIKM (short), 2021.   
[*Generating Sports News from Live Commentary: A Chinese Dataset for Sports Game Summarization*](https://aclanthology.org/2020.aacl-main.61/) Kuan-Hao Huang et al. In Proceedings of AACL (long), 2020.   

BTW, our new paper *Knowledge Enhanced Sports Game Summarization* (camera ready version is still being prepared) has been accepted by WSDM 2022 as a long paper. In this paper, we provide K-SportsSum dataset which contains more data (1.45 times) than SportsSum/SportsSum2.0. K-SportsSum also contains a large-scale knowledge corpus containing information of games as well as players. More details can be found at [K-SportsSum](https://github.com/krystalan/K-SportsSum). 

## Download the Dataset
You can download the data [here](https://drive.google.com/file/d/1NnXkMqBb1BUq7WMN06t8vZqh8NrD1XZ8/view?usp=sharing)    

Each Game has four related files:  
- `news.txt`: Original news article from [SportsSum](https://github.com/ej0cl6/SportsSum).
- `[League]_[id].txt`: Cleaned news article. `[league]` indicates the which league did the game take place in, such as, Bundesliga, CSL, Europa, La Liga, etc. `[id]` is the identifier of game. 
- `live.json`: Live commentary document which contains commentary sentences, timeline information and real time scores.
- `linesup.json`: Metadata file (contains rosters, starting lineups, player positions, etc.).

## Acknowledge
Jiaan Wang would like to thank Kuan-Hao Huang, the first author of SportsSum, for his positive response.  


## Citation and Contact
If you find this data is useful or use the data in your work, please cite our paper and original SportsSum.

```
@article{Wang2021SportsSum20GH,
  title={SportsSum2.0: Generating High-Quality Sports News from Live Text Commentary},
  author={Jiaan Wang and Zhixu Li and Qiang Yang and Jianfeng Qu and Zhigang Chen and Qingsheng Liu and Guoping Hu},
  journal={Proceedings of the 30th ACM International Conference on Information \& Knowledge Management},
  year={2021}
}
```

```
@inproceedings{Huang2020sportssum,
    author    = {Kuan-Hao Huang and
                 Chen Li and
                 Kai-Wei Chang},
    title     = {Generating Sports News from Live Commentary: A Chinese Dataset for Sports Game Summarization},
    booktitle = {Proceedings of the 1st Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics (AACL)},
    year      = {2020},
}
```

Please contact Jiaan Wang (jawang1[at].stu.suda.edu.cn) for questions and suggestions.
