<template>
	<Layout>
		<div id="hero" class="h-screen bg-black text-white bg-cover bg-center mb-20 hidden sm:block"></div>
		<div id="hero-mobile" class="h-screen sm:hidden bg-no-repeat bg-black text-white bg-contain bg-center mb-20"></div>
		<div id="t-shirt-giveaway" class="block sm:block lg:flex bg-fixed">
			<div class="lg:w-2/4 sm:w-full lg:px-20 sm:px-10 text-gray-800 ">
				<g-image src="~/assets/images/february-tshirt-giveaway.jpg" />
			</div>
			<div class="w-full lg:w-2/4 p-20">
				<h2 class="text-3xl font-extrabold text-gray uppercase mb-10">February 2020 T-Shirt Giveaway</h2>
				<p class="mb-8">Women Pray is giving T-shirts away for FREE. No strings attached. This shirt has helped women open up to strangers and share Jesus Christ. It also makes people more willing to ask for prayer.</p>
				<p><strong>NOTE:</strong>We are giving out shirts until all shirts are gone and shipped. Only available to individuals in the US.</p>
				<a class="bg-yellow-400 hover:bg-black hover:text-white text-black px-10 py-3 inline-block mx-auto cursor-pointer" href="https://forms.gle/1NpuP1mu2MZJQCJT8">Get FREE T-Shirt</a>
			</div>
		</div>
		<div id="about" class="block sm:block lg:flex bg-fixed">
			<div class="lg:w-2/4 sm:w-full lg:px-20 sm:px-10 text-gray-800 ">
				<g-image src="~/assets/images/tammy-battle-headshot.jpg" />
			</div>
			<div class="w-full lg:w-2/4 p-20">
				<h2 class="text-3xl font-extrabold text-gray uppercase mb-10">Before you react, Pray.</h2>
				<p class="mb-8">This is the place to take the makeup off. To learn how to be strong yet gentle. For the women seeking healing. How to create balance between a spiritual response and emotional response. This is where women learn how to fight!</p>
			</div>
			
		</div>
		<div id="location" class="block bg-cover bg-fixed text-white p-20 sm:text-center">
			<div class="lg:w-2/4 mx-auto block">
				<h2 class="text-3xl font-extrabold text-gray uppercase mb-10">Registration is FREE</h2>
				<p class="mb-8">Women Pray.&trade; is a bi-monthly women's conference hosted by <a href="https://www.facebook.com/tammymoodybattle">Tammy Battle</a>. It's purpose is to help women fight with faith, understanding, and purpose.</p>
				<p class="mb-8">The next conference will take place in Greensboro, NC on Friday, March 20th, 2020 from 7PM to 9PM at an undisclosed location. <span class="bg-yellow-400 text-black">The conference is FREE but registration is required.</span> Location will be provided to attendees after registration. (Hint: It's not at church)</p>
				<a class="bg-yellow-400 hover:bg-black hover:text-white text-black px-10 py-3 inline-block mx-auto cursor-pointer" href="https://forms.gle/MpHkBMaWHmk2JPRK7">Register Now</a>
			</div>
		</div>
		<div id="footer" class="p-20 bg-black text-gray-400 text-center">
			<h2 class="mb-10 text-3xl">Need prayer? Text <span class="text-yellow-400">336-542-5971</span></h2>
			<p><span class="text-lato uppercase text-white">Women Pray.</span> is a trademark of <a href="https://www.facebook.com/tammymoodybattle">Tammy Battle</a>. Copyright &copy; 2020. All rights servered. </p>
		</div>
	</Layout>
</template>

<script>
export default {
	metaInfo: {
		// title: 'Women Pray'
	}
}
</script>

<style>
	#hero {
		background-image: url(~@/assets/images/women-pray-hero-march-2020.jpg);
	}
	#hero-mobile {
		background-image: url(~@/assets/images/women-pray-hero-march-2020-mobile.jpg);
	}
	#location {
		background-image: url(~@/assets/images/hero-bg-ink-greensboro.jpg);
	}
</style>
