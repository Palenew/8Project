## rpgmaker mv API
* rpg_manager.js 管理各种json数据
* 怎么获得装备呢？
通过在各个核心js文件中搜索gain item、 change item等关键词，我们找到了获得物品的函数是放在rpg_objects.js中的Game_Party.prototype.gainItem函数。这样的话，我们也可以调用这个函数来获取装备
* 一样的对gold，money等进行搜索，我们找到了控制金钱数量的方法，Game_Party.prototype.gold等等
* **核心还是抄原来的插件，照着葫芦画瓢，就很气**
