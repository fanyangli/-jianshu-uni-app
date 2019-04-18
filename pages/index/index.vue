<template>
  <div id="app">
    <div class="header"> 
		<router-link to="/task" class="nav-item-one">
			推荐
			<div class="link"></div>
		</router-link>
		<router-link to="" class="nav-item-one">
			专题
			<div class="link"></div>
		</router-link>
		<router-link to="b" class="nav-item-one">
			连载
			<div class="link"></div>
		</router-link>
	</div>
	<div class="container">
		<router-view></router-view>
	</div>
  </div>
</template>

<script>
	export default {
	  name: 'App',
	   courseId:""
	}
</script>
<style>

	
	#app{
			background-color: rgb(244,244,244);
		}
		
		.header{
			display: flex;
			height: 50px;
			background-color: #fff;
			font-size: 20px;
			padding-left: 200px;
			align-items: center;
		}
		
		.nav-item-logo img{
			width: 120px;
			height: 30px;
			margin-right: 50px;
			margin: 1 1 50%;
			padding-right: 100px;
		}
		
		.nav-item-one{
			display: flex;
			align-items: center;
			margin-right: 20px;
			font-size: 15px;
			color: black;
		}
		
		.nav-item-one img{
			width: 20px;
			height: 20px;
			margin-right:5px;
		}
		
		.nav-item-two{
			display: flex;
			align-items: center;
			color: black;
			font-size: 15px;
			padding-right: 25px;
		}
		
		.nav-item-two img{
			width: 30px;
			height: 30px;
			border-radius: 100%;
			margin-right: 10px;
		}
		
		.nav-item{
			width: 100px;
			margin-right: 20px;
		}
		
		.container {
			width: 85%;
			margin: 0 auto;
			padding-bottom: 40px;
		}
		
		a{
			text-decoration: none;
			color: #aaa;
		}
		
		.content{
			background-color: lightgray;
			color: #FFFFFF;
		}
		
		a:hover{
			color:rgb(2,165,218);
		}
		
		.link{
			margin-left: 15px;
			height: 12px;
			border: 0.5px solid gainsboro;
			background-color: gainsboro;
		}
	</style>
