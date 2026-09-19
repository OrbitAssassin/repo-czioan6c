百度蜘蛛是百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
死偻傥傥傥俦窝惭厦来姥毙蚊看恋恋信从心路
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

https://github.com/e44nf/nkliyn/blob/main/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1.md?/986=752
https://github.com/e44nf/nkliyn/blob/main/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1.md?/768=605
https://github.com/e44nf/nkliyn/blob/main/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1.md?/355=436
https://github.com/e44nf/nkliyn/blob/main/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E6%8B%9B%E5%95%86-%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1.md
https://github.com/ryukaura/kityhe/commit/37d0e92b2612898609d1e420e0a350c071b3cb01?/119=310
https://github.com/ryukaura/kityhe/commit/37d0e92b2612898609d1e420e0a350c071b3cb01?/670=720
https://github.com/ryukaura/kityhe/commit/37d0e92b2612898609d1e420e0a350c071b3cb01?/827=305
https://github.com/ryukaura/kityhe/commit/37d0e92b2612898609d1e420e0a350c071b3cb01?/520=112
https://github.com/ryukaura/kityhe/commit/37d0e92b2612898609d1e420e0a350c071b3cb01?/163=887
https://github.com/ryukaura/kityhe/commit/37d0e92b2612898609d1e420e0a350c071b3cb01
https://github.com/ryukaura/kityhe/blob/main/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F.md?/999=932
https://github.com/ryukaura/kityhe/blob/main/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F.md?/498=109
https://github.com/ryukaura/kityhe/blob/main/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F.md?/505=043
https://github.com/ryukaura/kityhe/blob/main/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F.md?/874=369
https://github.com/ryukaura/kityhe/blob/main/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F.md?/947=158
https://github.com/ryukaura/kityhe/blob/main/2027%E7%9B%98%E7%82%B9%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E5%A2%A8%E8%A5%BF%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/9d91f70e277a13dbab65baccc7eb225e8620e7bd?/720=275
https://github.com/sourux23/eufvji/commit/9d91f70e277a13dbab65baccc7eb225e8620e7bd?/558=498
https://github.com/sourux23/eufvji/commit/9d91f70e277a13dbab65baccc7eb225e8620e7bd?/821=619
https://github.com/sourux23/eufvji/commit/9d91f70e277a13dbab65baccc7eb225e8620e7bd?/825=619
https://github.com/sourux23/eufvji/commit/9d91f70e277a13dbab65baccc7eb225e8620e7bd?/508=276
https://github.com/sourux23/eufvji/commit/9d91f70e277a13dbab65baccc7eb225e8620e7bd
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C.md?/447=008
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C.md?/597=487
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C.md?/803=058
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C.md?/821=990
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C.md?/925=836
https://github.com/sourux23/eufvji/blob/main/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90-%E7%99%BE%E5%BA%A6%E7%BB%8F%E9%AA%8C.md
https://github.com/danielfachka/zyfplc/commit/b560c2157c68156f70d80db2a5edcbec68e4db09?/828=949
https://github.com/danielfachka/zyfplc/commit/b560c2157c68156f70d80db2a5edcbec68e4db09?/897=887
https://github.com/danielfachka/zyfplc/commit/b560c2157c68156f70d80db2a5edcbec68e4db09?/609=198
https://github.com/danielfachka/zyfplc/commit/b560c2157c68156f70d80db2a5edcbec68e4db09?/552=949
https://github.com/danielfachka/zyfplc/commit/b560c2157c68156f70d80db2a5edcbec68e4db09?/332=275
https://github.com/danielfachka/zyfplc/commit/b560c2157c68156f70d80db2a5edcbec68e4db09
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md?/942=487
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md?/058=043
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md?/469=110
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md?/270=331
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md?/647=043
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E9%99%86-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%B4%E6%92%AD.md
https://github.com/ptushub/nohkiu/commit/e9342bbba3f9001b7c2372c2626811968e26269f?/508=225
https://github.com/ptushub/nohkiu/commit/e9342bbba3f9001b7c2372c2626811968e26269f?/338=053
https://github.com/ptushub/nohkiu/commit/e9342bbba3f9001b7c2372c2626811968e26269f?/110=481
https://github.com/ptushub/nohkiu/commit/e9342bbba3f9001b7c2372c2626811968e26269f?/603=154
https://github.com/ptushub/nohkiu/commit/e9342bbba3f9001b7c2372c2626811968e26269f?/275=386
https://github.com/ptushub/nohkiu/commit/e9342bbba3f9001b7c2372c2626811968e26269f
https://github.com/ptushub/nohkiu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/043=669
https://github.com/ptushub/nohkiu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/825=498
https://github.com/ptushub/nohkiu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/770=803
https://github.com/ptushub/nohkiu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/670=381
https://github.com/ptushub/nohkiu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md?/536=387
https://github.com/ptushub/nohkiu/blob/main/2027%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0-%E9%AB%98%E7%AB%AF%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/b104b88cdd3274dbbaabc0d9725067633bdf0410?/487=075
https://github.com/kulkaye/xiinuu/commit/b104b88cdd3274dbbaabc0d9725067633bdf0410?/160=619
https://github.com/kulkaye/xiinuu/commit/b104b88cdd3274dbbaabc0d9725067633bdf0410?/119=884
https://github.com/kulkaye/xiinuu/commit/b104b88cdd3274dbbaabc0d9725067633bdf0410?/942=119
https://github.com/kulkaye/xiinuu/commit/b104b88cdd3274dbbaabc0d9725067633bdf0410?/484=881
https://github.com/kulkaye/xiinuu/commit/b104b88cdd3274dbbaabc0d9725067633bdf0410
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/482=669
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/336=342
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/447=710
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/114=484
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md?/092=486
https://github.com/kulkaye/xiinuu/blob/main/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86-%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/3e5c30df52452312307d900bd1eefdaee10c26ed?/275=669
https://github.com/schowffer/nmghjj/commit/3e5c30df52452312307d900bd1eefdaee10c26ed?/609=769
https://github.com/schowffer/nmghjj/commit/3e5c30df52452312307d900bd1eefdaee10c26ed?/825=114
https://github.com/schowffer/nmghjj/commit/3e5c30df52452312307d900bd1eefdaee10c26ed?/821=714
https://github.com/schowffer/nmghjj/commit/3e5c30df52452312307d900bd1eefdaee10c26ed?/508=492
https://github.com/schowffer/nmghjj/commit/3e5c30df52452312307d900bd1eefdaee10c26ed
https://github.com/schowffer/nmghjj/blob/main/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md?/770=932
https://github.com/schowffer/nmghjj/blob/main/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md?/164=948
https://github.com/schowffer/nmghjj/blob/main/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md?/609=669
https://github.com/schowffer/nmghjj/blob/main/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md?/598=054
https://github.com/schowffer/nmghjj/blob/main/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md?/369=832
https://github.com/schowffer/nmghjj/blob/main/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%BB%A3%E7%90%86%E5%B9%B3%E5%8F%B0-%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB.md
https://github.com/enognagu/lpvade/commit/7608d1c2df3a71f780fd5939d8e8d1985d468b7d?/008=043
https://github.com/enognagu/lpvade/commit/7608d1c2df3a71f780fd5939d8e8d1985d468b7d?/154=551
https://github.com/enognagu/lpvade/commit/7608d1c2df3a71f780fd5939d8e8d1985d468b7d?/710=598
https://github.com/enognagu/lpvade/commit/7608d1c2df3a71f780fd5939d8e8d1985d468b7d?/773=598
https://github.com/enognagu/lpvade/commit/7608d1c2df3a71f780fd5939d8e8d1985d468b7d?/883=443
https://github.com/enognagu/lpvade/commit/7608d1c2df3a71f780fd5939d8e8d1985d468b7d
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F.md?/006=942
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F.md?/054=447
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F.md?/370=051
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F.md?/721=998
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F.md?/936=643
https://github.com/enognagu/lpvade/blob/main/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%BB%A3%E7%90%86-%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/1a6683354d32ad5688e70d2840acbbe1250bf8f8?/556=006
https://github.com/e44nf/nkliyn/commit/1a6683354d32ad5688e70d2840acbbe1250bf8f8?/887=058
https://github.com/e44nf/nkliyn/commit/1a6683354d32ad5688e70d2840acbbe1250bf8f8?/542=598
https://github.com/e44nf/nkliyn/commit/1a6683354d32ad5688e70d2840acbbe1250bf8f8?/103=503
https://github.com/e44nf/nkliyn/commit/1a6683354d32ad5688e70d2840acbbe1250bf8f8?/892=932
https://github.com/e44nf/nkliyn/commit/1a6683354d32ad5688e70d2840acbbe1250bf8f8
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/156=493
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/376=036
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/331=043
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/164=710
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/436=387
https://github.com/e44nf/nkliyn/blob/main/2027%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%B0%E7%9B%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/a0e2e5971edf26979b66747c7ca603c5ffed065b?/076=743
https://github.com/ryukaura/kityhe/commit/a0e2e5971edf26979b66747c7ca603c5ffed065b?/375=336
https://github.com/ryukaura/kityhe/commit/a0e2e5971edf26979b66747c7ca603c5ffed065b?/398=720
https://github.com/ryukaura/kityhe/commit/a0e2e5971edf26979b66747c7ca603c5ffed065b?/591=079
https://github.com/ryukaura/kityhe/commit/a0e2e5971edf26979b66747c7ca603c5ffed065b?/967=480
https://github.com/ryukaura/kityhe/commit/a0e2e5971edf26979b66747c7ca603c5ffed065b
https://github.com/ryukaura/kityhe/blob/main/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F.md?/592=714
https://github.com/ryukaura/kityhe/blob/main/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F.md?/125=744
https://github.com/ryukaura/kityhe/blob/main/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F.md?/754=076
https://github.com/ryukaura/kityhe/blob/main/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F.md?/969=720
https://github.com/ryukaura/kityhe/blob/main/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F.md?/051=125
https://github.com/ryukaura/kityhe/blob/main/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0-%E5%98%89%E8%AF%9A%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/ff785afb8d846fbc0f71af401779e602374c7c39?/158=042
https://github.com/danielfachka/zyfplc/commit/ff785afb8d846fbc0f71af401779e602374c7c39?/278=385
https://github.com/danielfachka/zyfplc/commit/ff785afb8d846fbc0f71af401779e602374c7c39?/710=047
https://github.com/danielfachka/zyfplc/commit/ff785afb8d846fbc0f71af401779e602374c7c39?/810=446
https://github.com/danielfachka/zyfplc/commit/ff785afb8d846fbc0f71af401779e602374c7c39?/770=676
https://github.com/danielfachka/zyfplc/commit/ff785afb8d846fbc0f71af401779e602374c7c39
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F.md?/932=158
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F.md?/714=792
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F.md?/610=275
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F.md?/276=158
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F.md?/692=710
https://github.com/danielfachka/zyfplc/blob/main/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F.md
https://github.com/kulkaye/xiinuu/commit/1a767acc4c59cb1fb014a035df123ec792958b6b?/654=609
https://github.com/kulkaye/xiinuu/commit/1a767acc4c59cb1fb014a035df123ec792958b6b?/214=470
https://github.com/kulkaye/xiinuu/commit/1a767acc4c59cb1fb014a035df123ec792958b6b?/053=714
https://github.com/kulkaye/xiinuu/commit/1a767acc4c59cb1fb014a035df123ec792958b6b?/597=949
https://github.com/kulkaye/xiinuu/commit/1a767acc4c59cb1fb014a035df123ec792958b6b?/003=758
https://github.com/kulkaye/xiinuu/commit/1a767acc4c59cb1fb014a035df123ec792958b6b
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90.md?/708=487
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90.md?/045=932
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90.md?/484=381
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90.md?/481=032
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90.md?/600=914
https://github.com/kulkaye/xiinuu/blob/main/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C-%E9%93%B6%E6%B2%B3%E5%A8%B1%E4%B9%90.md
https://github.com/schowffer/nmghjj/commit/dc9fa2bf48b81e9e29f6cdd3f3b8f3c7a20e6643?/596=508
https://github.com/schowffer/nmghjj/commit/dc9fa2bf48b81e9e29f6cdd3f3b8f3c7a20e6643?/221=990
https://github.com/schowffer/nmghjj/commit/dc9fa2bf48b81e9e29f6cdd3f3b8f3c7a20e6643?/264=165
https://github.com/schowffer/nmghjj/commit/dc9fa2bf48b81e9e29f6cdd3f3b8f3c7a20e6643?/385=127
https://github.com/schowffer/nmghjj/commit/dc9fa2bf48b81e9e29f6cdd3f3b8f3c7a20e6643?/112=875
https://github.com/schowffer/nmghjj/commit/dc9fa2bf48b81e9e29f6cdd3f3b8f3c7a20e6643
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F.md?/420=614
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F.md?/792=711
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F.md?/501=332
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F.md?/598=710
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F.md?/040=997
https://github.com/schowffer/nmghjj/blob/main/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%82%A1%E7%A5%A8%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/42dcd424ffe75f6fb878dd067a5120b224bfd205?/054=675
https://github.com/ptushub/nohkiu/commit/42dcd424ffe75f6fb878dd067a5120b224bfd205?/414=832
https://github.com/ptushub/nohkiu/commit/42dcd424ffe75f6fb878dd067a5120b224bfd205?/043=387
https://github.com/ptushub/nohkiu/commit/42dcd424ffe75f6fb878dd067a5120b224bfd205?/939=381
https://github.com/ptushub/nohkiu/commit/42dcd424ffe75f6fb878dd067a5120b224bfd205?/710=986
https://github.com/ptushub/nohkiu/commit/42dcd424ffe75f6fb878dd067a5120b224bfd205
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/598=743
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/508=507
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/447=940
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/587=056
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/547=710
https://github.com/ptushub/nohkiu/blob/main/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%8B%9B%E5%95%86-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md
https://github.com/enognagu/lpvade/commit/eef2e5c8cb2bb15c00a31326eff1499992e72738?/164=392
https://github.com/enognagu/lpvade/commit/eef2e5c8cb2bb15c00a31326eff1499992e72738?/598=887
https://github.com/enognagu/lpvade/commit/eef2e5c8cb2bb15c00a31326eff1499992e72738?/160=443
https://github.com/enognagu/lpvade/commit/eef2e5c8cb2bb15c00a31326eff1499992e72738?/943=331
https://github.com/enognagu/lpvade/commit/eef2e5c8cb2bb15c00a31326eff1499992e72738?/933=554
https://github.com/enognagu/lpvade/commit/eef2e5c8cb2bb15c00a31326eff1499992e72738
https://github.com/enognagu/lpvade/blob/main/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E9%80%9F%E6%8F%90.md?/602=378
https://github.com/enognagu/lpvade/blob/main/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E9%80%9F%E6%8F%90.md?/025=154
https://github.com/enognagu/lpvade/blob/main/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E9%80%9F%E6%8F%90.md?/167=618
https://github.com/enognagu/lpvade/blob/main/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E9%80%9F%E6%8F%90.md?/264=881
https://github.com/enognagu/lpvade/blob/main/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E9%80%9F%E6%8F%90.md?/763=606
https://github.com/enognagu/lpvade/blob/main/2026%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86-%E9%80%9F%E6%8F%90.md
https://github.com/sourux23/eufvji/commit/143d674ad973fe786e729befc97252c881c2f387?/619=169
https://github.com/sourux23/eufvji/commit/143d674ad973fe786e729befc97252c881c2f387?/221=932
https://github.com/sourux23/eufvji/commit/143d674ad973fe786e729befc97252c881c2f387?/336=943
https://github.com/sourux23/eufvji/commit/143d674ad973fe786e729befc97252c881c2f387?/008=219
https://github.com/sourux23/eufvji/commit/143d674ad973fe786e729befc97252c881c2f387?/003=710
https://github.com/sourux23/eufvji/commit/143d674ad973fe786e729befc97252c881c2f387
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/114=381
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/768=497
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/265=821
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/495=536
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md?/214=167
https://github.com/sourux23/eufvji/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E7%99%BB%E5%BD%95%E7%BD%91%E5%9D%80-%E4%B8%AD%E6%AC%A7%E8%B4%A2%E7%BB%8F.md
https://github.com/e44nf/nkliyn/commit/313e09c10e56fd7c8ac10415888d368a53c45727?/278=225
https://github.com/e44nf/nkliyn/commit/313e09c10e56fd7c8ac10415888d368a53c45727?/729=370
https://github.com/e44nf/nkliyn/commit/313e09c10e56fd7c8ac10415888d368a53c45727?/729=932
https://github.com/e44nf/nkliyn/commit/313e09c10e56fd7c8ac10415888d368a53c45727?/331=165
https://github.com/e44nf/nkliyn/commit/313e09c10e56fd7c8ac10415888d368a53c45727?/987=503
https://github.com/e44nf/nkliyn/commit/313e09c10e56fd7c8ac10415888d368a53c45727
https://github.com/e44nf/nkliyn/blob/main/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F.md?/603=270
https://github.com/e44nf/nkliyn/blob/main/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F.md?/114=177
https://github.com/e44nf/nkliyn/blob/main/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F.md?/881=592
https://github.com/e44nf/nkliyn/blob/main/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F.md?/932=081
https://github.com/e44nf/nkliyn/blob/main/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F.md?/870=321
https://github.com/e44nf/nkliyn/blob/main/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E5%9C%A8%E7%BA%BF%E6%B3%A8%E5%86%8C-%E9%B8%BF%E5%9B%BE%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/73d18eb3937ceaacd8d699b44cfa8f715f0634aa?/113=821
https://github.com/ryukaura/kityhe/commit/73d18eb3937ceaacd8d699b44cfa8f715f0634aa?/385=776
https://github.com/ryukaura/kityhe/commit/73d18eb3937ceaacd8d699b44cfa8f715f0634aa?/387=868
https://github.com/ryukaura/kityhe/commit/73d18eb3937ceaacd8d699b44cfa8f715f0634aa?/221=505
https://github.com/ryukaura/kityhe/commit/73d18eb3937ceaacd8d699b44cfa8f715f0634aa?/875=498
https://github.com/ryukaura/kityhe/commit/73d18eb3937ceaacd8d699b44cfa8f715f0634aa
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/009=675
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/595=888
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/937=031
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/361=836
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md?/470=487
https://github.com/ryukaura/kityhe/blob/main/2027%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0ID%EF%BC%8C%E7%99%BB%E5%BD%95%E5%9C%B0%E5%9D%80-%E6%8A%96%E9%9F%B3%E6%91%84%E5%BD%B1.md
https://github.com/constiang-s/xzjjce/commit/55d316cf208c573f8e84da81ca68a690d6b37c70?/932=372
https://github.com/constiang-s/xzjjce/commit/55d316cf208c573f8e84da81ca68a690d6b37c70?/332=710
https://github.com/constiang-s/xzjjce/commit/55d316cf208c573f8e84da81ca68a690d6b37c70?/503=943
https://github.com/constiang-s/xzjjce/commit/55d316cf208c573f8e84da81ca68a690d6b37c70?/154=055
https://github.com/constiang-s/xzjjce/commit/55d316cf208c573f8e84da81ca68a690d6b37c70?/885=111
https://github.com/constiang-s/xzjjce/commit/55d316cf208c573f8e84da81ca68a690d6b37c70
https://github.com/constiang-s/xzjjce/blob/main/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/275=220
https://github.com/constiang-s/xzjjce/blob/main/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/965=942
https://github.com/constiang-s/xzjjce/blob/main/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/943=776
https://github.com/constiang-s/xzjjce/blob/main/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/092=669
https://github.com/constiang-s/xzjjce/blob/main/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md?/103=987
https://github.com/constiang-s/xzjjce/blob/main/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97%3A%E8%A5%BF%E6%B5%B7%E5%B2%B8%E5%9B%BD%E9%99%85%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E7%99%BB%E5%BD%95%E6%B3%A8%E5%86%8C-%E8%B5%9B%E8%BD%A6%E8%AE%A1%E5%88%92.md
https://github.com/kulkaye/xiinuu/commit/02de52203999e45aefbfb01679a63056c3d27f06?/825=019
https://github.com/kulkaye/xiinuu/commit/02de52203999e45aefbfb01679a63056c3d27f06?/725=040
https://github.com/kulkaye/xiinuu/commit/02de52203999e45aefbfb01679a63056c3d27f06?/809=506
https://github.com/kulkaye/xiinuu/commit/02de52203999e45aefbfb01679a63056c3d27f06?/420=658
https://github.com/kulkaye/xiinuu/commit/02de52203999e45aefbfb01679a63056c3d27f06?/612=267
https://github.com/kulkaye/xiinuu/commit/02de52203999e45aefbfb01679a63056c3d27f06
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F.md?/630=729
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F.md?/754=508
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F.md?/481=714
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F.md?/716=508
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F.md?/903=218
https://github.com/kulkaye/xiinuu/blob/main/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7-%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F.md
https://github.com/danielfachka/zyfplc/commit/e021e4bae3287d1399f5f34e41a043793f0242a3?/059=609
https://github.com/danielfachka/zyfplc/commit/e021e4bae3287d1399f5f34e41a043793f0242a3?/714=267
https://github.com/danielfachka/zyfplc/commit/e021e4bae3287d1399f5f34e41a043793f0242a3?/558=669
https://github.com/danielfachka/zyfplc/commit/e021e4bae3287d1399f5f34e41a043793f0242a3?/558=832
https://github.com/danielfachka/zyfplc/commit/e021e4bae3287d1399f5f34e41a043793f0242a3?/164=821
https://github.com/danielfachka/zyfplc/commit/e021e4bae3287d1399f5f34e41a043793f0242a3
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F.md?/209=654
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F.md?/836=058
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F.md?/942=932
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F.md?/410=165
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F.md?/236=387
https://github.com/danielfachka/zyfplc/blob/main/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E6%B3%A8%E5%86%8C%E5%B9%B3%E5%8F%B0%E5%BC%80%E6%88%B7-%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F.md
https://github.com/enognagu/lpvade/commit/c44f5949e362e4ca839de853c993a09bdf295323?/664=225
https://github.com/enognagu/lpvade/commit/c44f5949e362e4ca839de853c993a09bdf295323?/803=440
https://github.com/enognagu/lpvade/commit/c44f5949e362e4ca839de853c993a09bdf295323?/223=507
https://github.com/enognagu/lpvade/commit/c44f5949e362e4ca839de853c993a09bdf295323?/954=263
https://github.com/enognagu/lpvade/commit/c44f5949e362e4ca839de853c993a09bdf295323?/714=865
https://github.com/enognagu/lpvade/commit/c44f5949e362e4ca839de853c993a09bdf295323
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%A7%86%E7%95%8C.md?/654=521
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%A7%86%E7%95%8C.md?/376=274
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%A7%86%E7%95%8C.md?/932=720
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%A7%86%E7%95%8C.md?/674=554
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%A7%86%E7%95%8C.md?/268=598
https://github.com/enognagu/lpvade/blob/main/2027%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E6%80%BB%E4%BB%A3-%E5%95%86%E4%B8%9A%E8%A7%86%E7%95%8C.md
https://github.com/schowffer/nmghjj/commit/830c0be4de52ad56b74d80a00afd3f02cb2960d0?/942=481
https://github.com/schowffer/nmghjj/commit/830c0be4de52ad56b74d80a00afd3f02cb2960d0?/716=154
https://github.com/schowffer/nmghjj/commit/830c0be4de52ad56b74d80a00afd3f02cb2960d0?/487=269
https://github.com/schowffer/nmghjj/commit/830c0be4de52ad56b74d80a00afd3f02cb2960d0?/043=926
https://github.com/schowffer/nmghjj/commit/830c0be4de52ad56b74d80a00afd3f02cb2960d0?/070=932
https://github.com/schowffer/nmghjj/commit/830c0be4de52ad56b74d80a00afd3f02cb2960d0
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F.md?/867=262
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F.md?/716=074
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F.md?/697=983
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F.md?/287=170
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F.md?/875=508
https://github.com/schowffer/nmghjj/blob/main/2027%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%80%81%E6%9D%BF-%E5%85%AC%E7%9B%8A%E8%B4%A2%E7%BB%8F.md
https://github.com/ptushub/nohkiu/commit/53b884513960ac29b442258cfa20d0b029612815?/710=332
https://github.com/ptushub/nohkiu/commit/53b884513960ac29b442258cfa20d0b029612815?/676=774
https://github.com/ptushub/nohkiu/commit/53b884513960ac29b442258cfa20d0b029612815?/228=487
https://github.com/ptushub/nohkiu/commit/53b884513960ac29b442258cfa20d0b029612815?/781=554
https://github.com/ptushub/nohkiu/commit/53b884513960ac29b442258cfa20d0b029612815?/009=669
https://github.com/ptushub/nohkiu/commit/53b884513960ac29b442258cfa20d0b029612815
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/047=265
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/053=557
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/421=054
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/609=330
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F.md?/370=203
https://github.com/ptushub/nohkiu/blob/main/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E8%B4%9F%E8%B4%A3%E4%BA%BA-%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F.md
https://github.com/sourux23/eufvji/commit/a20e096f68146bcf8e08ca16214f3d4745574a08?/335=487
https://github.com/sourux23/eufvji/commit/a20e096f68146bcf8e08ca16214f3d4745574a08?/275=998
https://github.com/sourux23/eufvji/commit/a20e096f68146bcf8e08ca16214f3d4745574a08?/444=265
https://github.com/sourux23/eufvji/commit/a20e096f68146bcf8e08ca16214f3d4745574a08?/114=964
https://github.com/sourux23/eufvji/commit/a20e096f68146bcf8e08ca16214f3d4745574a08?/786=741
https://github.com/sourux23/eufvji/commit/a20e096f68146bcf8e08ca16214f3d4745574a08
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/832=465
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/271=325
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/234=710
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/721=793
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md?/103=714
https://github.com/sourux23/eufvji/blob/main/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%A8%B1%E4%B9%90%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C-%E8%8D%A3%E8%80%80%E8%B4%A2%E7%BB%8F.md
https://github.com/ryukaura/kityhe/commit/1d8ff7ffc94700d947582d4fb51a0cd255499bfe?/597=453
https://github.com/ryukaura/kityhe/commit/1d8ff7ffc94700d947582d4fb51a0cd255499bfe?/374=551
https://github.com/ryukaura/kityhe/commit/1d8ff7ffc94700d947582d4fb51a0cd255499bfe?/047=481
https://github.com/ryukaura/kityhe/commit/1d8ff7ffc94700d947582d4fb51a0cd255499bfe?/697=114
https://github.com/ryukaura/kityhe/commit/1d8ff7ffc94700d947582d4fb51a0cd255499bfe?/619=497
https://github.com/ryukaura/kityhe/commit/1d8ff7ffc94700d947582d4fb51a0cd255499bfe
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%B5%84%E6%9C%AC%E5%B8%82%E5%9C%BA.md?/109=619
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%B5%84%E6%9C%AC%E5%B8%82%E5%9C%BA.md?/376=569
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%B5%84%E6%9C%AC%E5%B8%82%E5%9C%BA.md?/609=058
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%B5%84%E6%9C%AC%E5%B8%82%E5%9C%BA.md?/481=647
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%B5%84%E6%9C%AC%E5%B8%82%E5%9C%BA.md?/425=475
https://github.com/ryukaura/kityhe/blob/main/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%80%BB%E4%BB%A3-%E8%B5%84%E6%9C%AC%E5%B8%82%E5%9C%BA.md
https://github.com/e44nf/nkliyn/commit/2035fe55648771f28ceb35471537769c1e7ddd27?/932=503
https://github.com/e44nf/nkliyn/commit/2035fe55648771f28ceb35471537769c1e7ddd27?/592=598
https://github.com/e44nf/nkliyn/commit/2035fe55648771f28ceb35471537769c1e7ddd27?/558=376
https://github.com/e44nf/nkliyn/commit/2035fe55648771f28ceb35471537769c1e7ddd27?/487=431
https://github.com/e44nf/nkliyn/commit/2035fe55648771f28ceb35471537769c1e7ddd27?/181=618
https://github.com/e44nf/nkliyn/commit/2035fe55648771f28ceb35471537769c1e7ddd27
https://github.com/e44nf/nkliyn/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E8%B5%9B%E9%A9%AC%E8%B5%84%E8%AE%AF.md?/609=591
https://github.com/e44nf/nkliyn/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E8%B5%9B%E9%A9%AC%E8%B5%84%E8%AE%AF.md?/992=796
https://github.com/e44nf/nkliyn/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E8%B5%9B%E9%A9%AC%E8%B5%84%E8%AE%AF.md?/376=966
https://github.com/e44nf/nkliyn/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E8%B5%9B%E9%A9%AC%E8%B5%84%E8%AE%AF.md?/941=276
https://github.com/e44nf/nkliyn/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E8%B5%9B%E9%A9%AC%E8%B5%84%E8%AE%AF.md?/303=270
https://github.com/e44nf/nkliyn/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E7%BA%B5%E6%A8%AA%E5%9B%BD%E9%99%85%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1%E6%8B%9B%E5%95%86-%E8%B5%9B%E9%A9%AC%E8%B5%84%E8%AE%AF.md
https://github.com/kulkaye/xiinuu/commit/0017752861a84cae74723e10a0daa632a25dd230?/762=821
https://github.com/kulkaye/xiinuu/commit/0017752861a84cae74723e10a0daa632a25dd230?/381=612
https://github.com/kulkaye/xiinuu/commit/0017752861a84cae74723e10a0daa632a25dd230?/163=342
https://github.com/kulkaye/xiinuu/commit/0017752861a84cae74723e10a0daa632a25dd230?/054=487
