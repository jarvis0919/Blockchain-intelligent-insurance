# Blockchain-intelligent-insurance区块链智能保险
致力于建立全新信任社会体系#
## 前言
现代社会发展过程中,风险无处不在,保险公司是社会经济正常运转、持续发展的后盾。经过改革开放30年的发展,我国保险业取得了举世瞩目的成就,逐步成长为国民经济发展中的明星行业。保险业积极参与经济建设和社会发展活动,积极主动渗透到国民经济的方方面面。
到2007年,保险机构已成为债券市场的第二大机 构投资者和股票市场的重要机构投资者,在企业债、次级债等投资领域占据了主导地位;同时,积极参与抗灾救灾,勇于承担社会责任。在2008年初南方低温雨 雪冰冻灾害和5.12汶川地震两场重大自然灾害发生后,保险业全力投入抗灾救灾和灾后重建,得到了各级党委政府和人民群众的认可。保险逐浙成为人们日常生活话题。当然,随着保险业快速发展,存在产品结构单一、创新能力不足、行业恶性竞争、形象不佳和理赔运行现状不甚理想等问题也十分突出。因此,正确分析和认识中国保险业的现状及其存在问题,对规范中国保险市场、促进保险业的发展, 均有重要的指导意义。


1. [The specification](spec.md) for how a standard README should look.
2. A link to a linter you can use to keep your README maintained ([work in progress](https://github.com/RichardLitt/standard-readme/issues/5)).
3. A link to [a generator](https://github.com/RichardLitt/generator-standard-readme) you can use to create standard READMEs.
4. [A badge](#badge) to point to this spec.
5. [Examples of standard READMEs](example-readmes/) - such as this file you are reading.

Standard Readme is designed for open source libraries. Although it’s [historically](#background) made for Node and npm projects, it also applies to libraries in other languages and package managers.


## 目录
- [前言](#前言)
- [第一章 背景与现状](#第一章-背景与现状)
	- [1.1 保险业的发展历史](#11保险业的发展历史)
	- [1.2 保险业利用信息化社会的发展现状](#12保险业利用信息化社会的发展现状)
	- [1.3 基于区块链的保险业的发展前景](#13基于区块链的保险业的发展前景)
- [第二章 区块链技术于保险业的优势](#第二章-区块链技术于保险业的优势)
	- [2.1 传统保险业的弊端](#21传统保险业的弊端)
	- [2.2 基于区块链的智能保险业的优势](#22基于区块链的智能保险业的优势)
- [第三章 基于区块链的智能化保险方案设计](#第三章-基于区块链的智能化保险方案设计)
 	- [3.1 业务设计](#31业务设计)
	- [3.2 架构设计](#32架构设计)
	- [3.3 交互设计](#33交互设计)
- [第四章 方案设计的技术支持](#第四章-方案设计的技术支持)
   	- [4.1 以太坊](#generator)
- [第五章 应用及业务实践](#第五章-应用及业务实践)
- [第六章 商业模式](#第六章-商业模式)

## 第一章 背景与现状
### 1.1保险业的发展历史

##### （一）中国保险业的开端。
> 鸦片战争以后，西方列强迫使清政府签订了一系列不平等条约，加强了对我国的政治、军事、经济的侵略。外国保险公司纷纷登陆中国，中国保险市场逐渐形成。外国保险公司凭借不平等条约所持有的政治特权扩张业务领域，利用买办招揽业务，垄断了早期的中国保险市场从中，攫取了巨额利润。面对外商独占中国保险市场，每年从中国掠夺巨额利润，致使白银大量外流这一严峻事实，中国人民振兴图强、维护民族权利、自办保险的民族意识被激起。在此情况下，1865年月25日义和公司保险行在上海创立。义和公司保险行，是我国第一家自办的保险机构，其成立打破了外商保险公司独占中国保险市场的局面，为以后民族保险业的兴起开辟了先河。提到保险业就不得不提到航运业，保险与贸易两者是互为表里的关系。轮船招商局于1872年在上海成立，是中国人自办的最早的轮船航运企业，也是现在的招商局集团的前身。它不仅是中国现代航运业的起点，也可以说是中国保险业的源头之一。轮船招商局自创办之日起就深刻明白保险对于航运业的重要作用。作为一种打击竞争对手的手法，早期依附于外商航运业的外资保险公司听命于上司，为了击垮轮船招商局，对其所属船舶百般刁难。收取高额保费、对中国本土产的船只不保等限制。以李鸿章为代表的洋务派，为适应航运业发展的需要，先后创办了“保险招商局”、“仁和水险公司”和“济和水火险公司”等官办保险公司，取得了较好保险的经营业绩，并坚持与外商保险公司进行斗争，从而在一定程度上抵制了外商对中国保险市场的控制。当然，洋务派在保险业方面的努力不能改变外商垄断中国保险市场的局面。
##### （二）建国前在夹缝中生存发展的民族保险业。
> 民国初期，中国民族保险业获得了难得的发展机遇：一是民国初建需要刺激工商业的发展以稳定政权；二是第一次世界大战的爆发，欧美列强卷入战争，无暇东顾，大大减缓了洋商对中国保险市场的控制；三是五四运动的爆发，反帝斗争的兴起，赢得了整个民族对民族工商业的支持和对洋商的抵制。从1912年到1925，国内陆续创办了华安合群等30余家民族保险公司，华资寿险市场一度兴起，但由于经营不善，其中停业者居多。
至上世纪20年代中后期，金融资本投入保险业，民族银行开始兴办保险企业，民族保险业始有进一步发展。保险业有了突破性的发展，出现了太平保险公司这样实力雄厚、信誉卓著，分支机构代理网点遍布全国各大城市，甚至涉足南洋市场，在国际上也有一定声誉的民族保险公司。但是抗日战争爆发后，保险业受到巨大的冲击。
##### （三）新中国后保险行业的发展
> 建国后中国保险业的发展史，可谓跌宕起伏。经历了建国初期的起步，到六七十年代的低谷，最后到现在的快速发展的过程。保险业作为国家经济发展的晴雨表，到上个世纪末，经过了四个发展时期。一是在五十年代的初创时期，保险业仅中国人民保险公司一家国有保险公司，保险业务的发展还处于初级拓荒阶段，业务范围也十分狭窄，但是当时保险业配合新中国经济建设，在保障生产安全、促进物资交流、安定人民生活、壮大国有资产等发挥了积极作用；第二阶段是在六七十年代的低谷期，由于当时的历史原因，本外币保险业务基本停办，仅保留五大口岸城市的涉外险业务，保险业陷入长达二十年的停滞时期，发展严重受挫；第三阶段是八十年代的复苏期，伴随着中国改革开放和经济发展，保险业迅速崛起，为国家经济建设和人民生活提供多方面广泛的服务，但市场经营主体仍处于人保独家垄断状态；第四阶段是九十年代的发展期，保险业独家垄断的格局被打破，取而代之的是中外保险公司多家竞争、共同发展的多元化新格局。进入二十世纪未找到目录项。以来，我国保险业正步入一个全新的发展阶段，根据我国入世承诺，保险业在金融行业中开放力度最大，开放过渡期最短。2004年12月11日过渡期结束，我国保险业进入全面对外开放的新时期，呈现出日渐市场化、专业化、国际化、规范化的新特点。
30年的改革开放为我国保险业发展注入了新的生机和活力。改革开放之初，我国保险市场由一家公司经营，全部保费收入只有4.6亿元。到2007年，全国保险公司达到110家，总资产达到2.9万亿元，实现保费收入7000多亿元，市场规模增长
1500多倍。
##### （四）目前我国保险业发展现状
> 中国保险业的整体实力与核心竞争能力不断提升、经济功能初步显现。回顾保险业６０年来的改革发展历程，虽然经历了曲折，但全行业始终坚持改革创新，在探索中国特色保险业发展道路上迈出了坚实的步伐取得了令人瞩目的发展成就，特别是党的十六大以来，在“抓监管、防风险、促发展”的总体思路指导下，我国保险业保持了又好又快的发展势头，在各方面取得了突出的成绩。

> 1、保险业务大发展，行业实力显著增强，竞争格局基本形成。保险业快速发展，业务领域逐步拓展。1980年恢复国内保险业务时，我国只有企财险、货运险、家财险、汽车险等几个保险业务种类。此后随着国内保险业风险管理技术的进步和经营管理能力的提高，业务领域逐步从财产损失保险扩展到人寿保险、责任保险、信用保证保险、意外伤害保险、健康保险等领域，目前已基本形成涵盖所有可保风险领域的业务和产品体系。保险业恢复经营以来，我国保费收入年均增长超过20%，是国民经济中发展最快的行业之一。2008年实现原保费收入9789亿元，世界排名第6位，中国已逐步成长为新兴的保险大国。资产规模不断壮大。1949年人民保险公司成立之初，仅有资本金约200万元。目前，全国保险公司总资产达到3.7万亿元。市场体系日益完善，从由国有保险独家经营保险业务，到目前全国共有保险公司120多家，初步建成了多种组织形式和所有制形式并存，公平竞争、共同发展的保险市场体系。

> 2、体制机制发生积极变化自改革开放以来，我国的保险业就分别从经营体制改革、公司体制改革、资金管理体制改革、保险监管体制改革四方面，进行了有条不紊的改革。首先保险业务经营体制改革。1996年，为了适应保险业快速发展和防范风险的需要，建立了保险分业经营体制，对产险、寿险实行专业化经营。人保、平安、太平洋等综合性保险公司相继完成产寿险分业经营体制改革。同时，为了提升保险业服务经济社会的能力与水平，对农业保险、健康保险、养老保险等业务领域探索实行专业化经营，专业性的保险公司开始逐渐成立。保险中介市场也逐步发育完善。公司体制改革。坚持从实际出发，采取“三步走”的战略，积极吸引外资和民营资本参股，引进境外战略投资者，优化股权结构，公司治理结构和运行机制不断完善。保险资金管理体制改革。实现了保险资金专业化集中运用，保险资产管理公司从无到有，目前达到10家，管理资产占保险业全部资产的82.6%；从资金运用结构看，实现了从银行存款为主向债券投资为主的转变。

> 3、全社会的风险和保险意识大提高改革开放前，我国保险市场的消费者规模相当有限，消费者对保险的了解非常少，保险意识处在一个较低的水平。随着革开放的不断推进，保险知识的普及也日渐展开，消费者对保险的认识和理解逐步深化。同时，随着收入水平的提高和市场化体制改革的推进，全社会的风险和保险意识逐步提升，消费者开始主动购买所需要的保险产品，并且在购买保险产品时，多方搜集所需保险产品的信息，了解保险市场行情。人民群众保险意识不断增强和消费行为日趋理性，标志着我国保险市场逐步向成熟的方向迈进。

> 4、保险创新取得积极进展。产品创新更加贴近市场需求，适应不同消费群体，开放不同的产品。针对居民日趋多元化的金融保险需求，突破保险产品传统保障功能的限制，开发了具有投资理财功能的产品。针对低收入人群开发了保费低廉、手续简便、保障适度的小额保险产品。适应建立多层次社会保障体系需要，开发了多种形式的商业养老和健康保险产品等。在产品贴近市场的情况下，营销创新与时俱进。从个人营销代理到现在的通过银行、邮局、车行等机构代理，甚至通过利用网络、电话等方式销售保险产品，为保险消费者提供便利、质优价廉的保险服务。在做到服务创新的同时，理论创新为产品创新和营销创新提供了理论基础。近年来特别是十六大以来，在总结保险实践经验的基础上，保险理论创新不断深入推进。提出了保险业发展阶段理论，作出了我国保险业仍处于发展的初级阶段的判断，首要任务是加快发展，做大做强。



### 1.2 保险业利用信息化社会的发展现状


加入WTO之后，外资保险公司全面进入，给并不发达的中国寿险、财险和再保险事业都带来了巨大影响。沿续传统的运作思路，已无法帮助中国保险企业培养起自身竞争力。仅以车险为例，2003年1月1日起，新的车险条款费率管理制度开始实施，机动车保险在市场开放、价格自由、竞争激烈的情况下，保险公司即使对购买同一车型的客户，也要考虑年龄不同、驾龄不同等因素，采取灵活的保费策略。这一点，没有IT系统的支持，没有客户信息的集成管理，没有整合的业务数据及精准的数据挖掘能力，没有完整的精算模型，显然是无法实现的。无人会怀疑，中国将会是最大的新兴保险市场。但就数据挖掘和CRM而言，中国保险企业的应用现状却令任何人都难以宽慰。在业务和技术投资“冒进式”增长的同时，保险公司在CRM应用、客户资源整合管理方面的投入，显然无法适应自身快速的成长势头。相比起普遍进入中国的世界性保险企业，中国保险公司的CRM应用落伍，已是不争的事实。信息化被视作金融业的生命线，对保险公司来讲，数据则如同企业生命体中生生不息的血脉。近10年来国内保险业信息一直处于加速度状态，2003年全年中国保险行业IT应用市场规模更是创记录地突破50亿元，人保、人寿、平安等大型保险公司和新成立的小型保险公司在信息化方面的投入都不遗余力。但在巨资进行信息化的同时，信息化技术组合中更为锐利、高效和复杂的数据仓库和决策支持工具，还没有被中国保险企业所广泛掌握。用一些保险公司业务人员的牢骚话来描述这种现状：报表、报告满天飞，不知哪个没水分数据、数字遍地有，不知哪个是真的客户、业务到处是，不知哪个最该抓考核、决策天天搞，不知哪个有准头。目前中国保险业数据管理应用的普遍现状是，汇集了大量客户信息和业务数据，但因为缺乏挖掘数据背后隐藏的知识的手段和工具，往往导致“数据爆炸但有效信息贫乏”，“信息繁杂但业务知识孤立”——这种局面若无改观，保险公司就会长期处于“低智商”的业务运行状态。从业务数据化到业务知识化，以数据挖掘(DM)为基础的数据仓库(Data Warehouse)、决策支持系统(DSS)建设，在未来数年中将受到保险公司的追捧。为提高决策支持水平，增进商业智能(BI)，保险公司往往需要以联机分析处理(OLAP)为平台进行数据挖掘(DM)，借助大规模数据，通过清洗、转换、装载等数据处理方法，发现大量资料间的关联与趋势，探寻独特的、通过其他方法发现不了的业务规律和模式。一般来看，数据挖掘的任务可以划分成四个层次：数据分析、知识发现、决策支持和金融智能。数据分析、知识发现、决策支持和金融智能，不仅是数据挖掘的不同层级的任务，也体现了保险公司在开展数据挖掘工作中的规划进度。早期的保险业数据仓库建设，关注的往往是数据分析和知识发现的内容，如提供统一及时的业务报表，提供集成的客户信息等。当具备了相应的数据挖掘基础，保险公司有可能将数据仓库的应用引入决策支持和商业智能的层面，更关注于提供决策信息支持、辅助业务管理、分析和评价经营业绩等主题领域，从而帮助保险公司跳出“低智商竞赛”的泥潭。今天的中国保险业，已不再是一个封闭的市场和垄断的格局，国际保险公司正层出不穷地推出新产品和新服务。致力于通过电子化和客户关系管理体系建设提升核心竞争力的中国保险公司，就一定要从核心的业务需求出发，切实推动自身的多层次CRM应用。从业务需求来看，作为典型的金融服务业企业，保险公司的主要业务集中在保险产品销售、风险控制、财务管理和投资管理上。在业务系统的处理中，目前的保险公司业务系统分为三个层级：核心业务处理系统、财务投资管理系统和风险管理系统。核心业务处理主要包括保险产品销售、保单处理、审核、出单、保全批改以及理陪、赔付等，体现了传统保险业务的主要流程;财务和投资管理主要涉及财务核算、资金管理、出于保值增值目标的投资管理、以及进入基金、债券市场的相应业务管理等;风险管理系统则包括了风险控制、绩效考核、再保险等内容。事实上，以业务为标准划分的保险系统，随着保险公司管理体制的变革、业务流程的更新必然会发生变化。最重要的是，如果系统的设计应用不是以客户为中心，以满足客户保险需求为基础的话，保险公司的服务质量和销售业绩就不可能大幅提高。换言之，保险公司在原有业务系统的基础上推动CRM应用，必须从多个层次着手。
>第一，必须以客户为中心，提高客户服务水平，如果没有CRM技术系统、呼叫中心等的支持，企业就难以大规模、标准化地提高服务质量；
第二，保险公司必须以集成管理客户信息为突破点，做好关键客户管理工作，从而稳定和发展优质的保险客户;
第三，保险公司要能够集成数据，实时分析业务发展情况，从而及时采取营销和调整策略，改进自己的销售管理和业务管理;
第四，
要能够通过分析数据、通过指标和模型来加强风险控制，做好绩效考核;
第五，
是借助CRM系统，分析客户需求以开发新产品，实现与业务系统的整合，提高保险公司的决策支持和商业智能水平。



### 1.3 基于区块链的保险业的发展前景

1. 具有广阔的应用价值
区块链可在产品开发、风险防范、流程优化以及相互保险等领域具有应用价值。身份识别:通过不可更改的身份证明信息降低保险欺诈风险；智能合约：智能合约能够完成理赔处理的自动执行，对于客户来说，这是一种可靠且透明的支付机制，而且智能合约能够用来强化具体合约规则；相互保险：利用区块链重构信任的基本特点，破解相互保险的信任难题，细化不同群体的风险特征和风险分散诉求，提升成员之间的知情权和选择权，从而创造一个更加公平、透明、安全和高效的互助机制。

2. 有助于提升保险业降本增效
区块链技术的去信任化与共识机制,使客户可以在平台自主下单,可以使保险行业运营成本大幅降低。弹性赔付机制,可以使保险公司合理安排存量资金,提高资金的配置效率。
在降低成本方面，以各保险公司为节点的联盟链，可以实现保险公司之间的信息共享。比如，在有共保或再保的保险赔偿情形中，通过将赔偿文件录入区块链中，所有的合同主体（保险人、再保险人及承保代理人等）都可以监测到保险赔偿的进展，能够及时处理保险理赔，极大地减少了保险公司的运营成本。

3. 有助缓解保险业务信息不对称
区块链技术可以打通保险机构与其他相关组织之间数据共享,防止道德风险和逆向选择。有助缓解保险业务信息不对称。

4. 自动理赔或成为发展方向
保险公司的产品资料利用区块链的方式储备。保险公司利用联盟链将数据上链，联盟链与银行及经纪的系统对接，双方所看到的产品资料便会保持一致。另外，区块链亦可记录保单的赔偿内容，可以为大部分的保险产品做到自动理赔。
总而言之，区块链在保险行业的应用因具有广阔的发展前景和众多的业务契合点，各家保险公司也已经开始布局和加速落地。毋容置疑，区块链等关键技术的日益成熟将为保险行业各环节价值链的重塑再造带来机遇，同时对投保人来讲也是长期利好。
案例剖析之提升健康险理赔流程
今年4月，波士顿咨询发布《携手区块链，保险科技企业引领行业技术革新》，对蚂蚁金服、众安保险通过区块链技术颠覆传统业务模型及IT架构进行了分析。随后中国银行保险报网就蚂蚁金服的案例进行了公开报道，我们来回顾一下。
根据以往经验，健康险的理赔处理可能耗时很长。然而，蚂蚁金服在2018年末推出了一个新的基于区块链的票据系统，极大地提升了流程的效率。
简单来说，在该系统中，医院、蚂蚁服务后端、保险公司等利益相关方都以“共识节点（consensus node）”的形式接入区块链中，即时同步数据和信息流。共识节点的设计旨在确保多个参与方在网络中的高可靠性，即网络中的基本分布式“单元”，并遵照特定的协议或算法达成一致（或共识）。只要支持区块链的基础设施运行良好（即信号基站、Wi-Fi带宽、laaS云配置等），就可以在几秒钟内完成保险理赔的处理和验证。
具体来看，在用户层，显示的是线下用户行为以及支付宝应用内的资金或理赔流。当患者前往医院时，只需携带已安装支付宝应用的智能手机。一旦患者完成治疗并付款，医院就会将电子发票开具至支付宝平台上的“发票管家”小程序，供患者即时查看。只需几次点击，同意保险条款和条件，理赔流程就会自动启动，患者将在约5秒内收到报销款项。
在功能层，从医院的角度来看，防篡改的发票可以直接在区块链上生成并发布，无需担心验证过程是否可靠。验证结果可为支付宝所接受，并供其他共识节点进行信息同步。
从蚂蚁区块链的角度来看，这就像一个链上客观中立的第三方，负责验证及同步必要的数据信息、连接重要的利益相关方。依赖于区块链本身不可篡改、可存证、可信流转的机制，蚂蚁区块链可充分消除该生态内其他参与方的信任顾虑。对于蚂蚁金服之外的各参与方来说，医疗票据流通过程中由于不信任而产生的交易摩擦、时间和人力成本得以充分降低，生态系统的多样性也将大大丰富。
从保险公司的角度来看，共识节点旨在提升理赔效率。如果采用传统的线下运营模式，患者即便通过电子钱包完成支付，也仍然需要提交许多纸质理赔材料，与理赔专员见面，或前往保险公司在当地的线下门店，并至少等待10个工作日才能获得赔款，而这还仅仅是在患者遵照要求提供了材料的前提下才成立的。如果在发票生成时就运用区块链进行跟踪同步的话，就可以用高效的自动化识别技术替代繁琐的核验流程。这样就可以从源头杜绝超标理赔、虚假理赔、发票欺诈等问题。只需等待患者同意和系统响应，即可立即进行理赔资金划拨。
在基础构架层，区块链的性质决定了其有能力迅速执行和同步反欺诈指令。与此同时，基础架构层能确保区块链的安全性，并为网络中的所有数据提供存储。未来预计将产生越来越多、各种类别的数据，例如医院开具的电子处方、可转让的通证化保险资产等。而那时，需要确保基础架构层足够稳固可靠，避免因基础架构能力不足而可能导致的数据事故。



## 第二章 区块链技术于保险业的优势
### 2.1 传统保险业的弊端

##### 一、寿险方面：
(一)、保险代理人的问题。
>1.有关保险代理人无证展业、展业宣传不规范，不完全履行对保险合同条款，特别是合同中的免责条款的说明和明确说明的法定义务的问题。实践中，往往存在未取得保险代理人资格的业务员展业的情况，也存在保险代理人在向客户介绍保险产品时，不出示保险合同原件的问题，阻碍了保险消费者对合同条款的理解，保险人也不能够履行说明和明确说明其法定的义务。
2、有的保险代理人，未经询问就代替保险消费者履行如实告知义务，为了促成保险合同成立，获得佣金收入阻碍保险消费者如实告知患病史、向保险消费者推荐缴费高、保障程度低的险种。保险代理人的收入主要是促成合同成立后，提取的佣金。有的保险代理人不顾职业道德，涉嫌误导和阻碍保险消费者履行告知义务，不负责任的促成合同成立，获得不当佣金收入。有的保险代理人为了获取高额佣金收入，不是按照保险消费者的需要，推荐保费高而保障程度低的险种，获取高额佣金收入，导致保险消费者在发生保险事故时，不能获得充分的保险金给付。

(二)、理赔时，
>保险公司收取保险消费者的保险合同原件无道理，导致保险消费者维权时缺乏证据的问题。当被保险人发生保险事故并申请理赔时，保险公司除了要求被保险人或是受益人提供证明被保险人发生保险事故的证据外，还要求保险消费者将保险合同的原件交回保险公司。当发生纠纷时，为了维权，保险消费者想讨回资料，哪怕是复印件都是非常困难的，人为的为保险消费者的维权设置门槛。

(三)、保险公司拒赔时不透明，不明确告知保险消费者拒赔的具体理由和所依据的证据。
>如保险公司以被保险人未如实告知为由拒赔时，不向保险消费者详细说明未告知的内容，即所依据的具体证据。

(四)、学平险违规承保的问题。
>保险公司往往通过教育行政管理部门或是学校变相地强制所有的学生购买学平险，甚至教师代收保险费。还有一些保险公司对新入学的大学生一次性的连续收取四年的保险费，违规短险长做。(五)、银行代理保险存在的问题
1、银行一般是以兼业代理人的身份代理销售保险产品，有关窗口的储蓄人员是否得到培训、是否具备销售保险产品的能力是个问题。
2、在银行代理保险中，储蓄员误导销售的情况屡有发生，如故意混淆保险和储蓄，用储蓄的概念来同保险产品进行类比。以不收取利息税、强调固定的收益率等来引诱储户来购买保险。甚至储蓄员不告知提前退保要扣除佣金，使低收入者、强调资金的流动性的资金所有者提前支取资金时受到损失。导致消费者对银行保险的产品性质不明、主体不明，以致保险纠纷不断。

(六)、一些含死亡责任的保单未有被保险人亲笔签名的问题这涉及保险消费者的生命利益的保护问题，也涉及到保险消费者的合同效力的问题、涉及到消费者是否能够获得保险理赔的问题、涉及到保险消费者的财产权的问题。
(七)、意外伤害保险合同约定，自发生事故之日起，180天内未向本公司提出书面索赔申请，即视为自动放弃权益。保险法规定，人寿保险的索赔期是五年，财产险的索赔期是两年。自发生事故之日起，180天应该是定残的时间。
(八)、公路旅客意外伤害险保单内容过于简化，缺少保户必有的信息。乘客乘坐车次、座位号、乘客的姓名等信息不明、保险公司不掌握购买保险的乘客的相关信息，易导致事故发生时的确认困难，影响保险消费者的合同利益，另一方面，易导致保险欺诈，损害保险公司的利益。
(九)、公路旅客意外医疗险的保险责任有限且与承运人应承担的责任重叠。公路旅客意外伤害保险设计存在瑕疵。公路旅客意外伤害保险中，意外医疗保险责任与承运人应该承担的责任及承运人责任险的保险责任重叠，易导致乘客受伤，在承运人承担责任后，得不到保险理赔或道德风险的发生。
(十)、共保体垄断销售航空旅客意外伤害保险
>(行业指导条款)，禁止航意险替代产品的
销售，涉嫌限制竞争导致垄断。在市场经济条件下，
目前“共保体”的存在制约了保险公司之间的竞争空间；限制了保险公司之间的价格竞争；客观上阻碍了保险商品的价格回归到客观、真实水平的进程；严重地挫伤了经营管理较好的、充满活力的、意图创新的新成立的保险公司实现扩大自己市场份额的积极性；不利于保险业的健康发展的，同时损害了消费者的利益，使得消费者的知情权、自主选择权、公平交易权受到侵害。
#### 二、财险方面：
(一)、机动车辆保险中，车损险及其附加险超额承保以及“新车购置价”易引发歧义的问题。
>1、新车购置价概念理解有歧义，通常消费者易理解为以前购买该保险机动车新车时的价格。但是，新车购置价却是指：合同中的新车购置价，是指：本保险合同签订时，在签订地购置与保险机动车同类型新车
(含车辆购置附加税)的价格。
2、在订立保险合同时，不对新车购置价进行解释，涉嫌大面积超额承保的问题。保险公司有关在车辆部分损害的情况下，新件换旧件的解释存在原则性的错误。损失补偿是原则。按照保险公司的逻辑，旧件就应该换旧件，这是原则，那么，即使是按照新车价投保，也应该是旧件换旧件。
3、保险公司如何公示新车购置价，特别是停产车型的新车购置价的确定问题。

(二)、部分财产保险公司的业务人员，专业素质差，对于应该理赔的案件，不按照正常申请理赔的程序作出理赔决定，口头错误的告知保险消费者拒赔，并拒收保险消费者的理赔材料，导致错误。比如：空中坠落物导致行使中的机动车车损，保险公司的出现场的工作人员错误地认为不属于保险责任范围，不对现场进行勘查和收取保险消费者的理赔材料，正常作出理赔决定。事实上，这种情况保险公司是应该理赔的。



### 2.2 基于区块链的智能保险业的优势
##### ▲保险索赔
- 处理保险索赔是一个缓慢、繁琐且容易出错的流程，需要重要数据和多方合作。例如，考虑由于另一个驾驶员的过失而发生车祸的驾驶员，驾驶员向保险公司提出索赔以弥补损失。然后，保险公司审查索赔并从过失驾驶人的保险公司处收回损失，不同保险公司可能具有不同的索赔处理流程和系统。这种方法效率低下且耗时长。
- 保险公司可以在保险索赔处理中利用区块链加快程序并最大限度地降低运营成本。利用区块链的安全和分布式分类账，保险公司和投保人可以数字化监控和管理每一项有形资产。保险公司可以使用智能合约对特定业务规则进行编码以自动处理索赔。例如，一些保险公司为延误的航班提供航班保险，在智能合约的帮助下，保险公司可以收集航班信息并与全球航空数据库通信，以监控多个航班状态，如果投保人延误超过两小时，智能合约可在与机场和投保人确认航班信息后，自动支付赔付费用。在区块链保险理赔的帮助下，投保人可以避免填写理赔表格。此外，保险公司可以减少处理和验证索赔数据的时间。

##### ▲健康保险
- 由于医疗机构、保险公司和患者等多方的参与，导致处理健康保险索赔流程变得异常复杂。例如，如果患者希望提交心脏手术的健康保险索赔，那么医疗机构必须向保险公司索取若干文件。为此，医疗机构必须从保险公司获得提交索赔的授权。手术后，保险公司从每个医疗机构和诊断病人的医生那里收集文件，而整个过程需要大量的文书工作。此外，医疗机构和保险公司用于记录患者信息的后端基础设施已经过时，而且不同医疗机构和保险公司可能会使用不同的格式和标准来存储数据，这可能会导致不一致和混淆。此外，敏感的患者数据受严格的隐私法保护。因此，医疗机构无意间在其组织内创建了数据孤岛。区块链在保险公司的出现可以帮助患者安全地分享他们的数据，同时确保隐私。区块链网络是加密安全的，以避免非法修改数据。患者可以根据具体情况授予保险公司访问权限。在区块链的帮助下，医疗保健机构可以创建一个实时同步的全行业患者数据存储库。使用这种方法，保险公司可以审计多个医疗机构的医疗信息。
##### ▲资产跟踪
- 据统计，在美国有70540人拥有价值5000万美元以上的净资产。这些高净值人士拥有高价值资产，如珠宝、艺术品、葡萄酒、私人岛屿、游艇等。随着资产数量的不断增加，追踪这些资产所有权和价值的证据会变得越来越复杂。保险公司可以在分散网络的帮助下利用区块链进行资产跟踪。资产所有者可以在区块链网络上注册他们的资产，而网络的每个节点都将包含资产的不可变记录。如果资产所有者将资产转让给另一个人，那么该交易将被记录在网络上。使用这种方法，每个资产所有者都可以追溯到所有以前的所有者。此外，由于区块链的加密性质，交易历史不能修改或编辑。通过这种方法，将区块链引入保险公司可以有效简化资产跟踪并提供所有权证明。
##### ▲欺诈检测
- 统计数据显示，据保守估计，保险欺诈每年窃取近800亿美元。由于这种保险欺诈，美国家庭平均面临400至700美元的保费上涨。参与保险欺诈的犯罪分子经常利用漏洞，在这些漏洞中，欺诈模式只能通过跨多个保险公司的广泛数据集来识别。然而，由于竞争和法律方面的挑战，保险公司无法共享此类信息，因此，传统的欺诈检测方法是无效的。将区块链引入保险公司将改善多家保险公司之间的合作。借助区块链驱动的分布式账本，保险公司可以记录每一笔交易，并使用加密和访问控制保护数据。保险公司可以共享交易数据，并协作在整个生态系统中查找可疑行为和模式。通过利用保险公司中的区块链，保险公司可以消除重复保险索赔订单，并减少伪造和保费损失。




## 第三章  基于区块链的智能化保险方案设计
### 3.1	业务设计

### 3.2 架构设计
|设保项目|
【车险保险】
【健康保险】
|投保人|
【是否满足投保人要求】
【投保人是否满足购保要求】
（例如：满足投保年龄的要求）
【投保人是否有投保项目相应隐患】
（例如：满足健康状况的要求）
|受益人|
【需有承担受益的能力】
（无行为能力者需有监护人）
儿童或不能辨认自己行为的精神病人。
|购保金额|
|保证金额|
|保险时限|
【购保时间】
【持续时长】
|违约惩罚|
【规定时限未交维保金额】
（根据保单类型情况分以下俩种情况）
1.通知客户
支付保险金后，扣除保单宽限期内应缴的当期保险费
超过保单宽限期没有交费，那么保单进入中止期，取消保单。
2.直接取消用户所受保单。
注：违保或骗保造成的损失定则以及契约精神违背的惩罚。

### 3.3 交互设计

## 第四章 方案设计的技术支持
### 4.1 以太坊

## 第五章 应用及业务实践

## 第六章 商业模式


~ [Ken Williams, Perl Hackers](http://mathforum.org/ken/perl_modules.html#document)

Writing READMEs is way too hard, and keeping them maintained is difficult. By offloading this process - making writing easier, making editing easier, making it clear whether or not an edit is up to spec or not - you can spend less time worrying about whether or not your initial documentation is good, and spend more time writing and using code.

By having a standard, users can spend less time searching for the information they want. They can also build tools to gather search terms from descriptions, to automatically run example code, to check licensing, and so on.

The goals for this repository are:

1. A well defined **specification**. This can be found in the [Spec document](spec.md). It is a constant work in progress; please open issues to discuss changes.
2. **An example README**. This Readme is fully standard-readme compliant, and there are more examples in the `example-readmes` folder.
3. A **linter** that can be used to look at errors in a given Readme. Please refer to the [tracking issue](https://github.com/RichardLitt/standard-readme/issues/5).
4. A **generator** that can be used to quickly scaffold out new READMEs. See [generator-standard-readme](https://github.com/RichardLitt/generator-standard-readme).
5. A **compliant badge** for users. See [the badge](#badge).

## Install

This project uses [node](http://nodejs.org) and [npm](https://npmjs.com). Go check them out if you don't have them locally installed.

```sh
$ npm install --global standard-readme-spec
```

## Usage

This is only a documentation package. You can print out [spec.md](spec.md) to your console:

```sh
$ standard-readme-spec
# Prints out the standard-readme spec
```

### Generator

To use the generator, look at [generator-standard-readme](https://github.com/RichardLitt/generator-standard-readme). There is a global executable to run the generator in that package, aliased as `standard-readme`.

## Badge

If your README is compliant with Standard-Readme and you're on GitHub, it would be great if you could add the badge. This allows people to link back to this Spec, and helps adoption of the README. The badge is **not required**.

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

To add in Markdown format, use this code:

```
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
```

## Example Readmes

To see how the specification has been applied, see the [example-readmes](example-readmes/).

## Related Efforts

- [Art of Readme](https://github.com/noffle/art-of-readme) - 💌 Learn the art of writing quality READMEs.
- [open-source-template](https://github.com/davidbgk/open-source-template/) - A README template to encourage open-source contributions.

## Maintainers

[@RichardLitt](https://github.com/RichardLitt).

## Contributing

Feel free to dive in! [Open an issue](https://github.com/RichardLitt/standard-readme/issues/new) or submit PRs.

Standard Readme follows the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct.

### Contributors

This project exists thanks to all the people who contribute. 
<a href="https://github.com/RichardLitt/standard-readme/graphs/contributors"><img src="https://opencollective.com/standard-readme/contributors.svg?width=890&button=false" /></a>


## License

[MIT](LICENSE) © Richard Littauer
