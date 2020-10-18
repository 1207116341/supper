<template>
	<tab-bar>
		<tab-bar-item path="/home"activeColor="blue">
			<div slot="item-icon"><img src="~assets/img/tabbar/home.png" alt=""></div>
			<div slot="item-icon-active"><img src="~assets/img/tabbar/home1.png" alt=""></div>
			<div slot="item-text">首页</div>
		</tab-bar-item>
		<tab-bar-item path="/category">
			<div slot="item-icon"><img src="~assets/img/tabbar/fen.png" alt=""></div>
			<div slot="item-icon-active"><img src="~assets/img/tabbar/fen1.png" alt=""></div>
			<div slot="item-text">分类</div>
		</tab-bar-item>
		<tab-bar-item path="/cart">
			<div slot="item-icon"><img src="~assets/img/tabbar/car.png" alt=""></div>
			<div slot="item-icon-active"><img src="~assets/img/tabbar/car1.png" alt=""></div>
			<div slot="item-text">购物车</div>
		</tab-bar-item>
		<tab-bar-item path="/profile">
			<div slot="item-icon"><img src="~assets/img/tabbar/me.png" alt=""></div>
			<div slot="item-icon-active"><img src="~assets/img/tabbar/me1.png" alt=""></div>
			<div slot="item-text">我的</div>
		</tab-bar-item>
	</tab-bar>
</template>

<script>
	import TabBar from 'components/common/tabbar/TabBar.vue'
	import TabBarItem from 'components/common/tabbar/TabBarItem.vue'
	
	export default {
		name:'MainTabBar',
		components:{
			TabBar,
			TabBarItem
		}
	}
</script>

<style>

</style>
