先去每个py文件中确认包已经安装完成了，运行run_all.py文件
具体要爬的热搜前几的调整，爬取评论的页数，爬取帖子的数量在相应的文件中调整
每个文件替换自己的cookie和useragent
我调的时间间隔比较大，小一点的话就被封掉了
目前的文件是我的cookie和useragent，最好大家都换成自己的，不然几个运行的时候会出错：https://weibo.com/
我已经运行过一次了，里面的数据是我运行过的数据，如果想要在运行一次最好把：weibo_hot_search_results.csv，weibo_posts_output，weibo_comments_output，weibo_combined_output_info这四个文件删除