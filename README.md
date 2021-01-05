# Blockchain-intelligent-insurance区块链智能保险

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

A standard style for README files

Your README file is normally the first entry point to your code. It should tell people why they should use your module, how they can install it, and how they can use it. Standardizing how you write your README makes creating and maintaining your READMEs easier. Great documentation takes work!

This repository contains:

1. [The specification](spec.md) for how a standard README should look.
2. A link to a linter you can use to keep your README maintained ([work in progress](https://github.com/RichardLitt/standard-readme/issues/5)).
3. A link to [a generator](https://github.com/RichardLitt/generator-standard-readme) you can use to create standard READMEs.
4. [A badge](#badge) to point to this spec.
5. [Examples of standard READMEs](example-readmes/) - such as this file you are reading.

Standard Readme is designed for open source libraries. Although it’s [historically](#background) made for Node and npm projects, it also applies to libraries in other languages and package managers.


## 目录
- [前言](#install)
- [第一章 背景与现状](#Background)
	- [1.1 保险业的发展历史](#11保险业的发展历史)
	- [1.2 保险业利用信息化社会的发展现状](#generator)
	- [1.3 基于区块链的保险业的发展前景](#generator)
- [第二章 区块链技术于保险业的优势](#badge)
	- [2.1 传统保险业的弊端](#generator)
	- [2.2 基于区块链的智能保险业的优势](#generator)
- [第三章 基于区块链的智能化保险方案设计](#example-readmes)
 	- [3.1 业务设计](#generator)
	- [3.2 架构设计](#generator)
	- [3.3 交互设计](#generator)
- [第四章 方案设计的技术支持](#related-efforts)
   	- [4.1 以太坊](#generator)
- [第五章 应用及业务实践](#maintainers)
- [第六章 商业模式](#contributing)

# 第一章 背景与现状
#### 1.1保险业的发展历史
# 第一章 背景与现状
### 1.1保险业的发展历史

###### （一）中国保险业的开端。
> 鸦片战争以后，西方列强迫使清政府签订了一系列不平等条约，加强了对我国的政治、军事、经济的侵略。外国保险公司纷纷登陆中国，中国保险市场逐渐形成。外国保险公司凭借不平等条约所持有的政治特权扩张业务领域，利用买办招揽业务，垄断了早期的中国保险市场从中，攫取了巨额利润。面对外商独占中国保险市场，每年从中国掠夺巨额利润，致使白银大量外流这一严峻事实，中国人民振兴图强、维护民族权利、自办保险的民族意识被激起。在此情况下，1865年月25日义和公司保险行在上海创立。义和公司保险行，是我国第一家自办的保险机构，其成立打破了外商保险公司独占中国保险市场的局面，为以后民族保险业的兴起开辟了先河。提到保险业就不得不提到航运业，保险与贸易两者是互为表里的关系。轮船招商局于1872年在上海成立，是中国人自办的最早的轮船航运企业，也是现在的招商局集团的前身。它不仅是中国现代航运业的起点，也可以说是中国保险业的源头之一。轮船招商局自创办之日起就深刻明白保险对于航运业的重要作用。作为一种打击竞争对手的手法，早期依附于外商航运业的外资保险公司听命于上司，为了击垮轮船招商局，对其所属船舶百般刁难。收取高额保费、对中国本土产的船只不保等限制。以李鸿章为代表的洋务派，为适应航运业发展的需要，先后创办了“保险招商局”、“仁和水险公司”和“济和水火险公司”等官办保险公司，取得了较好保险的经营业绩，并坚持与外商保险公司进行斗争，从而在一定程度上抵制了外商对中国保险市场的控制。当然，洋务派在保险业方面的努力不能改变外商垄断中国保险市场的局面。
###### （二）建国前在夹缝中生存发展的民族保险业。
> 民国初期，中国民族保险业获得了难得的发展机遇：一是民国初建需要刺激工商业的发展以稳定政权；二是第一次世界大战的爆发，欧美列强卷入战争，无暇东顾，大大减缓了洋商对中国保险市场的控制；三是五四运动的爆发，反帝斗争的兴起，赢得了整个民族对民族工商业的支持和对洋商的抵制。从1912年到1925，国内陆续创办了华安合群等30余家民族保险公司，华资寿险市场一度兴起，但由于经营不善，其中停业者居多。
至上世纪20年代中后期，金融资本投入保险业，民族银行开始兴办保险企业，民族保险业始有进一步发展。保险业有了突破性的发展，出现了太平保险公司这样实力雄厚、信誉卓著，分支机构代理网点遍布全国各大城市，甚至涉足南洋市场，在国际上也有一定声誉的民族保险公司。但是抗日战争爆发后，保险业受到巨大的冲击。
###### （三）新中国后保险行业的发展
> 建国后中国保险业的发展史，可谓跌宕起伏。经历了建国初期的起步，到六七十年代的低谷，最后到现在的快速发展的过程。保险业作为国家经济发展的晴雨表，到上个世纪末，经过了四个发展时期。一是在五十年代的初创时期，保险业仅中国人民保险公司一家国有保险公司，保险业务的发展还处于初级拓荒阶段，业务范围也十分狭窄，但是当时保险业配合新中国经济建设，在保障生产安全、促进物资交流、安定人民生活、壮大国有资产等发挥了积极作用；第二阶段是在六七十年代的低谷期，由于当时的历史原因，本外币保险业务基本停办，仅保留五大口岸城市的涉外险业务，保险业陷入长达二十年的停滞时期，发展严重受挫；第三阶段是八十年代的复苏期，伴随着中国改革开放和经济发展，保险业迅速崛起，为国家经济建设和人民生活提供多方面广泛的服务，但市场经营主体仍处于人保独家垄断状态；第四阶段是九十年代的发展期，保险业独家垄断的格局被打破，取而代之的是中外保险公司多家竞争、共同发展的多元化新格局。进入二十世纪未找到目录项。以来，我国保险业正步入一个全新的发展阶段，根据我国入世承诺，保险业在金融行业中开放力度最大，开放过渡期最短。2004年12月11日过渡期结束，我国保险业进入全面对外开放的新时期，呈现出日渐市场化、专业化、国际化、规范化的新特点。
30年的改革开放为我国保险业发展注入了新的生机和活力。改革开放之初，我国保险市场由一家公司经营，全部保费收入只有4.6亿元。到2007年，全国保险公司达到110家，总资产达到2.9万亿元，实现保费收入7000多亿元，市场规模增长
1500多倍。
###### （四）目前我国保险业发展现状
> 中国保险业的整体实力与核心竞争能力不断提升、经济功能初步显现。回顾保险业６０年来的改革发展历程，虽然经历了曲折，但全行业始终坚持改革创新，在探索中国特色保险业发展道路上迈出了坚实的步伐取得了令人瞩目的发展成就，特别是党的十六大以来，在“抓监管、防风险、促发展”的总体思路指导下，我国保险业保持了又好又快的发展势头，在各方面取得了突出的成绩。

> 1、保险业务大发展，行业实力显著增强，竞争格局基本形成。保险业快速发展，业务领域逐步拓展。1980年恢复国内保险业务时，我国只有企财险、货运险、家财险、汽车险等几个保险业务种类。此后随着国内保险业风险管理技术的进步和经营管理能力的提高，业务领域逐步从财产损失保险扩展到人寿保险、责任保险、信用保证保险、意外伤害保险、健康保险等领域，目前已基本形成涵盖所有可保风险领域的业务和产品体系。保险业恢复经营以来，我国保费收入年均增长超过20%，是国民经济中发展最快的行业之一。2008年实现原保费收入9789亿元，世界排名第6位，中国已逐步成长为新兴的保险大国。资产规模不断壮大。1949年人民保险公司成立之初，仅有资本金约200万元。目前，全国保险公司总资产达到3.7万亿元。市场体系日益完善，从由国有保险独家经营保险业务，到目前全国共有保险公司120多家，初步建成了多种组织形式和所有制形式并存，公平竞争、共同发展的保险市场体系。

> 2、体制机制发生积极变化自改革开放以来，我国的保险业就分别从经营体制改革、公司体制改革、资金管理体制改革、保险监管体制改革四方面，进行了有条不紊的改革。首先保险业务经营体制改革。1996年，为了适应保险业快速发展和防范风险的需要，建立了保险分业经营体制，对产险、寿险实行专业化经营。人保、平安、太平洋等综合性保险公司相继完成产寿险分业经营体制改革。同时，为了提升保险业服务经济社会的能力与水平，对农业保险、健康保险、养老保险等业务领域探索实行专业化经营，专业性的保险公司开始逐渐成立。保险中介市场也逐步发育完善。公司体制改革。坚持从实际出发，采取“三步走”的战略，积极吸引外资和民营资本参股，引进境外战略投资者，优化股权结构，公司治理结构和运行机制不断完善。保险资金管理体制改革。实现了保险资金专业化集中运用，保险资产管理公司从无到有，目前达到10家，管理资产占保险业全部资产的82.6%；从资金运用结构看，实现了从银行存款为主向债券投资为主的转变。

> 3、全社会的风险和保险意识大提高改革开放前，我国保险市场的消费者规模相当有限，消费者对保险的了解非常少，保险意识处在一个较低的水平。随着革开放的不断推进，保险知识的普及也日渐展开，消费者对保险的认识和理解逐步深化。同时，随着收入水平的提高和市场化体制改革的推进，全社会的风险和保险意识逐步提升，消费者开始主动购买所需要的保险产品，并且在购买保险产品时，多方搜集所需保险产品的信息，了解保险市场行情。人民群众保险意识不断增强和消费行为日趋理性，标志着我国保险市场逐步向成熟的方向迈进。

> 4、保险创新取得积极进展。产品创新更加贴近市场需求，适应不同消费群体，开放不同的产品。针对居民日趋多元化的金融保险需求，突破保险产品传统保障功能的限制，开发了具有投资理财功能的产品。针对低收入人群开发了保费低廉、手续简便、保障适度的小额保险产品。适应建立多层次社会保障体系需要，开发了多种形式的商业养老和健康保险产品等。在产品贴近市场的情况下，营销创新与时俱进。从个人营销代理到现在的通过银行、邮局、车行等机构代理，甚至通过利用网络、电话等方式销售保险产品，为保险消费者提供便利、质优价廉的保险服务。在做到服务创新的同时，理论创新为产品创新和营销创新提供了理论基础。近年来特别是十六大以来，在总结保险实践经验的基础上，保险理论创新不断深入推进。提出了保险业发展阶段理论，作出了我国保险业仍处于发展的初级阶段的判断，首要任务是加快发展，做大做强。

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
