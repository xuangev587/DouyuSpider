# DouyuSpider
程序利用beautifulsoup 对斗鱼连接的解析，获取到直播室的基本信息，然后将信息写入到数据库。
由于斗鱼主页的每个页面最后只能显示120个直播间。并且斗鱼使用了js分页，目前还没有发现分页的明确规律
由于斗鱼的关注数是使用gif加载的形式，目前还没有找到合适的方法获取其每个直播间的关注数信息
完善了斗鱼在线实际人数的获取
