<script>
	import img from '../lib/images/illustration-article.svg'
	import proImg from '../lib/images/image-avatar.webp'
</script>

<div class="container">
	<img class='imgSel' src={img} alt=""> 
	<div class="learn" >
		Learning
	</div>
	<div class="date">Published 21 Dec 2023</div>
	<h1 class="heading">HTML & CSS foundations</h1>
	<p class="text">
		These languages are the backbone of every website, defining structure, content, and presentation.
	</p>
	<div class="profile">
		<img class="profile-img" src={proImg} alt="">
		<div class="profile-name">Greg Hooper</div>
	</div>
</div>

<style>
	.container {
		display: flex;
		flex-direction: column;
		padding: 24px;
		background-color: white;
		width: 336px;
		height: 474px;
		border-radius: 20px;
	}
	.imgSel {
		width: 336px;
		height: 200px;
		object-fit: cover;
		border-radius: 10px;
	}
	.learn {
		font-family: 'Figtree-ExtraBold', sans-serif;
		width: auto;
		align-self: flex-start;
		color: #111111 ;
		margin-top: 24px;
		border-radius: 4px;
		font-size: 14px;
		font-weight: bold;
		padding: 4px 12px;
		background-color: #F4D04E;
	}
	.date {
		margin-top: 12px;
		font-size: 14px;
	}
	.heading {
		cursor: pointer;
		font-size: 24px;
		font-weight: bold;
		margin-top: 12px;
		margin-bottom: 0;
		transition: color 0.3s ease;
	}
	.heading:hover {
		color: #F4D04E;
	}
	.text {
		margin-top: 12px;
		font-size: 16px;
		color: #6B6B6B;
	}
	.profile {
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
		gap: 12px;
		width: 129px;
		height: 32px;
	}
	.profile-img {
		width: 32px;
		height: 32px;
		border-radius: 100%;
		object-fit: cover;
	}
	.profile-name {
		font-family: 'Figtree-ExtraBold', sans-serif;
		font-size: 14px;
		font-weight: bold;
		color: #111111 ;
	}
</style>