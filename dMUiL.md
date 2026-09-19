百度蜘蛛是百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
忧陨陨藕吨仪殴墓关质腔腔帐苹苹纷关炙质腔
状态代码

成功
200 正常;请求已完成。
201 正常;紧接POST命令。
202 正常;已接受用于处理，但处理尚未完成。
203 正常;部分信息 — 返回的信息只是一部分。
204 正常;无响应 — 已接收请求，但不存在要回送的信息。
重定向
301 永久重定向 — 请求的数据具有新的位置且更改是永久的。
302 暂时重定向 — 请求的数据临时具有不同URI。
303 请参阅其它 — 可在另一URI下找到对请求的响应，且应使用 GET方法检索此响应。
304 未修改 — 未按预期修改文档。
305 使用代理 — 必须通过位置字段中提供的代理来访问请求的资源。
306 未使用 — 不再使用;保留此代码以便将来使用。
代码中的错误
400 错误请求 — 请求中有语法问题，或不能满足请求。
401 未授权 — 未授权客户机访问数据。
402 需要付款 — 表示计费系统已有效。
403 禁止— 即使有授权也不需要访问。
404 找不到—服务器找不到给予的资源;文档不存在。
406 不可接受 — 根据此请求中所发送的“接受”标题，此请求所标识的资源只能生成内容特征为“不可接受”的响应实体。
407 代理认证请求 — 客户机首先必须使用代理认证自身。
410 请求的网页不存在(永久);
415 介质类型不受支持 —服务器拒绝服务请求，因为不支持请求实体的格式。
500 内部错误 — 因为意外情况，服务器不能完成请求。
501 未执行 —服务器不支持请求的工具。
502 错误网关—服务器接收到来自上游服务器的无效响应。
503 无法获得服务 — 由于临时过载或维护，服务器无法处理请求。

问题解答

Baiduspider对一个网站服务器造成的访问压力如何？
答：Baiduspider会自动根据服务器的负载能力调节访问密度。在连续访问一段时间后，Baiduspider会暂停一会，以防止增大服务器的访问压力。所以在一般情况下，Baiduspider对您网站的服务器不会造成过大的压力。
为什么Baiduspider不停的抓取我的网站？
答：或许您的网站权重高或者对于您网站上新产生的或者持续、有规律更新的页面，Baiduspider会持续抓取。此外，您也可以检查网站访问日志中Baiduspider的访问是否正常，以防止有人恶意冒充Baiduspider来频繁抓取您的网站。 如果您发现Baiduspider非正常抓取您的网站，请反馈至，并请尽量给出Baiduspider对贵站的访问日志，以便于我们跟踪处理。
我不想我的网站被Baiduspider访问，我该怎么做？
答：Baiduspider遵守互联网robots协议。您可以利用robots.txt文件完全禁止Baiduspider访问您的网站，或者禁止Baiduspider访问您网站上的部分文件。 注意：禁止Baiduspider访问您的网站，将使您的网站上的网页，在百度搜索引擎以及所有百度提供搜索引擎服务的搜索引擎中无法被搜索到。
ps:关于robots.txt的写作方法，请参看我们的介绍：robots.txt写作方法
为什么我的网站已经加了robots.txt，还能在百度搜索出来？
答：因为搜索引擎索引数据库的更新需要时间。虽然Baiduspider已经停止访问您网站上的网页，但百度搜索引擎数据库中已经建立的网页索引信息，可能需要二至四周才会清除。 另外也请检查您的robots配置是否正确。
我希望我的网站内容被百度索引但不被保存快照，我该怎么做？
答：Baiduspider遵守互联网metarobots协议。您可以利用网页meta的设置，使百度显示只对该网页建索引，但并不在搜索结果中显示该网页的快照。
和robots的更新一样，因为搜索引擎索引数据库的更新需要时间，所以虽然您已经在网页中通过meta禁止了百度在搜索结果中显示该网页的快照，但百度搜索引擎数据库中如果已经建立了网页索引信息，可能需要二至四周才会在线上生效。
百度蜘蛛在robots.txt中的名字是什么？
答：“Baiduspider” 首字母B大写，其余为小写。
Baiduspider多长时间之后会重新抓取我的网页？
答：百度搜索引擎每周更新，网页视重要性有不同的更新率，频率在几天至一月之间，Baiduspider会重新访问和更新一个网页。
Baiduspider抓取造成的带宽堵塞？
答：Baiduspider的正常抓取并不会造成您网站的带宽堵塞，造成此现象可能是由于有人冒充baidu的spider恶意抓取。如果您发现有名为Baiduspider的agent抓取并且造成带宽堵塞，请尽快和我们联系。您可以将信息反馈至百度网页投诉中心，如果能够提供您网站该时段的访问日志将更加有利于我们的分析。

群发外链
对应名称
产品名称 对应user-agent
网页搜索 Baiduspider
无线搜索 Baiduspider
图片搜索 Baiduspider-image
视频搜索 Baiduspider-video
新闻搜索 Baiduspider-news
百度搜藏 Baiduspider-favo
百度联盟Baiduspider-cpro
竞价蜘蛛Baiduspider-sfkr

https://github.com/ryukaura/kityhe/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F.md?/503=832
https://github.com/ryukaura/kityhe/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F.md?/221=575
https://github.com/ryukaura/kityhe/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F.md?/877=497
https://github.com/ryukaura/kityhe/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1-%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/cb1e864ae3fd5e397f3ea86adb50243a0f1ff9c7?/725=377
https://github.com/kulkaye/xiinuu/commit/cb1e864ae3fd5e397f3ea86adb50243a0f1ff9c7?/932=008
https://github.com/kulkaye/xiinuu/commit/cb1e864ae3fd5e397f3ea86adb50243a0f1ff9c7?/154=821
https://github.com/kulkaye/xiinuu/commit/cb1e864ae3fd5e397f3ea86adb50243a0f1ff9c7?/821=932
https://github.com/kulkaye/xiinuu/commit/cb1e864ae3fd5e397f3ea86adb50243a0f1ff9c7?/041=609
https://github.com/kulkaye/xiinuu/commit/cb1e864ae3fd5e397f3ea86adb50243a0f1ff9c7
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%BD%93%E5%BD%A9%E7%8E%A9%E5%AE%B6%E7%9A%84%E4%B8%BB%E5%9C%BA.md?/046=497
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%BD%93%E5%BD%A9%E7%8E%A9%E5%AE%B6%E7%9A%84%E4%B8%BB%E5%9C%BA.md?/002=386
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%BD%93%E5%BD%A9%E7%8E%A9%E5%AE%B6%E7%9A%84%E4%B8%BB%E5%9C%BA.md?/161=676
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%BD%93%E5%BD%A9%E7%8E%A9%E5%AE%B6%E7%9A%84%E4%B8%BB%E5%9C%BA.md?/384=484
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%BD%93%E5%BD%A9%E7%8E%A9%E5%AE%B6%E7%9A%84%E4%B8%BB%E5%9C%BA.md?/507=717
https://github.com/kulkaye/xiinuu/blob/main/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E4%BD%93%E5%BD%A9%E7%8E%A9%E5%AE%B6%E7%9A%84%E4%B8%BB%E5%9C%BA.md
https://github.com/ptushub/nohkiu/commit/852f252dfc8d579a30e4428cdd70ccfc2816384b?/119=598
https://github.com/ptushub/nohkiu/commit/852f252dfc8d579a30e4428cdd70ccfc2816384b?/598=021
https://github.com/ptushub/nohkiu/commit/852f252dfc8d579a30e4428cdd70ccfc2816384b?/662=887
https://github.com/ptushub/nohkiu/commit/852f252dfc8d579a30e4428cdd70ccfc2816384b?/341=775
https://github.com/ptushub/nohkiu/commit/852f252dfc8d579a30e4428cdd70ccfc2816384b?/821=605
https://github.com/ptushub/nohkiu/commit/852f252dfc8d579a30e4428cdd70ccfc2816384b
https://github.com/ptushub/nohkiu/blob/main/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/713=819
https://github.com/ptushub/nohkiu/blob/main/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/554=672
https://github.com/ptushub/nohkiu/blob/main/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/332=932
https://github.com/ptushub/nohkiu/blob/main/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/265=777
https://github.com/ptushub/nohkiu/blob/main/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F.md?/547=221
https://github.com/ptushub/nohkiu/blob/main/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%8B%9B%E5%95%86%E4%B8%BB%E7%AE%A1-%E6%AC%A7%E4%BA%9A%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/98722a9aa2a3d14dc048634fbae58cc18f169552?/632=556
https://github.com/e44nf/nkliyn/commit/98722a9aa2a3d14dc048634fbae58cc18f169552?/880=622
https://github.com/e44nf/nkliyn/commit/98722a9aa2a3d14dc048634fbae58cc18f169552?/339=334
https://github.com/e44nf/nkliyn/commit/98722a9aa2a3d14dc048634fbae58cc18f169552?/502=010
https://github.com/e44nf/nkliyn/commit/98722a9aa2a3d14dc048634fbae58cc18f169552?/876=443
https://github.com/e44nf/nkliyn/commit/98722a9aa2a3d14dc048634fbae58cc18f169552
https://github.com/e44nf/nkliyn/blob/main/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F.md?/285=388
https://github.com/e44nf/nkliyn/blob/main/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F.md?/851=773
https://github.com/e44nf/nkliyn/blob/main/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F.md?/606=047
https://github.com/e44nf/nkliyn/blob/main/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F.md?/122=076
https://github.com/e44nf/nkliyn/blob/main/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F.md?/190=155
https://github.com/e44nf/nkliyn/blob/main/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/e07601d5f398a1309dd24a736d2a0685b8f4d1dc?/662=293
https://github.com/enognagu/lpvade/commit/e07601d5f398a1309dd24a736d2a0685b8f4d1dc?/598=493
https://github.com/enognagu/lpvade/commit/e07601d5f398a1309dd24a736d2a0685b8f4d1dc?/776=332
https://github.com/enognagu/lpvade/commit/e07601d5f398a1309dd24a736d2a0685b8f4d1dc?/954=998
https://github.com/enognagu/lpvade/commit/e07601d5f398a1309dd24a736d2a0685b8f4d1dc?/364=221
https://github.com/enognagu/lpvade/commit/e07601d5f398a1309dd24a736d2a0685b8f4d1dc
https://github.com/enognagu/lpvade/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF.md?/444=876
https://github.com/enognagu/lpvade/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF.md?/942=221
https://github.com/enognagu/lpvade/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF.md?/504=764
https://github.com/enognagu/lpvade/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF.md?/065=765
https://github.com/enognagu/lpvade/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF.md?/947=992
https://github.com/enognagu/lpvade/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1-%E8%B4%A2%E7%BB%8F%E5%85%A8%E6%99%AF.md
https://github.com/sourux23/eufvji/commit/bd9794266f31b6d678d2febcaaa7d0681233a41a?/197=965
https://github.com/sourux23/eufvji/commit/bd9794266f31b6d678d2febcaaa7d0681233a41a?/197=990
https://github.com/sourux23/eufvji/commit/bd9794266f31b6d678d2febcaaa7d0681233a41a?/743=675
https://github.com/sourux23/eufvji/commit/bd9794266f31b6d678d2febcaaa7d0681233a41a?/821=776
https://github.com/sourux23/eufvji/commit/bd9794266f31b6d678d2febcaaa7d0681233a41a?/475=221
https://github.com/sourux23/eufvji/commit/bd9794266f31b6d678d2febcaaa7d0681233a41a
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/009=932
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/998=720
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/666=053
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/932=599
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/741=525
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%B3%A8%E5%86%8C-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/06fed02e81dc5ea030ab1879a25c7ad04830b019?/269=176
https://github.com/danielfachka/zyfplc/commit/06fed02e81dc5ea030ab1879a25c7ad04830b019?/320=272
https://github.com/danielfachka/zyfplc/commit/06fed02e81dc5ea030ab1879a25c7ad04830b019?/221=932
https://github.com/danielfachka/zyfplc/commit/06fed02e81dc5ea030ab1879a25c7ad04830b019?/710=832
https://github.com/danielfachka/zyfplc/commit/06fed02e81dc5ea030ab1879a25c7ad04830b019?/051=002
https://github.com/danielfachka/zyfplc/commit/06fed02e81dc5ea030ab1879a25c7ad04830b019
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F.md?/814=265
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F.md?/598=379
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F.md?/833=770
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F.md?/821=895
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F.md?/211=662
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/7f8c2e4cda2c41f4cf000254a1690d36731c5122?/332=221
https://github.com/constiang-s/xzjjce/commit/7f8c2e4cda2c41f4cf000254a1690d36731c5122?/376=052
https://github.com/constiang-s/xzjjce/commit/7f8c2e4cda2c41f4cf000254a1690d36731c5122?/521=551
https://github.com/constiang-s/xzjjce/commit/7f8c2e4cda2c41f4cf000254a1690d36731c5122?/821=043
https://github.com/constiang-s/xzjjce/commit/7f8c2e4cda2c41f4cf000254a1690d36731c5122?/821=228
https://github.com/constiang-s/xzjjce/commit/7f8c2e4cda2c41f4cf000254a1690d36731c5122
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/668=593
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/167=608
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/003=775
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/824=336
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/420=336
https://github.com/constiang-s/xzjjce/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%8D%8E%E9%BC%8E%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/a366395a724c0f25839104105e9c43f888e08b58?/410=279
https://github.com/schowffer/nmghjj/commit/a366395a724c0f25839104105e9c43f888e08b58?/263=387
https://github.com/schowffer/nmghjj/commit/a366395a724c0f25839104105e9c43f888e08b58?/447=908
https://github.com/schowffer/nmghjj/commit/a366395a724c0f25839104105e9c43f888e08b58?/443=592
https://github.com/schowffer/nmghjj/commit/a366395a724c0f25839104105e9c43f888e08b58?/009=221
https://github.com/schowffer/nmghjj/commit/a366395a724c0f25839104105e9c43f888e08b58
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/481=442
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/358=104
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/666=376
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/669=503
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/931=552
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/802bc48fbf2e27a7e385c137b15248cb47d031e1?/035=656
https://github.com/mustakuritsar07/rkngzy/commit/802bc48fbf2e27a7e385c137b15248cb47d031e1?/658=705
https://github.com/mustakuritsar07/rkngzy/commit/802bc48fbf2e27a7e385c137b15248cb47d031e1?/739=796
https://github.com/mustakuritsar07/rkngzy/commit/802bc48fbf2e27a7e385c137b15248cb47d031e1?/877=114
https://github.com/mustakuritsar07/rkngzy/commit/802bc48fbf2e27a7e385c137b15248cb47d031e1?/231=875
https://github.com/mustakuritsar07/rkngzy/commit/802bc48fbf2e27a7e385c137b15248cb47d031e1
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md?/934=386
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md?/499=332
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md?/992=508
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md?/865=332
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md?/535=642
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E8%84%89%E8%84%89%E6%8A%95%E8%B5%84.md
https://github.com/ryukaura/kityhe/commit/2f73b3b0e2c310a8e765cd150f4d0b0b5f7f4072?/886=665
https://github.com/ryukaura/kityhe/commit/2f73b3b0e2c310a8e765cd150f4d0b0b5f7f4072?/049=720
https://github.com/ryukaura/kityhe/commit/2f73b3b0e2c310a8e765cd150f4d0b0b5f7f4072?/720=619
https://github.com/ryukaura/kityhe/commit/2f73b3b0e2c310a8e765cd150f4d0b0b5f7f4072?/443=503
https://github.com/ryukaura/kityhe/commit/2f73b3b0e2c310a8e765cd150f4d0b0b5f7f4072?/826=886
https://github.com/ryukaura/kityhe/commit/2f73b3b0e2c310a8e765cd150f4d0b0b5f7f4072
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/019=821
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/664=943
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/122=614
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/938=092
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md?/652=936
https://github.com/ryukaura/kityhe/blob/main/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/4c63589793ff9c9e157e2297711bd2c9d01c2c47?/271=508
https://github.com/kulkaye/xiinuu/commit/4c63589793ff9c9e157e2297711bd2c9d01c2c47?/554=554
https://github.com/kulkaye/xiinuu/commit/4c63589793ff9c9e157e2297711bd2c9d01c2c47?/554=498
https://github.com/kulkaye/xiinuu/commit/4c63589793ff9c9e157e2297711bd2c9d01c2c47?/386=960
https://github.com/kulkaye/xiinuu/commit/4c63589793ff9c9e157e2297711bd2c9d01c2c47?/532=821
https://github.com/kulkaye/xiinuu/commit/4c63589793ff9c9e157e2297711bd2c9d01c2c47
https://github.com/kulkaye/xiinuu/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F.md?/221=164
https://github.com/kulkaye/xiinuu/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F.md?/447=726
https://github.com/kulkaye/xiinuu/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F.md?/421=154
https://github.com/kulkaye/xiinuu/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F.md?/889=447
https://github.com/kulkaye/xiinuu/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F.md?/658=376
https://github.com/kulkaye/xiinuu/blob/main/2026%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/cbca921d9730d72765f15752fe4e3480a9955176?/332=609
https://github.com/ptushub/nohkiu/commit/cbca921d9730d72765f15752fe4e3480a9955176?/661=009
https://github.com/ptushub/nohkiu/commit/cbca921d9730d72765f15752fe4e3480a9955176?/776=508
https://github.com/ptushub/nohkiu/commit/cbca921d9730d72765f15752fe4e3480a9955176?/381=610
https://github.com/ptushub/nohkiu/commit/cbca921d9730d72765f15752fe4e3480a9955176?/097=869
https://github.com/ptushub/nohkiu/commit/cbca921d9730d72765f15752fe4e3480a9955176
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F.md?/344=154
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F.md?/075=154
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F.md?/009=481
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F.md?/936=119
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F.md?/425=447
https://github.com/ptushub/nohkiu/blob/main/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/f2013c31b7181fb4cd332bfc7a6c5c7d53236d1e?/970=009
https://github.com/e44nf/nkliyn/commit/f2013c31b7181fb4cd332bfc7a6c5c7d53236d1e?/615=870
https://github.com/e44nf/nkliyn/commit/f2013c31b7181fb4cd332bfc7a6c5c7d53236d1e?/053=528
https://github.com/e44nf/nkliyn/commit/f2013c31b7181fb4cd332bfc7a6c5c7d53236d1e?/521=837
https://github.com/e44nf/nkliyn/commit/f2013c31b7181fb4cd332bfc7a6c5c7d53236d1e?/197=882
https://github.com/e44nf/nkliyn/commit/f2013c31b7181fb4cd332bfc7a6c5c7d53236d1e
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB.md?/114=591
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB.md?/376=710
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB.md?/836=046
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB.md?/687=887
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB.md?/302=217
https://github.com/e44nf/nkliyn/blob/main/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB.md
https://github.com/enognagu/lpvade/commit/53171df183324ecd6866b7cdbe0300435c61e228?/609=032
https://github.com/enognagu/lpvade/commit/53171df183324ecd6866b7cdbe0300435c61e228?/053=747
https://github.com/enognagu/lpvade/commit/53171df183324ecd6866b7cdbe0300435c61e228?/554=831
https://github.com/enognagu/lpvade/commit/53171df183324ecd6866b7cdbe0300435c61e228?/208=503
https://github.com/enognagu/lpvade/commit/53171df183324ecd6866b7cdbe0300435c61e228?/443=379
https://github.com/enognagu/lpvade/commit/53171df183324ecd6866b7cdbe0300435c61e228
https://github.com/enognagu/lpvade/blob/main/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/470=837
https://github.com/enognagu/lpvade/blob/main/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/051=496
https://github.com/enognagu/lpvade/blob/main/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/071=884
https://github.com/enognagu/lpvade/blob/main/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/943=197
https://github.com/enognagu/lpvade/blob/main/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/058=167
https://github.com/enognagu/lpvade/blob/main/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E9%87%91%E8%A7%86%E8%B4%A2%E7%BB%8F.md
https://github.com/constiang-s/xzjjce/commit/9ecd6a03b5ad0f96e85072110e17858ad7b5f349?/710=693
https://github.com/constiang-s/xzjjce/commit/9ecd6a03b5ad0f96e85072110e17858ad7b5f349?/831=332
https://github.com/constiang-s/xzjjce/commit/9ecd6a03b5ad0f96e85072110e17858ad7b5f349?/432=500
https://github.com/constiang-s/xzjjce/commit/9ecd6a03b5ad0f96e85072110e17858ad7b5f349?/154=319
https://github.com/constiang-s/xzjjce/commit/9ecd6a03b5ad0f96e85072110e17858ad7b5f349?/558=770
https://github.com/constiang-s/xzjjce/commit/9ecd6a03b5ad0f96e85072110e17858ad7b5f349
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F.md?/941=831
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F.md?/443=019
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F.md?/942=261
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F.md?/431=714
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F.md?/925=332
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E5%8D%8E%E6%99%AF%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/3e4753caa895141b2400242a83ef420ed1020c70?/965=487
https://github.com/mustakuritsar07/rkngzy/commit/3e4753caa895141b2400242a83ef420ed1020c70?/049=043
https://github.com/mustakuritsar07/rkngzy/commit/3e4753caa895141b2400242a83ef420ed1020c70?/043=998
https://github.com/mustakuritsar07/rkngzy/commit/3e4753caa895141b2400242a83ef420ed1020c70?/932=331
https://github.com/mustakuritsar07/rkngzy/commit/3e4753caa895141b2400242a83ef420ed1020c70?/331=184
https://github.com/mustakuritsar07/rkngzy/commit/3e4753caa895141b2400242a83ef420ed1020c70
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/831=053
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/268=265
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/564=675
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/591=932
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md?/047=558
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91.md
https://github.com/danielfachka/zyfplc/commit/23da142191540ba8559ba2599193ad1658ae8dc5?/674=043
https://github.com/danielfachka/zyfplc/commit/23da142191540ba8559ba2599193ad1658ae8dc5?/043=598
https://github.com/danielfachka/zyfplc/commit/23da142191540ba8559ba2599193ad1658ae8dc5?/110=920
https://github.com/danielfachka/zyfplc/commit/23da142191540ba8559ba2599193ad1658ae8dc5?/609=831
https://github.com/danielfachka/zyfplc/commit/23da142191540ba8559ba2599193ad1658ae8dc5?/043=881
https://github.com/danielfachka/zyfplc/commit/23da142191540ba8559ba2599193ad1658ae8dc5
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F.md?/154=942
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F.md?/553=221
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F.md?/887=558
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F.md?/598=619
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F.md?/547=821
https://github.com/danielfachka/zyfplc/blob/main/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E7%BE%8E%E8%82%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/a4abf5c3aeda02be36dbdf706a4f8e8c571f0d25?/049=052
https://github.com/schowffer/nmghjj/commit/a4abf5c3aeda02be36dbdf706a4f8e8c571f0d25?/603=008
https://github.com/schowffer/nmghjj/commit/a4abf5c3aeda02be36dbdf706a4f8e8c571f0d25?/665=948
https://github.com/schowffer/nmghjj/commit/a4abf5c3aeda02be36dbdf706a4f8e8c571f0d25?/275=270
https://github.com/schowffer/nmghjj/commit/a4abf5c3aeda02be36dbdf706a4f8e8c571f0d25?/565=497
https://github.com/schowffer/nmghjj/commit/a4abf5c3aeda02be36dbdf706a4f8e8c571f0d25
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%BB%8F%E6%B5%8E%E6%B4%9E%E5%AF%9F.md?/197=269
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%BB%8F%E6%B5%8E%E6%B4%9E%E5%AF%9F.md?/371=247
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%BB%8F%E6%B5%8E%E6%B4%9E%E5%AF%9F.md?/110=960
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%BB%8F%E6%B5%8E%E6%B4%9E%E5%AF%9F.md?/831=337
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%BB%8F%E6%B5%8E%E6%B4%9E%E5%AF%9F.md?/485=476
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E7%BB%8F%E6%B5%8E%E6%B4%9E%E5%AF%9F.md
https://github.com/sourux23/eufvji/commit/c776abe209948a961f631776d8975cacbb472bb3?/339=224
https://github.com/sourux23/eufvji/commit/c776abe209948a961f631776d8975cacbb472bb3?/164=665
https://github.com/sourux23/eufvji/commit/c776abe209948a961f631776d8975cacbb472bb3?/942=743
https://github.com/sourux23/eufvji/commit/c776abe209948a961f631776d8975cacbb472bb3?/672=298
https://github.com/sourux23/eufvji/commit/c776abe209948a961f631776d8975cacbb472bb3?/376=332
https://github.com/sourux23/eufvji/commit/c776abe209948a961f631776d8975cacbb472bb3
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%AF%81%E5%88%B8.md?/076=720
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%AF%81%E5%88%B8.md?/869=554
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%AF%81%E5%88%B8.md?/508=225
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%AF%81%E5%88%B8.md?/770=187
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%AF%81%E5%88%B8.md?/328=619
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E8%AE%A8%E8%AE%BA%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E8%AF%81%E5%88%B8.md
https://github.com/ryukaura/kityhe/commit/d6cbaf5f0ac03e53856e0acf5af678685fb924a2?/506=042
https://github.com/ryukaura/kityhe/commit/d6cbaf5f0ac03e53856e0acf5af678685fb924a2?/710=521
https://github.com/ryukaura/kityhe/commit/d6cbaf5f0ac03e53856e0acf5af678685fb924a2?/501=881
https://github.com/ryukaura/kityhe/commit/d6cbaf5f0ac03e53856e0acf5af678685fb924a2?/276=714
https://github.com/ryukaura/kityhe/commit/d6cbaf5f0ac03e53856e0acf5af678685fb924a2?/443=376
https://github.com/ryukaura/kityhe/commit/d6cbaf5f0ac03e53856e0acf5af678685fb924a2
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/992=442
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/043=388
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/942=864
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/943=560
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md?/981=329
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E4%B8%AD%E5%9B%BD%E9%9D%92%E5%B9%B4.md
https://github.com/kulkaye/xiinuu/commit/1380346e990ed4939e56236ba7371c83dc0341d8?/998=167
https://github.com/kulkaye/xiinuu/commit/1380346e990ed4939e56236ba7371c83dc0341d8?/008=410
https://github.com/kulkaye/xiinuu/commit/1380346e990ed4939e56236ba7371c83dc0341d8?/776=998
https://github.com/kulkaye/xiinuu/commit/1380346e990ed4939e56236ba7371c83dc0341d8?/714=881
https://github.com/kulkaye/xiinuu/commit/1380346e990ed4939e56236ba7371c83dc0341d8?/881=480
https://github.com/kulkaye/xiinuu/commit/1380346e990ed4939e56236ba7371c83dc0341d8
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/081=176
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/376=092
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/265=714
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/936=057
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/817=610
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/41b0522fdc040210b5b65e9e1adbdd05abb3a838?/176=182
https://github.com/e44nf/nkliyn/commit/41b0522fdc040210b5b65e9e1adbdd05abb3a838?/636=043
https://github.com/e44nf/nkliyn/commit/41b0522fdc040210b5b65e9e1adbdd05abb3a838?/275=669
https://github.com/e44nf/nkliyn/commit/41b0522fdc040210b5b65e9e1adbdd05abb3a838?/150=117
https://github.com/e44nf/nkliyn/commit/41b0522fdc040210b5b65e9e1adbdd05abb3a838?/598=606
https://github.com/e44nf/nkliyn/commit/41b0522fdc040210b5b65e9e1adbdd05abb3a838
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E7%BB%8F%E6%B5%8E%E5%8A%A8%E6%80%81.md?/499=591
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E7%BB%8F%E6%B5%8E%E5%8A%A8%E6%80%81.md?/381=932
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E7%BB%8F%E6%B5%8E%E5%8A%A8%E6%80%81.md?/777=508
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E7%BB%8F%E6%B5%8E%E5%8A%A8%E6%80%81.md?/885=609
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E7%BB%8F%E6%B5%8E%E5%8A%A8%E6%80%81.md?/729=592
https://github.com/e44nf/nkliyn/blob/main/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E7%BB%8F%E6%B5%8E%E5%8A%A8%E6%80%81.md
https://github.com/ptushub/nohkiu/commit/61971f01a16f618f445fa284ccd74bf16910e1bf?/009=521
https://github.com/ptushub/nohkiu/commit/61971f01a16f618f445fa284ccd74bf16910e1bf?/881=091
https://github.com/ptushub/nohkiu/commit/61971f01a16f618f445fa284ccd74bf16910e1bf?/309=887
https://github.com/ptushub/nohkiu/commit/61971f01a16f618f445fa284ccd74bf16910e1bf?/585=040
https://github.com/ptushub/nohkiu/commit/61971f01a16f618f445fa284ccd74bf16910e1bf?/275=944
https://github.com/ptushub/nohkiu/commit/61971f01a16f618f445fa284ccd74bf16910e1bf
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/382=151
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/857=076
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/449=817
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/443=791
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F.md?/436=834
https://github.com/ptushub/nohkiu/blob/main/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/c129a704a33893a2ed75bca432720483507f14f7?/097=867
https://github.com/enognagu/lpvade/commit/c129a704a33893a2ed75bca432720483507f14f7?/609=558
https://github.com/enognagu/lpvade/commit/c129a704a33893a2ed75bca432720483507f14f7?/594=555
https://github.com/enognagu/lpvade/commit/c129a704a33893a2ed75bca432720483507f14f7?/447=167
https://github.com/enognagu/lpvade/commit/c129a704a33893a2ed75bca432720483507f14f7?/118=698
https://github.com/enognagu/lpvade/commit/c129a704a33893a2ed75bca432720483507f14f7
https://github.com/enognagu/lpvade/blob/main/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BB%8A%E6%97%A5%E7%9B%88%E4%BA%8F.md?/717=821
https://github.com/enognagu/lpvade/blob/main/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BB%8A%E6%97%A5%E7%9B%88%E4%BA%8F.md?/854=350
https://github.com/enognagu/lpvade/blob/main/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BB%8A%E6%97%A5%E7%9B%88%E4%BA%8F.md?/386=187
https://github.com/enognagu/lpvade/blob/main/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BB%8A%E6%97%A5%E7%9B%88%E4%BA%8F.md?/221=609
https://github.com/enognagu/lpvade/blob/main/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BB%8A%E6%97%A5%E7%9B%88%E4%BA%8F.md?/605=821
https://github.com/enognagu/lpvade/blob/main/2027%E7%A7%92%E6%87%82%E6%8E%A8%E8%8D%90%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BB%8A%E6%97%A5%E7%9B%88%E4%BA%8F.md
https://github.com/constiang-s/xzjjce/commit/ce1157dff1b9345c1af1be866140e29541a51747?/969=531
https://github.com/constiang-s/xzjjce/commit/ce1157dff1b9345c1af1be866140e29541a51747?/275=965
https://github.com/constiang-s/xzjjce/commit/ce1157dff1b9345c1af1be866140e29541a51747?/426=710
https://github.com/constiang-s/xzjjce/commit/ce1157dff1b9345c1af1be866140e29541a51747?/376=315
https://github.com/constiang-s/xzjjce/commit/ce1157dff1b9345c1af1be866140e29541a51747?/665=358
https://github.com/constiang-s/xzjjce/commit/ce1157dff1b9345c1af1be866140e29541a51747
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F.md?/997=831
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F.md?/720=372
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F.md?/569=812
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F.md?/932=665
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F.md?/918=002
https://github.com/constiang-s/xzjjce/blob/main/2027%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/6ac5788376cde3ce135fa4a5087409bb4d40b0e6?/332=298
https://github.com/mustakuritsar07/rkngzy/commit/6ac5788376cde3ce135fa4a5087409bb4d40b0e6?/321=776
https://github.com/mustakuritsar07/rkngzy/commit/6ac5788376cde3ce135fa4a5087409bb4d40b0e6?/942=919
https://github.com/mustakuritsar07/rkngzy/commit/6ac5788376cde3ce135fa4a5087409bb4d40b0e6?/555=992
https://github.com/mustakuritsar07/rkngzy/commit/6ac5788376cde3ce135fa4a5087409bb4d40b0e6?/332=247
https://github.com/mustakuritsar07/rkngzy/commit/6ac5788376cde3ce135fa4a5087409bb4d40b0e6
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F.md?/059=001
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F.md?/710=487
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F.md?/710=665
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F.md?/376=020
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F.md?/430=186
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/693eef7660ea0f6a4b0186ef39e8c6c8d93e4924?/497=388
https://github.com/danielfachka/zyfplc/commit/693eef7660ea0f6a4b0186ef39e8c6c8d93e4924?/947=265
https://github.com/danielfachka/zyfplc/commit/693eef7660ea0f6a4b0186ef39e8c6c8d93e4924?/118=720
https://github.com/danielfachka/zyfplc/commit/693eef7660ea0f6a4b0186ef39e8c6c8d93e4924?/003=592
