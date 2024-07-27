<script>
	import img from '../lib/images/illustration-article.svg'
</script>

<div class="container">
	<img class='imgSel' src={img} alt=""> 
	<div class="learn" >
		Learning
	</div>
	<div class="date">Published 21 Dec 2023</div>
	<h1 class="testing">HTML & CSS foundations</h1>

</div>

<style>
	.container {
		display: flex;
		flex-direction: column;
		margin: 0 auto;
		background-color: white;
		width: 384px;
		height: 522px;
		border-radius: 20px;
	}
	.imgSel {
		margin: 24px;
		width: 336px;
		height: 200px;
		object-fit: cover;
		border-radius: 10px;
	}
	.learn {
		display: flex;
		border-radius: 4px;
		font-size: 18px;
		font-weight: bold;
		justify-content: center;
		align-items: center;
		width: 100px;
		height: 50px;
		background-color: #F4CF53;
		margin-left: 25px;
	}
</style>