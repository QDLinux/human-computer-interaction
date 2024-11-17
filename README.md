# human-computer-interaction

2024 年11 月10日
1系统设计目的与意义
随着信息技术的发展，电子商务越来越普及，蛋糕商城系统的建设为蛋糕行业带来了新的发展机遇。相比于传统的线下蛋糕购买方式，蛋糕商城系统可以通过线上渠道满足用户对于便捷、快速、个性化的购买需求。电脑和移动设备的普及也为蛋糕商城系统的设计和开发提供了广阔的市场，电脑在处理数据、图片等信息方面更具优势，适合展示精美的蛋糕图片和复杂的交互功能。开发一个综合性的蛋糕商城网站，能够方便用户进行蛋糕浏览、选购和定制，从而提升用户体验。以下是该系统的设计目的与意义：
（1）市场的变化
随着生活水平的提高，用户对于甜品、尤其是蛋糕的需求逐渐增加，不再满足于传统线下门店的购买模式，更倾向于在便捷的线上平台进行挑选和定制。蛋糕商城系统可以帮助企业在电子商务市场中更好地发展，为用户提供多样化、个性化的选择，满足现代用户的高品质需求。
（2）蛋糕销售模式的创新
面对用户日益增长的需求，蛋糕商城系统能够为用户提供多样化的购买方式和配送模式。例如，用户可以选择当日送达或预约配送，系统还可以提供主题蛋糕、生日定制等服务，满足不同用户的需求。这种灵活的销售模式可以让企业更加贴近用户需求，提升客户满意度。
（3）新的营销方式的应用
在互联网快速发展的背景下，信息传播方式和速度不断提升，对于蛋糕企业来说，系统可以集成多种营销推广渠道，如社交媒体推广、SEO优化、搜索引擎推广等，帮助企业扩大品牌知名度。通过个性化推荐和定期促销活动，吸引更多潜在客户，并增强用户黏性。
（4）多端适配的重要性
随着移动端用户数量的增加，蛋糕商城系统不仅需要支持PC端，也需要支持移动端。移动端用户达到了数亿人，开发响应式的蛋糕商城网站，实现PC端和移动端的无缝衔接，是顺应市场趋势、获取更多用户的关键。因此，系统设计上应重视移动端优化，实现全网营销。
（5）系统设计的价值和意义
蛋糕商城系统通过线上平台的建设，为蛋糕企业带来了新的盈利模式，扩大了客户群体，提高了客户服务水平。系统设计不仅关注用户的浏览和购买体验，还提供了商家管理、数据分析等功能，帮助蛋糕企业优化运营。


技术实现：
该蛋糕商城系统主要采用了Java编程语言，项目构建采用了Maven仓库，数据库选用MySQL关系型数据库，以提高数据查询和缓存效率。后端技术基于Servlet实现，前端则主要使用JSP和jQuery，以实现良好的交互效果。

2需求分析
2.1系统可行性分析
蛋糕商城系统的可行性分析主要从技术、经济和操作三方面进行评估，确保系统开发的合理性和可行性。
（1）技术可行性
技术成熟度：该系统基于Java语言开发，使用了成熟的开发框架（如Spring、MySQL、Redis等），这些技术在电商系统中应用广泛，技术方案成熟稳定。
开发环境：项目可以使用现有的开发工具（如IntelliJ IDEA、Maven等），并结合前端技术（如HTML、CSS、JavaScript、JSP、jQuery等），实现用户友好的交互界面和便捷的操作体验。
系统架构：系统采用B/S（浏览器/服务器）架构，用户可以通过浏览器进行访问，操作简便，跨平台支持更广泛。使用MySQL作为关系型数据库，用于存储核心业务数据，结合Redis缓存以提高查询效率和系统响应速度。
数据安全性：基于主流的加密技术，可以保障用户信息和交易数据的安全性，并通过完善的权限控制和防护机制，保护系统免受网络攻击。
（2）经济可行性
开发成本：由于所用的开发工具和技术基本是开源且免费的，所以开发成本主要集中在开发人力上。系统功能需求明确，可分阶段开发，降低了开发成本。
维护成本：采用成熟的框架和数据库系统，系统的维护成本较低，开发完成后仅需进行小规模更新和Bug修复。
收益预期：蛋糕商城系统将为蛋糕企业提供全新的营销渠道，帮助企业在激烈的市场竞争中吸引更多用户。通过定期促销和个性化推荐功能，提高用户购买率和复购率，进而提升企业收益。
（3）操作可行性
用户操作便捷性：系统界面设计简洁友好，用户可以快速完成注册、登录、浏览和下单等操作，符合用户的使用习惯。网站首页推荐和搜索功能将便于用户快速找到所需蛋糕，提升用户体验。
商家操作便捷性：商家管理后台简化了库存、订单、用户数据的管理，使商家可以更高效地维护产品信息、进行订单管理，系统操作简单、易于上手，适合无专业背景的工作人员使用。
系统推广难度：由于目前市场上存在多个知名的电商平台，蛋糕商城系统需要制定合理的推广策略，以确保系统能够获得用户和商家的关注。不过，通过社交媒体、线下活动等方式进行宣传，系统有望在目标用户群体中快速积累一定的市场份额。
综上所述，该蛋糕商城系统在技术、经济、操作和法律方面均具备可行性，能够有效满足蛋糕企业和用户的需求，具有较高的应用价值和市场潜力。因此，系统开发具备较高的可行性。

2.2系统的功能需求
蛋糕商城系统是一个综合性电商平台，通过用例图反映用户的实际交互需求。该系统功能丰富，此处选取其中5个主要用例，分别为注册/登录、浏览首页、搜索蛋糕、查看蛋糕详情、加入购物车。
在蛋糕商城系统中，首页主要分为三个基础模块，分别为推荐、热销、促销栏。用户可以根据需求在相应模块中查看蛋糕信息。此外，用户可以通过上方的搜索栏查找目标蛋糕，并查看详情和将商品加入购物车。以下用例均是用户能够直接进行的操作，具体如下所述：
1. 注册/登录：用户通过邮箱或手机号注册新账号，注册成功后可使用账号密码登录系统。
2. 浏览首页：用户进入首页后可以查看推荐、热销、促销等蛋糕信息，获得购买灵感和促销资讯。
3. 搜索蛋糕：用户在搜索框输入关键词（如蛋糕种类、口味、价格等）进行模糊查询，快速找到符合需求的蛋糕。
4. 查看蛋糕详情：用户点击蛋糕商品后进入详情页面，查看蛋糕的详细信息，包括图片、描述、价格、评价等。
5. 加入购物车：用户在商品详情页点击“加入购物车”按钮，将选中的蛋糕添加至购物车，以便后续结算。
以下用例图展示了用户与蛋糕商城系统的交互关系，包括注册/登录、浏览首页、搜索蛋糕、查看详情和加入购物车等主要用例（如图2-2 顾客用例图所示）：

图 2-2 顾客用例图

3系统功能结构模块
3.1系统功能结构图
 蛋糕商城系统具备丰富的功能并划分为明确的区域。总体可分为两个大板块：管理员功能板块、用户功能板块。这两个板块又可细分为不同的子功能模块。
 各个板块实现的功能分别为：

普通用户功能
（1）用户管理：
   - 注册：用户可以创建新账户。
   - 登录：用户登录系统，访问个人功能。
   - 找回密码：用户可通过邮箱或手机找回密码。
（2）商品浏览：
   - 商品分类浏览：用户根据商品类别浏览不同的蛋糕产品。
   - 商品搜索：用户通过关键词搜索特定蛋糕产品。
   - 商品详情查看：查看选定蛋糕的详细信息，包括图片、描述、价格等。
（3）购物功能：
   - 购物车管理：用户将商品添加到购物车，查看和管理购物车内的商品。
   - 收藏夹：用户将喜欢的商品加入收藏夹，方便后续查看。
   - 在线支付：用户完成订单的支付操作。
（4）订单管理：
   - 订单提交：用户确认购物车内商品并提交订单。
   - 订单查询：用户查看订单的状态和详情。
   - 订单评价：用户对已完成的订单进行评价。
（5）个人中心：
   - 个人信息维护：用户维护和更新个人资料。
   - 收货地址管理：用户管理配送地址信息。
   - 消息通知：用户接收系统或管理员的通知消息。

管理员功能
（1）商品管理：
   - 商品上下架：管理员管理商品的上架和下架状态。
   - 商品分类管理：管理员添加、编辑或删除商品类别。
   - 库存管理：管理员管理商品的库存数量。
（2）订单管理：
   - 订单查询处理：管理员查看并处理所有订单。
   - 退款处理：管理员处理用户的退款申请。
   - 配送管理：管理员安排订单的配送状态和物流信息。
（3）用户管理：
   - 用户信息管理：管理员查看和管理用户的基本信息。
   - 用户权限管理：管理员设定用户权限（如管理员、普通用户）。
   - 用户反馈处理：管理员查看并处理用户提交的反馈或投诉。

3.2系统流程图
蛋糕商城系统流程图是用于描述蛋糕商城的业务流程和系统功能的图示工具。它通过黑盒子形式，用图形符号表示系统各个模块及其之间的数据流动情况，帮助开发人员全面了解系统的工作流程，并为后续的开发和分析提供便利。系统流程图还增强了开发团队之间的沟通和协作，使得系统的分析和设计更加合理和高效。以下是蛋糕商城系统流程图的文字表述部分：
在蛋糕商城的使用流程中，首先用户需要进行登录操作，输入用户名和密码进行身份验证。登录成功后，用户将进入商城首页，在首页可以浏览商城的热销蛋糕、最新活动、特价商品等信息。用户可以通过搜索功能查找自己感兴趣的蛋糕或商品，并根据需求进行筛选。
当用户选择某个商品时，可以进入商品详情页面，查看蛋糕的详细描述、价格、配料信息、评价等内容。如果用户决定购买该商品，可以将其添加到购物车。购物车页面会显示用户已选择的商品列表及其数量、总价等信息，用户可以修改商品数量或删除商品。
在结算环节，用户可以选择配送地址、支付方式等信息，完成订单提交。当订单生成后，系统会进行支付处理，支持多种支付方式（如支付宝、微信支付等），支付成功后，订单状态将更新为“已支付”，并进入配送流程。用户可以在“我的订单”页面查看订单的实时状态，包括待发货、已发货、已完成等状态。
此外，用户可以在个人页面管理个人信息、查看积分、查看购物历史和订单状态等。在“我的收藏”中，用户可以查看自己喜欢的蛋糕或商品，并可以随时加入购物车或直接购买。
当用户完成操作或想要返回上一级页面时，系统将提供明显的返回按钮或提示，帮助用户快速切换页面或功能模块。系统流程图有助于清晰地展示整个蛋糕商城系统的功能与流程，确保系统开发和用户操作的高效性。
具体如图3-2 系统流程图所示：

图 3-2 系统流程图


4抽象视图设计
视图表达了人与系统交互过程中某一时刻系统的状态，以及用户在这一时刻可能改变系统状态的方法。视图抽象设计通过组合模型概念中的对象和对象操作，提供系统运行的方法和方式，为具体的设计提供指导，并要为系统的不同方案提供灵活的界面选择。视图抽象设计阶段就是仔细研究系统的对象模型，列出其系统状态，对每一个视图抽象出其中设计的对象，以及对象的属性和行为。在视图设计过程的初级阶段,视图的描述没有必要十分具体。具体视图在人机界面设计后期需要完善的。而在人机界面设计最终完成之前的不同设计阶段产生的视图都会有不同程度的抽象性。所有相对具体的视图都是从某种程度的抽象视图具体化而得到的。在抽象设计阶段，只需要考虑可能的交互操作和需要的信息，至于具体交互系统的细节实现则不必考虑，以适应交互的灵活性。该系统的抽象视图设计如图4-1 抽象视图设计所示。

图 4-1 抽象视图设计


5视图概要设计
蛋糕商城系统视图概要设计（普通用户与管理员）
（1）登录首页
在登录首页中，页面顶部显示系统名称，明确提示用户该界面的功能。接下来，通过设计系统LOGO，不仅提升页面美观度，还帮助用户快速识别系统品牌。LOGO旁边设置登录框，供用户输入微信号和密码进行登录。页面底部显示版权信息，简洁明了地标明商城版权声明。整体页面设计简洁，突出登录功能。
布局示意：
顶部：系统名称
中部：登录框（输入手机号、密码及登录按钮）
底部：版权信息

（2）普通用户页面
普通用户页面设计以用户体验为主，顶部显示用户名和用户等级（如普通用户或会员身份），并提供退出按钮，用户可随时退出。页面左侧是功能列表，包括浏览商品、购物车、订单管理、个人资料等功能。用户点击功能列表中的项，右侧将展示相应的功能内容区域，比如商品详情、订单状态等。功能内容区域上方设有主页导航条，提醒用户当前所在的功能模块。
布局示意：
顶部右侧：用户名 + 退出按钮
顶部左侧：功能列表（浏览商品、购物车、订单管理、个人资料等）
中间：商品内容区域（商品概要、商品推荐等）
顶部导航条：提示当前功能模块
底部：版权信息

（3）管理员页面
管理员页面设计与普通用户页面的结构相似，但功能上有所不同，适用于管理后台操作。顶部显示管理员的用户名和权限等级（如管理员），并设置退出按钮，方便管理员退出。左侧是功能列表，包括用户管理、商品管理、订单管理、活动管理等功能。管理员通过选择功能列表中的项目，右侧展示对应的功能内容区域，例如管理用户信息、商品发布、订单查看等。功能内容区域的上方同样有主页导航条，提示当前操作所在的模块。
布局示意：
顶部：用户名 + 权限 + 退出按钮
左侧：功能列表（用户管理、商品管理、订单管理、活动管理等）
中间：商品内容区域（商品概要、商品推荐等）
顶部导航条：提示当前功能模块
底部：版权信息


首页布局图：

功能菜单区：位于页面顶部，用于放置网站的主要导航链接。
轮播图：位于功能菜单区下方，是一个大型矩形区域，通常用于展示重要信息或产品图片，并且可以自动切换显示不同的内容。
商品展示区：在轮播图下方，分为四个小矩形区域，分别标记为“商品1”、“商品2”、“商品3”和“商品4”，每个区域代表一个商品的展示位置。
版权信息：位于页面底部，用于显示网站的版权声明和其他相关信息。

蛋糕商城系统的视图设计将用户区分为普通用户和管理员两个角色，提供不同的功能和页面布局。普通用户页面关注购物和个人信息管理，管理员页面则重点在于后台管理和数据操作。两种角色的界面都采用相似的结构设计，确保用户能够轻松找到所需功能，并提供清晰的导航和操作区域。通过这种设计，系统能够提供高效的用户体验和便捷的管理员操作，同时保持界面的统一性和简洁性。


6视图关联设计
任何一个人机交互系统的界面都可能包括若干状态，用户在不同界面状态下根据自己完成任务需要进行不同的操作；很多交互任务需要从一个状态转化为另一个状态，这就要考虑用户完成任务所需的信息和功能，并将不同交互视图之间的联系和状态转换关系整理清楚。前面阐述了旅游网站的概要设计图，这些模块与其他模块有机地联系在一起，使得用户使用流畅。在状态转换图中可以清晰地了解每个界面之间是如何进行交互的。该网站的所有界面都是使用的同一个顶部，都可以实现点击顶部的一些功能按钮切换到首页页面、登录页面、注册页面、展示页面。该网站的功能状态图如图6-1所示。

图 6-1




7视图全面设计
本次软件具体设计共涉及14个页面，“首页”页面、“商品分类”下拉菜单默认8个子页面、“热销”页面、“新品”页面、“注册”页面、“登录”页面、“我的订单”页面、“个人中心”页面、“我的购物车”页面、“蛋糕店后台首页”页面、“蛋糕店后台订单管理”页面、“蛋糕店客户管理”页面、“蛋糕店后台商品管理”页面、“蛋糕店后台类目管理”页面。能够满足用户查看各种信息以及页面之间互相跳转的基本需求。如图7-1、7-2、7-3、7-4、7-5、7-6、7-7、7-8、7-9、7-10、7-11、7-12、7-13、7-14所示。


图 7-1 首页

图 7-2 商品分类-全部系列


图 7-3 热销


图 7-4 新品

图 7-5 注册


图 7-6 登录



图 7-7 我的订单

图 7-8 个人中心


图 7-9 我的购物车


图 7-10蛋糕店后台-首页

图 7-11 蛋糕店后台-订单管理


图 7-12 蛋糕店后台-客户管理


图 7-13 蛋糕店后台-商品管理

图 7-14 蛋糕店后台-类目管理


8  数据库设计
8.1 数据库的设计过程及遵循的原则
对于软件开发来说，数据库无疑是软件的核心，数据也是企业应用中价值最高的部分。如果软件的数据库的设计不符合规定，将会大大增加开发人员的维护难度，甚至还会影响到软件的运行与使用。所以数据库的设计必须遵循一定的设计规范，避免磁盘IO瓶颈，减少服务器资源竞争和CPU利用率等优化性能技术。
数据库的字段设计的要长一些，便于以后的扩展，这样可以达到数据存储更加完整的效果，能够满足不同用户的需求，使得数据库拥有更高的完整性。
8.2 数据库的详细设计
根据对蛋糕商城管理系统的需求分析，架构设计和系统E-R图的分析，对该系统进行了数据表的设计。总共有三张表，分别为goods（商品表）、order（订单信息表）、user（用户信息表）。
其中goods用于存储商品的序号，名称，价格等基本信息，在基本信息之外，还存储了商品图片和简介等详细信息，结构如表8-1 goods所示。
序号	字段名称	字段类型	中文含义
1	Id	int	id标识
2	Name	varchar	商品名称
3	Price	float	商品价格
4	Intro	varchar	商品介绍
5	Image	varchar	商品图片
表 8-1 goods

order表用于存储订单信息。表的具体内容为id号、添加时间等基本信息，结构如表8-2 order所示。
序号	字段名称	字段类型	中文含义
1	Id	int	订单id标识
2	Total	float	订单总价
3	Status	tinyint	订单状态
4	Paytype	tinyint	支付方式
5	Name	varchar	订单人姓名
6	Phone	varchar	订单人电话
7	Address	varchar	订单人地址
8	Datatime	datatime	订单时间
9	user_id	int	订单人对应user表中的id
表 8-2 order

user表用于存储注册用户信息。表的具体内容为ID号、用户名、用户邮箱、用户密码、收货人信息等基本信息，结构如表8-3 user所示。
序号	字段名称	字段类型	中文含义
1	ID	int	id标识
2	Username	varchar	用户名
3	Email	varchar	用户邮箱
4	Password	varchar	用户密码
5	Name	varchar	收货人姓名
6	Phone	varchar	收货人电话
7	Address	varchar	收货人地址
8	Isadmin	bit	是否为管理员
表 8-3 user

9设计思想与理念
9.1logo设计理念
"Cake Mall"的logo设计体现了几个巧妙的设计理念：
（1）可爱风格：
- 采用卡通化的拟人设计，主角是一个带有大眼睛、可爱表情的杯子蛋糕
- 使用明亮活泼的色彩，如粉红色、蓝色等
- 角色表情充满活力和友好感
（2）丰富的视觉元素：
- 主体杯子蛋糕周围配有冰淇淋、甜甜圈等其他甜点
- 撒落的彩色糖针作为装饰元素，增添趣味性
- 购物袋的元素暗示这是一个购物场所
（3）品牌寓意：
- "Mall"(商场)与甜点的结合，表明这是一个专注于甜点的购物场所
- 通过可爱的拟人化设计，传达出品牌亲和力
- 丰富的甜点种类暗示商场商品的多样性
（4）色彩运用：
- 使用蓝色作为背景，形成视觉焦点
- 粉色、橙色等暖色调营造温馨甜蜜的氛围
- 色彩搭配鲜明但不杂乱
（5）商业策略：
- 可爱的设计风格容易吸引目标客群，特别是年轻人和儿童
- 整体设计容易记忆，有助于品牌识别
- 视觉效果让人联想到美味和愉悦的购物体验
这个logo将甜点商场的概念通过一个生动、可爱且专业的设计表现出来，既体现了商业属性，又保持了趣味性和亲和力。Logo如图9-1 logo所示：

图 9-1 logo
9.2logo设计原则
（1）连续性原则
- 视觉元素的流畅排列：从左到右依次排列甜甜圈、主体杯子蛋糕、冰淇淋和购物袋，形成自然的视觉动线
- 彩色糖针的随机分布创造出连续的背景效果，增强整体感
- 蓝色圆形背景与主体蛋糕形成连续的层次关系
- 曲线的运用（如奶油的形状）创造出流畅的视觉体验
（2）完整和闭合性原则
- 主体杯子蛋糕形象完整，轮廓清晰
- 蓝色圆形背景创造出封闭的视觉空间，突出中心主体
- 每个甜点元素都是独立完整的个体
- 整体构图形成一个视觉上的封闭单元，不会让视线散失
（3）简单性原则
- 虽然包含多个元素，但每个元素都经过简化处理
- 色彩使用鲜明但不杂乱，主要以蓝色、粉色等为主
- 字体设计简洁易读
- 主次关系明确，主体蛋糕占据中心位置
（4）相近性和相似性原则
相近性：
- 所有甜点元素靠近排列，形成一个统一的群组
- 装饰性糖针元素分布在周围，形成背景群组
- 文字标识位于底部，与图形元素保持适当距离
相似性：
- 所有甜点都采用相似的卡通风格
- 使用统一的描边和高光处理方式
- 色彩风格协调统一
- 各元素的拟人化处理方式一致（如白色手套）

设计优点：
1. 这些原则的运用使logo具有良好的视觉平衡和整体性
2. 能够有效传达品牌信息和视觉美感
3. 在保持趣味性的同时确保了专业水准
这个logo在运用视觉设计原则方面，既保持了品牌特色，又确保了良好的视觉效果和识别度。

9.3页面设计思想
随着电子计算机的飞速发展，软件产品的用户群体已经发生了巨大的转变，各种各样的软件工具花样层出，软件的用户界面作为人机接口起着越来越来重要的作用，一个友好的界面设计首先要对人的感性特性有所了解，明白人是如何处理信息的，以及人可能会犯什么错误。良好的交互不仅会给自己的软件起到锦上添花的效果，增添自己的魅力，更重要的是它能够全面地体现应用软件的系统功能，它的好坏会直接影响该软件的生存寿命。一个界面友好的软件不会挑战用户的一些基本的惯性操作，界面设计要整体页面简洁流畅，按钮通俗易懂，主题明确，在视觉上不会让用户感到厌烦。用户能够清晰地明白这个界面的想要表达的是什么，如何进行操作运用对应的功能。对于用户来说，这无疑是一种享受，这会促使用户毫不犹豫地选择它，即使有另一个软件存在类似的功能，用户也会选择界面友好的设计。目前，追求应用软件友好的界面已经越来越成为了众多设计者和使用者的共识。

9.4页面设计原则
9.4.1以用户为中心
不同的用户会有不同的习性，他们在个性上的差异、行为方式的不同、认知方面的区别都有可能对人机交互的界面产生不同的影响。不同的人对同一软件界面的评价也不尽相同。
在设计界面中给标签栏设置了6-8个类别，这样的话使用户来说很容易使用，同时在学会时候后应当容易记忆。即使长时间不使用后也能迅速回想起它的使用方法和流程。并且按照人们的习惯将功能列表栏设置在了浏览器页面的最上方，放在这个位置有助于用户记忆和使用，用户打开的第一眼就能看到，简单朴素，让人不会有视觉疲劳。左上的标题清晰明了的指出该页面的主题，同时顶端也更容易被用户发现。例子如图9-2、图9-3、图9-4所示。

图 9-2 游客

图 9-3 普通用户

图 9-4 管理员

9.4.2.黄金规则7±2理论
信息在短时记忆中大约只能保持30秒，且短时记忆的存储能力也非常有限，约为7±2个信息单元，这一发现被称为7±2理论。浏览菜单和工具栏基于人的识别能力。7±2理论提醒我们在进行页面设计时要尽可能减小对用户的记忆需求，同时可考虑通过将信息放置在一定的上下文中，来减少信息单元的数目。
此次设计中用户（普通用户/管理员）选择商品分类为八个栏目，并且管理员可以通过后台管理来增减栏目。太过详细的分类会使得使用者记忆疲惫，同时产生视觉疲劳。例子如图9-5所示。

图 9-5

9.4.3.一致性
因为每个新的系统对于使用者来说都是一次新的学习过程，如果界面风格经常变化，不保持统一性，这无疑会增加用户的使用难度，也许会导致用户的厌烦从而放弃使用该系统。保持一致性可以使用户建立起精准的心理模型，使用熟练一个界面后，切换到另外一个页面也能够轻松地推测出各种对应的功能，语句理解也不费神，同时还可以降低开发的时间和成本，一举多得。
此次在“首页”页面、“商品分类”子页面、“新品”页面、“热销”页面中采取一致性原则，在排版、按钮的位置和颜色风格都保持统一。按钮统一放在图片右下方，对应的详情按钮都放在图片中央，体现了操作一致性。同时符合用户使用其他软件的操作手感，让用户更加容易上手。如图9-6、9-7、9-8所示。

图 9-6

图 9-7

图 9-8

9.4.4.Fitts定律
Fitts定律告诉我们，要缩短到达目标的时间可以采取两种措施：一是缩短到目标的距离，二是增大目标的大小。
在“商品详情”的提示模块中，采用缩短当前位置到目标区域的距离以及增大商品图片大小来提高用户的使用感，用户不需要将光标精准定位到图片的中央，只要点击到边框及其内部就可以进入商品详情页，这个移动的距离要小于光标移动到中央位置的区域，如图9-9所示。

图 9-9

9.4.5可视化设计-控件
控件是用户和数字产品进行交流的屏幕对象，它具有可操作性和自包含性，是创建图形用户接口的主要构造模块，有时也被称为“小部件”、“小配件”或者“小零件”。
在首页的上方设置了一个搜索图标，光标移动到搜索图标时会自动弹出框，用户可以在此对自己想要去的景点进行输入和搜索，用户可以很好的确定自己的需要，如图9-10所示。

图 9-10

9.4.6简约至上
在平台设计时，始终注重平台页面的简洁、用户操作的快捷和结果呈现的直观，在充分学习了简约至上：交互设计的四策略的基础至上一步一步进行开发设计。在活动页面等部分的设计上采用了删除和组织策略，让页面布局更加合理减少了用户的记忆负担。在活动详情页和社团详情页的开发上，使用色彩一致和直接的页面文字展示，减少了页面内容的冗余。在用户输入和功能设置方面，使用了隐藏的策略，部分功能在用户需要时适时出现，同时在页面中使用提示和线索的方式使隐藏的功能更容易让用户找到。简约至上的设计理念已经渐渐融入到越来越多的系统设计中，并越来越受到用户的青睐。

9.4.7美观与协调性原则
本次设计元素大小适合美学观点，感觉协调舒适，能够在有效的范围内吸引用户的注意力。在长宽设计时接近黄金比例，布局合理，没有使得模块充满整个屏幕，存在适当的留白，不过与密集，合理利用空间。同时，按钮大小都基本相近，与界面的大小和空间都相协调。整体设计中，前景和背景色相互搭配，没有过大的反差，所有页面均使用较浅的暖色系，在保持界面风格一致的时候，也使界面具有亲和力。

9.4.8.删除原则
删除指去掉所有不必要的组件，直至减到不能再减。删除原则源于十条启发式规则之一——用户享有控制权和自主权。在整体页面设计中，删除了视觉混乱，每个模块之间用空白或者轻微背景来划分，而不是使用线条。减少了元素大小的变化，功能相似的模块，出现在页面的大小也相同。还减少了元素形状的变化，每个页面只是用了一种界面样式，使用了一种按钮方式，避免太过花哨。这样适当的删除，减少用户必须处理的信息，可以使用户将注意力集中在真正重要的内容上。

10总结
通过本次的课程设计，在项目界面设计的过程中，我进一步的了解和学习了人机交互的思想，从更深一步的了解了从人机交互角度进行项目界面设计的原则。毫无疑问，学习人交互是非常重要的，我们生活在一个信息化的时代，用户开始期望系统能够简单易用。同时，对那些设计低劣的系统容忍度越来越差，设计的系统项目需要一个良好的人机交互性来更好地满足用户并且优质的人机交互界面可以有效的提高使用人员的效率，在不经意间减少操作时间，运用人机交互思想设计的界面，也可以增强产品的使用效果。此外，人机交互的思想和原则的应用能够能够降低系统产品的后续支持成本。我们设计的人机交互界面应该是高效，无差错的，在设计过程中也要满足不同用户在身体认知能力，感知能力，文化和个性的多样性需求，所以人机交互在一个系统开发中占据重要位置。今天，计算机已经从传统的大型、昂贵且只呗少数专业人员使用的机器逐渐演化为小型、廉价、易于使用的机器。可以说计算机已经逐渐融入人们生活的方方面面，几乎任何和人有关的服务领域都离不开计算机的身影。随之而来的问题就是人们对计算机软件的要求越来越高，软件不仅要稳定可靠，而且还应该易学、好用。换句话说，交互性能的好坏日益成为衡量软件设计优劣的关键。良好的交互设计不仅能够赢得用户的喜爱和信赖，也应该能够是喜爱产品的用户向其朋友们推荐该产品。当然拙劣的交互设计也会极大打击用户的实用热情，从而减少软件的使用寿命。
在这次蛋糕商城的人机交互设计课程中，我从优化用户购物体验和方便商城管理的角度出发，开发了一个蛋糕商城系统。系统旨在实现商品展示、用户下单、订单管理等核心功能，从而帮助顾客方便快捷地选择和购买蛋糕，同时为商城管理人员减轻工作负担，实现商城的数字化管理。本次设计采用了SSM框架，并结合JavaScript组件库、HTML、CSS等前端技术来实现。
在实际设计过程中，我第一次将人机交互的理念应用到项目中，深刻体会到一个成功的界面设计需要关注的不仅仅是功能的实现，还包括用户需求的深度分析、界面的美观与协调性，以及页面布局的合理性等方面。一个良好的界面设计并非一蹴而就，而是需要经过多次推敲和迭代，真正为用户提供易用的交互体验。
在设计过程中，遇到了不少前端开发的技术问题，比如如何使界面响应迅速、如何提升交互的流畅度等。这些问题让我有机会深入学习了许多前端知识，并且通过参考学习资料和查询相关文档，逐步找到了解决方案。我还学会了如何调试和优化代码，确保系统能够在用户端稳定运行。
本次设计让我进一步理解了页面设计的规范流程。从最初的需求分析，到视图的抽象设计，再到概要设计，最后形成全面的界面设计，每一步都需要细致考量。需求分析阶段明确了用户在蛋糕商城中的主要任务，比如查找商品、查看详细信息、添加到购物车、结算付款等，这帮助我在设计每个界面时都能够准确对应用户需求，确保了功能的完整性和使用便捷性。
这次课程设计不仅让我提升了前端和后端整合的技能，也让我对人机交互设计有了新的理解。通过不断优化界面布局和交互细节，我真正认识到一个良好的设计是通过对用户需求的关注以及对技术细节的完善而实现的。这次项目让我在分析、设计、编码、测试等方面都有了综合提升，能够更好地将理论知识运用到实际开发中。
蛋糕商城的人机交互设计课程让我认识到，技术和设计并行的重要性。好的交互设计不仅能够实现功能，还能够让用户获得更好的体验感受。通过这次实践，我积累了更多关于交互设计和系统开发的经验，为今后的设计和开发工作奠定了坚实基础。
