<script lang="ts">
	import TallWidget from '$lib/TallWidget.svelte';
</script>

<TallWidget>
	<section slot="header" class="mb-6 flex justify-between items-center">
		<h2 class="text-xl font-semibold">Capital One</h2>
		<p class="text-sm font-light">YTD <span class="font-semibold ml-1">+24%</span></p>
	</section>
	<div slot="body" class="flex flex-col">
		<div class="flex justify-between items-center flex-1 mb-6">
			<di class="flex justify-between flex-col space-y-4">
				<div>
					<h3 class="font-light mb-2">Total</h3>
					<p class="text-4xl font-semibold">$1200</p>
				</div>
				<div>
					<h4 class="font-light mb-2">Monthly Earnings</h4>
					<p class="text-2xl font-semibold">$1722</p>
				</div>
			</di>
			<div class="flex justify-between flex-col space-y-4">
				<div>
					<h4 class="font-light mb-2">Outstanding Debt</h4>
					<p class="text-2xl leading-10 font-semibold">$13000</p>
				</div>
				<div>
					<h4 class="font-light mb-2">Monthly Costs</h4>
					<p class="text-2xl font-semibold">$684</p>
				</div>
			</div>
		</div>
		<h4 class="font-light mb-2">Recent Purchases</h4>
		<ul class="text-sm space-y-1 mb-6">
			<li class="flex justify-between">
				<p>Amazon</p>
				<div class="flex space-x-4">
					<p class="font-semibold">($23.02)</p>
					<p>7/20/23</p>
				</div>
			</li>
			<li class="flex justify-between">
				<p>BarXI</p>
				<div class="flex space-x-4">
					<p class="font-semibold">($7.35)</p>
					<p>7/20/23</p>
				</div>
			</li>
			<li class="flex justify-between">
				<p>Costco Gas</p>
				<div class="flex space-x-4">
					<p class="font-semibold">($34.55)</p>
					<p>7/20/23</p>
				</div>
			</li>
		</ul>
		<h4 class="font-light mb-4">Categories</h4>
		<div class="flex justify-between items-center">
			<div class="w-20 h-20 rounded-full bg-white/70" />
            <div class="flex items-center space-x-6">
                <div class="flex flex-col items-start text-xs space-y-2">
                    <div class="flex items-center space-x-2">
                        <div class="w-2 h-2 rounded-full bg-white/70" />
                        <p>Food</p>
                    </div>
                    <div class="flex items-center space-x-2">
                        <div class="w-2 h-2 rounded-full bg-white/70" />
                        <p>Gas</p>
                    </div>
                    <div class="flex items-center space-x-2">
                        <div class="w-2 h-2 rounded-full bg-white/70" />
                        <p>Rent</p>
                    </div>
                </div>
                <div class="flex flex-col items-start text-xs space-y-2">
                    <div class="flex items-center space-x-2">
                        <div class="w-2 h-2 rounded-full bg-white/70" />
                        <p>Entertainment</p>
                    </div>
                    <div class="flex items-center space-x-2">
                        <div class="w-2 h-2 rounded-full bg-white/70" />
                        <p>Car Payments</p>
                    </div>
                    <div class="flex items-center space-x-2">
                        <div class="w-2 h-2 rounded-full bg-white/70" />
                        <p>Clothing</p>
                    </div>
                </div>
            </div>
			
		</div>
	</div>
	<section slot="footer" />
</TallWidget>
