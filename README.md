# bert_sts-b
从tensorflow版的run_classifier.py和run_scorer.py上修改的用来算文本相识度的模型。
对不对的不保证。本人菜鸡且不清楚sts-b原来那个task到底是做分类还是回归，也不清楚那个task是怎么评价的。我只是为了完成一个课的期末发表。

bert基础上finetune3回合的模型，不分类直接回归算分数。
训练数据用的是sts-b
用来做日本センター試験英语卷6B的52-55题タイトル付与
exam2014是2014年考卷，以此类推。
