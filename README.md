
<!DOCTYPE html>
<html>
<head>
<title>潇洒桐庐</title>
<link href="{dede:global.cfg_templets_skin/}/css/bootstrap.css" rel="stylesheet" type="text/css" media="all" />
<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
<script src="{dede:global.cfg_templets_skin/}/js/jquery.min.js"></script>
<!-- Custom Theme files -->
<!--theme-style-->
<link href="{dede:global.cfg_templets_skin/}/css/style.css" rel="stylesheet" type="text/css" media="all" />	
<!--//theme-style-->
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="keywords" content="Furniture Home Responsive web template, Bootstrap Web Templates, Flat Web Templates, Andriod Compatible web template, 
Smartphone Compatible web template, free webdesigns for Nokia, Samsung, LG, SonyErricsson, Motorola web design" />
<script type="application/x-javascript"> addEventListener("load", function() { setTimeout(hideURLbar, 0); }, false); function hideURLbar(){ window.scrollTo(0,1); } </script>
<!--fonts-->
<link href='http://fonts.useso.com/css?family=Droid+Serif:400,700' rel='stylesheet' type='text/css'>
<link href='http://fonts.useso.com/css?family=Arimo:400,700' rel='stylesheet' type='text/css'>
<!--//fonts-->
  <script src="{dede:global.cfg_templets_skin/}/js/responsiveslides.min.js"></script>
<script>
    // You can also use "$(window).load(function() {"
    $(function () {
      // Slideshow 1
      $("#slider1").responsiveSlides({
         auto: true,
		 nav: true,
		 speed: 500,
		 namespace: "callbacks",
      });
    });
  </script>
</head>
<body> 
<!--header-->
<div class="header">
<div class="slider">
	    <ul class="rslides" id="slider1">
	      <li><img src="{dede:global.cfg_templets_skin/}/images/banner1.jpg" alt=""></li>
	      <li><img src="{dede:global.cfg_templets_skin/}/images/banner.jpg" alt=""></li>
	      <li><img src="{dede:global.cfg_templets_skin/}/images/banner2.jpg" alt=""></li>
	    </ul>
    </div>
<!---->
{dede:include filename="head.html"/}
<div class="content">
<!---->
<div class="container">
	<div class="top-grid-top">
		<div class="top-grids">				
		
			<div class="col-md-4 top-grid">
				<h3>荻浦村</h3>
				<a href="a/tongluxiangcun/"><img class="img-responsive" src="{dede:global.cfg_templets_skin/}/images/pi.jpg" title="name" alt=""></a>
				<a href="a/tongluxiangcun/" class="read">进入</a>
			</div>
			<div class="col-md-4 top-grid">
				<h3>环溪村</h3>
				<a href="a/tongluxiangcun/"><img class="img-responsive" src="{dede:global.cfg_templets_skin/}/images/pi1.jpg" title="name" alt="" ></a>
				<a href="a/tongluxiangcun/" class="read">进入</a>
			</div>
			<div class="col-md-4 top-grid" >
				<h3>钟山乡</h3>
				<a href="a/tongluxiangcun/"><img class="img-responsive" src="{dede:global.cfg_templets_skin/}/images/pi2.jpg" title="name" alt="" ></a>
				<a href="a/tongluxiangcun/" class="read">进入</a>
			</div>
			<div class="clearfix"> </div>
		</div>
	</div>
	<!---->
    <div class="copyrights">Collect from <a href="http://www.mycodes.net/" target="_blank">源码之家</a></div>
		<div class="middle-grid">
			<div class="col-md-4 grid-middle">
				<h3>关于桐庐</h3>
				<span>桐庐县，镶嵌在浙西北的翡翠，撒落在富春江畔的一颗璀璨明珠！</span>
				<p class="sed">桐庐自225年置县，至今已有1770余年历史。境内总面积1825平方公里，辖7个镇、4个乡、2个街道，人口40万，隶属杭州市管辖，是国务院批准的对外开放县。桐庐系多山丘陵地区，属亚热带季风气候，冬暖夏凉，四季分明，自然景观多姿多彩。</p>
				<p>桐庐历来是文人雅士邀游吟诗之地。自南北朝至清代，曾有一千位名贤高蹈之士，在这里留下了脍炙人口的名著佳作。桐庐的山山水水，已与历史、文化、传说融为一体。春秋战国时，桐庐先属吴、越，后属楚，秦始皇时，今富阳、桐庐。建德均为富春县。三国吴孙权黄武四年(225年)，富春县分出相溪乡置桐庐县，属吴郡。这是桐庐建县之始。 </p>
				<p>桐庐历史悠久、人文荟萃，素有“钟灵毓秀之地、潇洒文明之邦”的美誉。北宋名臣范仲淹感慨于这片土地的奇山异水，赞之为“潇洒桐庐”，并写下了传世名篇《潇洒桐庐郡·十咏》。</p>
			
				<a href="{dede:global.cfg_templets_skin/}/video/video3.mp4">
				<img class="img-responsive" src="{dede:global.cfg_templets_skin/}/images/视频图.jpg" title="name" alt="" ></a>
				<a  href="a/xueyuangaikuang/" class="more">更多故事</a>
			</div>
			<div class="col-md-4 grid-middle">
				<h3>桐庐新闻</h3>
				<p>立足桐庐，依托桐庐、结合桐庐时事，让世界了解桐庐、让桐庐走进世界，权威新闻、快捷新闻、精彩新闻。快速了解、分享、评论桐庐本地发生的新鲜事、桐庐新闻。</p>
				<p>快速了解、分享、评论桐庐本地发生的新鲜事、桐庐新闻。</p>
				<ul>
					{dede:arclist row=7 titlelen=32 typeid='5'}
                    <li>
                        <a href="[field:arcurl/]">&nbsp;&nbsp;&nbsp;&nbsp;[field:title/]</a>
                        <span class="datetime">[field:pubdate function="GetDateMK(@me)"/]</span>
                    </li>
                    {/dede:arclist}
					
				</ul>
				<a  href="a/xiaoyuanxinwen/" class="more">更多资讯</a>
			</div>
			<div class="col-md-4 grid-middle">
				<h3>特色村落</h3>
				<p>桐庐县现辖4个街道、6个镇、4个乡（其中1个民族乡）：旧县街道、桐君街道、城南街道、凤川街道、富春江镇、横村镇、分水镇、瑶琳镇、百江镇、江南镇、莪山畲族乡、钟山乡、新合乡、合村乡。县政府驻城南街道迎春南路298号。</p>
				<div class="latest-grid">
					<div class="news">
						<a href="a/tongluxiangcun/"><img class="img-responsive" src="{dede:global.cfg_templets_skin/}/images/ne.jpg" title="name" alt="" ></a>
					</div>
					<div class="news-in">
						<b>梅蓉村</b>
						<p>梅蓉村，属桐庐县桐君街道，原名梅洲，又名九里洲，坐落于富春江北岸，南起富春江中的放马洲，北依刺山、虎山、乌龟山至水面山，东连窄溪，西接横弓里，与濮家庄毗连。面积12.7平方公里，至2014年有村民3245人。</p>
					</div>
					<div class="clearfix"> </div>
				</div>
				<div class="latest-grid">
					<div class="news">
						<a href="a/tongluxiangcun/"><img class="img-responsive" src="{dede:global.cfg_templets_skin/}/images/ne1.jpg" title="name" alt="" ></a>
					</div>
					<div class="news-in">
						<b>芦茨慢生活</b>
						<p>芦茨“土屋”是一个承载着梦想的民宿，田园露台、中式靠椅、地中海风情餐厅、铺满细沙的庭院、全景阳光房……“土屋”是一栋典型的乡间别墅，每间客房都有着自己独有的调调，住哪间？就看你钟情哪里了。</p>
					</div>
					<div class="clearfix"> </div>
				</div>
				<div class="latest-grid">
					<div class="news">
						<a href="a/tongluxiangcun/"><img class="img-responsive" src="{dede:global.cfg_templets_skin/}/images/ne2.jpg" title="name" alt="" ></a>
					</div>
					<div class="news-in">
						<b>悦延居、白云源景区</b>
						<p>大片落地玻璃，阳光洒落一地的是数不尽的惬意和慵懒，折射着书架上、原木长椅靠垫上的点点光晕……不上山，不入林，便已将水墨远山，奇幻云海尽收于心。</p>
					</div>
					<div class="clearfix"> </div>
				</div>
				<a href="a/wanzhuantonglu/" class="more">走进村落</a>
			</div>
					<div class="clearfix"> </div>
		</div>
		<!---->
		<div class="bottom-grid">
			<h3>桐庐景区</h3>
			<div class="col-md-4 bottom-grids">
				<a href="a/wanzhuantonglu/"><img class="img-responsive" src="{dede:global.cfg_templets_skin/}/images/vi.jpg" title="name" alt="" ></a>
				<p>红灯笼外婆家，由外婆家、小木屋、灵鸡寺、农业观光园等四部分组成，总面积约2平方公里。地处天目溪畔，距桐庐县城25公里，离中国旅游胜地四十佳瑶琳仙境3公里。背负青山，面临碧水，是一处独具田园风光和乡村情趣的休闲度假旅游区。 风景名胜红灯笼外婆家自然风光旖旎独特，有怪石嶙峋的象鼻山，有芳草萋萋的卵石滩，更有清冽的天目溪缓缓流过。 去红灯笼乡村家园，要穿越60米长的隧道，再过依山峭壁而建的长百米的栈道，临崖设有栏杆、亭阁。人行其上，仰首是直插云霄的陡岩峭壁，俯视是深不可测的碧潭。</p>
			</div>
			<div class="col-md-4 bottom-grids">
				<a href="a/wanzhuantonglu/"><img class="img-responsive" src="{dede:global.cfg_templets_skin/}/images/vi1.jpg" title="name" alt="" ></a>
				<p>瑶琳仙境，又名瑶琳洞，纵深1公里，总面积达28000平方米，位于浙江西部的桐庐县瑶琳镇，距杭州80公里誉满海内外的瑶琳仙境，是"中国旅游胜地四十佳"、"浙江省十大旅游胜地"之一。2002年跻入国家4A级风景旅游景区行列。瑶林仙境以其神奇的地势地貌和瑰丽多姿的钟乳石景，吸引着全世界各国旅游爱好者的目光。它属于典型的喀斯特地貌，是华东沿海中部亚热带湿润区喀斯特洞穴的典型代表，属国家级风景名胜区。</p>
			</div>
			<div class="col-md-4 possible-about">
					<h4>更多景区</h4>
						<div class="tab1">
							<ul class="place">
								<li><img src="{dede:global.cfg_templets_skin/}/images/cir.png" alt=""></li>
								<li>琴溪香谷</li>
							</ul>
						<p >琴溪香谷，地处浙江省桐庐县瑶琳镇琴溪村，属高山台地峡谷景观。景区总面积约400公顷，林壑幽深，溪涧跌宕，古藤缠绵，满峡飘香，野趣横生。</p>
						</div>
						<div class="tab2">
							<ul class="place">
								<li><img src="{dede:global.cfg_templets_skin/}/images/cir.png" alt=""></li>
								<li>大奇山</li>
							</ul>
						<p >大奇山国家森林公园位于浙江省杭州市桐庐县，在富春江南岸，是一处集江南山水与草原风光于一体的综合性森林公园。大奇山又称"塞基山"，史称"江南第一名山"。境内有山峦、怪石、峡谷、溪瀑，以雄、险、奇、秀、旷著称。大奇山国家森林公园距320国道1公里，与桐君山、七里扬帆、富春江小三峡、严子陵钓台共同构成富春江旅游板块。</p>
						</div>
						<div class="tab3">
							<ul class="place">
								<li><img src="{dede:global.cfg_templets_skin/}/images/cir.png" alt=""></li>
								<li>严子陵钓台</li>
							</ul>
						<p >严子陵钓台位于桐庐县城南15公里的富春山麓，是富春江主要风景点。 严子陵钓台是东汉古迹之一。因东汉高士严子陵拒绝光武帝刘秀之召，拒封“谏议大夫”之官位，来此地隐居垂钓而闻名古今。</p>
						</div>
						<div class="tab4">
							<ul class="place">
								<li><img src="{dede:global.cfg_templets_skin/}/images/cir.png" alt=""></li>
								<li>垂云通天河</li>
							</ul>
						<p >垂云通天河，是一条岩溶地下暗河，由于亿万年前的地壳变动及火山爆发等因素，使景区所在地理范围形成了典型的喀斯特岩溶地貌。垂云通天河全长4.5公里，河道落差 380米，总面积为8万余平方米。河道内岩溶地貌发育良好，地下水源丰沛，水质甘澄，空气清新，终年流水潺潺，河道曲折幽深，或成潭、或成泊、或成瀑激流浅滩，变幻无穷，使人流连忘返。</p>
						</div>
						
						
						<!--script-->
						<script>
							$(document).ready(function(){
								$(".tab1 p").hide();
								$(".tab2 p").hide();
								$(".tab3 p").hide();
								$(".tab4 p").hide();
								$(".tab1 ul").click(function(){
									$(".tab1 p").slideToggle(300);
									$(".tab2 p").hide();
									$(".tab3 p").hide();
									$(".tab4 p").hide();
								})
								$(".tab2 ul").click(function(){
									$(".tab2 p").slideToggle(300);
									$(".tab1 p").hide();
									$(".tab3 p").hide();
									$(".tab4 p").hide();
								})
								$(".tab3 ul").click(function(){
									$(".tab3 p").slideToggle(300);
									$(".tab4 p").hide();
									$(".tab2 p").hide();
									$(".tab1 p").hide();
								})
								$(".tab4 ul").click(function(){
									$(".tab4 p").slideToggle(300);
									$(".tab3 p").hide();
									$(".tab2 p").hide();
									$(".tab1 p").hide();
								})	
							});
						</script>
						<!-- script -->
					</div>
			<div class="clearfix"> </div>
		</div>
	</div>
</div>
<div class="footer">
		<div class="container">
			<div class="footer-top">
				<div class="col-md-4 amet-sed">
				<h4>关于我们</h4>
				<p>版权所有：哑舍三人组</p>
				<p>地址：1-329 哑舍三人组</p>
				<p>技术支持：编辑1401 站长统计</p>
				<ul class="social">
					<li><i> </i>sector 21 , main road </li>
					<li class="phone"><i> </i> +71999-56985</li>
					<li class="mail"><a href="mailto:contact@example.com"><i> </i> contact@example.com</a></li>
				</ul>
				</div>
				<div class="col-md-4 amet-sed">
				<h4>所获荣誉</h4>
				<p>中国民间艺术之乡---剪纸</p>
				<p>中国最佳休闲旅游县</p>
				<p>全国综合实力发展百强县</p>
				<p>全国生态示范区</p>
				<p>中国最具国际影响力旅游目的地</p>
				</div>
				<div class="col-md-4 amet-sed ">
				<h4>关注我们</h4>
				<ul class="social-icons">
					<li><a href="#"><span> </span> </a></li>
					<li class="twitter"><a href="#"><span> </span></a></li>
					<li class="gmail"><a href="#"><span> </span> </a></li>
					<li class="print"><a href="#"><span> </span> </a></li>
				</ul>
				</div>
				<div class="clearfix"> </div>
			</div>
				<p class="footer-class"> 0705140104黄娇丽 0705140125金佩 0705140127方雨静 <a href="http://www.mycodes.net/" target="_blank">编辑1401班</a> <a href="http://www.mycodes.net/" title="网页模板" target="_blank">网络传播学院</a> </p>
		</div>
	</div>
</body>
</html>									
