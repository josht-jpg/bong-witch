<script>
  import Logo from "$lib/images/logo-transparent.png"
</script>

<header
>
<section class="top">
<img src={Logo} class="logo" alt="bong witch" />

<!-- <h3>Victoria, BC</h3> -->
<!-- <img src={Logo} class="logo" alt="bong witch" /> -->


<!-- <p class="number-of-the-beast">666</p> -->

</section>
<div>
<div class="header-container" >
<h1>Bong Witch</h1>
</div>

<div class="selects" >
	<button style="  opacity: 85%;" >Lore</button>
	<button style="  opacity: 85%;" >Merch</button>
	<button style="  opacity: 85%;" >Contact</button>
	<button style="  opacity: 85%;" >Listen</button>
	<!-- <button>Shows</button> -->
	<button style="margin-right: 8px;  opacity: 65%;">Shows</button>
	</div>
</div>
</header>

<style>


.header-container {
	text-align: end;
}

.selects {
	width: 100%;
	display: flex;
	justify-content: flex-end;
	font-size: 20px;
	padding-top: 4px;
	padding-bottom: 2px;
	column-gap: 14px;
	/* padding-left: 8px;
	padding-right: 8px; */

	border-top: 2px solid rgba(0, 0, 0, .5);

}


button, input[type="submit"], input[type="reset"] {
	background: none;
	color: inherit;
	border: none;
	padding: 0;
	font: inherit;
	cursor: pointer;
	outline: inherit;
}


h1 {
	opacity: 68%;
	margin: 0;
	font-size: 68px;
	text-align: end;
	margin-bottom: 4px;
}

h3 {
	opacity: 50%;
}

.number-of-the-beast {
	font-size: 14px;
	margin-top: -10px;
}

.logo {
	margin-right: -14px;
	opacity: 80%;
	display: block;
	width: 62px;
border-radius: 60px;
margin-top: 0px;
margin-left: 6px;


}
	.top {
		width: 100%;
align-items: center;
/* justify-content: flex-end; */
		display: flex;
		height: 40%;
		/* border-bottom: 2px rgba(0, 0, 0, .5) solid; */
	}
	header {

		display: flex;
		flex-direction: column;
		justify-content: space-between;
		color: #000;
		font-weight: 300;
		padding-top:4px;
		padding-bottom: 4px;

	height: 25%;
	background-image: url($lib/images/hb-69.png);
	/* background-color: #c02a0f; */
	/* border-top-right-radius: 14px;
	border-top-left-radius: 14px; */
	}


</style>
