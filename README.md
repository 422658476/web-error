## 把互联网标准出卖给扩展（ublock、adblock、adguard或其他扩展）的浏览器企业 | Browser companies that sell Internet standards to extensions (ublock, adblock, adguard, or others)

### ![](./img/mpv-logo-128.png)  🌐 Language of this page  : `中文` | [`English`](https://github-com.translate.goog/422658476/web-error?_x_tr_sl=zh-CN&_x_tr_tl=en&_x_tr_hl=zh-CN&_x_tr_pto=wapp)

作者： https://github.com/422658476/

原文地址：https://github.com/422658476/web-error

授权：Welcome to translate and reprint | 欢迎翻译和转载

互联网应该是人类历史上最伟大的发明之一，它让我们的生活变的更加的有趣，信息和智慧也因此能够比书籍快上许多倍的速度传输和传递给需要的人，很多公司也依靠互联网进行盈利。

在这其中浏览器和网页渲染标准都是功不可没的，html、css、js的功能和标准至关重要，只有所有的浏览器进行相同标准的渲染，大家看到的网页才能完全一致，如果你的年纪稍微有点大，并且制作过网页，那么肯定经历过兼容ie6的可怕经历，也对其深恶痛绝。

所以，互联网企业，尤其是研发浏览器（拥有自己渲染引擎）的公司，以及参与互联网标准制定的团体和个人就至关重要，没有他们的努力也没有现在的美好，现在网页制作也比以前容易的多，因为通常无需担心兼容性问题。

但这些公司和团体制定完标准，浏览器公司却扭头就把这些标准出卖给了：浏览器扩展。由于对扩展的审核的宽松或者没有审核，导致浏览器不仅没有成为网页的乐园，而是成为了浏览器扩展的后花园，一句话：我（浏览器扩展）自己就是标准，我让你能够执行才能执行，我觉得你能执行才能执行，我觉得这个不需要就可以不显示，而网页没有任何反抗的权力。

而这些可怕的心得是和ublock、adblock、adguard等广告过滤扩展进行了几年的斗争后获得的（为了对抗这些互联网乞丐，他们甚至还不如乞丐，才有了花费了大量时间和精力制作的【banana detect adblock】 ，并且这段代码还不能完全阻止这些不公平，你还可以从代码和代码的使用说明中看到为了阻止这些不公平进行了多少不必要的修改），这些扩展从浏览器获得权限之后，就完全滥用这些给予它们的功能和权力，它们把互联网标准当作擦屁股的纸一样扔进了抽水马桶，最后按下开关把它们冲进了下水道，在这其中浏览器企业自己也负有很大的责任。

作为一个浏览器，它带有渲染html、css、js的功能，这些功能对于任何人、任何一段代码来说都是标准的，只要你输入一段正确的指令，那么你就可以获得想要的正确结果。

所以浏览器不光可以使用这些技术来渲染网页，这些技术也可以套用在其他地方，比如制作成扩展运行在浏览器中，甚至还能制作成程序。

看到这边你一定会坚信：由于网页和浏览器扩展都是运行在浏览器中的，所以网页和浏览器扩展都使用相同的html渲染引擎、css渲染引擎、js渲染引擎，所以相同一段代码，不管是在网页中加载还是在扩展中加载都会得到相同的结果，因为它们遵守同一套规范，现实真的是这样吗？

很不幸，现实就像是这篇文章上面说的那样，当遇到ublock、adblock、adguard等广告过滤扩展，这些公有标准在浏览器中完全失效了，所有的渲染都变成了ublock、adblock、adguard等广告过滤扩展的私有标准（在这其中ublock是最不守规矩的，也是最没底线的），这些私有标准在运行时甚至是带有个人感情色彩（完全偏向自己有利的一面），甚至能够选择性执行，甚至执行能够给出错误结果的，请问这叫“标准”吗？这样的人可以定义“标准”吗？这样定义的“标准”你接受吗？

打个比方，浏览器就像是一个建好了标准赛道的体育馆，网页和扩展就像是进行比赛跑步的运动员和裁判（扩展是裁判吗？？就当它是裁判吧）。

突然有一天体育馆工作人员和你说，今天裁判也想和你来场50米赛跑，我觉得没有问题啊，比就比嘛，当发令枪响后，这个上场比赛的裁判当众打断了你2条腿，然后一个人跑过了终点。

为什么？

上场比赛的裁判：和我比跑步你不能有脚。

？？？？？？？？？？你让我飞过去？

上场比赛的裁判：不行，和我比赛不能飞。

？？？？？？？？？？？

上场比赛的裁判：这么和你说吧，只要和我比赛，只准我赢。

。。。。。。。。。请问一个在体育馆里和其他人公用一片场地的人是否可以根据自己的喜好随便改建跑道、另定规则等东西？？？？？

作为一个扩展是如何做到这样的，接下来就解释给你听，如果你觉得这些不切实际，那么大可以通过在任意一个网站（ublock、adblock、adguard中对此网站带有特定过滤规则）上开启/关闭这些扩展比较结果的差异。

如果你看不懂或不了解，也没有关系，请浏览ublock的wiki的页面【 https://github.com/gorhill/uBlock/wiki 】（你只要看页面上的【My filters pane 】【My rules pane】页面和它们的子页面即可），上面对ublock功能的说明赤裸裸的告诉你它在干什么损人只利己的事情，这时还是要问一句，谁给这些扩展这些权力做这些事的？浏览器：我不知道啊，我真的不知道。

### ublock、adblock、adguard或其他广告过滤扩展的罪责：

#### 1、禁止网页中的js代码使用指定功能。

+js(no-setTimeout-if 			//禁止网页中的js使用settimeout功能

+js(abort-current-script, jQuery 			//禁止网页中的js使用使用jq

+js(abort-current-script, document.writeln 			//禁止网页中的js使用document.writeln功能

当然这些只是冰山一脚，实际上只要是js带有的任何功能，只要ublock、adblock、adguard或其他广告过滤扩展和其过滤器维护者需要，都可以禁用。

比如禁止使用if，禁止使用window.onload，禁止使用function()，禁止使用document.getElementById，禁止使用element.innerHTML。

你会说，如果网页中的js连这些功能都不能使用，那js还能用吗？

实际上是广告过滤扩展和其过滤器维护者觉得你的网页不需要js或者有些功能，那就可以禁止你使用，他们觉得行就行，为什么，因为你正在用这些功能检测广告过滤扩展是否启用（只能我限制和干扰你，你不能限制和干扰我，这里我最大）。

你知道吗，这些行为在这些扩展中是用js代码实现的，因为ublock wiki页面上就可以看到这些功能大都是.js结尾的，也就是说在同一时间，扩展在用着所有的js功能，并通过它们来限制你使用js，相同的js解释器，它只为【扩展】正常服务，却不为它真正的目标【网页】进行服务，你也没有任何方法能在网页中反过来限制扩展使用指定js功能，谁给这些扩展权力做这些事的？浏览器：我不知道啊，我真的不知道。

#### 2、滥用CSP（内容安全策略 Content-Security-Policy）

或许你从来不知道还有这么个东西，但通过搜索引擎很容易就可以知道它的功能：当在页面启用csp后，可以保护网页不被其他代码注入。

由于扩展都是通过浏览器给与的api注入到你的网页中的，所以当开启ublock、adblock、adguard这些广告过滤扩展后，在浏览器的【web开发者工具】（也就是右键菜单中的检查，或者f12快捷键调出的调试界面）的【查看器】中，可以看到页面的</header>和</body>（元素尾部）之前载入了很多默认网页上根本没有的东西，这些都是广告过滤扩展加入的。

你会发现广告过滤扩展添加的东西永远都在你加载的元素的更后面，为什么，因为可以覆盖你的行为啊，当然这边就不讨论这些完全无赖一样的操作了。

看到这边你会发现，如果给网页添加CSP，比如仅允许网址本身载入的内联js代码能够运行，那么不就可以阻止这些额外的外部内容加载到页面中了吗？

当你添加了这些csp，你会在【查看器】中看到，扩展添加的外部内容都消失了。。。。真的消失了吗？。。。实际上它们还在运行着，只是你看不见而已，因为它们依旧发挥着作用。

也就是说，浏览器扩展可以完全无视CSP的存在，那就奇怪了，csp这个标准制定了有什么意义？浏览器：我不知道啊，我真的不知道。

也就是说，想要偷取一个网页中的机密数据，根本不需要利用什么跨站漏洞啊，注入啊，写个扩展随便偷。

这是你使用csp时候的情况，那如果ublock、adblock、adguard这些广告过滤扩展给你的网站添加csp规则会什么样？

啊？广告过滤扩展保护我的网页，有这种好事情？

真的有这种好事情，比如:

```
xxx.com^$inline-script
```

这条代码什么含义，查看ublock wiki页面就可以知道，使用csp功能禁止你的网站使用所有内联js（你说我还可以用外联js啊。。。哈哈哈哈，扩展们都笑了），就像是绑住了你的双手双脚，这个时候这些广告过滤扩展就可以开始群魔乱舞了，因为此时它们根本不受这个限制。

扩展：什么是csp？有这种东西吗？

那请问：csp是用来保护谁的？浏览器：我不知道啊，我真的不知道。

#### 3、根本无视css的优先级标准和类似标准。

我们都知道css中是带有优先级的，通常为：

ID 选择器（例如 #example） >   类选择器 (例如 .example） >  类型选择器（例如 h1）。

也就是css中的样式如果指定的对象越详细，那么这个样式优先级越高越不容易被覆盖。

如果你的网页中带有：

```
body > div > div#page_id(max-height: 300px;)
```

但在ublock、adblock、adguard这些广告过滤扩展中,你的网页被添加了这样一行css样式：

```
body > div *{max-height: auto;}
```

请问div#page_id元素的高度是多少，相信所有人都认为是300px，因为【\*】这种最为抽象的通配符的优先级是最低的。

但最后页面显示的高度却是auto，在【查看器】中可以看到解释：因为某个过滤器使用了这个规则。也就是只要扩展对某个元素添加了某种样式，你就算ID 选择器带上!important它都不会生效，以扩展给的样式为准，现实中这些扩展还总是比你先用!important。

打个比方就是：一年级一班的小明穿蓝色校服 >  一年级一班穿绿色校服 > 全校都穿红色校服。小明最后肯定是穿蓝色校服。

但隔壁面店来了个送外卖的，说了一声全校都要穿紫色校服，结果全校每个人都必须要穿紫色校服了。。。。。。（请猜猜校长此时的心情：啊？今天我也要穿紫色校服？）

#### 4.抹掉它认为所有没有用的html元素、内容或者id、class等标记。

ublock、adblock、adguard或其他广告过滤扩展中如果给你网页添加了下面这行代码。

```
+js(ra, id, #page > div:not(#site-header-menu))
```

那么div#page包含的儿子辈div（孙子辈的div不涉及）的所有id都会被自动删除（除了名字叫做site-header-menu的id）。

这样就可以防止你使用document.getElementById('___id___').innerHTML = "在带有【___id___】id名的元素中插入的内容";

当然，它也能够直接删除带有指定文字的元素，比如文章中带有一个【a】字，通过规则就可以删除带有a字的文章所有内容，但通常他们都是反过来，除了文章内容，抹掉所有其他对他们有威胁的文字内容。

#### 5、扩展能够让js解释器给出错误的计算结果。

ublock、adblock、adguard或其他广告过滤扩展中如果给你网页添加了下面这行代码。

比如+js(set, var_xxxx_test, 1)         意思：扩展主动帮你把 var_xxxx_test这个变量的值设置为1

js解释器会给出什么可笑的结果（以ublock为例）：

例子1：

```
if (typeof var_xxxx_test == "undefined") {

}else{
	var_xxxx_test = null;
	if(var_xxxx_test == null){
		//正常情况下，js解释器给出的结果为跳转到此处，因为var_xxxx_test = null
		//Under normal circumstances, the result given by the js interpreter is to jump here, because var_xxxx_test = null
	}else{
		//当扩展给你设置这个变量值之后，js解释器会跳转到此处，也就是var_xxxx_test 依旧为 1
		//When the extension sets this variable value for you, the js interpreter will jump here, that is, var_xxxx_test is still 1
	}
}
```

例子2：
我们稍微修改一下代码

```
if (typeof var_xxxx_test == "undefined") {

}else{
	var_xxxx_test = 999;
	if(var_xxxx_test == null){
			
	}else{
		//正常情况下，js解释器给出的结果为跳转到此处，因为var_xxxx_test = 999
		//Under normal circumstances, the result given by the js interpreter is to jump here, because var_xxxx_test = 999
			
		//当扩展给你设置这个变量值之后，js解释器会跳转到此处，也就是var_xxxx_test =  999
		//When the extension sets this variable value for you, the js interpreter will jump here, that is, var_xxxx_test = 999
	}
}
```

为什么会出现这么匪夷所思的现象，实际上只要站在ublock、adblock、adguard这些广告过滤扩展的立场思考很简单。

当ublock、adblock、adguard这些广告过滤扩展主动给变量赋值，说明如果网页中这个变量没有或者为null，有些js可能没有正常加载，我们只要通过js检测到【没有这个变量】或者【这个变量为null】，就说明广告过滤扩展开启了。

当扩展给变量主动赋值，其实给与的是【这个变量一定要有某个值】这个命令，甚至值不对都行。

也就是说+js(set, var_xxxx_test, 1)  

可以让变量禁止被负值为null。浏览器：我不知道啊，我真的不知道。

从这些现象可以看处，网页js代码使用js解释器之前，还要给扩展“审核”一下代码才会被执行，也就是说，扩展不喜欢的代码可以不执行，扩展说不行就不行。

请问这还是一个js解释器吗？为什么要给扩展这种权限？？？？？？

#### 6、选择性的执行相同的js命令

2段代码，一段使用js往指定元素中插入菜单，一段使用js往另一个指定元素中插入"请关闭广告过滤扩展"文字

	setTimeout(function(){
		......
			document.getElementById('menu').innerHTML = "html菜单内容|html menu content";
		......
	}, 999);

	setTimeout(function(){
			......
			document.getElementById('xxxx').innerHTML = "请关闭广告过滤扩展|Please turn off the ad filter extension";
			......
	}, 4444);
    
ublock、adblock、adguard或其他广告过滤扩展中如果给你网页添加了下面这行规则。

比如xxxx.com##+js(nostif, .innerHTML)  意思：禁止包含.innerHTML的settimeout执行

理论上应该是2段代码同时失效，但是在ublock开启时，你可能会发现上面那段代码能够执行，而下方那段代码却无法执行。

如果你使用第三段类似的代码来测试这个现象时：

	setTimeout(function(){
		......
			document.getElementById('menu_aaaaa').innerHTML = "html菜单内容|html menu content";
		......
		......
			document.getElementById('xxxx_aaaaaa').innerHTML = "请关闭广告过滤扩展|Please turn off the ad filter extension";
		......
	},2222);
    
你可能会发现第三段代码中2个innerHTML行为

1、上面一个执行，下面一个不执行

2、下面一个执行，上面一个不执行

3、2个都执行

4、2个都不执行

扩展好像在猜测行为，看哪种运行方式后你不关闭广告过滤扩展。

但当多个规则中，有个规则带有【menu】、【menu_aaaaa】字眼，那么插入菜单功能又肯定会无效，也就是只要和一堆规则中有关的行为，就会被禁用。

请问这还是一个js解释器吗？？？？？？？

#### 7、完全不抛出该有的控制台error，不能够捕获该有的error。

广告过滤扩展通常在执行下方这个规则后，

@@||cpro.baidu.com/cpro/ui/rt.js$domain=xxx.com 			//意思：阻止加载rt.js链接 ，也就是js链接加载错误，通常这会抛出error并且能够被捕获
||cpro.baidu.com/cpro/ui/rt.js$script,redirect=noop.js,domain=xxx.com,important  			//意思：阻止加载rt.js链接后让rt.js跳转到noop.js，假装它成功加载了

不管是【web开发者工具】的控制台（红色文字显示这种行为的错误），还是

```
window.addEventListener('error',function(event) {	
	if(event.target.tagName == "SCRIPT" || event.target.tagName == undefined){

	}
},true);
```

都应该能收集到错误，这个应该是浏览器遇到链接加载错误的标准的抛出error的行为。

但当在ublock中出现下面或者类似的规则后：

\*$script,redirect-rule=noopjs,domain=xxx.com 			//意思所有链接都被阻止并跳转到noop.js，假装它们成功加载了

【web开发者工具】的控制台和window.addEventListener一切正常，平安无事，为什么要给扩展这种权限。浏览器：我不知道啊，我真的不知道。

当然还有其他更多的罪责。。。。欢迎补充。

如果你觉得上面这些内容有些不可思议，依旧只需要看ublock的wiki即可，上面的内容更加丰富和精彩。

所以从头到尾看到，ublock、adblock、adguard这些广告过滤扩展根本没有任何什么公平公正的原则，一群根本就不知道什么是标准的人在给所有的浏览器制定的他们心中所谓的理想标准：我说行就行，我说你不行就不行。

你会说浏览器不装这些扩展的时候是正常的啊， 但是你要知道有多少浏览器安装这些广告过滤扩展，有多少这类的扩展被扩展中心作为推荐安装的扩展，安装之后请问互联网标准还正常吗，一个有名无实的标准有用吗？

当你使用扩展增强你的浏览器之后，浏览器的渲染功能还不如那臭名昭著的ie6，这是科技的进步？

如果你是一个互联网开发者，你会在这种完全不公平的环境下为其他人提供服务吗，你还会写网页吗？这和法律鼓励偷窃、入室抢劫有什么区别？

请问写网页需要考虑一个扩展所执行的所谓的标准吗？或者说网页渲染和代码执行需要考虑某几个广告过滤扩展贡献者的个人标准吗？为什么代码功能在一个标准环境中会失效？

像这样的扩展为什么能够一直存在在浏览器扩展中心中？？？？浏览器：我不知道啊，我真的不知道。

作为浏览器本身，几大浏览器公司本身都是靠广告给与的收入维持自身的研发和运作，他们不仅没有和真正的客户相濡以沫，反而去帮助损害自生收益来源的东西。如果用母亲和孩子做比喻，那就是：生块叉烧都比生你好。

你知道吗？这些扩展的代码被托管在github，但是这些扩展在过滤着github的网页内容和js，如何定义扩展的这种行为？如果用母亲和孩子做比喻，那就是:______。

浏览器和浏览器扩展的这种行为出卖了所有以互联网为生的公司和个人，标准制定者为他们的用户提供了所有标准，同时又出卖了他们，有名无实的标准对我们有什么用？纸上写着一视同仁，实际是人为刀俎，我为鱼肉。

看看ublock、adblock、adguard这些广告过滤扩展中那比长江都要长的N个过滤列表，每天都要给互联网造成多少损失，让互联网丧失多少活力。不发工资的公司你回去吗？当然去，管饭就行，那午饭也不提供呢。。。。

当你建了一个体育馆，并且在里面举办各种比赛，但为什么你又把假裁判、吹黑哨、吃药的、修改跑道、改规则的这些影响正常比赛的人员放了进来？同时又没有警察和保安。。。。浏览器：我不知道啊，我真的不知道。浏览器扩展：有警察啊，我知道，我就是警察！由我来维持秩序。

互联网真的是免费的吗？互联网的成本远比你想的高的多。互联网现在的环境也比你想象的恶劣的多，如果你生活在互联网中，那么你迟早会遇到这群连乞丐都不如的__?经历他们给你的苦难。

