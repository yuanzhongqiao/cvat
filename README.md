<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
  <animated-image data-catalyst="" style="width: 100%;"><a target="_blank" rel="noopener noreferrer" href="https://github.com/cvat-ai/cvat/blob/develop/site/content/en/images/cvat-readme-gif.gif" data-target="animated-image.originalLink"><img src="https://github.com/cvat-ai/cvat/raw/develop/site/content/en/images/cvat-readme-gif.gif" alt="CVAT 平台" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage" _mstalt="193037" _msthash="426"></a>
    
</p>
<p align="center" dir="auto">
  <a href="https://app.cvat.ai/" rel="nofollow">
    <img src="/cvat-ai/cvat/raw/develop/site/content/en/images/cvat-readme-button-tr-bg.png" alt="立即开始批注" style="max-width: 100%;" _mstalt="380757" _msthash="431">
  </a>
</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="69839016" _msthash="432">计算机视觉注释工具 （CVAT）</h1><a id="user-content-computer-vision-annotation-tool-cvat" class="anchor" aria-label="永久链接：计算机视觉注释工具 （CVAT）" href="#computer-vision-annotation-tool-cvat" _mstaria-label="1554644" _msthash="433"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://github.com/cvat-ai/cvat/actions"><img src="https://github.com/cvat-ai/cvat/actions/workflows/main.yml/badge.svg?branch=develop" alt="词" style="max-width: 100%;" _mstalt="13689" _msthash="434"></a>
<a href="https://gitter.im/opencv-cvat/public" rel="nofollow"><img src="https://camo.githubusercontent.com/7d43347cea74e51549da5122f3b7f21de611d6710da810820997c3d2f4816142/68747470733a2f2f696d672e736869656c64732e696f2f6769747465722f726f6f6d2f6f70656e63762d637661742f7075626c69633f7374796c653d666c6174" alt="Gitter 聊天" data-canonical-src="https://img.shields.io/gitter/room/opencv-cvat/public?style=flat" style="max-width: 100%;" _mstalt="156962" _msthash="435"></a>
<a href="https://discord.gg/fNR3eXfk6C" rel="nofollow"><img src="https://camo.githubusercontent.com/348b39dbd882e0d6c0ea1f098defebb1518dc5a7b3ec7deb08880fdf9e1a46de/68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f313030303738393934323830323333373833343f6c6162656c3d646973636f7264" alt="不和" data-canonical-src="https://img.shields.io/discord/1000789942802337834?label=discord" style="max-width: 100%;" _mstalt="93990" _msthash="436"></a>
<a href="https://codecov.io/github/cvat-ai/cvat" rel="nofollow"><img src="https://camo.githubusercontent.com/16d5c430fb71ac697b3774c7187a528c15a8a9075f965a27cc231dc9b66daf6d/68747470733a2f2f636f6465636f762e696f2f6769746875622f637661742d61692f637661742f6272616e63682f646576656c6f702f67726170682f62616467652e737667" alt="覆盖状态" data-canonical-src="https://codecov.io/github/cvat-ai/cvat/branch/develop/graph/badge.svg" style="max-width: 100%;" _mstalt="259493" _msthash="437"></a>
<a href="https://hub.docker.com/r/cvat/server" rel="nofollow"><img src="https://camo.githubusercontent.com/7962e7818e48881ca13de433ca735cd62f740660b6e68657053f4071b3a40e33/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f70756c6c732f637661742f7365727665722e7376673f7374796c653d666c61742d737175617265266c6162656c3d73657276657225323070756c6c73" alt="服务器拉取" data-canonical-src="https://img.shields.io/docker/pulls/cvat/server.svg?style=flat-square&amp;label=server%20pulls" style="max-width: 100%;" _mstalt="191035" _msthash="438"></a>
<a href="https://hub.docker.com/r/cvat/ui" rel="nofollow"><img src="https://camo.githubusercontent.com/d41b46c6a77ab5b446b87481117986c38517f2961af315f4cbfcec8217af6b12/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f70756c6c732f637661742f75692e7376673f7374796c653d666c61742d737175617265266c6162656c3d554925323070756c6c73" alt="UI 拉取" data-canonical-src="https://img.shields.io/docker/pulls/cvat/ui.svg?style=flat-square&amp;label=UI%20pulls" style="max-width: 100%;" _mstalt="101608" _msthash="439"></a>
<a href="https://zenodo.org/badge/latestdoi/139156354" rel="nofollow"><img src="https://camo.githubusercontent.com/a348d33b6a4d78edd0b4269ebc218b805def433fe7325be288686d27d16cb242/68747470733a2f2f7a656e6f646f2e6f72672f62616467652f3133393135363335342e737667" alt="数字对象标识符" data-canonical-src="https://zenodo.org/badge/139156354.svg" style="max-width: 100%;" _mstalt="22945" _msthash="440"></a></p>
<p dir="auto" _msttexthash="1495213083" _msthash="441">CVAT 是一种交互式视频和图像注释
计算机视觉工具。它被数以万计的用户使用
世界各地的公司。我们的使命是帮助开发人员、公司和
世界各地的组织使用以数据为中心的解决方案解决实际问题
AI 方法。</p>
<p dir="auto" _msttexthash="578129526" _msthash="442">开始在线使用 CVAT：<a href="https://cvat.ai" rel="nofollow" _istranslated="1">cvat.ai</a>。您可以免费使用它，
或<a href="https://www.cvat.ai/pricing/cloud" rel="nofollow" _istranslated="1">订阅</a>以获取无限数据，
组织、自动注释以及 <a href="https://www.cvat.ai/post/integrating-hugging-face-and-roboflow-models" rel="nofollow" _istranslated="1">Roboflow 和 HuggingFace 集成</a>。</p>
<p dir="auto" _msttexthash="1671833371" _msthash="443">或者将 CVAT 设置为自托管解决方案：<a href="https://docs.cvat.ai/docs/administration/basics/installation/" rel="nofollow" _istranslated="1">自托管安装指南</a>。
我们提供<a href="https://www.cvat.ai/pricing/on-prem" rel="nofollow" _istranslated="1">企业支持</a>
具有高级功能的自托管安装：SSO、LDAP、Roboflow 和
HuggingFace 集成和高级分析（即将推出）。我们还
进行培训和 24 小时 SLA 的专门支持。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="13319462" _msthash="444">快速开始 ⚡</h2><a id="user-content-quick-start-" class="anchor" aria-label="永久链接： 快速入门 ⚡" href="#quick-start-" _mstaria-label="3918005" _msthash="445"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://docs.cvat.ai/docs/administration/basics/installation/" rel="nofollow" _msttexthash="11513372" _msthash="446">安装指南</a></li>
<li><a href="https://docs.cvat.ai/docs/manual/" rel="nofollow" _msttexthash="4490473" _msthash="447">手动</a></li>
<li><a href="https://docs.cvat.ai/docs/contributing/" rel="nofollow" _msttexthash="6354283" _msthash="448">贡献</a></li>
<li><a href="https://github.com/cvat-ai/datumaro/blob/develop/README.md" _msttexthash="31807841" _msthash="449">Datumaro 数据集框架</a></li>
<li><a href="#api" _msttexthash="7219901" _msthash="450">服务器 API</a></li>
<li><a href="#sdk" _msttexthash="21817211" _msthash="451">Python 开发工具包</a></li>
<li><a href="#cli" _msttexthash="14258062" _msthash="452">命令行工具</a></li>
<li><a href="https://docs.cvat.ai/docs/manual/advanced/xml_format/" rel="nofollow" _msttexthash="17261673" _msthash="453">XML 注释格式</a></li>
<li><a href="https://docs.cvat.ai/docs/administration/basics/aws-deployment-guide/" rel="nofollow" _msttexthash="17073043" _msthash="454">AWS 部署指南</a></li>
<li><a href="https://docs.cvat.ai/docs/faq/" rel="nofollow" _msttexthash="25404483" _msthash="455">常见问题解答</a></li>
<li><a href="#where-to-ask-questions" _msttexthash="17468438" _msthash="456">在哪里提问</a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="20663565" _msthash="457">合作 伙伴 ❤️</h2><a id="user-content-partners-️" class="anchor" aria-label="永久链接： 合作伙伴 ❤️" href="#partners-️" _mstaria-label="25634765" _msthash="458"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="846365455" _msthash="459">CVAT 被世界各地的团队使用。在列表中，您可以找到
帮助我们支持产品或我们生态系统的重要组成部分。如果您使用我们，
请给我们写一封信 <a href="mailto:contact+github@cvat.ai" _istranslated="1">contact@cvat.ai</a>.</p>
<ul dir="auto">
<li _msttexthash="223933164" _msthash="460"><a href="https://hmt.ai" rel="nofollow" _istranslated="1">Human Protocol</a> 使用 CVAT 作为向 Human Protocol 添加注释服务的一种方式。</li>
<li _msttexthash="910310726" _msthash="461"><a href="https://fiftyone.ai" rel="nofollow" _istranslated="1">FiftyOne</a> 是一个开源的数据集管理和模型分析
用于可视化、探索和改进与 CVAT <a href="https://voxel51.com/docs/fiftyone/integrations/cvat.html" rel="nofollow" _istranslated="1">紧密集成的</a>计算机视觉数据集和模型的工具
进行注释和标签优化。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="15931890" _msthash="462">公共数据集</h2><a id="user-content-public-datasets" class="anchor" aria-label="永久链接：公共数据集" href="#public-datasets" _mstaria-label="597389" _msthash="463"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="615512274" _msthash="464"><a href="https://github.com/smhassanerfani/atlantis" _istranslated="1">ATLANTIS</a>，一个用于语义分割的开源数据集
的水体图像，由 <a href="http://ce.sc.edu/iwers/" rel="nofollow" _istranslated="1">iWERS</a> 集团在
南卡罗来纳大学土木与环境工程系正在使用 CVAT。</p>
<p dir="auto" _msttexthash="179089664" _msthash="465">有关使用 CVAT 开发语义分割数据集的信息，请参阅：</p>
<ul dir="auto">
<li><a href="https://www.sciencedirect.com/science/article/pii/S1364815222000391" rel="nofollow" _msttexthash="32087835" _msthash="466">ATLANTIS 发表的文章</a></li>
<li><a href="https://github.com/smhassanerfani/atlantis/tree/master/adk" _msttexthash="19073717" _msthash="467">ATLANTIS 开发套件</a></li>
<li _msttexthash="48549657" _msthash="468"><a href="https://www.youtube.com/playlist?list=PLIfLGY-zZChS5trt7Lc3MfNhab7OWl2BR" rel="nofollow" _istranslated="1">ATLANTIS 注释教程视频</a>。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="19471491" _msthash="469">CVAT 在线： <a href="https://cvat.ai" rel="nofollow" _istranslated="1">cvat.ai</a></h2><a id="user-content-cvat-online-cvatai" class="anchor" aria-label="永久链接：CVAT 在线：cvat.ai" href="#cvat-online-cvatai" _mstaria-label="708851" _msthash="470"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="126845602" _msthash="471">这是 CVAT 的在线版本。它免费、高效且易于使用。</p>
<p dir="auto" _msttexthash="741949663" _msthash="472"><a href="https://cvat.ai" rel="nofollow" _istranslated="1">cvat.ai</a> 运行该工具的最新版本。您可以创建
到 10 个任务，并上传最多 500Mb 的数据进行注释。它只会是
对您或您为其分配的人员可见。</p>
<p dir="auto" _msttexthash="399990760" _msthash="473">目前，它不具备管理和监控数据注释团队等<a href="https://docs.cvat.ai/docs/administration/advanced/analytics/" rel="nofollow" _istranslated="1">分析功能</a>。它也不允许导出图像，只允许导出注释。</p>
<p dir="auto" _msttexthash="149548126" _msthash="474">我们计划使用新的强大功能来增强 <a href="https://cvat.ai" rel="nofollow" _istranslated="1">cvat.ai</a>。敬请期待！</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="54825147" _msthash="475">预构建的 Docker 镜像 🐳</h2><a id="user-content-prebuilt-docker-images-" class="anchor" aria-label="永久链接：预构建的 Docker 镜像 🐳" href="#prebuilt-docker-images-" _mstaria-label="55336359" _msthash="476"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="284419564" _msthash="477">预构建的 docker 映像是在本地开始使用 CVAT 的最简单方法。它们在 Docker Hub 上可用：</p>
<ul dir="auto">
<li><a href="https://hub.docker.com/r/cvat/server" rel="nofollow" _msttexthash="11756420" _msthash="478">CVAT/服务器</a></li>
<li><a href="https://hub.docker.com/r/cvat/ui" rel="nofollow" _msttexthash="21990332" _msthash="479">CVAT/用户界面</a></li>
</ul>
<p dir="auto" _msttexthash="104307996" _msthash="480">到目前为止，这些图像已被下载超过 1M 次。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="30795986" _msthash="481">截屏视频 🎦</h2><a id="user-content-screencasts-" class="anchor" aria-label="永久链接：截屏视频 🎦" href="#screencasts-" _mstaria-label="42212820" _msthash="482"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="93740920" _msthash="483">以下是一些演示如何使用 CVAT 的截屏视频。</p>

<p dir="auto" _msttexthash="1190956520" _msthash="484"><a href="https://www.youtube.com/playlist?list=PL0to7Ng4PuuYQT4eXlHb_oIlq_RPeuasN" rel="nofollow" _istranslated="1">计算机视觉注释课程</a>：
我们介绍了我们的课程系列，旨在帮助您更快、更好地注释数据
使用 CVAT。本课程是关于 CVAT 部署和集成的，它包括
演示文稿，涵盖以下主题：</p>
<ul dir="auto">
<li _msttexthash="1254856083" _msthash="485"><strong _istranslated="1">加快数据注释过程：CVAT 和 Datumaro 简介</strong>。
CVAT 和 Datumaro 解决了哪些问题，以及它们如何加快您的模型
培训过程。您可以使用一些资源来了解有关如何使用它们的更多信息。</li>
<li _msttexthash="2797342587" _msthash="486"><strong _istranslated="1">部署和使用 CVAT</strong>。在 <a href="https://app.cvat.ai" rel="nofollow" _istranslated="1">app.cvat.ai</a> 在线使用该应用程序。
本地部署。使用 Docker Compose 的容器化本地部署（用于常规使用），
以及使用 Kubernetes 的本地集群部署（适用于企业用户）。A 2 分钟
界面导览，CVAT 内部结构的分解，并演示如何
使用 Docker Compose 部署 CVAT。</li>
</ul>
<p dir="auto" _msttexthash="815140469" _msthash="487"><a href="https://www.youtube.com/playlist?list=PL0to7Ng4Puua37NJVMIShl_pzqJTigFzg" rel="nofollow" _istranslated="1">产品导览</a>：在本课程中，我们将展示如何使用 CVAT，并帮助熟悉 CVAT 功能和界面。本课程不涵盖集成，专门针对 CVAT。它涵盖以下主题：</p>
<ul dir="auto">
<li _msttexthash="370464081" _msthash="488"><strong _istranslated="1">管道</strong>。在本视频中，我们将展示如何使用 <a href="https://app.cvat.ai" rel="nofollow" _istranslated="1">app.cvat.ai</a>：如何注册、上传数据、批注和下载数据。</li>
</ul>

<p dir="auto" _msttexthash="61065173" _msthash="489">有关反馈，请参阅 <a href="#contact-us" _istranslated="1">联系我们</a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="19122688" _msthash="490">应用程序接口</h2><a id="user-content-api" class="anchor" aria-label="永久链接： API" href="#api" _mstaria-label="197821" _msthash="491"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://docs.cvat.ai/docs/api_sdk/api/" rel="nofollow" _msttexthash="5144373" _msthash="492">文档</a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="13007306" _msthash="493">开发工具包</h2><a id="user-content-sdk" class="anchor" aria-label="永久链接：SDK" href="#sdk" _mstaria-label="199485" _msthash="494"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="5773755" _msthash="495">安装</font><code>pip install cvat-sdk</code></li>
<li><a href="https://pypi.org/project/cvat-sdk/" rel="nofollow" _msttexthash="12798006" _msthash="496">PyPI 包主页</a></li>
<li><a href="https://docs.cvat.ai/docs/api_sdk/sdk/" rel="nofollow" _msttexthash="5144373" _msthash="497">文档</a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="17596449" _msthash="498">命令行界面</h2><a id="user-content-cli" class="anchor" aria-label="永久链接：CLI" href="#cli" _mstaria-label="197327" _msthash="499"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="5773755" _msthash="500">安装</font><code>pip install cvat-cli</code></li>
<li><a href="https://pypi.org/project/cvat-cli/" rel="nofollow" _msttexthash="12798006" _msthash="501">PyPI 包主页</a></li>
<li><a href="https://docs.cvat.ai/docs/api_sdk/cli/" rel="nofollow" _msttexthash="5144373" _msthash="502">文档</a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="25779598" _msthash="503">支持的注释格式</h2><a id="user-content-supported-annotation-formats" class="anchor" aria-label="永久链接：支持的注释格式" href="#supported-annotation-formats" _mstaria-label="1228604" _msthash="504"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1012810955" _msthash="505">CVAT 支持多种注释格式。您可以选择格式
单击后 <strong _istranslated="1">Upload annotation</strong> 和 <strong _istranslated="1">Dump annotation</strong> 按钮。<a href="https://github.com/cvat-ai/datumaro" _istranslated="1">Datumaro</a> 数据集框架允许
使用其命令行工具和 Python 库进行其他数据集转换。</p>
<p dir="auto" _msttexthash="149422923" _msthash="506">有关支持的格式的更多信息，请参阅： <a href="https://docs.cvat.ai/docs/manual/advanced/formats/" rel="nofollow" _istranslated="1">注释格式</a>.</p>

<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th _msttexthash="12704146" _msthash="507">注释格式</th>
<th _msttexthash="5584657" _msthash="508">进口</th>
<th _msttexthash="4143126" _msthash="509">出口</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://docs.cvat.ai/docs/manual/advanced/xml_format/#annotation" rel="nofollow" _msttexthash="14507428" _msthash="510">用于图像的 CVAT</a></td>
<td _msttexthash="7674420" _msthash="511">✔️</td>
<td _msttexthash="7674420" _msthash="512">✔️</td>
</tr>
<tr>
<td><a href="https://docs.cvat.ai/docs/manual/advanced/xml_format/#interpolation" rel="nofollow" _msttexthash="10866622" _msthash="513">视频的 CVAT</a></td>
<td _msttexthash="7674420" _msthash="514">✔️</td>
<td _msttexthash="7674420" _msthash="515">✔️</td>
</tr>
<tr>
<td><a href="https://github.com/cvat-ai/datumaro" _msttexthash="13485407" _msthash="516">拿图马罗</a></td>
<td _msttexthash="7674420" _msthash="517">✔️</td>
<td _msttexthash="7674420" _msthash="518">✔️</td>
</tr>
<tr>
<td><a href="http://host.robots.ox.ac.uk/pascal/VOC/" rel="nofollow" _msttexthash="95589" _msthash="519">PASCAL VOC</a></td>
<td _msttexthash="7674420" _msthash="520">✔️</td>
<td _msttexthash="7674420" _msthash="521">✔️</td>
</tr>
<tr>
<td _msttexthash="39505349" _msthash="522"><a href="http://host.robots.ox.ac.uk/pascal/VOC/" rel="nofollow" _istranslated="1">来自 PASCAL VOC</a> 的分割掩码</td>
<td _msttexthash="7674420" _msthash="523">✔️</td>
<td _msttexthash="7674420" _msthash="524">✔️</td>
</tr>
<tr>
<td><a href="https://pjreddie.com/darknet/yolo/" rel="nofollow" _msttexthash="35477" _msthash="525">YOLO</a></td>
<td _msttexthash="7674420" _msthash="526">✔️</td>
<td _msttexthash="7674420" _msthash="527">✔️</td>
</tr>
<tr>
<td><a href="http://cocodataset.org/#format-data" rel="nofollow" _msttexthash="21096621" _msthash="528">MS COCO 目标检测</a></td>
<td _msttexthash="7674420" _msthash="529">✔️</td>
<td _msttexthash="7674420" _msthash="530">✔️</td>
</tr>
<tr>
<td><a href="http://cocodataset.org/#format-data" rel="nofollow" _msttexthash="27918254" _msthash="531">MS COCO 关键点检测</a></td>
<td _msttexthash="7674420" _msthash="532">✔️</td>
<td _msttexthash="7674420" _msthash="533">✔️</td>
</tr>
<tr>
<td><a href="https://motchallenge.net/" rel="nofollow" _msttexthash="5042297" _msthash="534">移动</a></td>
<td _msttexthash="7674420" _msthash="535">✔️</td>
<td _msttexthash="7674420" _msthash="536">✔️</td>
</tr>
<tr>
<td><a href="https://www.vision.rwth-aachen.de/page/mots" rel="nofollow" _msttexthash="71448" _msthash="537">MOTS PNG</a></td>
<td _msttexthash="7674420" _msthash="538">✔️</td>
<td _msttexthash="7674420" _msthash="539">✔️</td>
</tr>
<tr>
<td><a href="http://labelme.csail.mit.edu/Release3.0" rel="nofollow" _msttexthash="5730088" _msthash="540">标签 3.0</a></td>
<td _msttexthash="7674420" _msthash="541">✔️</td>
<td _msttexthash="7674420" _msthash="542">✔️</td>
</tr>
<tr>
<td><a href="http://www.image-net.org" rel="nofollow" _msttexthash="7991399" _msthash="543">图像网</a></td>
<td _msttexthash="7674420" _msthash="544">✔️</td>
<td _msttexthash="7674420" _msthash="545">✔️</td>
</tr>
<tr>
<td><a href="http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/" rel="nofollow" _msttexthash="17329299" _msthash="546">摄像头视频</a></td>
<td _msttexthash="7674420" _msthash="547">✔️</td>
<td _msttexthash="7674420" _msthash="548">✔️</td>
</tr>
<tr>
<td><a href="http://shuoyang1213.me/WIDERFACE/" rel="nofollow" _msttexthash="8258991" _msthash="549">WIDE 脸型</a></td>
<td _msttexthash="7674420" _msthash="550">✔️</td>
<td _msttexthash="7674420" _msthash="551">✔️</td>
</tr>
<tr>
<td><a href="https://github.com/ox-vgg/vgg_face2" _msttexthash="88101" _msthash="552">VGGFace2</a></td>
<td _msttexthash="7674420" _msthash="553">✔️</td>
<td _msttexthash="7674420" _msthash="554">✔️</td>
</tr>
<tr>
<td><a href="https://www.aitribune.com/dataset/2018051063" rel="nofollow" _msttexthash="4547309" _msthash="555">市场-1501</a></td>
<td _msttexthash="7674420" _msthash="556">✔️</td>
<td _msttexthash="7674420" _msthash="557">✔️</td>
</tr>
<tr>
<td><a href="https://rrc.cvc.uab.es/?ch=2" rel="nofollow" _msttexthash="87139" _msthash="558">ICDAR13/15</a></td>
<td _msttexthash="7674420" _msthash="559">✔️</td>
<td _msttexthash="7674420" _msthash="560">✔️</td>
</tr>
<tr>
<td><a href="https://storage.googleapis.com/openimages/web/index.html" rel="nofollow" _msttexthash="10135463" _msthash="561">打开图像 V6</a></td>
<td _msttexthash="7674420" _msthash="562">✔️</td>
<td _msttexthash="7674420" _msthash="563">✔️</td>
</tr>
<tr>
<td><a href="https://www.cityscapes-dataset.com/login/" rel="nofollow" _msttexthash="12201033" _msthash="564">城市景观</a></td>
<td _msttexthash="7674420" _msthash="565">✔️</td>
<td _msttexthash="7674420" _msthash="566">✔️</td>
</tr>
<tr>
<td><a href="http://www.cvlibs.net/datasets/kitti/" rel="nofollow" _msttexthash="45604" _msthash="567">KITTI</a></td>
<td _msttexthash="7674420" _msthash="568">✔️</td>
<td _msttexthash="7674420" _msthash="569">✔️</td>
</tr>
<tr>
<td><a href="https://www.cvlibs.net/datasets/kitti/raw_data.php" rel="nofollow" _msttexthash="10377315" _msthash="570">Kitti Raw 格式</a></td>
<td _msttexthash="7674420" _msthash="571">✔️</td>
<td _msttexthash="7674420" _msthash="572">✔️</td>
</tr>
<tr>
<td><a href="http://vis-www.cs.umass.edu/lfw/" rel="nofollow" _msttexthash="24375" _msthash="573">LFW</a></td>
<td _msttexthash="7674420" _msthash="574">✔️</td>
<td _msttexthash="7674420" _msthash="575">✔️</td>
</tr>
<tr>
<td><a href="https://docs.supervise.ly/data-organization/00_ann_format_navi" rel="nofollow" _msttexthash="19549530" _msthash="576">监督点云格式</a></td>
<td _msttexthash="7674420" _msthash="577">✔️</td>
<td _msttexthash="7674420" _msthash="578">✔️</td>
</tr>
<tr>
<td><a href="https://docs.ultralytics.com/datasets/detect/" rel="nofollow" _msttexthash="9685169" _msthash="579">YOLOv8 检测</a></td>
<td _msttexthash="7674420" _msthash="580">✔️</td>
<td _msttexthash="7674420" _msthash="581">✔️</td>
</tr>
<tr>
<td><a href="https://docs.ultralytics.com/datasets/obb/" rel="nofollow" _msttexthash="32290635" _msthash="582">面向 YOLOv8 的边界框</a></td>
<td _msttexthash="7674420" _msthash="583">✔️</td>
<td _msttexthash="7674420" _msthash="584">✔️</td>
</tr>
<tr>
<td><a href="https://docs.ultralytics.com/datasets/segment/" rel="nofollow" _msttexthash="8628035" _msthash="585">YOLOv8 分段</a></td>
<td _msttexthash="7674420" _msthash="586">✔️</td>
<td _msttexthash="7674420" _msthash="587">✔️</td>
</tr>
<tr>
<td><a href="https://docs.ultralytics.com/datasets/pose/" rel="nofollow" _msttexthash="7809984" _msthash="588">YOLOv8 姿势</a></td>
<td _msttexthash="7674420" _msthash="589">✔️</td>
<td _msttexthash="7674420" _msthash="590">✔️</td>
</tr>
<tr>
<td><a href="https://docs.ultralytics.com/datasets/classify/" rel="nofollow" _msttexthash="9409543" _msthash="591">YOLOv8 分类</a></td>
<td _msttexthash="7674420" _msthash="592">✔️</td>
<td _msttexthash="7674420" _msthash="593">✔️</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>

<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="83049772" _msthash="594">用于自动标记的深度学习无服务器函数</h2><a id="user-content-deep-learning-serverless-functions-for-automatic-labeling" class="anchor" aria-label="永久链接：用于自动标记的深度学习无服务器函数" href="#deep-learning-serverless-functions-for-automatic-labeling" _mstaria-label="3125720" _msthash="595"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="570427689" _msthash="596">CVAT 支持自动标记。它可以加快注释过程
高达 10 倍。以下是我们支持的算法列表，以及它们可以运行的平台：</p>

<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th _msttexthash="4389879" _msthash="597">名字</th>
<th _msttexthash="5230641" _msthash="598">类型</th>
<th _msttexthash="5190354" _msthash="599">框架</th>
<th _msttexthash="13886119" _msthash="600">中央处理器</th>
<th _msttexthash="14256658" _msthash="601">图形处理器</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/pytorch/facebookresearch/sam/nuclio" _msttexthash="286559" _msthash="602">Segment Anything</a></td>
<td _msttexthash="162331" _msthash="603">interactor</td>
<td _msttexthash="93444" _msthash="604">PyTorch</td>
<td _msttexthash="7674420" _msthash="605">✔️</td>
<td _msttexthash="7674420" _msthash="606">✔️</td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/openvino/dextr/nuclio" _msttexthash="251433" _msthash="607">Deep Extreme Cut</a></td>
<td _msttexthash="162331" _msthash="608">interactor</td>
<td _msttexthash="96200" _msthash="609">OpenVINO</td>
<td _msttexthash="7674420" _msthash="610">✔️</td>
<td></td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/openvino/omz/public/faster_rcnn_inception_resnet_v2_atrous_coco/nuclio" _msttexthash="134706" _msthash="611">Faster RCNN</a></td>
<td _msttexthash="118066" _msthash="612">detector</td>
<td _msttexthash="96200" _msthash="613">OpenVINO</td>
<td _msttexthash="7674420" _msthash="614">✔️</td>
<td></td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/openvino/omz/public/mask_rcnn_inception_resnet_v2_atrous_coco/nuclio" _msttexthash="94016" _msthash="615">Mask RCNN</a></td>
<td _msttexthash="118066" _msthash="616">detector</td>
<td _msttexthash="96200" _msthash="617">OpenVINO</td>
<td _msttexthash="7674420" _msthash="618">✔️</td>
<td></td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/openvino/omz/public/yolo-v3-tf/nuclio" _msttexthash="60307" _msthash="619">YOLO v3</a></td>
<td _msttexthash="118066" _msthash="620">detector</td>
<td _msttexthash="96200" _msthash="621">OpenVINO</td>
<td _msttexthash="7674420" _msthash="622">✔️</td>
<td></td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/onnx/WongKinYiu/yolov7/nuclio" _msttexthash="60931" _msthash="623">YOLO v7</a></td>
<td _msttexthash="118066" _msthash="624">detector</td>
<td _msttexthash="35867" _msthash="625">ONNX</td>
<td _msttexthash="7674420" _msthash="626">✔️</td>
<td _msttexthash="7674420" _msthash="627">✔️</td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/openvino/omz/intel/person-reidentification-retail-0277/nuclio" _msttexthash="528034" _msthash="628">Object reidentification</a></td>
<td _msttexthash="46163" _msthash="629">reid</td>
<td _msttexthash="96200" _msthash="630">OpenVINO</td>
<td _msttexthash="7674420" _msthash="631">✔️</td>
<td></td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/openvino/omz/intel/semantic-segmentation-adas-0001/nuclio" _msttexthash="21282313" _msthash="632">ADAS 的语义分割</a></td>
<td _msttexthash="7818902" _msthash="633">探测器</td>
<td _msttexthash="8631948" _msthash="634">OpenVINO 公司</td>
<td _msttexthash="7674420" _msthash="635">✔️</td>
<td></td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/openvino/omz/intel/text-detection-0004/nuclio" _msttexthash="11911757" _msthash="636">文本检测 v4</a></td>
<td _msttexthash="7818902" _msthash="637">探测器</td>
<td _msttexthash="8631948" _msthash="638">OpenVINO 公司</td>
<td _msttexthash="7674420" _msthash="639">✔️</td>
<td></td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/pytorch/foolwood/siammask/nuclio" _msttexthash="13028691" _msthash="640">暹罗面具</a></td>
<td _msttexthash="9678045" _msthash="641">跟踪器</td>
<td _msttexthash="8686002" _msthash="642">PyTorch 插件</td>
<td _msttexthash="7674420" _msthash="643">✔️</td>
<td _msttexthash="7674420" _msthash="644">✔️</td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/pytorch/dschoerk/transt/nuclio" _msttexthash="74698" _msthash="645">TransT</a></td>
<td _msttexthash="9678045" _msthash="646">跟踪器</td>
<td _msttexthash="8686002" _msthash="647">PyTorch 插件</td>
<td _msttexthash="7674420" _msthash="648">✔️</td>
<td _msttexthash="7674420" _msthash="649">✔️</td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/pytorch/saic-vul/fbrs/nuclio" _msttexthash="8586968" _msthash="650">f-BRS 系列</a></td>
<td _msttexthash="6511908" _msthash="651">交互器</td>
<td _msttexthash="8686002" _msthash="652">PyTorch 插件</td>
<td _msttexthash="7674420" _msthash="653">✔️</td>
<td></td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/pytorch/saic-vul/hrnet/nuclio" _msttexthash="53924" _msthash="654">HRNet</a></td>
<td _msttexthash="6511908" _msthash="655">交互器</td>
<td _msttexthash="8686002" _msthash="656">PyTorch 插件</td>
<td></td>
<td _msttexthash="7674420" _msthash="657">✔️</td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/pytorch/shiyinzhang/iog/nuclio" _msttexthash="23973495" _msthash="658">由内而外的指导</a></td>
<td _msttexthash="6511908" _msthash="659">交互器</td>
<td _msttexthash="8686002" _msthash="660">PyTorch 插件</td>
<td _msttexthash="7674420" _msthash="661">✔️</td>
<td></td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/tensorflow/faster_rcnn_inception_v2_coco/nuclio" _msttexthash="8547487" _msthash="662">更快的 RCNN</a></td>
<td _msttexthash="7818902" _msthash="663">探测器</td>
<td _msttexthash="157508" _msthash="664">TensorFlow</td>
<td _msttexthash="7674420" _msthash="665">✔️</td>
<td _msttexthash="7674420" _msthash="666">✔️</td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/tensorflow/matterport/mask_rcnn/nuclio" _msttexthash="5558293" _msthash="667">掩码 RCNN</a></td>
<td _msttexthash="7818902" _msthash="668">探测器</td>
<td _msttexthash="157508" _msthash="669">TensorFlow</td>
<td _msttexthash="7674420" _msthash="670">✔️</td>
<td _msttexthash="7674420" _msthash="671">✔️</td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/pytorch/facebookresearch/detectron2/retinanet_r101/nuclio" _msttexthash="130234" _msthash="672">RetinaNet</a></td>
<td _msttexthash="7818902" _msthash="673">探测器</td>
<td _msttexthash="8686002" _msthash="674">PyTorch 插件</td>
<td _msttexthash="7674420" _msthash="675">✔️</td>
<td _msttexthash="7674420" _msthash="676">✔️</td>
</tr>
<tr>
<td><a href="/cvat-ai/cvat/blob/develop/serverless/openvino/omz/intel/face-detection-0205/nuclio" _msttexthash="12049076" _msthash="677">人脸检测</a></td>
<td _msttexthash="7818902" _msthash="678">探测器</td>
<td _msttexthash="8631948" _msthash="679">OpenVINO 公司</td>
<td _msttexthash="7674420" _msthash="680">✔️</td>
<td></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>

<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="9675445" _msthash="681">许可证</h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license" _mstaria-label="331903" _msthash="682"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="48608378" _msthash="683">该代码在 <a href="https://opensource.org/licenses/MIT" rel="nofollow" _istranslated="1">MIT 许可证</a>下发布。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="2176927961" _msthash="684">目录中包含的代码在 <strong _mstmutation="1" _istranslated="1">MIT 许可证</strong>下发布。
但是，它可能会下载和使用各种资产，例如源代码、架构和权重等。
这些资源可以根据不同的许可证（包括非商业许可证）进行分发。
在使用资产之前，您有责任确保遵守这些许可证的条款。</font><code>/serverless</code></p>
<p dir="auto" _msttexthash="452270676" _msthash="685">该软件使用来自 <a href="https://www.ffmpeg.org" rel="nofollow" _istranslated="1">FFmpeg</a> 项目的 LGPL 许可库。
有关如何配置和编译 FFmpeg 的确切步骤，可以在 <a href="/cvat-ai/cvat/blob/develop/Dockerfile" _istranslated="1">Dockerfile</a> 中找到。</p>
<p dir="auto" _msttexthash="2143836552" _msthash="686">FFmpeg 是一个开源框架，根据 LGPL 和 GPL 获得许可。
请参阅 <a href="https://www.ffmpeg.org/legal.html" rel="nofollow" _istranslated="1">https://www.ffmpeg.org/legal.html</a>。您全权负责
用于确定您对 FFmpeg 的使用是否需要任何
其他许可证。CVAT.ai Corporation 不负责获取任何
此类许可，也不承担
与您使用 FFmpeg 的连接。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="11880817" _msthash="687">联系我们</h2><a id="user-content-contact-us" class="anchor" aria-label="永久链接： 联系我们" href="#contact-us" _mstaria-label="408174" _msthash="688"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="631343999" _msthash="689"><a href="https://gitter.im/opencv-cvat/public" rel="nofollow" _istranslated="1">Gitter</a> 询问与 CVAT 使用相关的问题。
通常，核心团队或社区会很快回答问题。您还可以在此处浏览其他常见问题。</p>
<p dir="auto" _msttexthash="201222099" _msthash="690"><a href="https://discord.gg/S6sRHhuQ7K" rel="nofollow" _istranslated="1">Discord</a> 也是提出问题或讨论与 CVAT 相关的任何其他事情的地方。</p>
<p dir="auto" _msttexthash="80861859" _msthash="691"><a href="https://www.linkedin.com/company/cvat-ai/" rel="nofollow" _istranslated="1">LinkedIn</a> 上的公司和工作相关问题。</p>
<p dir="auto" _msttexthash="102888591" _msthash="692"><a href="https://www.youtube.com/@cvat-ai" rel="nofollow" _istranslated="1">YouTube</a> 查看有关 CVAT 的截屏视频和教程。</p>
<p dir="auto" _msttexthash="320490222" _msthash="693">功能请求或 bug 报告的 <a href="https://github.com/cvat-ai/cvat/issues" _istranslated="1">GitHub 问题</a>。
如果它是一个错误，请添加步骤以重现它。</p>
<p dir="auto" _msttexthash="293572396" _msthash="694"><a href="https://stackoverflow.com/search?q=%23cvat" rel="nofollow" _istranslated="1">#cvat</a> StackOverflow 上的标签是另一种询问方式
问题并获得我们的支持。</p>
<p dir="auto" _msttexthash="112125546" _msthash="695"><a href="mailto:contact+github@cvat.ai" _istranslated="1">如果您需要</a>商业支持，contact@cvat.ai 与我们联系。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6123858" _msthash="696">链接</h2><a id="user-content-links" class="anchor" aria-label="永久链接： 链接" href="#links" _mstaria-label="274456" _msthash="697"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><a href="https://www.intel.ai/introducing-cvat" rel="nofollow" _msttexthash="225884282" _msthash="698">英特尔 AI 博客：新的计算机视觉工具加速数字图像和视频的注释</a></p>
</li>
<li>
<p dir="auto"><a href="https://software.intel.com/en-us/articles/computer-vision-annotation-tool-a-universal-approach-to-data-annotation" rel="nofollow" _msttexthash="199304807" _msthash="699">英特尔软件：计算机视觉注释工具：数据注释的通用方法</a></p>
</li>
<li>
<p dir="auto"><a href="https://venturebeat.com/2019/03/05/intel-open-sources-cvat-a-toolkit-for-data-labeling/" rel="nofollow" _msttexthash="200885932" _msthash="700">VentureBeat：Intel 开源 CVAT，一个用于数据标记的工具包</a></p>
</li>
<li>
<p dir="auto"><a href="https://blog.roboflow.com/cvat/" rel="nofollow" _msttexthash="60384103" _msthash="701">如何使用 CVAT（Roboflow 指南）</a></p>
</li>
<li>
<p dir="auto"><a href="https://blog.roboflow.com/how-to-use-roboflow-models-in-cvat/" rel="nofollow" _msttexthash="202046780" _msthash="702">如何使用 Roboflow Universe 上的 50,000+ 模型之一在 CVAT 中自动标记数据</a></p>

</li>
</ul>
</article></div>
