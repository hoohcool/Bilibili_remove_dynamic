# Bilibili_remove_dynamic
删除B站（bilibili）老旧的动态
# 使用说明：
1. 打开浏览器F12，选择为移动端模式，访问bilibili.com
2. 登录b站后，在开发者工具，应用程序中查找一config中对应的字段的值
3. 将对应的值填写进config.json文件中，设置要删除的截至年份，例如2021，则运行程序后只保留2022年的动态
4. 运行程序要求，python3.6及以上版本
5. `pip install requests`
6. `python main.py`即可看到运行结果，等待结果完成即可。
