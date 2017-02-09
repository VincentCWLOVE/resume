<template>
	<div class="project">
		<h2>求职意向：</h2>
		<ul>
			<li>
			{{c1}}:{{c1_info}}
			</li>
			<li>
				{{c2}}:{{c2_info}}
			</li>	
		</ul>
		
	</div>
</template>
<script>

	export default {
    	data:function () {
	        return {
	           c1:"iOS项目",
	           c1_info:"车网通、微点乐、雅惠点餐、Gif部落、衣联进货宝、衣联批发商、爱语、密爱",
	           c2:"前端项目",
	           c2_info:"公司官网、三个公司的后台管理系统（两个PHP，一个node）、小程序教学项目、以及公司的一些旧项目的更新"   
	        }
	    } 
    }
</script>
<style>
	.project h2 {
		margin-top: 100px;
		margin-left: 100px;
		text-align: left;
	}
	.project h3{
		margin-top: 30px;
		margin-left: 140px;
		text-align: left;
	}
	.project ul ,.project li {
		text-align: left;
		margin-left: 100px;
		margin-top: 25px;
		display: block;
		
	}	
	


</style>