<template>
	<div class="skill">
		<h2>求职意向：</h2>
		<p>{{ want }}</p>
		<h2>专业技能：</h2>
		<h3>前端：</h3>
		<ul>
			<li>
			熟悉各主流浏览器与低版本IE浏览器之间的兼容问题，以及如何解决CSS兼容问题，能够实现优雅降级及渐进增强</li>

			<li>熟悉HTML5各种新特性以及API接口，包括各种新标签、本地存储、canvas画布以及获取地理信息、全屏切换、电池状态、在离线状态、访问本地相册及相机等 </li>

			<li>熟悉移动端、微信页面编写，使用响应式布局适配各移动设备</li>

			<li>熟悉JavaScript模块化编程</li>
		</ul>

		<h3>iOS：</h3>
		<ul>
			<li>
				熟悉C、Swift 、AppleScript 等Mac平台开发语言
			</li>
			<li>
				熟悉 Apple macOS、iOS、Apple Watch、tvOS 各平台Cocoa框架
			</li>
			<li>
				熟悉 iOS Apple Pay、TouchID等软硬融合开发
			</li>
			<li>
				熟悉 Apple MVC 架构设计模式
			</li>
			<li>
				熟悉 Swift 解释性runtime 内核原理
			</li>
		</ul>

		<h3>全栈：</h3>
		<ul>
			<li>
				熟悉各类JavaScript主流框架，jQuery、Angular.js、Node.js、Vue.js
			</li>
			<li>
				熟悉PHP，熟练使用TP框架
			</li>
			<li>
				熟悉MySql、MongoDB数据库
			</li>
			<li>
				熟悉Apache服务器，能够部署中小型的云端项目
			</li>

		</ul>
	</div>
</template>
<script>

	export default {
    	data:function () {
	        return {
	           want :"全栈工程师"   
	        }
	    } 
    }
</script>
<style>
	.skill h2 {
		margin-top: 100px;
		margin-left: 100px;
		text-align: left;
	}
	.skill h3{
		margin-top: 30px;
		margin-left: 140px;
		text-align: left;
	}
	.skill ul ,.skill li {
		text-align: left;
		margin-left: 100px;
		margin-top: 25px;
		display: block;
		
	}	
	


</style>