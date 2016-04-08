---
layout: page
title: جکیل
permalink: /jekyll/
---
<body style="direction:rtl">
<div class="container clearfix">
                 
                  <div class="content">
<article class="post">
	<header>
	  <h1>چرا تصمیم گرفتم از Jekyll استفاده کنم</h1>
	</header>
    <div class="meta clearfix">
  <div class="clearfix"><div><i class="icon-user"></i><span class="author">جواد سالاری</span> &nbsp;&nbsp;</div><div><i class="icon-clock"></i><span class="date">پنجشنبه 20/1/1395</span></div></div>
</div>
	<div class="post-content">
	  
<p><a href="http://jekyllrb.com/">Jekyll</a> یک نرم افزار سایت ساز است که تمامی صفحات شما را به شکل استاتیک ایجاد می‌کند. ساختاری بسیار ساده دارد و شما برای نوشتن پست هیچ احتیاجی به ادیتور خاص و یا لاگین کردن در صفحه ای خاص ندارید. تنها کاری که باید انجام بدهید این است که متن خود را با فرمت <a href="http://daringfireball.net/projects/markdown/">markdown</a> داخل یک فایل با پسوند md یا markdown ذخیره کنید و آن را در پوشه  _post قرار دهید. Jekyll این پوشه را شناسایی کرده و محتوای داخل آن را می‌شناسد و پستی را برای شما با استفاده از همان فایل ایجاد می‌کند. </p>

<p>با استفاده از Jekyll چند مشکل برای من برطرف شد. اول اینکه دیگر نیازی به هوست ندارم و با صرف هزینه ثبت یک دومین ir و اتصال آن به صفحات گیت از طریق سرویس های مدیریت DNS رایگان مثل <a href="http://namecheap.com/">namecheap.com</a> می‌توانم تمامی فایل‌های استاتیک خود را با هر حجمی روی سرورهای گیت‌ هاب قرار دهم. سرورهای گیت هاب سرعت فوق‌العاده‌ای دارند و مطمئنا از هر server ای که شما در ایران در اختیار دارید٬ سریعتر و مطمئن‌تراند. دوم اینکه قالب جکیل کاملا HTML و CSS و JS است و شما برای ساخت بلاگ حتی یک خط کدنویسی server-side انجام نمی‌دهید. البته می‌دانم که وردپرس CMS بسیار مناسب و راحتی است و زحمت ترجمه و پشیبانی‌اش را نیز دوستان به دوش می‌کشند ولی واقعا برای اغلب بلاگ‌های موجود وردپرس بیش از حد قوی و بزرگ است. در حال حاضر بلاگ‌هایی داریم که بعد از ۵ سال فعالیت٬ مجموع پست‌هایشان به ۵۰۰ پست نرسیده. واقعا این بلاگ‌ها اینقدر بزرگ نیستند که بخواهند از سیستمی مثل وردپرس استفاده کنند و خیلی راحت می‌شود از سیستم‌های ساده تر برای راه‌اندازیشان استفاده کرد. بلاگ من هم از این دست بلاگ‌های کم پست محسوب می‌شود. به همین خاطر جکیل را انتخاب کردم. </p>

<p>مزایای جکیل این موارد است:</p>

<ol>
  <li>سرعت بالاتر به خاطر استاتیک بودن صفحات</li>
  <li>ساختار ساده تر </li>
  <li>راه اندازی ساده تر برای کسانی که به HTML و CSS تسلط دارند.</li>
  <li>امنیت بیشتر به خاطر دارا نبودن بخش back-end و نبود دیتابیس</li>
</ol>

<p>البته معایبی هم دارد:</p>

<ol>
  <li>از دست دادن تمامی قابلیت‌هایی که از طریق پردازش server-side ممکن بود مثل بخش کامنت و فرم تماس و قابلیت جستجو در سایت</li>
  <li>جدید بودن و در دسترس نبودن پلاگین های فراوان مثل وردپرس</li>
  <li>سخت بودن برای کسانی که به HTML, CSS مسلط نیستند.</li>
</ol>

<p>برخی از معایب را می‌توان برطرف کرد. مثلا برای بخش کامنت می‌توان از سرویس‌های جانبی مثل <a href="https://disqus.com/">DISQUS</a> استفاده کرد که من هم از همین سرویس استفاده کردم. برای فرم تماس هم سرویس‌های بسیاری وجود دارد از جمله <a href="http://www.wufoo.com/">WuFoo</a>, <a href="http://www.123contactform.com/">123contactform</a> و یا <a href="http://www.jotform.com/">jotform</a> که هم به شما این اجازه را می‌دهند که یک فرم تماس را در صفحات استاتیک خود بگنجانید. مورد آخر که مربوط به search است را نیز می‌توان به شیوه‌های مختلف حل کرد. اول اینکه با داشتن sitemap و به کمک گوگل این شانس وجود دارد که مطالب شما خیلی زود index شده و در گوگل قابل جستجو باشد. به نظرم استفاده از <a href="https://www.google.com/cse/">Google Custom Search</a> کفایت می‌کند ولی می‌توان از سرویس‌های دیگر نیز استفاده کرد از جمله <a href="http://tapirgo.com/">Tapir</a> که آدرس feed شما را گرفته و مطالب شما را برایتان در server خودش index می‌کند و شما از طریق یک API می‌توانید به سرچ دسترسی داشته باشید. ابزارهای دیگری نیز وجود دارد که مطالب شما را بر روی همان سیستم local شما با فرمت JSON برایتان index می‌کند و شما عملا یک دیتابیس لوکال از نوع JSON خواهید داشت که حاوی همه مطالب سایت شماست. در هر صورت برای شروع کار حجم مطالب بلاگ اینقدر زیاد نیست که اصلا احتیاجی به جستجو داشته باشد. </p>

<p>حال سوالی که پیش می‌آید این است که وردپرس بهتر است یا جکیل؟
سوال نابجایی است :) هر کدام از این ابزارها برای هدفی خاص ایجاد شده‌اند. همه چیز بستگی به شرایط دارد. اگر قصد راه‌اندازی سایتی را دارید که افراد مختلفی باید بر روی آن مطلب بنویسند٬ امکانات ویژه نیاز دارید و کسانی که مطلب را می‌نویسند افراد فنی و با‌تجربه نیستند٬ قطعا وردپرس بهترین انتخاب است. ولی اگر قصد دارید که بلاگ کوچکی داشته باشید و یا برای پروژه‌ای که روی آن کار می‌کنید٬ مستندات تهیه می‌کنید  و قصد دارید مطالب را بر روی گیت هاب قرار دهید به نظرم جکیل گزینه مناسبی می‌آید. </p>

<p>اگرفرصتی شد درباره نصب جکیل بر روی ویندوز و استفاده ساده از آن در آینده می‌نویسم.</p>

	</div>
	<footer class="post-footer">
      
      
    </footer>
    
    
    <script type="text/javascript">
        /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
        var disqus_shortname = 'Front-end'; // required: replace example with your forum shortname

        /* * * DON'T EDIT BELOW THIS LINE * * */
        (function() {
            var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
            dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
            (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
        })();
    </script>
    <noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
    
    
</article>
</div>                       
            
                <aside class="sidebar">
<a href="#" class="sidebar-close"><i class="icon-cancel"></i></a>
     <section class="widget monthly-archive">
          
</aside>
                   
            </div>
<div class="page-content">
      <div class="wrapper">
        <div itemscope="" itemtype="http://schema.org/Article" class="post">

  <header class="post-header">
    <h1 itemprop="name" class="post-title">آموزش نصب jekyll بر روی ویندوز (قسمت اول)</h1>
    <p class="post-meta">
    <svg height="16px" style="enable-background:new 0 0 32 32;" viewBox="0 0 32 32" width="16px"><g></g><g><g><path d="M16,4c6.617,0,12,5.383,12,12s-5.383,12-12,12S4,22.617,4,16S9.383,4,16,4 M16,0    C7.164,0,0,7.164,0,16s7.164,16,16,16s16-7.164,16-16S24.836,0,16,0L16,0z" style="fill:#BBBBBB;"></path><path d="M21.422,18.578L18,15.152V8h-4.023v7.992c0,0.602,0.277,1.121,0.695,1.492l3.922,3.922    L21.422,18.578z" style="fill:#AAAAAA;"></path></g></g></svg> 
    <span itemprop="datePublished" content="2014-09-30 21:00:00 +0000">پنجشنبه 20/1/1395</span> &nbsp;&nbsp;&nbsp;
	
          <svg height="16px" viewBox="0 0 32 32" width="16px"><title></title><desc></desc><defs></defs><g fill="none" fill-rule="evenodd" stroke="none" stroke-width="1"><g fill="#929292"><path d="M17,11 L15,7 L4.00276013,7 C2.89666625,7 2,7.88967395 2,8.991155 L2,27.008845 C2,28.1085295 2.89971268,29 3.99328744,29 L29.0067126,29 C30.1075748,29 31,28.1073772 31,27.0049107 L31,12.9950893 C31,11.8932319 30.1029399,11 28.9941413,11 L17,11 Z"></path></g></g></svg> tutorial
        
    </p>
  </header>

  <article itemprop="articleBody" class="post-content">
    <div class="container centeralized">
</div>
<p>اینجا قصد دارم یه توضیح و آموزشی در مورد jekyll داشته باشم.امیدوارم که از این برنامه و آموزش اون در اینجا خوشتون بیاد.
یکی از مشکلاتی که jekyll داره و شاید اکثر برنامه های این شکلی دارن اینه که تو ویندوز به درستی کار نمی کنن. در واقع این برنامه ها برای سیستم عامل لینوکس ساخته میشن.
اما همیشه راه ها یا هک هایی وجود داره که میشه این مشکلات رو رفع کرد.</p>


<p>یکی از این هک ها تو وبسایت <a href="http://jekyll-windows.juthilo.com/">jekyll-windows.juthilo.com</a> معرفی شده که من خودم از این روش استفاده می کنم ولی باز هم مشکلاتی داشت که در اینجا روشهای حل اون رو توضیح میدم.
در کل اگه با <a href="http://jekyllrb.com">jekyll</a> آشنایی ندارین می تونین پست «<a href="http://front-end.ir/webdesign/why-i-have-chosen-jekyll/">چرا تصمیم گرفتم از Jekyll استفاده کنم</a>» رو که امیرعباس زحمتش رو کشیده مطالعه کنید. من خودم از طریق همین پست با jekyll آشنا شدم.</p>

<p>مزیت مهمی که jekyll داره اینه که می تونین از هاست <a href="http://github.com">github</a> به صورت رایگان برای وبسایت یا وبلاگتون استفاده کنین و تنها با خرید یک دامنه یک وبسایت کامل راه اندازی کنین. این آموزش به سه دسته تقسیم میشه:</p>
<h1>نصب jekyll</h1>
<p>همونطور که تو وبسایت <a href="http://jekyll-windows.juthilo.com/">jekyll-windows.juthilo.com</a> توضیح داده شده اول از همه نیازه که <a href="http://rubyinstaller.org/downloads/">Ruby</a> رو نصب کنیم. با مراجعه به <a href="http://rubyinstaller.org/downloads/">صفحه دانلود ruby</a> نسخه مناسب با کامپیوترمون رو دانلود می کنیم و اونرو نصب می کنیم. توجه کنید که تو مراحل نصب حتما گزینه Add ruby executables to your PATH رو مثل شکل زیر تیک زده باشید. این گزینه باعث میشه از هرجایی به دستورات ruby دسترسی داشته باشیم. البته اگه این گزینه رو تیک نزده باشید می تونین این کار رو دستی انجام بدید.(<a href="https://www.google.com/#q=how+to+add+executables+to+path+in+windows">جستجو کنید</a>)</p>

<div class="container centeralized">
	<img src="../img/ruby-path.png" alt="Ruby Installation" width="513" height="399">
</div>

<p>بعد از نصب Ruby نوبت به نصب Ruby DevKit میرسه که از همون آدرس قبلی قابل دسترسی هست. برای نصب ابتدا محتویات فایل zip رو درون یک پوشه (ترجیحا در root یکی از درایورها) که اسمش بدون فاصله و حروف خاص باشه قرار می دیم. بطور مثال <span class="inline-code">C:\RubyDevKit</span> مکان مناسبی برای نصب Ruby DevKit است. پس از قرار دادن فایلها نوبت به اجرای اونها میرسه. کدهای زیر رو برای نصب DevKit توی command prompt ویندوز وارد می کنیم. دقت کنید که باید توی مسیر همین پوشه ایجاد شده باشیم تا بتونیم محتویاتش رو نصب کنیم.</p>

<div class="highlight"><pre><code class="language-ruby" data-lang="ruby"><span class="ss">C</span><span class="p">:\</span><span class="no">RubyDevKit</span><span class="o">&gt;</span> <span class="n">chcp</span> <span class="mi">1252</span>
<span class="ss">C</span><span class="p">:\</span><span class="no">RubyDevKit</span><span class="o">&gt;</span> <span class="n">ruby</span> <span class="n">dk</span><span class="o">.</span><span class="n">rb</span> <span class="n">init</span>
<span class="ss">C</span><span class="p">:\</span><span class="no">RubyDevKit</span><span class="o">&gt;</span> <span class="n">ruby</span> <span class="n">dk</span><span class="o">.</span><span class="n">rb</span> <span class="n">install</span></code></pre></div>

<p>بعد از اینکه نصب ruby و ruby DevKit تموم شد نوبت به نصب jekyll میرسه. برای نصب jekyll کدهای زیر رو توی command prompt ویندوز وارد کنید.</p>

<div class="highlight"><pre><code class="language-ruby" data-lang="ruby"><span class="n">gem</span> <span class="n">install</span> <span class="n">jekyll</span></code></pre></div>

<p>یکی از مشکلات یا ناسازگاری های jekyll با ویندوز عدم هماهنگی افزونه highlight اون هست که برای حل اون جایگزینی وجود داره. افزونه پیش فرض jekyll برای highlight کردن کدهای درون صفحات، افزونه pygments هست که توی ویندوز اجرا نمیشه و هر دفعه که شما کد رو اجرا کنید پیام خطا میده. برای رفع مشکل highlight از افزونه rouge که با ویندوز سازگاری داره استفاده می کنیم. برای نصب این افزونه کد زیر رو توی command prompt ویندوز وارد کنید.</p>

<div class="highlight"><pre><code class="language-ruby" data-lang="ruby"><span class="n">gem</span> <span class="n">install</span> <span class="n">rouge</span></code></pre></div>

<p>در نهایت هم برای اضافه کردن قابلیت watch (مشاهده تغییرات در آن واحد) به jekyll کد زیر رو وارد می کنیم تا افزونه مورد نظر نصب بشه.</p>

<div class="highlight"><pre><code class="language-ruby" data-lang="ruby"><span class="n">gem</span> <span class="n">install</span> <span class="n">wdm</span></code></pre></div>

<p>حالا برنامه ما به طور کامل نصب شده و ما می تونیم ازش استفاده کنیم. بطور مثال کدهای زیر یک وبسایت demo در شاخه <span class="inline-code">D:\</span> میسازه و بعد اون رو برای مشاهده روی آدرس <span class="inline-code">http://localhost:4000</span> قابل دسترس می کنه.</p>

<div class="highlight"><pre><code class="language-ruby" data-lang="ruby"><span class="n">jekyll</span> <span class="kp">new</span> <span class="n">demo</span>
<span class="n">cd</span> <span class="n">demo</span>
<span class="n">jekyll</span> <span class="n">serve</span> <span class="o">-</span><span class="n">w</span></code></pre></div>

<p>اگر در مرحله سوم با اجرای کد <span class="inline-code">jekyll serve -w</span> با مشکل برخوردید باید تنظیمات برنامه رو تغییر بدین. به مسیر <span class="inline-code">D:\demo</span> رفته و فایل <span class="inline-code">_config.yml</span> رو با notepad باز کنید. در این فایل تنظیمات وبسایت demo ذخیره شده. به آخر فایل خط زیر رو اضافه کنید که نشون میده ما میخوایم از rouge استفاده کنیم.</p>

<div class="highlight"><pre><code class="language-html" data-lang="html">highlighter: rouge</code></pre></div>

<p>jekyll تنظیمات بسیار زیادی داره که می تونید تموم اونها رو توی وبسایت رسمی <a href="http://jekyllrb.com">jekyll</a> مشاهده کنید. تو قسمت documentation این سایت تمام ساختار jekyll به سادگی توضیح داده شده که می تونید از اونها استفاده کنید.</p>

<p>در پست بعدی قصد دارم در مورد اتصال github و jekyll بنویسم. خوشحال میشم نظرتون رو در مورد این پست بدونم.</p>

<ul><h3>نکات مهم</h3>
<li>jekyll از زبان نشانه گذاری yaml برای پست ها استفاده می کنه. استفاده از این زبان خیلی خیلی ساده هست و شما فقط کافیه از مثال ها برای یادگیری اون استفاده کنید.</li>
<li>ساختار پوشه ها کاملا مشخصه ولی نکته ای که این وسط مهمه اینه که وبسایت کامل شده و ترجمه شده نهاییتون در پوشه _site ذخیره میشه.</li>
<li>زمانی که از کد <span class="inline-code">jekyll serve -w</span> استفاده می کنید. برنامه در حالت اجرا میمونه و به تغییراتتون توجه می کنه تا اون رو سریع ترجمه کنه و خروجی رو روی پورت 4000 بهتون نشون بده. تنها تغییراتی که به صورت آنی اعمال نمیشه، تغییراتی هست که روی فایل <span class="inline-code">_config.yml</span> انجام می دین. برای اعمال این تغییرات کافیه jekyll رو متوقف کنید و بعد دوباره اون رو اجرا کنید.</li>
</ul>


  </article>

   
    <script type="text/javascript">
        /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
        var disqus_shortname = 'iakrami'; // required: replace example with your forum shortname

        /* * * DON'T EDIT BELOW THIS LINE * * */
        (function() {
            var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
            dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
            (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
        })();
    </script>
    <noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
    

</div>

      </div>
    </div>
	<div class="page-content">
      <div class="wrapper">
        <div itemscope="" itemtype="http://schema.org/Article" class="post">

  <header class="post-header">
    <h1 itemprop="name" class="post-title">آموزش نصب jekyll بر روی ویندوز (قسمت دوم)</h1>
    <p class="post-meta">
    <svg height="16px" style="enable-background:new 0 0 32 32;" viewBox="0 0 32 32" width="16px"><g></g><g><g><path d="M16,4c6.617,0,12,5.383,12,12s-5.383,12-12,12S4,22.617,4,16S9.383,4,16,4 M16,0    C7.164,0,0,7.164,0,16s7.164,16,16,16s16-7.164,16-16S24.836,0,16,0L16,0z" style="fill:#BBBBBB;"></path><path d="M21.422,18.578L18,15.152V8h-4.023v7.992c0,0.602,0.277,1.121,0.695,1.492l3.922,3.922    L21.422,18.578z" style="fill:#AAAAAA;"></path></g></g></svg> 
    <span itemprop="datePublished" content="2014-10-04 11:00:00 +0000"> پنجشنبه 20/1/1395</span> &nbsp;&nbsp;&nbsp;
	
          <svg height="16px" viewBox="0 0 32 32" width="16px"><title></title><desc></desc><defs></defs><g fill="none" fill-rule="evenodd" stroke="none" stroke-width="1"><g fill="#929292"><path d="M17,11 L15,7 L4.00276013,7 C2.89666625,7 2,7.88967395 2,8.991155 L2,27.008845 C2,28.1085295 2.89971268,29 3.99328744,29 L29.0067126,29 C30.1075748,29 31,28.1073772 31,27.0049107 L31,12.9950893 C31,11.8932319 30.1029399,11 28.9941413,11 L17,11 Z"></path></g></g></svg> tutorial
        
    </p>
  </header>

  <article itemprop="articleBody" class="post-content">
    <div class="container centeralized">
	
</div>
<p>در قسمت دوم آموزش نصب jekyll، نحوه اتصال این برنامه به یک صفحه github و طریقه پیکربندی اون رو توضیح خواهم داد. در اینجا نکته ای که بسیار اهمیت داره نحوه پیکربندی برنامه تو ویندوز هست.
چون اجرای jekyll روی ویندوز با تنظیمات پیش فرض github به دلیل ناسازگاری افزونه هایی مثل pygments پیغام خطا میده.</p>


<h1>ایجاد حساب github</h1>
<p>بعد از ثبت نام در وبسایت <a href="http://github.com">github</a>، در منو بالا New Repository رو انتخاب کرده و یک <a href="http://git-scm.com/book/en/Getting-Started-Git-Basics">مخزن</a> ایجاد کنید. در قسمت نام مخزن، عبارت <span class="inline-code">username.github.io</span> رو وارد کنید (بجای username نام کاربری خودتون رو بنویسید). ما بقی تنظیمات را در حالت پیش فرض قرار دهید.</p>

<p>سپس با استفاده از نرم افزار github در ویندوز از مخزن خود clone بگیرید و اونو تو یک فولدر بریزید <a href="https://help.github.com/articles/adding-repositories-with-github-for-windows/">(آموزش)</a>.</p>

<p>خب حالا نوبت به jekyll میرسه. در اینجا باید یک وبسایت جدید با jekyll تو همون مسیر ایجاد کنید. به طور مثال اگه مسیر مخزن شما <span class="inline-code">C:\username.github.io</span> باشه کد زیر رو وارد می کنید.</p>

<div class="highlight"><pre><code class="language-ruby" data-lang="ruby"><span class="n">jekyll</span> <span class="kp">new</span> <span class="ss">C</span><span class="p">:\</span><span class="n">username</span><span class="o">.</span><span class="n">github</span><span class="o">.</span><span class="n">io</span></code></pre></div>

<p>تنظیمات مربوط به وبسایتتون که شامل نام و توضیحات و … میشه رو تو فایل <span class="inline-code">_config.yml</span> وارد کنید. بعد از تغییر دادن محتویات این فایل اون رو تو همین مسیر با نام جدید مثلا <span class="inline-code">win_config.yml</span> کپی کنید. تو فایل جدید کد زیر رو به انتهای فایل اضافه کنید.</p>

<div class="highlight"><pre><code class="language-text" data-lang="text">highlight: rouge</code></pre></div>

<p>دلیل ایجاد این فایل و اضافه کردن این خط اینه که می خوایم برنامه تو ویندوز با فایل تنظیمات دوم اجرا بشه تا مشکلی برای اون پیش نیاد ولی موقع آپلود و قرار گرفتن روی سرور فایل اصلی اجرا بشه.</p>

<p>اگر دقت کنید یک فایل با نام <span class="inline-code">.gitignore</span> توی مسیر اصلی مخزنتون وجود داره. اونرو باز کنید و اسم فایل دوم رو بهش اضافه کنید. این فایل مشخص می کنه که چه فولدرها و فایلهایی از کامپیوترتون به سرور آپلود نشه. احتمالا فولدر <span class="inline-code">_site</span> قبلا به این فایل اضافه شده.</p>

<p>بعد از اینکه تموم این تنظیمات رو انجام دادید می تونید با jekyll وبسایت خودتون رو بسازید و اونرو بعد از هر بار commit کردن تو آدرس username.github.io ببینید.</p>

<ul><h3>نکات مهم</h3>
<li>تنظیمات زیر در github بعد از هر بار اجرا بازنویسی می شن و شما نمی تونین این تنظیمات رو به هیچ شکلی عوض کنید:

<div class="highlight"><pre><code class="language-text" data-lang="text">highlighter: pygments
safe: true
lsi: false
github: [Repository metadata]</code></pre></div>

</li>
<li>تنظیم source رو به هیچ وجه دستکاری نکنید.</li>
<li>چون jekyll در github به صورت safe بالا میاد پس هیچ افزونه اضافی رو برای jekyll نمی تونید اضافه کنید.</li>
<li>لیست تنظیمات jekyll در <a href="http://jekyllrb.com/docs/configuration/">این صفحه</a> موجود است.</li>
</ul>

<p>در پست بعد اتصال دامنه به github رو آموزش خواهم داد. لطفا نظرات و سوالاتتون رو در مورد این پست در قسمت نظرات عنوان کنید.</p>


  </article>


   
    <script type="text/javascript">
        /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
        var disqus_shortname = 'iakrami'; // required: replace example with your forum shortname

        /* * * DON'T EDIT BELOW THIS LINE * * */
        (function() {
            var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
            dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
            (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
        })();
    </script>
    <noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
    

</div>

      </div>
    </div>
<body/>