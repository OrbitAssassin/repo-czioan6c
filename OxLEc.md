百度蜘蛛是百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
陨关附冉燃山冉官官话急及奖急赝示死俺来姥
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

https://github.com/enognagu/lpvade/blob/main/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97%3AJDB%E7%94%B5%E5%AD%90%E5%90%A7-%E7%BB%8F%E6%B5%8E%E8%AF%84%E8%AE%BA.md?/547=275
https://github.com/enognagu/lpvade/blob/main/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97%3AJDB%E7%94%B5%E5%AD%90%E5%90%A7-%E7%BB%8F%E6%B5%8E%E8%AF%84%E8%AE%BA.md?/552=265
https://github.com/enognagu/lpvade/blob/main/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97%3AJDB%E7%94%B5%E5%AD%90%E5%90%A7-%E7%BB%8F%E6%B5%8E%E8%AF%84%E8%AE%BA.md?/710=386
https://github.com/enognagu/lpvade/blob/main/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97%3AJDB%E7%94%B5%E5%AD%90%E5%90%A7-%E7%BB%8F%E6%B5%8E%E8%AF%84%E8%AE%BA.md?/267=619
https://github.com/enognagu/lpvade/blob/main/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97%3AJDB%E7%94%B5%E5%AD%90%E5%90%A7-%E7%BB%8F%E6%B5%8E%E8%AF%84%E8%AE%BA.md?/152=112
https://github.com/enognagu/lpvade/blob/main/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97%3AJDB%E7%94%B5%E5%AD%90%E5%90%A7-%E7%BB%8F%E6%B5%8E%E8%AF%84%E8%AE%BA.md
https://github.com/ptushub/nohkiu/commit/fd023614036eb1774f64866dac760f2503daec3a?/487=776
https://github.com/ptushub/nohkiu/commit/fd023614036eb1774f64866dac760f2503daec3a?/864=225
https://github.com/ptushub/nohkiu/commit/fd023614036eb1774f64866dac760f2503daec3a?/664=554
https://github.com/ptushub/nohkiu/commit/fd023614036eb1774f64866dac760f2503daec3a?/497=154
https://github.com/ptushub/nohkiu/commit/fd023614036eb1774f64866dac760f2503daec3a?/742=619
https://github.com/ptushub/nohkiu/commit/fd023614036eb1774f64866dac760f2503daec3a
https://github.com/ptushub/nohkiu/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91%3Ajdb%E7%94%B5%E5%AD%90%E7%89%88%E6%98%AF%E4%BB%80%E4%B9%88-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/991=664
https://github.com/ptushub/nohkiu/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91%3Ajdb%E7%94%B5%E5%AD%90%E7%89%88%E6%98%AF%E4%BB%80%E4%B9%88-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/110=825
https://github.com/ptushub/nohkiu/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91%3Ajdb%E7%94%B5%E5%AD%90%E7%89%88%E6%98%AF%E4%BB%80%E4%B9%88-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/150=720
https://github.com/ptushub/nohkiu/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91%3Ajdb%E7%94%B5%E5%AD%90%E7%89%88%E6%98%AF%E4%BB%80%E4%B9%88-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/154=798
https://github.com/ptushub/nohkiu/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91%3Ajdb%E7%94%B5%E5%AD%90%E7%89%88%E6%98%AF%E4%BB%80%E4%B9%88-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/381=270
https://github.com/ptushub/nohkiu/blob/main/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91%3Ajdb%E7%94%B5%E5%AD%90%E7%89%88%E6%98%AF%E4%BB%80%E4%B9%88-%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/dcedb913a74605b27546ce5c52d311e43d0245cc?/484=773
https://github.com/mustakuritsar07/rkngzy/commit/dcedb913a74605b27546ce5c52d311e43d0245cc?/821=781
https://github.com/mustakuritsar07/rkngzy/commit/dcedb913a74605b27546ce5c52d311e43d0245cc?/047=810
https://github.com/mustakuritsar07/rkngzy/commit/dcedb913a74605b27546ce5c52d311e43d0245cc?/110=054
https://github.com/mustakuritsar07/rkngzy/commit/dcedb913a74605b27546ce5c52d311e43d0245cc?/487=314
https://github.com/mustakuritsar07/rkngzy/commit/dcedb913a74605b27546ce5c52d311e43d0245cc
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E5%8C%85%E5%A4%A7%E4%BA%BA-%E8%B4%A2%E5%AF%8C%E8%A7%86%E7%95%8C.md?/440=058
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E5%8C%85%E5%A4%A7%E4%BA%BA-%E8%B4%A2%E5%AF%8C%E8%A7%86%E7%95%8C.md?/870=884
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E5%8C%85%E5%A4%A7%E4%BA%BA-%E8%B4%A2%E5%AF%8C%E8%A7%86%E7%95%8C.md?/854=870
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E5%8C%85%E5%A4%A7%E4%BA%BA-%E8%B4%A2%E5%AF%8C%E8%A7%86%E7%95%8C.md?/936=508
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E5%8C%85%E5%A4%A7%E4%BA%BA-%E8%B4%A2%E5%AF%8C%E8%A7%86%E7%95%8C.md?/052=495
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E5%8C%85%E5%A4%A7%E4%BA%BA-%E8%B4%A2%E5%AF%8C%E8%A7%86%E7%95%8C.md
https://github.com/sourux23/eufvji/commit/ac25060a9b739af00b4753a1128350b771e17397?/786=836
https://github.com/sourux23/eufvji/commit/ac25060a9b739af00b4753a1128350b771e17397?/120=571
https://github.com/sourux23/eufvji/commit/ac25060a9b739af00b4753a1128350b771e17397?/698=554
https://github.com/sourux23/eufvji/commit/ac25060a9b739af00b4753a1128350b771e17397?/262=639
https://github.com/sourux23/eufvji/commit/ac25060a9b739af00b4753a1128350b771e17397?/814=619
https://github.com/sourux23/eufvji/commit/ac25060a9b739af00b4753a1128350b771e17397
https://github.com/sourux23/eufvji/blob/main/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD%E7%B2%BE%E9%80%89.md?/070=881
https://github.com/sourux23/eufvji/blob/main/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD%E7%B2%BE%E9%80%89.md?/940=043
https://github.com/sourux23/eufvji/blob/main/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD%E7%B2%BE%E9%80%89.md?/151=480
https://github.com/sourux23/eufvji/blob/main/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD%E7%B2%BE%E9%80%89.md?/717=225
https://github.com/sourux23/eufvji/blob/main/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD%E7%B2%BE%E9%80%89.md?/195=074
https://github.com/sourux23/eufvji/blob/main/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A4%A7%E5%A5%96%E8%A7%86%E9%A2%91-%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD%E7%B2%BE%E9%80%89.md
https://github.com/constiang-s/xzjjce/commit/d50715bfb5b73b156472c2d6e70806bb3a343d41?/009=334
https://github.com/constiang-s/xzjjce/commit/d50715bfb5b73b156472c2d6e70806bb3a343d41?/987=831
https://github.com/constiang-s/xzjjce/commit/d50715bfb5b73b156472c2d6e70806bb3a343d41?/389=221
https://github.com/constiang-s/xzjjce/commit/d50715bfb5b73b156472c2d6e70806bb3a343d41?/806=856
https://github.com/constiang-s/xzjjce/commit/d50715bfb5b73b156472c2d6e70806bb3a343d41?/043=120
https://github.com/constiang-s/xzjjce/commit/d50715bfb5b73b156472c2d6e70806bb3a343d41
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/269=609
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/840=597
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/999=373
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/154=154
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md?/170=821
https://github.com/constiang-s/xzjjce/blob/main/2027%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86-%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9.md
https://github.com/danielfachka/zyfplc/commit/e0bb35c28f8996d826d7118326e181a7fcc2505c?/421=557
https://github.com/danielfachka/zyfplc/commit/e0bb35c28f8996d826d7118326e181a7fcc2505c?/447=453
https://github.com/danielfachka/zyfplc/commit/e0bb35c28f8996d826d7118326e181a7fcc2505c?/154=019
https://github.com/danielfachka/zyfplc/commit/e0bb35c28f8996d826d7118326e181a7fcc2505c?/631=609
https://github.com/danielfachka/zyfplc/commit/e0bb35c28f8996d826d7118326e181a7fcc2505c?/221=376
https://github.com/danielfachka/zyfplc/commit/e0bb35c28f8996d826d7118326e181a7fcc2505c
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/156=287
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/554=436
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/332=163
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/942=770
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F.md?/203=265
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%84%E5%BE%8B-%E5%AE%8F%E9%BC%8E%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/e1c32e746359a46fe2221db6dece98281ea08797?/443=834
https://github.com/schowffer/nmghjj/commit/e1c32e746359a46fe2221db6dece98281ea08797?/125=157
https://github.com/schowffer/nmghjj/commit/e1c32e746359a46fe2221db6dece98281ea08797?/619=204
https://github.com/schowffer/nmghjj/commit/e1c32e746359a46fe2221db6dece98281ea08797?/410=834
https://github.com/schowffer/nmghjj/commit/e1c32e746359a46fe2221db6dece98281ea08797?/342=827
https://github.com/schowffer/nmghjj/commit/e1c32e746359a46fe2221db6dece98281ea08797
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F.md?/387=221
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F.md?/152=710
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F.md?/332=686
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F.md?/421=579
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F.md?/692=534
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E6%8A%80%E5%B7%A7-%E6%B5%B7%E6%B4%8B%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/2250b410942ba899c46ca894c79bfbc736ddbd2d?/725=376
https://github.com/e44nf/nkliyn/commit/2250b410942ba899c46ca894c79bfbc736ddbd2d?/187=376
https://github.com/e44nf/nkliyn/commit/2250b410942ba899c46ca894c79bfbc736ddbd2d?/268=276
https://github.com/e44nf/nkliyn/commit/2250b410942ba899c46ca894c79bfbc736ddbd2d?/710=537
https://github.com/e44nf/nkliyn/commit/2250b410942ba899c46ca894c79bfbc736ddbd2d?/119=125
https://github.com/e44nf/nkliyn/commit/2250b410942ba899c46ca894c79bfbc736ddbd2d
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E5%9B%BE%E7%89%87-%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/154=595
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E5%9B%BE%E7%89%87-%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/775=054
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E5%9B%BE%E7%89%87-%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/276=883
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E5%9B%BE%E7%89%87-%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/885=932
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E5%9B%BE%E7%89%87-%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/753=943
https://github.com/e44nf/nkliyn/blob/main/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E5%9B%BE%E7%89%87-%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/db534b23e231fda46de366141433f89e8f14d04e?/166=164
https://github.com/kulkaye/xiinuu/commit/db534b23e231fda46de366141433f89e8f14d04e?/101=932
https://github.com/kulkaye/xiinuu/commit/db534b23e231fda46de366141433f89e8f14d04e?/043=164
https://github.com/kulkaye/xiinuu/commit/db534b23e231fda46de366141433f89e8f14d04e?/114=721
https://github.com/kulkaye/xiinuu/commit/db534b23e231fda46de366141433f89e8f14d04e?/266=969
https://github.com/kulkaye/xiinuu/commit/db534b23e231fda46de366141433f89e8f14d04e
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0%3AJDB%E7%94%B5%E5%AD%90%E7%88%86%E9%AB%98%E5%88%86%E8%A7%86%E9%A2%91-%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F.md?/854=614
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0%3AJDB%E7%94%B5%E5%AD%90%E7%88%86%E9%AB%98%E5%88%86%E8%A7%86%E9%A2%91-%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F.md?/032=998
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0%3AJDB%E7%94%B5%E5%AD%90%E7%88%86%E9%AB%98%E5%88%86%E8%A7%86%E9%A2%91-%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F.md?/609=247
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0%3AJDB%E7%94%B5%E5%AD%90%E7%88%86%E9%AB%98%E5%88%86%E8%A7%86%E9%A2%91-%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F.md?/487=114
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0%3AJDB%E7%94%B5%E5%AD%90%E7%88%86%E9%AB%98%E5%88%86%E8%A7%86%E9%A2%91-%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F.md?/970=619
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0%3AJDB%E7%94%B5%E5%AD%90%E7%88%86%E9%AB%98%E5%88%86%E8%A7%86%E9%A2%91-%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/e905df7596019886352d7eb653ba49d393f8958f?/669=720
https://github.com/enognagu/lpvade/commit/e905df7596019886352d7eb653ba49d393f8958f?/110=497
https://github.com/enognagu/lpvade/commit/e905df7596019886352d7eb653ba49d393f8958f?/716=224
https://github.com/enognagu/lpvade/commit/e905df7596019886352d7eb653ba49d393f8958f?/776=224
https://github.com/enognagu/lpvade/commit/e905df7596019886352d7eb653ba49d393f8958f?/945=487
https://github.com/enognagu/lpvade/commit/e905df7596019886352d7eb653ba49d393f8958f
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/989=776
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/190=379
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/221=558
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/508=710
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md?/092=447
https://github.com/enognagu/lpvade/blob/main/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96-%E7%8E%AF%E7%90%83%E7%BB%8F%E6%B5%8E.md
https://github.com/ryukaura/kityhe/commit/c9ab376220140f13f6e0f5dfcdd4ebaf26f00796?/887=554
https://github.com/ryukaura/kityhe/commit/c9ab376220140f13f6e0f5dfcdd4ebaf26f00796?/386=158
https://github.com/ryukaura/kityhe/commit/c9ab376220140f13f6e0f5dfcdd4ebaf26f00796?/480=824
https://github.com/ryukaura/kityhe/commit/c9ab376220140f13f6e0f5dfcdd4ebaf26f00796?/669=727
https://github.com/ryukaura/kityhe/commit/c9ab376220140f13f6e0f5dfcdd4ebaf26f00796?/828=497
https://github.com/ryukaura/kityhe/commit/c9ab376220140f13f6e0f5dfcdd4ebaf26f00796
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/664=669
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/836=887
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/058=276
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/871=221
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F.md?/941=554
https://github.com/ryukaura/kityhe/blob/main/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%AD%E8%A7%86%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/bcc4b235eda93b7285d9e20551046f8158aa4a07?/998=725
https://github.com/ptushub/nohkiu/commit/bcc4b235eda93b7285d9e20551046f8158aa4a07?/487=045
https://github.com/ptushub/nohkiu/commit/bcc4b235eda93b7285d9e20551046f8158aa4a07?/381=606
https://github.com/ptushub/nohkiu/commit/bcc4b235eda93b7285d9e20551046f8158aa4a07?/720=725
https://github.com/ptushub/nohkiu/commit/bcc4b235eda93b7285d9e20551046f8158aa4a07?/447=481
https://github.com/ptushub/nohkiu/commit/bcc4b235eda93b7285d9e20551046f8158aa4a07
https://github.com/ptushub/nohkiu/blob/main/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%89%8D%E5%85%86-%E5%A4%A7%E6%B2%B3%E7%BD%91.md?/336=370
https://github.com/ptushub/nohkiu/blob/main/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%89%8D%E5%85%86-%E5%A4%A7%E6%B2%B3%E7%BD%91.md?/826=487
https://github.com/ptushub/nohkiu/blob/main/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%89%8D%E5%85%86-%E5%A4%A7%E6%B2%B3%E7%BD%91.md?/332=298
https://github.com/ptushub/nohkiu/blob/main/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%89%8D%E5%85%86-%E5%A4%A7%E6%B2%B3%E7%BD%91.md?/376=992
https://github.com/ptushub/nohkiu/blob/main/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%89%8D%E5%85%86-%E5%A4%A7%E6%B2%B3%E7%BD%91.md?/870=370
https://github.com/ptushub/nohkiu/blob/main/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%89%8D%E5%85%86-%E5%A4%A7%E6%B2%B3%E7%BD%91.md
https://github.com/mustakuritsar07/rkngzy/commit/e91af8edf3cd0ec905180de28b0f92d377c637e8?/332=881
https://github.com/mustakuritsar07/rkngzy/commit/e91af8edf3cd0ec905180de28b0f92d377c637e8?/714=381
https://github.com/mustakuritsar07/rkngzy/commit/e91af8edf3cd0ec905180de28b0f92d377c637e8?/710=053
https://github.com/mustakuritsar07/rkngzy/commit/e91af8edf3cd0ec905180de28b0f92d377c637e8?/555=160
https://github.com/mustakuritsar07/rkngzy/commit/e91af8edf3cd0ec905180de28b0f92d377c637e8?/576=086
https://github.com/mustakuritsar07/rkngzy/commit/e91af8edf3cd0ec905180de28b0f92d377c637e8
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91-%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/554=598
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91-%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/710=675
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91-%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/897=009
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91-%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/992=998
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91-%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/647=347
https://github.com/mustakuritsar07/rkngzy/blob/main/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91-%E5%8D%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/677003b44a8898545c63845dd0f460cca2f5148a?/154=838
https://github.com/sourux23/eufvji/commit/677003b44a8898545c63845dd0f460cca2f5148a?/932=053
https://github.com/sourux23/eufvji/commit/677003b44a8898545c63845dd0f460cca2f5148a?/376=669
https://github.com/sourux23/eufvji/commit/677003b44a8898545c63845dd0f460cca2f5148a?/710=619
https://github.com/sourux23/eufvji/commit/677003b44a8898545c63845dd0f460cca2f5148a?/758=481
https://github.com/sourux23/eufvji/commit/677003b44a8898545c63845dd0f460cca2f5148a
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E7%99%BD%E5%AF%8C%E7%BE%8E-%E9%87%91%E8%9E%8D%E7%83%AD%E7%82%B9.md?/821=619
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E7%99%BD%E5%AF%8C%E7%BE%8E-%E9%87%91%E8%9E%8D%E7%83%AD%E7%82%B9.md?/054=614
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E7%99%BD%E5%AF%8C%E7%BE%8E-%E9%87%91%E8%9E%8D%E7%83%AD%E7%82%B9.md?/380=225
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E7%99%BD%E5%AF%8C%E7%BE%8E-%E9%87%91%E8%9E%8D%E7%83%AD%E7%82%B9.md?/345=881
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E7%99%BD%E5%AF%8C%E7%BE%8E-%E9%87%91%E8%9E%8D%E7%83%AD%E7%82%B9.md?/700=487
https://github.com/sourux23/eufvji/blob/main/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E7%99%BD%E5%AF%8C%E7%BE%8E-%E9%87%91%E8%9E%8D%E7%83%AD%E7%82%B9.md
https://github.com/danielfachka/zyfplc/commit/285a7d228a136fd7304398dc6a65c227a08cfb2c?/684=387
https://github.com/danielfachka/zyfplc/commit/285a7d228a136fd7304398dc6a65c227a08cfb2c?/821=332
https://github.com/danielfachka/zyfplc/commit/285a7d228a136fd7304398dc6a65c227a08cfb2c?/643=325
https://github.com/danielfachka/zyfplc/commit/285a7d228a136fd7304398dc6a65c227a08cfb2c?/874=332
https://github.com/danielfachka/zyfplc/commit/285a7d228a136fd7304398dc6a65c227a08cfb2c?/046=908
https://github.com/danielfachka/zyfplc/commit/285a7d228a136fd7304398dc6a65c227a08cfb2c
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%9B%BE%E7%89%87-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/254=554
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%9B%BE%E7%89%87-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/619=998
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%9B%BE%E7%89%87-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/225=758
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%9B%BE%E7%89%87-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/487=665
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%9B%BE%E7%89%87-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md?/470=945
https://github.com/danielfachka/zyfplc/blob/main/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E5%9B%BE%E7%89%87-%E8%B4%A2%E7%BB%8F%E7%84%A6%E7%82%B9.md
https://github.com/constiang-s/xzjjce/commit/b66a259589ed175c383ea670ef7296657508d2bd?/481=053
https://github.com/constiang-s/xzjjce/commit/b66a259589ed175c383ea670ef7296657508d2bd?/995=914
https://github.com/constiang-s/xzjjce/commit/b66a259589ed175c383ea670ef7296657508d2bd?/387=710
https://github.com/constiang-s/xzjjce/commit/b66a259589ed175c383ea670ef7296657508d2bd?/003=828
https://github.com/constiang-s/xzjjce/commit/b66a259589ed175c383ea670ef7296657508d2bd?/447=823
https://github.com/constiang-s/xzjjce/commit/b66a259589ed175c383ea670ef7296657508d2bd
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E5%B9%B8%E8%BF%90%E9%BE%99-%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F.md?/492=492
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E5%B9%B8%E8%BF%90%E9%BE%99-%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F.md?/503=381
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E5%B9%B8%E8%BF%90%E9%BE%99-%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F.md?/373=158
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E5%B9%B8%E8%BF%90%E9%BE%99-%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F.md?/225=269
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E5%B9%B8%E8%BF%90%E9%BE%99-%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F.md?/369=777
https://github.com/constiang-s/xzjjce/blob/main/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E5%A5%96%E8%A7%86%E9%A2%91%E5%B9%B8%E8%BF%90%E9%BE%99-%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/5843576c42c83d101a2e553a9d7c50d8a84d9ebb?/831=154
https://github.com/schowffer/nmghjj/commit/5843576c42c83d101a2e553a9d7c50d8a84d9ebb?/164=287
https://github.com/schowffer/nmghjj/commit/5843576c42c83d101a2e553a9d7c50d8a84d9ebb?/043=487
https://github.com/schowffer/nmghjj/commit/5843576c42c83d101a2e553a9d7c50d8a84d9ebb?/607=265
https://github.com/schowffer/nmghjj/commit/5843576c42c83d101a2e553a9d7c50d8a84d9ebb?/236=003
https://github.com/schowffer/nmghjj/commit/5843576c42c83d101a2e553a9d7c50d8a84d9ebb
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E7%8E%87-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/114=159
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E7%8E%87-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/487=209
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E7%8E%87-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/710=447
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E7%8E%87-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/503=943
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E7%8E%87-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md?/658=164
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA%3Ajdb%E7%94%B5%E5%AD%90%E7%88%86%E7%8E%87-%E5%8C%97%E7%BE%8E%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/ffe931277050dca2ac44043ed188fd6e58423a97?/602=508
https://github.com/e44nf/nkliyn/commit/ffe931277050dca2ac44043ed188fd6e58423a97?/314=376
https://github.com/e44nf/nkliyn/commit/ffe931277050dca2ac44043ed188fd6e58423a97?/045=054
https://github.com/e44nf/nkliyn/commit/ffe931277050dca2ac44043ed188fd6e58423a97?/339=598
https://github.com/e44nf/nkliyn/commit/ffe931277050dca2ac44043ed188fd6e58423a97?/710=998
https://github.com/e44nf/nkliyn/commit/ffe931277050dca2ac44043ed188fd6e58423a97
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E7%AB%99-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA.md?/053=992
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E7%AB%99-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA.md?/491=320
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E7%AB%99-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA.md?/628=487
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E7%AB%99-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA.md?/944=215
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E7%AB%99-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA.md?/541=949
https://github.com/e44nf/nkliyn/blob/main/2026%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E7%AB%99-%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA.md
https://github.com/kulkaye/xiinuu/commit/b2b9fe8bb0dea50d382a910a7fd3a51aef114e21?/275=041
https://github.com/kulkaye/xiinuu/commit/b2b9fe8bb0dea50d382a910a7fd3a51aef114e21?/265=387
https://github.com/kulkaye/xiinuu/commit/b2b9fe8bb0dea50d382a910a7fd3a51aef114e21?/481=265
https://github.com/kulkaye/xiinuu/commit/b2b9fe8bb0dea50d382a910a7fd3a51aef114e21?/823=605
https://github.com/kulkaye/xiinuu/commit/b2b9fe8bb0dea50d382a910a7fd3a51aef114e21?/006=221
https://github.com/kulkaye/xiinuu/commit/b2b9fe8bb0dea50d382a910a7fd3a51aef114e21
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E5%9D%80-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F.md?/506=482
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E5%9D%80-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F.md?/440=443
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E5%9D%80-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F.md?/373=227
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E5%9D%80-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F.md?/047=265
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E5%9D%80-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F.md?/323=618
https://github.com/kulkaye/xiinuu/blob/main/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB%3Ajdb%E7%94%B5%E5%AD%90%E5%A4%87%E7%94%A8%E7%BD%91%E5%9D%80-%E8%8D%B7%E5%85%B0%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/d4b44e44e625a902477a63d2e56b3284e3cff7d1?/712=493
https://github.com/enognagu/lpvade/commit/d4b44e44e625a902477a63d2e56b3284e3cff7d1?/043=821
https://github.com/enognagu/lpvade/commit/d4b44e44e625a902477a63d2e56b3284e3cff7d1?/223=386
https://github.com/enognagu/lpvade/commit/d4b44e44e625a902477a63d2e56b3284e3cff7d1?/158=603
https://github.com/enognagu/lpvade/commit/d4b44e44e625a902477a63d2e56b3284e3cff7d1?/269=058
https://github.com/enognagu/lpvade/commit/d4b44e44e625a902477a63d2e56b3284e3cff7d1
https://github.com/enognagu/lpvade/blob/main/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7-%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/325=997
https://github.com/enognagu/lpvade/blob/main/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7-%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/047=843
https://github.com/enognagu/lpvade/blob/main/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7-%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/370=503
https://github.com/enognagu/lpvade/blob/main/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7-%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/475=983
https://github.com/enognagu/lpvade/blob/main/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7-%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F.md?/767=770
https://github.com/enognagu/lpvade/blob/main/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7-%E5%8E%9F%E5%88%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/456804c7ed6ed2c4c58c7313afa2ff02a1fc99f2?/053=386
https://github.com/ryukaura/kityhe/commit/456804c7ed6ed2c4c58c7313afa2ff02a1fc99f2?/110=887
https://github.com/ryukaura/kityhe/commit/456804c7ed6ed2c4c58c7313afa2ff02a1fc99f2?/387=932
https://github.com/ryukaura/kityhe/commit/456804c7ed6ed2c4c58c7313afa2ff02a1fc99f2?/232=151
https://github.com/ryukaura/kityhe/commit/456804c7ed6ed2c4c58c7313afa2ff02a1fc99f2?/376=814
https://github.com/ryukaura/kityhe/commit/456804c7ed6ed2c4c58c7313afa2ff02a1fc99f2
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/614=087
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/936=836
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/154=943
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/370=270
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F.md?/553=376
https://github.com/ryukaura/kityhe/blob/main/2026%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E7%88%86%E5%88%86%E8%A7%86%E9%A2%91-%E4%B8%8A%E5%B8%82%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/6830ff8f68d8481606c694b209c0087cdb280e4f?/981=481
https://github.com/ptushub/nohkiu/commit/6830ff8f68d8481606c694b209c0087cdb280e4f?/836=887
https://github.com/ptushub/nohkiu/commit/6830ff8f68d8481606c694b209c0087cdb280e4f?/598=670
https://github.com/ptushub/nohkiu/commit/6830ff8f68d8481606c694b209c0087cdb280e4f?/710=210
https://github.com/ptushub/nohkiu/commit/6830ff8f68d8481606c694b209c0087cdb280e4f?/710=829
https://github.com/ptushub/nohkiu/commit/6830ff8f68d8481606c694b209c0087cdb280e4f
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E6%B8%B8%E6%88%8F-%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/098=236
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E6%B8%B8%E6%88%8F-%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/338=555
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E6%B8%B8%E6%88%8F-%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/597=265
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E6%B8%B8%E6%88%8F-%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/275=492
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E6%B8%B8%E6%88%8F-%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/945=039
https://github.com/ptushub/nohkiu/blob/main/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A%3Ajdb%E7%94%B5%E5%AD%90%E8%B9%A6%E8%BF%AA%E5%90%A7%E6%B8%B8%E6%88%8F-%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/mustakuritsar07/rkngzy/commit/d652353303fefa34e6303d34fcf8373230886b19?/152=501
https://github.com/mustakuritsar07/rkngzy/commit/d652353303fefa34e6303d34fcf8373230886b19?/792=117
https://github.com/mustakuritsar07/rkngzy/commit/d652353303fefa34e6303d34fcf8373230886b19?/342=051
https://github.com/mustakuritsar07/rkngzy/commit/d652353303fefa34e6303d34fcf8373230886b19?/114=636
https://github.com/mustakuritsar07/rkngzy/commit/d652353303fefa34e6303d34fcf8373230886b19?/779=831
https://github.com/mustakuritsar07/rkngzy/commit/d652353303fefa34e6303d34fcf8373230886b19
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E5%BF%85%E8%B5%A2-%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/262=998
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E5%BF%85%E8%B5%A2-%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/612=997
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E5%BF%85%E8%B5%A2-%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/223=275
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E5%BF%85%E8%B5%A2-%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/571=887
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E5%BF%85%E8%B5%A2-%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/361=025
https://github.com/mustakuritsar07/rkngzy/blob/main/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C%3Ajdb%E7%94%B5%E5%AD%90%E5%BF%85%E8%B5%A2-%E8%A5%BF%E6%AC%A7%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/dbb0e0ae4819e2442214422e469665d864a272f2?/943=225
https://github.com/danielfachka/zyfplc/commit/dbb0e0ae4819e2442214422e469665d864a272f2?/276=999
https://github.com/danielfachka/zyfplc/commit/dbb0e0ae4819e2442214422e469665d864a272f2?/722=881
https://github.com/danielfachka/zyfplc/commit/dbb0e0ae4819e2442214422e469665d864a272f2?/376=610
https://github.com/danielfachka/zyfplc/commit/dbb0e0ae4819e2442214422e469665d864a272f2?/598=836
https://github.com/danielfachka/zyfplc/commit/dbb0e0ae4819e2442214422e469665d864a272f2
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3Ajdb%E7%94%B5%E5%AD%90%E5%8F%98-%E8%B4%A2%E5%AF%8C%E5%BF%AB%E8%AE%AF.md?/992=503
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3Ajdb%E7%94%B5%E5%AD%90%E5%8F%98-%E8%B4%A2%E5%AF%8C%E5%BF%AB%E8%AE%AF.md?/269=275
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3Ajdb%E7%94%B5%E5%AD%90%E5%8F%98-%E8%B4%A2%E5%AF%8C%E5%BF%AB%E8%AE%AF.md?/558=155
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3Ajdb%E7%94%B5%E5%AD%90%E5%8F%98-%E8%B4%A2%E5%AF%8C%E5%BF%AB%E8%AE%AF.md?/914=598
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3Ajdb%E7%94%B5%E5%AD%90%E5%8F%98-%E8%B4%A2%E5%AF%8C%E5%BF%AB%E8%AE%AF.md?/481=831
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92%3Ajdb%E7%94%B5%E5%AD%90%E5%8F%98-%E8%B4%A2%E5%AF%8C%E5%BF%AB%E8%AE%AF.md
https://github.com/constiang-s/xzjjce/commit/b3426e3c80100b30a330cc4f747ead2d37c4adfb?/886=543
https://github.com/constiang-s/xzjjce/commit/b3426e3c80100b30a330cc4f747ead2d37c4adfb?/345=157
https://github.com/constiang-s/xzjjce/commit/b3426e3c80100b30a330cc4f747ead2d37c4adfb?/320=556
https://github.com/constiang-s/xzjjce/commit/b3426e3c80100b30a330cc4f747ead2d37c4adfb?/339=075
https://github.com/constiang-s/xzjjce/commit/b3426e3c80100b30a330cc4f747ead2d37c4adfb?/123=228
https://github.com/constiang-s/xzjjce/commit/b3426e3c80100b30a330cc4f747ead2d37c4adfb
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5%3AJDB%E7%94%B5%E5%AD%90%E5%8F%98%E8%84%B8-%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F.md?/053=119
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5%3AJDB%E7%94%B5%E5%AD%90%E5%8F%98%E8%84%B8-%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F.md?/271=121
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5%3AJDB%E7%94%B5%E5%AD%90%E5%8F%98%E8%84%B8-%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F.md?/339=710
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5%3AJDB%E7%94%B5%E5%AD%90%E5%8F%98%E8%84%B8-%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F.md?/501=762
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5%3AJDB%E7%94%B5%E5%AD%90%E5%8F%98%E8%84%B8-%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F.md?/293=884
https://github.com/constiang-s/xzjjce/blob/main/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5%3AJDB%E7%94%B5%E5%AD%90%E5%8F%98%E8%84%B8-%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/7657d422f0feac533b8e8aa65e36112f8ba783a7?/265=265
https://github.com/schowffer/nmghjj/commit/7657d422f0feac533b8e8aa65e36112f8ba783a7?/710=332
https://github.com/schowffer/nmghjj/commit/7657d422f0feac533b8e8aa65e36112f8ba783a7?/444=447
https://github.com/schowffer/nmghjj/commit/7657d422f0feac533b8e8aa65e36112f8ba783a7?/180=714
