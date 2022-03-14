# DFC
大风车：抖音快手小姐姐短视频接口

接口信息：

url : https://lytcreate.com/dfc

method: get

示例调用文件：
test.py



import requests

url = 'https://lytcreate.com/dfc'

res = requests.get(url=url)

data = res.content

file = open("dy.mp4", "wb")

file.write(data)

file.close()




执行之后随机小姐姐视频 dy.mp4 就保存好啦！

提示：偶尔可能存在视频无法读取状况，重新获取即可。接口响应跟数据传输速度有关系，一般2～3s

接口仅供测试使用，切勿用于其它用途，未防止接口被恶意调用，每天限制调用次数10000次
欢迎加入交流Q群：733690997

