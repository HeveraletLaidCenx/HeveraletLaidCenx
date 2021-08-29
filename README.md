# :cat: 喵！Meow! Nya~

/play nyan

<style type="text/css">body {width: 100%;height: 100%;margin: 0;padding: 0;display: flex;align-items: center;justify-content: center;flex-direction: column;background-color: #222222;color: #CCCCCC;}p {margin: 0;padding: 0;}#topBar {width: 90%;display: block;}@keyframes press {0% {transform: scale(1, 1);}100% {transform: scale(0.90, 0.90);}}button {margin: 0;padding: 0;border-style: none;display: flex;align-items: center;justify-content: center;font-weight: bold;cursor: pointer;animation-name: none;animation-duration: 0.1s;animation-timing-function: ease-out;animation-fill-mode: forwards;}button:focus {outline-style: solid;outline-width: 1px;}button:active {animation-name: press;}#langBtn {width: 36px;height: 36px;background-color: #EC8AA4;color: #CC163A;}#langBtn:hover {background-color: #FF9900;}#langBtn:focus {outline-color: #CC163A;}@keyframes danmukuRL {0% {transform: translateX(100%);}100% {transform: translateX(-100%);}}.danmukuCtn {overflow: hidden;display: flex;align-items: center;justify-content: center;}.danmuku {width: fit-content;white-space: nowrap;animation-name: danmukuRL;animation-duration: 5s;animation-timing-function: ease-in-out;animation-iteration-count: infinite;animation-direction: normal;}#content {width: 90%;padding-top: 20px;padding-left: 20px;}</style>

<body>
	<div id="topBar">
		<button id="langBtn" onclick="langChange()">
			<div class="danmukuCtn" style="width: 100%;height: 100%;">
				<div class="danmuku">语言/Language...</div>
			</div>
		</button>
	</div>
	<div id="content">
		<p class="sc">关于语言：</p>
		<p class="tc">關於語言：</p>
		<p class="en">About Language: </p>
	</div>
	<script>
		var lanList = ["sc","tc","en"]
		var lanFlag = lanList.length
		
		function langChange(){
			if(lanFlag < lanList.length - 1){
				lanFlag += 1
			}
			else{
				lanFlag = 0
			}
			console.log("首选语言更改为：" + lanList[lanFlag])
			for(var i = 0;i < lanList.length;i++){
				var content = document.getElementsByClassName(lanList[i])
				var i2
				for(i2 = 0;i2 < content.length;i2++){
					if(i == lanFlag){
						content[i2].style.fontSize = "18px"
						content[i2].style.color = "#CCCCCC"
					}
					else{
						content[i2].style.fontSize = "10px"
						content[i2].style.color = "#666666"
					}
				}
			}
		}
		
		langChange()
	</script>
</body>

氦！我是翡翠，是一只不是计算机相关专业的咸鱼喵），翡翠是个简称，叫翡翠喵啥的都行。
He(chemical)!, I am LC, a salty-fish-cat which not major in computer or programming related fields. LC is an abbreviated nickname, LCMeow\LCCat... is ok.

关于语言：
中文ok，繁體可能有一些字難以直接認出來， for Eng, not good at Eng grammar but maybe can deal with some communication XD.