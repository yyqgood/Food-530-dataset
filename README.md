# Food-530 dataset

<img width="1000" alt="Screenshot 2019-08-18 at 3 53 06 PM" src="https://user-images.githubusercontent.com/35621763/63221793-bbd27100-c1d0-11e9-84df-b6916c9cca4e.png">

Food recognition is the key technology to automatic dietary assessment. Existing datasets for food recognition mainly contain Western and Japanese food, however, few Chinese food. In this project, we construct and release a new dataset called **Food-530**, which contains **392,183** food images from **530** categories, including Chinese food, Japanese food, Western food, and so on. This is currently the biggest Chinese food dataset.

The food categories are pupular dishes which were compiled from "Xinshipu". We collect food names from [this website](https://www.xinshipu.com/) by using Python Beautiful Soup. Images in the dataset were crawled from Baidu image by using Selenium. Besides, we also collected data from [Food-101](https://www.kaggle.com/kmader/food41) (contains 101 categories, 101,000 images) and [VireoFood-172](http://vireo.cs.cityu.edu.hk/VireoFood172/) (contains 172 catogories, 110,241 images) and translated food names into Chinese. We appreciate Food-101 and City University of Hong Kong for sharing the dataset.



# Statistics
**Number of Images:** 392,183 

**Number of Categories:** 530

**Food Names (in Chinese):**

'鳄梨酱', '日式炸猪排', '椰子补丁', '凯撒沙拉', '炒年糕', '咸水鸭', '排骨汤', '龙抄手', '土豆', '清蒸鱼', '果汁', '红烧鸡翅', '奶酪通心粉', '炒豆腐皮', '馄饨', '章鱼烧', '紫菜包饭', '芒果', '马蹄糕', '菠萝', '芒果糯米饭', '疙瘩汤', '牛排', '栗子', '饺子', '绿豆汤', '希腊沙拉', '乌冬面', '巧克力', '叉烧包', '干锅花椰菜', '龙井虾仁', '法国甜甜圈', '锅包肉', '石榴', '焦糖奶油', '桑葚', '奶酪三明治', '油炸花生', '手抓饼', '海带汤', '绿豆糕', '卷饼', '番茄炒蛋', '回锅肉', '泡芙', '糖醋鱼', '糖醋排骨', '香炸奶酪卷', '彩椒', '紫菜汤', '酥肉', '马卡龙', '香菇炖鸡', '吐司', '草莓蛋糕', '汉堡', '虾仁炝香芹', '洋葱圈', '秋葵炒鸡蛋', '凉拌黄瓜', '山竹', '蒜香排骨', '北京烤鸭', '夫妻肺片', '九转大肠', '鹅肝', '酸辣土豆丝', '牛肉面', '番石榴', '虾米沙拉', '菠萝炒饭', '加吉鱼刺身', '八宝饭', '清炒虾仁', '大饼卷鸡蛋', '姜茶', '人参果', '法式薯条', '红烧带鱼', '青椒炒鸡蛋', '凉拌木耳', '清炒山药', '蓝莓山药', '猪排', '扇贝', '驴肉火烧', '甜瓜', '荷包蛋', '小龙虾', '海胆刺身', '蛤蜊杂烩', '高汤', '紫菜蛋花汤', '海绵蛋糕', '墨鱼刺身', '鹰嘴豆', '姜汤', '鲫鱼豆腐汤', '煎蛋', '蛋挞', '小番茄', '奶茶', '酸橘汁腌鱼', '猪肉炖粉条', '咖喱角', '山药粥', '水饺', '黄焖鸡米饭', '咖喱饭', '猕猴桃', '土豆饼', '红醋栗', '哈密瓜', '柑橘', '四川泡菜', '糯米糍', '麻花', '醋青花鱼刺身', '蟹肉馅饼', '蒜苗炒肉丝', '蟹黄豆腐', '酒酿圆子', '果冻', '烤干酪辣味玉米片', '糖醋里脊', '皮蛋瘦肉粥', '盐焗鸡', '泡椒牛蛙', '柚子茶', '沙拉', '蒜苗炒腊肉', '银耳红枣汤', '凉拌西兰花', '重庆火锅', '胡萝卜蛋糕', '雪糕', '蒸鸡', '萝卜糕', '凉拌豆苗', '毛豆', '佛跳墙', '柚子', '葱烧海参', '巧克力蛋糕', '慕斯', '薏米水', '法式洋葱汤', '奶昔', '乌鸡汤', '炸鸡腿', '杨桃', '提拉米苏', '鱼香肉丝', '小米粥', '炒苦瓜', '玉米沙拉', '油条', '洋葱', '冰淇淋', '牛杂火锅', '猪肉三明治', '酸豆炒肉末', '酸辣粉', '油饼', '味噌汤', '金枪鱼', '薄饼', '生鱼片', '墨西哥煎蛋', '蘑菇炒青菜', '五香毛豆', '蒸肉', '干锅茶树菇', '凉粉', '韩国拌饭', '蛇皮果', '八宝粥', '百香果', '牛油果', '蘑菇炖鸡', '酱排骨', '香辣蛤蜊', '草莓', '酥饼', '天妇罗', '干煸豆角', '海鲜饭', '肉末茄子', '鞑靼牛排', '肠粉', '芝士鸡蛋', '白斩鸡', '甜甜圈', '青笋炒肉', '米糕', '可丽饼', '味增汤', '纸杯蛋糕', '刀削面', '热干面', '鸡翅', '烧卖', '南瓜饼', '牛肉汤', '丝绒蛋糕', '风味茄子', '蒸排骨', '京酱肉丝', '兰州拉面', '杨枝甘露', '华夫饼', '意式生牛肉片', '炸鸡翅', '咖啡', '手撕鸡', '鸡丝', '木须肉', '大饼', '香菇炒肉', '球茎甘蓝', '烤乳猪', '鲜虾花甲汤', '糯米藕', '拍黄瓜', '汤圆', '酸奶', '椰子', '蒜茸海带丝', '肉汁奶酪', '小鸡炖蘑菇', '烤鱿鱼', '炒饭', '鸡汤', '菲力牛排', '铜锣烧', '炒南瓜', '橙子', '披萨', '铁板鱿鱼', '葡萄柚', '蓝莓', '榅桲果', '担担面', '油焖大虾', '泡椒凤爪', '酱油鸡', '丝瓜炒鸡蛋', '大酱汤', '薄煎饼', '松鼠鱼', '蜜糖果仁千层酥', '卡博纳意大利面', '蒸糕', '凉拌腐竹', '金汤肥牛', '青口贝', '法式蜗牛', '炸虾', '烧麦', '岐山面', '烤三文鱼', '炒莲藕', '盐水菜心', '油炸虾', '豆浆', '麻辣香锅', '酱骨架', '芝士蛋糕', '铁板豆腐', '韭菜炒鸡蛋', '羊肉泡馍', '仙人掌果', '炖排骨', '红豆糕', '蚂蚁上树', '红烧排骨', '排骨粥', '猪肝汤', '法式吐司', '东坡肉', '辣炒鱿鱼丝', '芹菜炒豆干', '剁椒鱼头', '腊肠炒荷兰豆', '红烧豆腐', '石锅拌饭', '鸡蛋糕', '炒米粉', '冬瓜汤', '糯米鸡', '梅菜扣肉', '荔枝', '酸菜', '奶酪', '照烧鸡腿', '三杯鸡', '千层面', '西湖醋鱼', '排骨莲藕汤', '烧茄子', '曲奇', '糯米团子', '炒菠菜', '香蕉', '蒸蛋', '过桥米线', '柠檬', '炒鱿鱼', '冰沙', '蒜泥粉丝娃娃菜', '饭团', '青椒肉丝', '糖蒜', '胡辣汤', '鲈鱼刺身', '馄饨面', '辣子鸡', '咖喱牛肉', '包子', '炸糕', '茄子炒豆角', '牛奶布丁', '牛排上肋', '生蚝', '皮蛋豆腐', '橘子', '麻辣小龙虾', '鸡蛋汤', '榛子', '千层饼', '克罗克夫人三明治', '鸡鳊馅饼', '煎饼果子', '炒青椒', '春饼', '巧克力慕斯', '覆盆子', '双皮奶', '烤面筋', '干锅牛蛙', '玉米羹', '梨', '蟠桃', '煎饼', '炸鸡', '手撕包菜', '宫保鸡丁', '海藻沙拉', '凉拌苦瓜', '泰国咖喱', '炒鸡', '米饭', '锅贴', '葱爆羊肉', '拉面', '番茄', '黑米粥', '杏', '麻婆豆腐', '烤土豆', '日式烤鳗鱼', '烧饼', '桃', '南瓜粥', '寿司', '煎饺', '煲仔饭', '桔柚', '肉包子', '仔排', '酸菜鱼', '水煮鱼', '龙虾卷三明治', '鱼头汤', '沙拉三明治', '红烧牛肚片', '意大利肉酱面', '冬瓜排骨汤', '酸辣白菜', '意式烤面包', '冰冻酸奶', '樱桃', '枣', '白切鸡', '家常豆腐', '凉拌金针菇', '拌饭', '蔬菜汤', '茶叶蛋', '凉面', '核桃', '皮蛋', '日式肥牛饭', '白葡萄', '粉丝蒸扇贝', '凉拌茄子', '鱼汤', '酸辣汤', '番茄炒鸡蛋', '大盘鸡', '豆瓣鸡爪', '炒鸡蛋', '三明治', '烤茄子', '椰汁糕', '卤肉饭', '月饼', '水煮肉片', '红皮土豆', '柿子', '酱牛肉', '红烧猪蹄', '酸梅汤', '怪味鸡蛋', '土豆泥', '春卷', '油桃', '咕噜肉', '炸春卷', '松仁玉米', '甜菜沙拉', '鸭脖', '三文鱼刺身', '土豆炖牛肉', '蒜泥白肉', '红烧鱼', '清蒸大闸蟹', '蒸蛋糕', '葱油饼', '炖肉', '蛇果', '布丁', '干锅鸭头', '豆腐汤', '拔丝苹果', '热狗', '青苹果', '皮皮虾', '酸辣蕨根粉', '凉拌海带', '汉堡包', '蘑菇汤', '小笼包', '蛋包饭', '白菜猪肉炖粉条', '蘑菇炒猪肉', '通心粉', '鱼香茄子', '炖鸡', '红金枪刺身', '烤鱼', '牛尾汤', '羊肉汤', '扬州炒饭', '蚝油生菜', '馅饼', '辣椒酱', '口水鸡', '炒煮鸡蛋', '木须炒肉', '白糖糕', '粉蒸肉', '拔丝地瓜', '炒螺丝', '焗饭', '北极贝', '红烧肉', '猪肚汤', '黑浆果', '烤鸡', '红烧狮子头', '韩国泡菜', '火龙果', '孜然羊肉', '肉夹馍', '李子', '金桔', '红烧鸡', '辣椒炒肉', '香辣虾', '龙虾浓汤', '盖浇饭', '苹果派', '牛肉串', '北京火锅', '炸藕盒', '汤面', '花卷', '粽子', '香菇油菜', '骨头汤', '烤肉', '烤韭菜', '面包布丁', '拔丝山药', '炒饼', '水果沙拉', '炸酱面', '青柠', '糍粑', '意大利烩饭', '鸡蛋饼', '咖喱鸡', '梅花糕', '苹果', '烤鸡翅', '西米露', '发糕', '木瓜', '糖葫芦', '蒜香面包', '烧鸡', '卡普雷色拉', '红烧牛肉', '红豆沙', '芒果布丁', '炖牛肉', '鱼和薯条', '炒面', '稀饭', '葡萄', '四喜丸子', '凉拌银耳', '臭豆腐', '鸭血粉丝汤', '虾尾', '玉米饼', '苦瓜炒鸡蛋', '叉烧饭'


**Examples:**




# Download
The dataset is categorized by names, each category has 500 to 1000 images. You can obtain the dataset by sending an email to NUS AI Innovation and Commercialization Centre at Suzhou (NUS AI Center in short, aicenter@nusri.cn). Specifically, the researchers interested in Food-530 should download and fill up this [Agreement Form](https://drive.google.com/file/d/1gNIp3uFtCwtFQnLW9xKvTzJ-uBk5wbkO/view?usp=sharing) (if you are in China, you can click [here](https://wenku.baidu.com/view/7204647c7d1cfad6195f312b3169a4517623e526) to download) and send it back to NUS AI Center.
