<template>
	<div class="container1">
		<img :src="phoneInfo.image" alt="">
		<h3>{{phoneInfo.title}}</h3>
		<p>{{phoneInfo.info}}</p>
		<span>{{phoneInfo.price}}</span>
	</div>
</template>

<script>
	export default {
		data(){
			return{
				
			}
		},
		props:["phoneInfo"]
	}
</script>

<style>
.container1{
	width: 220px;
	text-align: center;
	margin: 10px;
	background-color: white;
	padding-bottom: 10px;
}
.container1 img{
	width: 100%;
}


</style>
