<template>
  <div class="_gp-ck"><section class="ouvJEz"><h1 class="_1RuRku">Markdown——入门指南</h1><div class="rEsl9f"><div class="_2mYfmT"><a class="_1qp91i _1OhGeD" href="/u/ea86ff9520da" target="_blank" rel="noopener noreferrer"><img class="_13D2Eh" src="https://upload.jianshu.io/users/upload_avatars/25820/3a1f8c37f8ad?imageMogr2/auto-orient/strip|imageView2/1/w/96/h/96/format/webp" alt=""></a><div style="margin-left: 8px;"><div class="_3U4Smb"><span class="FxYr8x"><a class="_1OhGeD" href="/u/ea86ff9520da" target="_blank" rel="noopener noreferrer">Te_Lee</a></span><button data-locale="zh-CN" type="button" class="_3kba3h _1OyPqC _3Mi9q9 _34692-"><span>关注</span></button></div><div class="s-dsoj"><span class="_3tCVn5"><i aria-label="ic-diamond" class="anticon"><svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class=""><use xlink:href="#ic-diamond"></use></svg></i><span>39</span></span><time datetime="2014-04-17T13:14:56.000Z">2014.04.17 21:14:56</time><span>字数 2,270</span><span>阅读 1,165,579</span></div></div></div></div><article class="_2rhmJa"><p><strong>转载请注明原作者，如果你觉得这篇文章对你有帮助或启发，也可以来请我<a href="https://link.jianshu.com?t=http://ww2.sinaimg.cn/large/6aee7dbbjw1eiixgkex2ij21kw0t7wn5.jpg" target="_blank" rel="nofollow">喝咖啡</a>。</strong></p>
    <h4>导语：</h4>
    <h2>一，认识 Markdown</h2>
    <p>在刚才的导语里提到，Markdown 是一种用来写作的轻量级<strong>「标记语言」</strong>，它用简洁的语法代替排版，而不像一般我们用的字处理软件 <em>Word</em> 或 <em>Pages</em> 有大量的排版、字体设置。它使我们专心于码字，用「标记」语法，来代替常见的排版格式。例如此文从内容到格式，甚至插图，键盘就可以通通搞定了。目前来看，支持 Markdown 语法的编辑器有很多，包括很多网站（例如<a href="https://www.jianshu.com" target="_blank">简书</a>）也支持了 Markdown 的文字录入。Markdown 从写作到完成，导出格式随心所欲，你可以导出 HTML 格式的文件用来网站发布，也可以十分方便的导出 PDF 格式，这种格式写出的简历更能得到 HR 的好感。甚至可以利用 <a href="https://link.jianshu.com?t=http://www.getcloudapp.com" target="_blank" rel="nofollow">CloudApp</a> 这种云服务工具直接上传至网页用来分享你的文章，全球最大的轻博客平台 <a href="https://link.jianshu.com?t=http://te1ee.tumblr.com" target="_blank" rel="nofollow">Tumblr</a>，也支持 Mou 这类 Markdown 工具的直接上传。</p>
    <h3>Markdown 官方文档</h3>
    <blockquote>
      <p>这里可以看到官方的 Markdown 语法规则文档，当然，<strong>后文我也会用自己的方式阐述这些语法的具体用法</strong>。</p>
    </blockquote>
    <ul>
      <li><a href="https://link.jianshu.com?t=http://daringfireball.net/projects/markdown/syntax" target="_blank" rel="nofollow"><em>创始人 John Gruber 的 Markdown 语法说明</em></a></li>
      <li><a href="https://link.jianshu.com?t=http://wowubuntu.com/markdown/#list" target="_blank" rel="nofollow"><em>Markdown 中文版语法说明</em></a></li>
    </ul>
    <h3>使用 Markdown 的优点</h3>
    <ul>
      <li>专注你的文字内容而不是排版样式，安心写作。</li>
      <li>轻松的导出 HTML、PDF 和本身的 .md 文件。</li>
      <li>纯文本内容，兼容所有的文本编辑器与字处理软件。</li>
      <li>随时修改你的文章版本，不必像字处理软件生成若干文件版本导致混乱。</li>
      <li>可读、直观、学习成本低。</li>
    </ul>
    <h3>使用 Markdown 的误区</h3>
    <blockquote>
      <p>*We believe that writing is about content, about what you want to say – not about fancy formatting. *</p>
    </blockquote>
    <p>我们坚信写作写的是内容，所思所想，而不是花样格式。<br>
      — <em>Ulysses for Mac</em></p>
    <ul>
      <li>Markdown 旨在简洁、高效，也由于 Markdown 的易读易写，人们用不同的编程语言实现了多个版本的解析器和生成器，这就导致了目前不同的 Markdown 工具集成了不同的功能（基础功能大致相同），例如流程图与时序图，复杂表格与复杂公式的呈现，虽然功能的丰富并没有什么本质的缺点，但终归有些背离初衷，何况在编写的过程中很费神，不如使用专业的工具撰写来的更有效率，所以如果你需实现复杂功能，专业的图形界面工具会更加方便。<strong>当然，如果你对折腾这些不同客户端对 Markdown 的定制所带来高阶功能感到愉悦的话，那也是无可厚非的。</strong>
      </li>
    </ul>
    <div class="image-package">
      <img src="http://ww2.sinaimg.cn/large/6aee7dbbgw1eq320claw3j21kw0kjdpc.jpg" data-original-src="http://ww2.sinaimg.cn/large/6aee7dbbgw1eq320claw3j21kw0kjdpc.jpg" alt="[flowchart.js on Github（使用 Markdown 绘制流程图）](https://github.com/adrai/flowchart.js)" data-image-index="1" style="cursor: zoom-in;"><div class="image-caption">[flowchart.js on Github（使用 Markdown 绘制流程图）](https://github.com/adrai/flowchart.js)</div>
    </div>
    <h3>我该用什么工具？</h3>
    <div class="image-package">
      <img src="http://ww2.sinaimg.cn/large/6aee7dbbgw1esvkj19bqmj20e80e874z.jpg" data-original-src="http://ww2.sinaimg.cn/large/6aee7dbbgw1esvkj19bqmj20e80e874z.jpg" alt="Mou for Mac" data-image-index="2" style="cursor: zoom-in;"><div class="image-caption">Mou for Mac</div>
    </div>
    <ul>
      <li>在 Mac OS X 上，我强烈建议你用 <a href="https://link.jianshu.com?t=http://mouapp.com" target="_blank" rel="nofollow">Mou</a> 这款免费且十分好用的 Markdown 编辑器，它支持<strong>实时预览</strong>，既左边是你编辑 Markdown 语言，右边会实时的生成预览效果。不仅如此，Mou 还有一些有趣的偏好设置（<em>Preference</em>），例如主题（<em>Themes</em>）与样式（<em>CSS</em>），它们可以配置出定制化的文本编辑效果与导出效果，如果你对自带的主题与样式不满意还可以到 <a href="https://link.jianshu.com?t=https://github.com/search?utf8=%E2%9C%93&amp;q=Mou" target="_blank" rel="nofollow">GitHub</a> 上搜索其它爱好者为 Mou 编写的更多主题样式，导入的方式可以在偏好设置的 Themes 或 CSS 选项中 选择 reload。</li>
    </ul>
    <div class="image-package">
      <img src="http://ww1.sinaimg.cn/large/6aee7dbbgw1effcq2gx92j210j0ustj7.jpg" data-original-src="http://ww1.sinaimg.cn/large/6aee7dbbgw1effcq2gx92j210j0ustj7.jpg" alt="Mou 的编写与预览窗口" data-image-index="3" style="cursor: zoom-in;"><div class="image-caption">Mou 的编写与预览窗口</div>
    </div>
    <p>如果你从事文字工作，我强烈建议你购买 <em><a href="https://link.jianshu.com?t=http://www.ulyssesapp.com" target="_blank" rel="nofollow">Ulysses for Mac</a></em>，这款软件入围了苹果 Mac App Store 的 <em>The Best of 2013</em>。它支持更多的写作格式、多文档的支持。Mou，iA writer 这些软件都是基于单文档的管理方式，而 Ulysses 支持 Folder、Filter 的管理，一个 Folder 里面可以创建多个 Sheet，Sheet 之间也可以进行 Combine 处理。</p>
    <div class="image-package">
      <img src="http://ww1.sinaimg.cn/large/6aee7dbbjw1eqgrj7suqoj217a0aiq4u.jpg" data-original-src="http://ww1.sinaimg.cn/large/6aee7dbbjw1eqgrj7suqoj217a0aiq4u.jpg" alt="Mac 上一些 Markdown 编辑器" data-image-index="4" style="cursor: zoom-in;"><div class="image-caption">Mac 上一些 Markdown 编辑器</div>
    </div>
    <ul>
      <li><p>由于笔者很少接触 Windows，Windows 下的 Markdown 没有过多涉猎，经朋友介绍，有两款还算不错，一款叫做 <a href="https://link.jianshu.com?t=http://www.markdownpad.com" target="_blank" rel="nofollow">MarkdownPad</a> ，另一款叫做 <a href="https://link.jianshu.com?t=http://code52.org/DownmarkerWPF/" target="_blank" rel="nofollow">MarkPad</a>。</p></li>
      <li><p>iOS 端很多 app 早已经支持了 Markdown 录入，例如 Drafts，Day One，iA writer 等，另外 Ulysses for iPad 现在已经上架，可以说是 iOS 平台最好的编辑器了。</p></li>
      <li><p>在 Web端，我强烈推荐<a href="https://www.jianshu.com" target="_blank">简书</a>这款产品，上面有无数热爱文字的人在不停的创造，分享。在 Web 端使用 Markdown 没有比简书更舒服的地方了，同样支持左右两栏的实时预览，字体优雅，简洁。</p></li>
    </ul>
    <div class="image-package">
      <img src="http://ww2.sinaimg.cn/large/6aee7dbbgw1effdkfijo1j21220nigth.jpg" data-original-src="http://ww2.sinaimg.cn/large/6aee7dbbgw1effdkfijo1j21220nigth.jpg" alt="简书的编辑预览模式" data-image-index="5" style="cursor: zoom-in;"><div class="image-caption">简书的编辑预览模式</div>
    </div>
    <h2>二，Markdown 语法的简要规则</h2>
    <h3>标题</h3>
    <div class="image-package">
      <img src="http://ww1.sinaimg.cn/large/6aee7dbbgw1effeaclhiyj20eh09cwez.jpg" data-original-src="http://ww1.sinaimg.cn/large/6aee7dbbgw1effeaclhiyj20eh09cwez.jpg" alt="标题" data-image-index="6" style="cursor: zoom-in;"><div class="image-caption">标题</div>
    </div>
    <p>标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 <code>#</code> 号即可。</p>
    <p><code># 一级标题</code></p>
    <p><code>## 二级标题</code></p>
    <p><code>### 三级标题</code></p>
    <p>以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。</p>
    <h3>列表</h3>
    <p>熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 <code>-</code> 或 <code>*</code> 即可变为无序列表，有序列表则直接在文字前加<code>1.</code> <code>2.</code> <code>3.</code> 符号要和文字之间加上一个字符的空格。</p>
    <div class="image-package">
      <img src="http://ww4.sinaimg.cn/large/6aee7dbbgw1effew5aftij20d80bz3yw.jpg" data-original-src="http://ww4.sinaimg.cn/large/6aee7dbbgw1effew5aftij20d80bz3yw.jpg" alt="无序列表与有序列表" data-image-index="7" style="cursor: zoom-in;"><div class="image-caption">无序列表与有序列表</div>
    </div>
    <h3>引用</h3>
    <p>如果你需要引用一小段别处的句子，那么就要用引用的格式。</p>
    <blockquote>
      <p>例如这样</p>
    </blockquote>
    <p>只需要在文本前加入 <code>&gt;</code> 这种尖括号（大于号）即可</p>
    <div class="image-package">
      <img src="http://ww3.sinaimg.cn/large/6aee7dbbgw1effezhonxlj20e009c3yu.jpg" data-original-src="http://ww3.sinaimg.cn/large/6aee7dbbgw1effezhonxlj20e009c3yu.jpg" alt="引用" data-image-index="8" style="cursor: zoom-in;"><div class="image-caption">引用</div>
    </div>
    <h3>图片与链接</h3>
    <p>插入链接与插入图片的语法很像，区别在一个 <code>!</code>号</p>
    <p>图片为：<code>![]()</code></p>
    <p>链接为：<code>[]()</code></p>
    <p>插入图片的地址需要图床，这里推荐<a href="https://link.jianshu.com?t=http://weibotuchuang.sinaapp.com" target="_blank" rel="nofollow">围脖图床修复计划</a> 与 <a href="https://link.jianshu.com?t=http://www.getcloudapp.com" target="_blank" rel="nofollow">CloudApp</a> 的服务，生成URL地址即可。</p>
    <div class="image-package">
      <img src="http://ww2.sinaimg.cn/large/6aee7dbbgw1efffa67voyj20ix0ctq3n.jpg" data-original-src="http://ww2.sinaimg.cn/large/6aee7dbbgw1efffa67voyj20ix0ctq3n.jpg" alt="URL 与图片" data-image-index="9" style="cursor: zoom-in;"><div class="image-caption">URL 与图片</div>
    </div>
    <h3>粗体与斜体</h3>
    <p>Markdown 的粗体和斜体也非常简单，用两个 <code>*</code> 包含一段文本就是粗体的语法，用一个 <code>*</code> 包含一段文本就是斜体的语法。</p>
    <p>例如：<strong>这里是粗体</strong> <em>这里是斜体</em></p>
    <h3>表格</h3>
    <p>表格是我觉得 Markdown 比较累人的地方，例子如下：</p>
    <div class="_2Uzcx_"><button class="VJbwyy" type="button" aria-label="复制代码"><i aria-label="icon: copy" class="anticon anticon-copy"><svg viewBox="64 64 896 896" focusable="false" class="" data-icon="copy" width="1em" height="1em" fill="currentColor" aria-hidden="true"><path d="M832 64H296c-4.4 0-8 3.6-8 8v56c0 4.4 3.6 8 8 8h496v688c0 4.4 3.6 8 8 8h56c4.4 0 8-3.6 8-8V96c0-17.7-14.3-32-32-32zM704 192H192c-17.7 0-32 14.3-32 32v530.7c0 8.5 3.4 16.6 9.4 22.6l173.3 173.3c2.2 2.2 4.7 4 7.4 5.5v1.9h4.2c3.5 1.3 7.2 2 11 2H704c17.7 0 32-14.3 32-32V224c0-17.7-14.3-32-32-32zM350 856.2L263.9 770H350v86.2zM664 888H414V746c0-22.1-17.9-40-40-40H232V264h432v624z"></path></svg></i></button><pre class="line-numbers  language-ruby"><code class="  language-ruby"><span class="token operator">|</span> <span class="token constant">Tables</span>        <span class="token operator">|</span> <span class="token constant">Are</span>           <span class="token operator">|</span> <span class="token constant">Cool</span>  <span class="token operator">|</span>
<span class="token operator">|</span> <span class="token operator">--</span><span class="token operator">--</span><span class="token operator">--</span><span class="token operator">--</span><span class="token operator">--</span><span class="token operator">--</span><span class="token operator">-</span> <span class="token operator">|</span><span class="token punctuation">:</span><span class="token operator">--</span><span class="token operator">--</span><span class="token operator">--</span><span class="token operator">--</span><span class="token operator">--</span><span class="token operator">--</span><span class="token operator">-</span><span class="token punctuation">:</span><span class="token operator">|</span> <span class="token operator">--</span><span class="token operator">--</span><span class="token operator">-</span><span class="token punctuation">:</span><span class="token operator">|</span>
<span class="token operator">|</span> col <span class="token number">3</span> is      <span class="token operator">|</span> right<span class="token operator">-</span>aligned <span class="token operator">|</span> $<span class="token number">1600</span> <span class="token operator">|</span>
<span class="token operator">|</span> col <span class="token number">2</span> is      <span class="token operator">|</span> centered      <span class="token operator">|</span>   $<span class="token number">12</span> <span class="token operator">|</span>
<span class="token operator">|</span> zebra stripes <span class="token operator">|</span> are neat      <span class="token operator">|</span>    $<span class="token number">1</span> <span class="token operator">|</span>
<span aria-hidden="true" class="line-numbers-rows"><span></span><span></span><span></span><span></span><span></span></span></code></pre></div>
    <p>这种语法生成的表格如下：</p>
    <table>
      <thead>
      <tr>
        <th>Tables</th>
        <th style="text-align:center">Are</th>
        <th style="text-align:right">Cool</th>
      </tr>
      </thead>
      <tbody>
      <tr>
        <td>col 3 is</td>
        <td style="text-align:center">right-aligned</td>
        <td style="text-align:right">$1600</td>
      </tr>
      <tr>
        <td>col 2 is</td>
        <td style="text-align:center">centered</td>
        <td style="text-align:right">$12</td>
      </tr>
      <tr>
        <td>zebra stripes</td>
        <td style="text-align:center">are neat</td>
        <td style="text-align:right">$1</td>
      </tr>
      </tbody>
    </table>
    <h3>代码框</h3>
    <p>如果你是个程序猿，需要在文章里优雅的引用代码框，在 Markdown下实现也非常简单，只需要用两个 ` 把中间的代码包裹起来。图例：</p>
    <div class="image-package">
      <img src="http://ww3.sinaimg.cn/large/6aee7dbbgw1effg1lsa97j20lt0a8dgs.jpg" data-original-src="http://ww3.sinaimg.cn/large/6aee7dbbgw1effg1lsa97j20lt0a8dgs.jpg" data-image-index="10" style="cursor: zoom-in;"><div class="image-caption"></div>
    </div>
    <p>使用 <code>tab</code> 键即可缩进。</p>
    <h3>分割线</h3>
    <p>分割线的语法只需要三个 <code>*</code> 号，例如：</p>
    <hr>
    <blockquote>
      <p>到这里，Markdown 的基本语法在日常的使用中基本就没什么大问题了，只要多加练习，配合好用的工具，写起东西来肯定会行云流水。更多的语法规则，其实 Mou 的 Help 文档栗子很好，当你第一次使用 Mou 时，就会显示该文档。可以用来对用的查找和学习。</p>
    </blockquote>
    <div class="image-package">
      <img src="http://ww3.sinaimg.cn/large/6aee7dbbgw1effgmnpgqlj210j0us44j.jpg" data-original-src="http://ww3.sinaimg.cn/large/6aee7dbbgw1effgmnpgqlj210j0us44j.jpg" data-image-index="11" style="cursor: zoom-in;"><div class="image-caption"></div>
    </div>
    <h2>
      <strong>三，相关推荐</strong>:</h2>
    <h3><strong>工具</strong></h3>
    <p><em>图床工具用来上传图片获取 URL 地址</em></p>
    <ul>
      <li><a href="https://link.jianshu.com?t=http://droplr.com" target="_blank" rel="nofollow">Droplr</a></li>
      <li><a href="https://link.jianshu.com?t=http://www.getcloudapp.com" target="_blank" rel="nofollow">Cloudapp</a></li>
      <li><a href="https://link.jianshu.com?t=https://itunes.apple.com/cn/app/yi-xiang/id672522335?mt=12&amp;uo=4" target="_blank" rel="nofollow">ezShare for Mac</a></li>
      <li><a href="https://link.jianshu.com?t=http://weibotuchuang.sinaapp.com" target="_blank" rel="nofollow">围脖图床修复计划</a></li>
    </ul>
    <p><em>在线好用的Markdown工具，为印象笔记而生</em></p>
    <ul>
      <li><a href="https://link.jianshu.com?t=http://maxiang.info" target="_blank" rel="nofollow">马克飞象，专为印象笔记打造的Markdown编辑器，非常推荐</a></li>
    </ul>
    <h3>
      <strong>相关文章阅读</strong>：</h3>
    <ul>
      <li><p><a href="https://www.jianshu.com/p/qqgjln" target="_blank">为什么作家应该用 Markdown 保存自己的文稿</a></p></li>
      <li><p><a href="https://link.jianshu.com?t=http://www.yangzhiping.com/tech/r-markdown-knitr.html" target="_blank" rel="nofollow">Markdown写作浅谈</a></p></li>
      <li><p><a href="https://link.jianshu.com?t=http://www.appinn.com/markdown-tools/" target="_blank" rel="nofollow">Markdown 工具补完</a></p></li>
      <li><p><a href="https://www.jianshu.com/p/63HYZ6" target="_blank">Drafts + Scriptogr.am + Dropbox 打造移动端 Markdown 风格博客</a></p></li>
      <li><p><a href="https://link.jianshu.com?t=http://www.ituring.com.cn/article/23" target="_blank" rel="nofollow">图灵社区，怎样使用Markdown</a></p></li>
      <li><p><a href="https://link.jianshu.com?t=http://news.cnblogs.com/n/139649/" target="_blank" rel="nofollow">为什么我们要学习Markdown的三个理由</a></p></li>
      <li><p><a href="https://link.jianshu.com?t=http://ibuick.me/?p=4093" target="_blank" rel="nofollow">Markdown 语法写作入门指南 by ibuick</a></p></li>
    </ul>
    <hr>
    <p><strong>本文首发在<a href="https://link.jianshu.com?t=http://sspai.com/25137" target="_blank" rel="nofollow">少数派</a>转载请注明原作者，如果你觉得这篇文章对你有帮助或启发，也可以来请我<a href="https://link.jianshu.com?t=http://ww2.sinaimg.cn/large/6aee7dbbjw1eiixgkex2ij21kw0t7wn5.jpg" target="_blank" rel="nofollow">喝咖啡</a>。<br>
      利益相关：本篇文章所有涉及到的软件均为笔者日常所用工具，无任何广告费用。</strong></p>
  </article><div></div><div class="_1kCBjS"><div class="_18vaTa"><div class="_3BUZPB"><div class="_2Bo4Th" role="button" tabindex="-1" aria-label="给文章点赞"><i aria-label="ic-like" class="anticon"><svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class=""><use xlink:href="#ic-like"></use></svg></i></div><span class="_1LOh_5" role="button" tabindex="-1" aria-label="查看点赞列表">3828人点赞<i aria-label="icon: right" class="anticon anticon-right"><svg viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em" height="1em" fill="currentColor" aria-hidden="true"><path d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z"></path></svg></i></span></div><div class="_3BUZPB"><div class="_2Bo4Th" role="button" tabindex="-1"><i aria-label="ic-dislike" class="anticon"><svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class=""><use xlink:href="#ic-dislike"></use></svg></i></div></div></div><div class="_18vaTa"><a class="_3BUZPB _1x1ok9 _1OhGeD" href="/nb/66924" target="_blank" rel="noopener noreferrer"><i aria-label="ic-notebook" class="anticon"><svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class=""><use xlink:href="#ic-notebook"></use></svg></i><span>我不是Geek</span></a><div class="_3BUZPB ant-dropdown-trigger"><div class="_2Bo4Th"><i aria-label="ic-others" class="anticon"><svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class=""><use xlink:href="#ic-others"></use></svg></i></div></div></div></div><div class="_19DgIp" style="margin-top:24px;margin-bottom:24px"></div><div class="_13lIbp"><div class="_16AzcO">更多精彩内容下载简书APP</div><div class="_6S_NkV"><canvas height="137" width="137" style="height: 110px; width: 110px;"></canvas></div><div class="_191KSt">"小礼物走一走，来简书关注我"</div><button type="button" class="_1OyPqC _3Mi9q9 _2WY0RL _1YbC5u"><span>赞赏支持</span></button><div class="_1Segjj"><a class="H4XBOO"><img src="https://cdn2.jianshu.io/assets/default_avatar/alipay-c192a7455bcf21ab8dd23d96679fc1c0.png" alt="  "></a><a class="H4XBOO _1OhGeD" href="/u/bc605076f528" target="_blank" rel="noopener noreferrer"><img src="https://upload.jianshu.io/users/upload_avatars/1511171/afc3530f-eb83-4660-860e-b39865a27f48.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt="  "></a><a class="H4XBOO"><img src="https://cdn2.jianshu.io/assets/default_avatar/wechat-771371d5741b0c32cd805caeb48ad6c0.png" alt="  "></a><a class="H4XBOO _1OhGeD" href="/u/747f3c48b178" target="_blank" rel="noopener noreferrer"><img src="https://cdn2.jianshu.io/assets/default_avatar/10-e691107df16746d4a9f3fe9496fd1848.jpg" alt="  "></a><a class="H4XBOO _1OhGeD" href="/u/a814fb1e19b1" target="_blank" rel="noopener noreferrer"><img src="https://upload.jianshu.io/users/upload_avatars/4033280/acdbeb4bb448?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt="  "></a><a class="H4XBOO"><img src="https://cdn2.jianshu.io/assets/default_avatar/alipay-c192a7455bcf21ab8dd23d96679fc1c0.png" alt="  "></a><a class="H4XBOO _14FSyQ" role="button" tabindex="-1" aria-label="查看赞赏列表"><i aria-label="ic-others" class="anticon"><svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class=""><use xlink:href="#ic-others"></use></svg></i></a><span class="yZLjoN" role="button" tabindex="-1" aria-label="查看赞赏人列表">共10人赞赏</span></div></div><div class="d0hShY"><a class="_1bPVBH _1OhGeD" href="/u/ea86ff9520da" target="_blank" rel="noopener noreferrer"><img class="_27NmgV" src="https://upload.jianshu.io/users/upload_avatars/25820/3a1f8c37f8ad?imageMogr2/auto-orient/strip|imageView2/1/w/100/h/100/format/webp" alt="  "></a><div class="Uz-vZq"><div class="Cqpr1X"><a class="HC3FFO _1OhGeD" href="/u/ea86ff9520da" title="Te_Lee" target="_blank" rel="noopener noreferrer">Te_Lee</a><span class="_2WEj6j" title="Twitter：@Te_1ee">Twitter：@Te_1ee</span></div><div class="lJvI3S"><span>总资产29 (约2.15元)</span><span>共写了1.6W字</span><span>获得4,266个赞</span><span>共2,069个粉丝</span></div></div><button data-locale="zh-CN" type="button" class="_1OyPqC _3Mi9q9"><span>关注</span></button></div></section><div id="note-page-comment"><div class="lazyload-placeholder"></div></div><section class="ouvJEz"><h3 class="QxT4hD"><span>被以下专题收入，发现更多相似内容</span></h3><div class="_2Nttfz"><a class="_3s5t0Q _1OhGeD" href="/c/cbdcd85c55d9" target="_blank" rel="noopener noreferrer"><img class="_2vEwGY" src="https://upload.jianshu.io/collections/images/1899445/1594788749.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_2-Djqu">源码空间</span></a><a class="_3s5t0Q _1OhGeD" href="/c/9b80a182f33c" target="_blank" rel="noopener noreferrer"><img class="_2vEwGY" src="https://upload.jianshu.io/collections/images/652205/M1M.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_2-Djqu">收藏小屋</span></a><a class="_3s5t0Q _1OhGeD" href="/c/cd4acd12cf27" target="_blank" rel="noopener noreferrer"><img class="_2vEwGY" src="https://upload.jianshu.io/collections/images/1847935/crop1578035880538.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_2-Djqu">vscode</span></a><a class="_3s5t0Q _1OhGeD" href="/c/3ee3a24a0711" target="_blank" rel="noopener noreferrer"><img class="_2vEwGY" src="https://upload.jianshu.io/collections/images/1839526/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20191023142036.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_2-Djqu">别动我的代码</span></a><a class="_3s5t0Q _1OhGeD" href="/c/a8c31ddcc6fb" target="_blank" rel="noopener noreferrer"><img class="_2vEwGY" src="https://upload.jianshu.io/collections/images/1829345/1572174494.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_2-Djqu">mac技巧</span></a><a class="_3s5t0Q _1OhGeD" href="/c/681bfa967e0a" target="_blank" rel="noopener noreferrer"><img class="_2vEwGY" src="https://upload.jianshu.io/collections/images/1667860/crop1538113584651.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_2-Djqu">实用干货</span></a><a class="_3s5t0Q _1OhGeD" href="/c/614849b2a5ad" target="_blank" rel="noopener noreferrer"><img class="_2vEwGY" src="https://upload.jianshu.io/collections/images/306528/QQ20161129-0.png?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_2-Djqu">程序员技术栈</span></a><div class="H7E3vT" role="button" tabindex="-1" aria-label="展开更多"><span>展开更多</span><i aria-label="icon: down" class="anticon anticon-down"><svg viewBox="64 64 896 896" focusable="false" class="" data-icon="down" width="1em" height="1em" fill="currentColor" aria-hidden="true"><path d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z"></path></svg></i></div></div><div class="_19DgIp" style="margin-top: 32px; margin-bottom: 32px;"></div><h3 class="QxT4hD"><span>推荐阅读</span><a class="_29KFEa _1OhGeD" href="/" target="_blank" rel="noopener noreferrer">更多精彩内容<i aria-label="ic-right" class="anticon"><svg width="1em" height="1em" fill="currentColor" aria-hidden="true" focusable="false" class=""><use xlink:href="#ic-right"></use></svg></i></a></h3><ul class="_1iTR78"><li class="_11jppn"><div class="JB6qEE"><div class="em6wEs" title="Markdown——入门指南" role="heading" aria-level="4"><a class="_2voXH8 _1OhGeD" href="/p/4b116aa04bba" target="_blank" rel="noopener noreferrer">Markdown——入门指南</a></div><div class="_3fvgn4">原作者：http://www.jianshu.com/p/1e402922ee32/ 导语： Markdown 是...</div><div class="_1pJt6F"><a class="_3IWz1q _1OhGeD" href="/u/6b92e52b11bf" target="_blank" rel="noopener noreferrer"><img class="_34VC_H" src="https://upload.jianshu.io/users/upload_avatars/2166772/71f55697-d6ba-44a2-a9f3-d1804c1d3596.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_3tPsL6">代码移动工程师</span></a><span class="_31hjBO">阅读<!-- --> <!-- -->738</span><span class="_31hjBO">评论<!-- --> <!-- -->0</span><span class="_31hjBO">赞<!-- --> <!-- -->3</span></div></div></li><li class="_11jppn"><div class="JB6qEE"><div class="em6wEs" title="Markdown——入门指南" role="heading" aria-level="4"><a class="_2voXH8 _1OhGeD" href="/p/b7117f772803" target="_blank" rel="noopener noreferrer">Markdown——入门指南</a></div><div class="_3fvgn4">导语： Markdown是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。看...</div><div class="_1pJt6F"><a class="_3IWz1q _1OhGeD" href="/u/2f8d6296255c" target="_blank" rel="noopener noreferrer"><img class="_34VC_H" src="https://upload.jianshu.io/users/upload_avatars/2183835/095be07ca2cb.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_3tPsL6">福哥_</span></a><span class="_31hjBO">阅读<!-- --> <!-- -->450</span><span class="_31hjBO">评论<!-- --> <!-- -->0</span><span class="_31hjBO">赞<!-- --> <!-- -->5</span></div></div><a class="_10MMAm _1OhGeD" href="/p/b7117f772803" target="_blank" rel="noopener noreferrer"><img class="_3zGDUj" src="//upload-images.jianshu.io/upload_images/2183835-7e2786e4d1b3d85b.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/300/h/240/format/webp" alt=""></a></li><li class="_11jppn"><div class="JB6qEE"><div class="em6wEs" title="【今日学点】Markdown——入门指南" role="heading" aria-level="4"><a class="_2voXH8 _1OhGeD" href="/p/ba896f306665" target="_blank" rel="noopener noreferrer">【今日学点】Markdown——入门指南</a></div><div class="_3fvgn4">导语：Markdown 是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。看...</div><div class="_1pJt6F"><a class="_3IWz1q _1OhGeD" href="/u/94c4895a43fe" target="_blank" rel="noopener noreferrer"><img class="_34VC_H" src="https://upload.jianshu.io/users/upload_avatars/48106/40d26941-f89e-4950-9b7a-68149e169796.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_3tPsL6">学习那点事</span></a><span class="_31hjBO">阅读<!-- --> <!-- -->1,827</span><span class="_31hjBO">评论<!-- --> <!-- -->1</span><span class="_31hjBO">赞<!-- --> <!-- -->9</span></div></div></li><li class="_11jppn"><div class="JB6qEE"><div class="em6wEs" title="Markdown——入门指南" role="heading" aria-level="4"><a class="_2voXH8 _1OhGeD" href="/p/8ce57433e6b5" target="_blank" rel="noopener noreferrer">Markdown——入门指南</a></div><div class="_3fvgn4">导语： Markdown 是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。...</div><div class="_1pJt6F"><a class="_3IWz1q _1OhGeD" href="/u/a1a4cee875b3" target="_blank" rel="noopener noreferrer"><img class="_34VC_H" src="https://upload.jianshu.io/users/upload_avatars/4347053/b4cf64f0-1367-499c-a188-c9e79b4765fe.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_3tPsL6">葛朋1990</span></a><span class="_31hjBO">阅读<!-- --> <!-- -->249</span><span class="_31hjBO">评论<!-- --> <!-- -->0</span><span class="_31hjBO">赞<!-- --> <!-- -->0</span></div></div><a class="_10MMAm _1OhGeD" href="/p/8ce57433e6b5" target="_blank" rel="noopener noreferrer"><img class="_3zGDUj" src="//upload-images.jianshu.io/upload_images/4347053-2b3d65466edea5bd.jpg?imageMogr2/auto-orient/strip|imageView2/1/w/300/h/240/format/webp" alt=""></a></li><li class="_11jppn"><div class="JB6qEE"><div class="em6wEs" title="对爸爸妈妈说爱他（她）" role="heading" aria-level="4"><a class="_2voXH8 _1OhGeD" href="/p/a26c5ed455d7" target="_blank" rel="noopener noreferrer">对爸爸妈妈说爱他（她）</a></div><div class="_3fvgn4">楼下出远门的女人回来了，她的小女儿几乎是小跑上去“妈妈，妈妈，我好想你呀，你终于回来了！” 好像很久很久以前，我也...</div><div class="_1pJt6F"><a class="_3IWz1q _1OhGeD" href="/u/e4099cd8febd" target="_blank" rel="noopener noreferrer"><img class="_34VC_H" src="https://upload.jianshu.io/users/upload_avatars/596474/f741e814ca58.jpeg?imageMogr2/auto-orient/strip|imageView2/1/w/48/h/48/format/webp" alt=""><span class="_3tPsL6">六月的雨_Cyy</span></a><span class="_31hjBO">阅读<!-- --> <!-- -->122</span><span class="_31hjBO">评论<!-- --> <!-- -->0</span><span class="_31hjBO">赞<!-- --> <!-- -->0</span></div></div></li></ul></section></div>

</template>

<script>
  export default {
    name: "TestArticle"
  }
</script>

<style scoped>

</style>