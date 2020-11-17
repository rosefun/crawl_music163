# crawl_music163



### Code

1. get_all_singers.py

   这部分程序用于提取网易云音乐中所有的歌手（包括乐队，以及网易云入驻的音乐人）及他们在网易云音乐中的id.

2. data_crawling.py

   这部分主要根据第一部分的网易云歌手的id，来爬取这个歌手所有专辑，以及专辑的每一首歌及这首歌在网易云音乐的id；

3. comments_num_crapy.py

   这部分主要根据第二部分提取的歌的id，来爬取这首歌的精彩评论及评论数。

   如果爬取频繁，id会被封，可以改良使用ip代理，这部分尝试还没成功。



### result

对应上面三个程序，all_singer.csv 是第一个程序爬取的结果；songs_of_singer_info是第二个程序爬取的结果；comments_num是第三个程序爬取的结果。

