<template>
	<div class="topdata">
		<ul>
			<li class="title"><h2>每周事项</h2></li>
			<li class="everyday" id="Sun"><button onclick="getday">周日</button></li>
			<li class="everyday" id="Mon"><button onclick="getday">周一</button></li>
			<li class="everyday" id="Tues"><button onclick="getday">周二</button></li>
			<li class="everyday" id="Wed"><button onclick="getday">周三</button></li>
			<li class="everyday" id="Thur"><button onclick="getday">周四</button></li>
			<li class="everyday" id="Fri"><button onclick="getday">周五</button></li>
			<li class="everyday" id="Sat"><button onclick="getday">周六</button></li>
		</ul>
	</div>
</template>

<script>
	export default{
		getday: function () {
			var day = getElementByClassName(everyday)+'list'
			return day
		}

	}
</script>

<style>
	.everyday{
		display: inline;
		margin: 3%;
	}
	.title{
		color: blue;
	}
</style>