<script></script>

<section class="ai-benefits-section">
	<h1 class="visually-hidden">AI Benefits</h1>
	<div class="ai-benefits-section__wrapper">
		<ul class="ai-benefits-section__benefits-list-1 benefits-list-1">
			<li class="benefits-list-1__reviews-card-item reviews-card-item">
				<h2 class="reviews-card-item__title">Social Media <strong>10x</strong> <em>Faster</em> with AI</h2>
				<div class="reviews-card-item__image-group">
					<img alt="Star" class="reviews-card-item__image" src="images/vector/star.svg">
					<img alt="Star" class="reviews-card-item__image" src="images/vector/star.svg">
					<img alt="Star"  class="reviews-card-item__image" src="images/vector/star.svg">
					<img alt="Star" class="reviews-card-item__image" src="images/vector/star.svg">
					<img alt="Star" class="reviews-card-item__image" src="images/vector/star.svg">
				</div>
				<p class="reviews-card-item__text">Over 4,000 5-star reviews</p>
			</li>
			<li class="benefits-list-1__accounts-card-item accounts-card-item">
				<div class="accounts-card-item__image-group">
					<img alt="Instagram and X badge" class="accounts-card-item__badges" src="images/raster/badges.webp">
				</div>
				<h3 class="accounts-card-item__title">Manage multiple accounts and platforms.</h3>
			</li>
			<li class="benefits-list-1__posting-schedule-card-item posting-schedule-card-item">
				<h3 class="posting-schedule-card-item__title">Maintain a consistent posting schedule.</h3>
				<img alt="Calendar" class="posting-schedule-card-item__image" src="images/vector/calendar.svg">
			</li>
			<li class="benefits-list-1__social-media-schedule-card-item social-media-schedule-card-item">
				<h3 class="social-media-schedule-card-item__title">Schedule to social media.</h3>
				<img alt="Time statistics" class="social-media-schedule-card-item__image" src="images/vector/time-stats.svg" />
				<p class="social-media-schedule-card-item__text">Optimize post timings to publish content at the perfect time for your audience.</p>
			</li>
			<li class="benefits-list-1__followers-growth-card-item followers-growth-card-item">
				<img alt="Growth statistics" class="followers-growth-card-item__image" src="images/vector/growth-stats.svg">
				<h3 class="followers-growth-card-item__title">Grow followers with non-stop content.</h3>
			</li>
			<li class="benefits-list-1__audience-growth-card-item audience-growth-card-item">
				<dl class="audience-growth-card-item__growth-data-list growth-data-list">
					<dt class="growth-data-list__term"><h3 class="audience-growth-card-item__title">faster audience growth</h3></dt>
					<dd class="growth-data-list__value">>56%</dd>
				</dl>
				<div class="audience-growth-card-item__image-group">
					<img alt="Woman showing heart" class="audience-growth-card-item__avatar1" src="images/raster/avatar-1.png">
					<img alt="Boy in mask" class="audience-growth-card-item__avatar2" src="images/raster/avatar-2.png">
					<img alt="Happy man in glasses" class="audience-growth-card-item__avatar3" src="images/raster/avatar-3.png">
				</div>
			</li>
		</ul>
		<ul class="ai-benefits-section__benefits-list-2 benefits-list-2">
			<li class="benefits-list-2__create-content-card-item create-content-card-item">
				<h3 class="create-content-card-item__title" >Create and schedule content <em>quicker.</em></h3>
				<img alt="Button" class="create-content-card-item__image" src="images/vector/button.svg">
			</li>
			<li class="benefits-list-2__ai-generated-content-card-item ai-generated-content-card-item">
				<h3 class="ai-generated-content-card-item__title">Write your content using AI.</h3>
				<img alt="Chat" class="ai-generated-content-card-item__image" src="images/vector/chat.svg">
			</li>
		</ul>
	</div>
</section>

<style>
	.ai-benefits-section {
		position: relative;
		padding: 32rem 16rem 68rem 16rem;
	}

	.ai-benefits-section__wrapper {
		position: relative;
		display: grid;
		grid-template-columns: 100%;
		grid-template-rows: auto;
		row-gap: 32rem;
	}

	.ai-benefits-section__benefits-list-1 {
		grid-column: 1 / -1;
		grid-row: 1 / 2;
	}

	.benefits-list-1 {
		display: grid;
		grid-template-columns: 100%;
		grid-template-rows: auto;
		row-gap: 32rem;
	}

	.benefits-list-1__reviews-card-item {
		grid-column: 1 / -1;
		grid-row: 1 / 2;
	}

	.reviews-card-item {
		border-radius: 10rem;
		padding: 40rem 32rem;
		background: var(--color-purple-500);
	}

	.reviews-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 46rem;
		line-height: 91%;
		letter-spacing: -0.04em;
		text-align: center;
		color: var(--color-white);

		& strong {
			color: var(--color-yellow-500);
		}

		& em {
			font-style: italic;
		}
	}

	.reviews-card-item__image-group {
		display: flex;
		align-items: center;
		justify-content: center;
		column-gap: 8rem;
		margin-top: 18rem;
	}

	.reviews-card-item__image {
		width: 26rem;
		height: 26rem;
		user-select: none;
		pointer-events: none;
	}

	.reviews-card-item__text {
		font-family: var(--font-family), sans-serif;
		font-weight: 400;
		font-size: 18rem;
		line-height: 111%;
		color: var(--color-white);
		text-align: center;
		margin-top: 11rem;
	}

	.benefits-list-1__accounts-card-item {
		grid-column: 1 / -1;
		grid-row: 2 / 3;
	}

	.accounts-card-item {
		border-radius: 10px;
		padding: 16px;
		background: var(--color-white);
	}

	.accounts-card-item__image-group {
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.accounts-card-item__badges {
		width: 316.08rem;
		height: 66.54rem;
		user-select: none;
		pointer-events: none;
	}

	.accounts-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 26px;
		line-height: 92%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		margin-top: 16rem;
	}

	.benefits-list-1__posting-schedule-card-item {
		grid-column: 1 / -1;
		grid-row: 3 / 4;
	}

	.posting-schedule-card-item {
		border-radius: 10rem;
		padding: 16rem 16rem 0 16rem;
		background: var(--color-yellow-500);
		max-height:  216rem;
		overflow: hidden;
	}

	.posting-schedule-card-item__title {
		font-family: var(--font-family),  sans-serif;
		font-weight: 500;
		font-size: 26rem;
		line-height: 92%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		margin-bottom: 11rem;
	}

	.posting-schedule-card-item__image {
		margin-left: -31rem;
		margin-top: -10rem;
		user-select: none;
		pointer-events: none;
	}

	.benefits-list-1__social-media-schedule-card-item {
		grid-column: 1 / -1;
		grid-row: 4 / 5;
	}

	.social-media-schedule-card-item {
		border-radius: 10px;
		padding: 32rem 17rem 32rem 17rem;
		background: var(--color-purple-100);
	}

	.social-media-schedule-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 26rem;
		line-height: 92%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		text-align: center;
		margin-bottom: 19rem;
	}

	.social-media-schedule-card-item__image {
		width: 100%;
		height: 272rem;
		user-select: none;
		pointer-events: none;
	}

	.social-media-schedule-card-item__text {
		font-family: var(--font-family), sans-serif;
		font-weight: 400;
		font-size: 18rem;
		line-height: 111%;
		text-align: center;
		color: var(--color-black);
		margin-top: 22rem;
	}

	.benefits-list-1__followers-growth-card-item {
		grid-column: 1 / -1;
		grid-row: 5 / 6;
	}

	.followers-growth-card-item {
		border-radius: 10rem;
		padding: 24rem;
		background: var(--color-purple-500);
	}

	.followers-growth-card-item__image {
		display: block;
		margin: 0 auto;
		user-select: none;
		pointer-events: none;
	}

	.followers-growth-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 32rem;
		line-height: 87%;
		letter-spacing: -0.06em;
		text-align: center;
		color: var(--color-white);
		margin-top: 33rem;
	}

	.benefits-list-1__audience-growth-card-item {
		grid-column: 1 / -1;
		grid-row: 6 / 7;
	}

	.audience-growth-card-item {
		border-radius: 10rem;
		padding: 24rem;
		background: var(--color-white);
	}

	.audience-growth-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 400;
		font-size: 18rem;
		line-height: 111%;
		color: var(--color-black);
	}

	.audience-growth-card-item__growth-data-list {
		position: relative;
	}

	.growth-data-list {
		display: flex;
		flex-direction: column-reverse;
		row-gap: 15rem;
	}

	.growth-data-list__term {
		position: relative;
	}

	.growth-data-list__value {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 46rem;
		line-height: 91%;
		letter-spacing: -0.04em;
		color: var(--color-black);
	}

	.audience-growth-card-item__image-group {
		margin-top: 23rem;
		display: flex;
		align-items: center;
		justify-content: start;
	}

	.audience-growth-card-item__avatar1 {
		margin-left: unset;
		user-select: none;
		pointer-events: none;
	}

	.audience-growth-card-item__avatar2 {
		margin-left: -11rem;
		user-select: none;
		pointer-events: none;
	}

	.audience-growth-card-item__avatar3 {
		margin-left: -11rem;
		user-select: none;
		pointer-events: none;
	}

	.ai-benefits-section__benefits-list-2 {
		grid-column: 1 / -1;
		grid-row: 2 / 3;
	}

	.benefits-list-2 {
		display: grid;
		grid-template-columns: 100%;
		grid-template-rows: auto;
		row-gap: 32rem;
	}

	.benefits-list-2__create-content-card-item {
		grid-column: 1 / -1;
		grid-row: 1 / 2;
	}

	.create-content-card-item {
		border-radius: 10rem;
		padding: 32rem;
		background: var(--color-yellow-100);
	}

	.create-content-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 32rem;
		line-height: 87%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		margin-bottom: 17rem;

		& em {
			font-style: italic;
			color: var(--color-purple-500);
		}
	}

	.create-content-card-item__image {
		width: auto;
		height: auto;
		user-select: none;
		pointer-events: none;
	}

	.benefits-list-2__ai-generated-content-card-item {
		grid-column: 1 / -1;
		grid-row: 2 / 3;
	}

	.ai-generated-content-card-item {
		border-radius: 10rem;
		padding: 24rem;
		background: var(--color-yellow-500);
	}

	.ai-generated-content-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 32rem;
		line-height: 87%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		margin-bottom: 17rem;
	}

	.ai-generated-content-card-item__image {
		width: auto;
		height: auto;
		user-select: none;
		pointer-events: none;
	}
</style>