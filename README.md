# xiaoshu
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
		<style>
			* {
				padding: 0;
				margin: 0;
			}
			body{
				display: flex;
				position: relative;
				width: 100%;
				height: 1000px;
				background-color: wheat;
			}
			.first {
				position: absolute;
				width: 100%;
				height: 100%;
			}
			.two {
				width: 97.5%;
				height: 30%;
				margin: 0 auto;
				background-color: navajowhite;
			}
			.two img{
				width: 100%;
				height: 300px;
			}
			.two .twot {
				width: 44.031%;
				height: 300px;
				float: left;
			}
			.two .three {
				width: 55.92%;
				height: 300px;
				float: right;
				background-color: blue;
			}
			.three div:nth-child(1){
				display: inline-block;
				text-align: center;
				width: 37%;
				height: 300px;
				background-color: lemonchiffon;
			}
			.three div:nth-child(1) b {
				display: inline-block;
				margin-top: 18px;
				font-size: 18px;
				color: lightseagreen;
			}
			.ini {
				margin-top: 20px;
				margin-left: -41px;
			}
			.inz {
				margin-top: 20px;
				margin-left: -41px;
			}
			.btn {
				margin: 20px;
				margin-left: -120px;
			}
			.threet {
				float: left;
				width: 100%;
				height: 32%;
			}
			.girl {
				float: left;
			}
			.girl img {
				margin-left: 110px;
				width: 50%;
				height: 50%;
			}
			.five {
				float: right;
				/* display: inline-block; */
				width: 63%;
				height: 300px;
				background-color: pink;
			}
			.lianjie {
				margin-top: 11px;
				width: 100%;
				height: 40px;
				text-align: center;
				background-color: lemonchiffon;
			}
			.lianjie a{
				text-decoration: none;
				color: lightseagreen;
				font-size: 17.5px;
				line-height: 40px;
				margin-left: 110px;
			}
			.lianjie a:hover {
				color: forestgreen;
				text-shadow: 5px 2px 3px gray;
			}
			.contentt {
				margin: 10px auto;
				width: 97.5%;
				height: 63%;
				background-color: wheat;
			}
			.contentt .cont1 {
				display: flex;
				position: relative;
				width: 100%;
				height: 37.5%;
				background-color: white;
			}
			.contentt .cont2 {
				margin-top: 10px;
				width: 100%;
				height: 54.5%;
				background-color: white;
			}
			.contentt .cont3 {
				margin-top: 10px;
				width: 100%;
				height: 6%;
				background-color: white;
			}
			.pucte {
				position: absolute;
				width: 30%;
				height: 100%;
				left: 32.5%;
			}
			.pucte img {
				position: absolute;
				left: 45%;
				width: 246px;
				/* height: 13%; */
				padding-top: 6px;
			}
			.cont12 {
				position: absolute;
				left: 18%;
				width: 28%;
				height: 100%;
			}
			.cont12 div:nth-child(1){
				color: lightseagreen;
				font-weight: 700;
				padding-left: 10px;
				padding-top: 5px;
			}
			.cont12 div:nth-child(2) p{
				margin-top: 5px;
				padding-left: 15px;
				text-indent: 1.5em;
			}
			.co {
				position: absolute;
				width: 30%;
				height: 100%;
				top:5%;
				left: 1%;
			}
			.co img {
				width: 50%;
			}
			.cont21 {
				position: absolute;
				left: 65%;
				width: 35%;
				height: 100%;
			}
			.goujian {
				color: lightseagreen;
				font-weight: 700;
				padding-left: 10px;
				padding-top: 5px;
			}
			.cont21 p {
				margin-top: 5px;
				padding-left: 15px;
				text-indent: 1.5em;
			}
			.cont21 img {
				float: right;
				/* position: absolute; */
				bottom: 2px;
				width: 20%;
			}
			.cont2 img{
				margin-left: 1%;
				width: 18%;
			}
			.cont22{
				display: inline-block;
				width: 30%;
				height: 30%;
				position: absolute;
			}
			.cont22 p:nth-child(1){
				color: lightseagreen;
				margin-top: 20px;
				font-weight: 700;
				padding-left: 10px;
				padding-top: 5px;
			}
			.cont22 p:nth-child(2){
				margin-top: 5px;
				padding-left: 15px;
				text-indent: 1.5em;
			}
			.cont22 p:nth-child(3){
				margin-top: 5px;
				padding-left: 15px;
				text-indent: 1.5em;
			}
			.updown {
				position: absolute;
				display: inline-block;
				left: 50%;
				width: 49%;
				height: 30%;
			}
			.updown img {
				float: right;
				width: 35%;
			}
			.updown p{
				display: inline-block;
				margin-top: 5px;
				padding-left: 15px;
				text-indent: 1.5em;
			}
			.updown div {
				color: lightseagreen;
				margin-top: 20px;
				font-weight: 700;
				padding-left: 10px;
				padding-top: 5px;
			}
			.cont3{
				font-weight: 700;
				font-size: 19px;
				text-align: center;
				line-height: 187%;
				color: lightseagreen;
			}
			.gry{
				color: gray;
			}
		</style>
	</head>
	<body>
		<div class="first">
			<div class="two">
				<div class="twot"><img src="http://127.0.0.1:8848/%E7%BD%91%E9%A1%B5%E8%AE%BE%E8%AE%A12/img/%E8%B7%91%E6%AD%A5.jpg" alt="" /></div>
				<div class="three">
					<div>
						<b>健康是人生第一财富</b>
						<div class="threet">
							<form action="">
								<input class="ini" type="text" placeholder="请输入您的身高"/>		
								<br/>
								<input type="text" class="inz" placeholder="请输入您的体重"/>
								<br/>
								<button class="btn">确定</button>
								<input type="reset" value="重置" />
							</form>
						</div>
						<div class="girl" >
							<img src="http://127.0.0.1:8848/%E7%BD%91%E9%A1%B5%E8%AE%BE%E8%AE%A12/img/%E5%81%A5%E5%BA%B7%E5%B0%8F%E5%A5%B3%E5%AD%A92.png" alt="" />
						</div>
					</div>
					<div class="five">
						<img src="http://127.0.0.1:8848/%E7%BD%91%E9%A1%B5%E8%AE%BE%E8%AE%A12/img/%E9%A3%9F%E7%89%A9.jpg" alt="" />
					</div>
				</div>
			</div>
			<div class="lianjie">
				<a href="./健康饮食概念.html" target="_blank">健康饮食概念</a>
				<a href="./饮食营养均衡.html" target="_blank">饮食营养均衡</a>
				<a href="./良好饮食习惯.html" target="_blank">良好饮食习惯</a>
				<a href="./食物合理搭配.html" target="_blank">食物合理搭配</a>
			</div>
			<div class="contentt">
				<div class="cont1">
					<div class="co">
						<img src="http://127.0.0.1:8848/%E7%BD%91%E9%A1%B5%E8%AE%BE%E8%AE%A12/img/%E7%B2%97%E7%B2%AE.jpg" alt="" />
					</div>
					<div class="cont12">
						<div>提供能量</div>
						<div>
							<p>碳水化合物是人体最主要的能量来源。像米饭、面包等主食，进入人体后会被分解为葡萄糖，为身体的各种活动，如肌肉运动、大脑思考等提供动力。每克碳水化合物能提供约4千卡的能量。</p>
							<p>脂肪也是高能量物质，每克脂肪可提供约9千卡的能量。它是身体的"能量储备库"，在身体需要时缓慢释放能量，并且能够帮助人体吸收某些维生素。</p>
							<p>蛋白质在一定程度上也可以提供能量，不过它主要的功能是构建和修复身体组织。</p>
						</div>
					</div>
					
					<div class="pucte"><img src="http://127.0.0.1:8848/%E7%BD%91%E9%A1%B5%E8%AE%BE%E8%AE%A12/img/%E9%87%91%E5%AD%97%E5%A1%942.jpg" alt="" /></div>
					<div class="cont21">
						<div class="goujian">构建和修复组织</div>
						<p>
							蛋白质是身体细胞的重要组成部分。身体的生长发育离不开蛋白质，例如肌肉、骨骼、皮肤、毛发等组织器官的生长和修复都需要蛋白质的参与。像瘦肉、鱼类、豆类等食物都是优质蛋白质的良好来源。矿物质也在构建身体组织方面发挥作用。钙是骨骼和牙齿的主要成分，磷同样参与骨骼的形成，而铁是制造血红蛋白的关键原料，有助于维持血液正常的运输氧气的功能。<img src="http://127.0.0.1:8848/%E7%BD%91%E9%A1%B5%E8%AE%BE%E8%AE%A12/img/%E7%89%9B%E8%82%89%E9%9D%A2.jpg" alt="" />
						</p>
					</div>
				</div>
				<div class="cont2">
					<img src="http://127.0.0.1:8848/%E7%BD%91%E9%A1%B5%E8%AE%BE%E8%AE%A12/img/%E9%AB%98%E8%83%BD%E9%87%8F.jpg" alt="" />
					<div class="cont22">
						<p>为什么运动使人健康？</p>
						<p>从生理层面讲，运动时心跳加速、呼吸加深，能强化心肺功能，提升耐力。像跑步等有氧运动，可以让心肺更有效地工作，为身体输送更多氧气。而且运动能促进新陈代谢，帮助身体更好地消化吸收营养，排出废物。经常运动还可以增强肌肉和骨骼的力量，降低骨质疏松等问题的发生几率。</p>
						<p>从心理角度看，运动能够促使身体分泌内啡肽，这种物质能让人产生愉悦感，帮助缓解压力和焦虑情绪。</p>
					</div>
					<div class="updown">
						<div>坚持运动给身体带来了哪些变化？</div>
						<p>在心血管系统方面，它能降低静息心率，使心脏每次搏动更有力，更有效地输送血液。同时能降低血压、血脂，减少动脉粥样硬化的风险，有助于心血管健康。<img src="http://127.0.0.1:8848/%E7%BD%91%E9%A1%B5%E8%AE%BE%E8%AE%A12/img/%E7%91%9C%E4%BC%BD.jpg" alt="" />对于呼吸系统，能增加肺活量，使每次呼吸能摄取和交换更多氧气和二氧化碳。运动还能增强呼吸肌力量，让呼吸更顺畅。在肌肉骨骼系统，运动可以增加肌肉量，让肌肉更紧实，提升基础代谢率。并且可以增强骨骼密度，预防骨质疏松，降低骨折的风险。从身体的外在表现看，运动能够减少身体脂肪，塑造良好的身材线条。同时，运动可以改善皮肤状态，促进血液循环，使皮肤红润有光泽。
						</p>
					</div>
				</div>
				<div class="cont3">健康生活</div>
			</div>
		</div>
	</body>
	<script>
		var in1=document.querySelector('.ini')
		var in2=document.querySelector('.inz')
		var btl=document.querySelector('.btn')
		// in1.addEventListener('click',function(){
		// 	this.value=' '
		// })
		// in1.addEventListener('blur',function(){
		// 	this.value="请输入您的身高"
		// 	this.class="gry"
		// })
		// in2.addEventListener('click',function(){
		// 	this.value=' '
		// })
		// in2.addEventListener('blur',function(){
		// 	this.value="请输入您的身高"
		// 	this.class="gry"
		// })
		btl.addEventListener('click',function(){
			var shengao=in1.value
			var tizhong=in2.value
			if(parseFloat(tizhong/(shengao*shengao)>27.9)){
				alert("你要减肥啦！")
			}
			else if(parseFloat(tizhong/(shengao*shengao)>23.9)){
				alert("可以少吃点发胖食品")
			}
			else if(parseFloat(tizhong/(shengao*shengao))>18.4){
				alert("你的身材很健康！")
			}
			else {
				alert("你太瘦啦！")
			}
		})
	</script>
</html>
