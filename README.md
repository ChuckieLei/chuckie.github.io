<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>❤Love❤U❤</title>
    <link type="text/css" rel="stylesheet" href="./renxi/default.css">
	<script type="text/javascript" src="./renxi/jquery.min.js"></script>
	<script type="text/javascript" src="./renxi/jscex.min.js"></script>
	<script type="text/javascript" src="./renxi/jscex-parser.js"></script>
	<script type="text/javascript" src="./renxi/jscex-jit.js"></script>
	<script type="text/javascript" src="./renxi/jscex-builderbase.min.js"></script>
	<script type="text/javascript" src="./renxi/jscex-async.min.js"></script>
	<script type="text/javascript" src="./renxi/jscex-async-powerpack.min.js"></script>
	<script type="text/javascript" src="./renxi/functions.js" charset="utf-8"></script>
	<script type="text/javascript" src="./renxi/love.js" charset="utf-8"></script>
    <style type="text/css">
	</style>
</head>
<body>
	<audio autoplay="autopaly">
	<source src="renxi.mp3" type="audio/mp3" /></audio>  
	<div id="main">
	<div id="error">本页面采用HTML5编辑，目前您的浏览器无法显示，请换成谷歌(<a href="http://www.google.cn/chrome/intl/zh-CN/landing_chrome.html?hl=zh-CN&brand=CHMI">Chrome</a>)或者火狐(<a href="http://firefox.com.cn/download/">Firefox</a>)浏览器，或者其他游览器的最新版本。</div>
		<div id="wrap">
			<div id="text">
				<div id="code">
					<font color="#FF0000">
						<span class="say">亲爱的，我爱你，虽然你看不见我对你的告白</span><br>
						<span class="say"> </span><br>
						<span class="say"> 我知道我不会甜言蜜语，但是我会用行动证明一切</span><br>
						<span class="say"> </span><br>
						<span class="say">你说我啰嗦，有些东西因为越在乎所以越失去</span><br>
						<span class="say"> </span><br>
						<span class="say">因为我太爱你了，所以我失去你了</span><br>
						<span class="say"> </span><br>
						<span class="say">因为我太啰嗦了，所以你离开了我</span><br>
						<span class="say"> </span><br>
						<span class="say">虽然你看不见我的告白，但是我还是要把这些心里话说</span><br>
						<span class="say"> </span><br>
						<span class="say">虽然你看不见我的告白，但是我还是要把这些心里话说</span><br>
						<span class="say"> </span><br>
						<span class="say">虽然你看不见我的告白，但是我还是要把这些心里话说</span><br>
						<span class="say"> </span><br>
						<span class="say">虽然你看不见我的告白，但是我还是要把这些心里话说</span><br>
						<span class="say"> </span><br>
						<span class="say"> -- 爱你的午夜阳光--</span>
					</font>
				</div>
			</div>
			<div id="clock-box">
				<span><font color="#666666">亲爱的，我们相识已经是</font></span>
				<div id="clock"></div>
			</div>
			<canvas id="canvas" width="1100" height="680"></canvas>
		</div>
	</div>
	<script>
	//(function(){var canvas = $('#canvas');if (!canvas[0].getContext) {$("#error").show();return false;}var width = canvas.width();var height = canvas.height();canvas.attr("width", width);canvas.attr("height", height);var opts = {seed: {x: width / 2 - 20,color: "rgb(190, 26, 37)",scale: 2},branch: [[535,680,570,250,500,200,30,100,[[540,500,455,417,340,400,13,100,[[450,435,434,430,394,395,2,40]]],[550,445,600,356,680,345,12,100,[[578,400,648,409,661,426,3,80]]],[539,281,537,248,534,217,3,40],[546,397,413,247,328,244,9,80,[[427,286,383,253,371,205,2,40],[498,345,435,315,395,330,4,60]]],[546,357,608,252,678,221,6,100,[[590,293,646,277,648,271,2,80]]]]]],bloom: {num: 700,width:1080,height:650,},footer:{width:1200,height:5,speed:10,}};var tree = new Tree(canvas[0], width, height, opts);var seed = tree.seed;var foot = tree.footer;var hold = 1;canvas.click(function(e) {var offset = canvas.offset(), x, y;x = e.pageX - offset.left;y = e.pageY - offset.top;if (seed.hover(x, y)) {hold = 0; canvas.unbind("click");canvas.unbind("mousemove");canvas.removeClass('hand');}}).mousemove(function(e){var offset = canvas.offset(), x, y;x = e.pageX - offset.left;y = e.pageY - offset.top;canvas.toggleClass('hand', seed.hover(x, y));});var seedAnimate = eval(Jscex.compile("async", function () {seed.draw();while (hold) {$await(Jscex.Async.sleep(10));}while (seed.canScale()) {seed.scale(0.95);$await(Jscex.Async.sleep(10));}while (seed.canMove()) {seed.move(0, 2);foot.draw();$await(Jscex.Async.sleep(10));}}));var growAnimate = eval(Jscex.compile("async", function () {do {tree.grow();$await(Jscex.Async.sleep(10));} while (tree.canGrow());}));var flowAnimate = eval(Jscex.compile("async", function () {do {tree.flower(2);$await(Jscex.Async.sleep(10));} while (tree.canFlower());}));var moveAnimate = eval(Jscex.compile("async", function () {tree.snapshot("p1", 240, 0, 610, 680);while (tree.move("p1", 500, 0)) {foot.draw();$await(Jscex.Async.sleep(10));}foot.draw();tree.snapshot("p2", 500, 0, 610, 680);canvas.parent().css("background", "url(" + tree.toDataURL('image/png') + ")");canvas.css("background", "#ffe");$await(Jscex.Async.sleep(300));canvas.css("background", "none");}));var jumpAnimate = eval(Jscex.compile("async", function () {var ctx = tree.ctx;while (true) {tree.ctx.clearRect(0, 0, width, height);tree.jump();foot.draw();$await(Jscex.Async.sleep(25));}}));var textAnimate = eval(Jscex.compile("async", function () {var together = new Date();together.setFullYear(2015,(9-1),(3-1));together.setHours(22);together.setMinutes(22);together.setSeconds(0);together.setMilliseconds(0);$("#code").show().typewriter();$("#clock-box").fadeIn(500);while (true) {timeElapse(together);$await(Jscex.Async.sleep(1000));}}));var runAsync = eval(Jscex.compile("async", function () {$await(seedAnimate());$await(growAnimate());$await(flowAnimate());$await(moveAnimate());textAnimate().start();$await(jumpAnimate());}));runAsync().start();})();
	var name = "The Window";
	var object={
		name : "My object",
		getNameFunc : function(){
			return function(){
				return this.name;
			}
		}

	};
	alert(object.getNameFunc()());
	</script>
</body>
</html>
