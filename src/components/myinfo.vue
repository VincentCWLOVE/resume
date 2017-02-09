<template>
	<div>
		<p>姓名：<span>{{ name }}</span></p>
		<p>联系方式：<span>{{cellphone}}</span></p>
		<p>邮箱：<a>{{email}}</a></p>
		<p>个人博客：<a>{{blog}}</a></p>
		<p>github：<a>{{github}}</a></p>
		<p>公众号：<a>{{OfficialAccounts}}</a></p>

	</div>
</template>
<script>

	export default {
    	data:function () {
	        return {
	            name: "陈文",
	            cellphone: "18665639841",
	            email: "438419787@qq.com",
	            blog: "https://vincentcwlove.github.io/",
	            github: "https://github.com/VincentCWLOVE",
	            OfficialAccounts: "LoveLifeLoveCoding（拥有420+的粉丝）"    
	        }
	    } 
    }
</script>