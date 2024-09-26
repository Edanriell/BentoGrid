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
					<img alt="Instagram badge" class="accounts-card-item__instagram-badge" src="images/vector/instagram-badge.svg">
					<img alt="X badge" class="accounts-card-item__x-badge" src="images/vector/x-badge.svg">
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

		@media (width >= 768px) {
			padding: 52rem 40rem 76rem 40rem;
		}

		@media (width >= 1440px) {
			padding: 83rem 160rem 65rem 160rem;
		}
	}

	.ai-benefits-section__wrapper {
		position: relative;
		display: grid;
		grid-template-columns: 100%;
		grid-template-rows: auto;
		row-gap: 32rem;

		@media (width >= 1440px) {
			grid-template-columns: 1fr 3fr;
			column-gap: 32rem;
		}
	}

	.ai-benefits-section__benefits-list-1 {
		grid-column: 1 / -1;
		grid-row: 1 / 2;

		@media (width >= 1440px) {
			grid-column: 2 / 3;
			grid-row: 1 / -1;
		}
	}

	.benefits-list-1 {
		display: grid;
		grid-template-columns: 100%;
		grid-template-rows: auto;
		row-gap: 32rem;

		@media (width >= 768px) {
			grid-template-columns: repeat(2, 1fr);
			column-gap: 32rem;
		}

		@media (width >= 1440px) {
			grid-template-columns: repeat(3, 1fr);
			grid-template-rows: 324rem 247rem 247rem;
		}
	}

	.benefits-list-1__reviews-card-item {
		grid-column: 1 / -1;
		grid-row: 1 / 2;

		@media (width >= 1440px) {
			grid-column: 1 / 3;
		}
	}

	.reviews-card-item {
		border-radius: 10rem;
		padding: 40rem 32rem;
		background: var(--color-purple-500);

		@media (width >= 768px) {
			padding: 72rem 76rem;
		}

		@media (width >= 1440px) {
			padding: 62rem 32rem;
		}
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
			font-weight: 500;
		}

		& em {
			font-style: italic;
			font-weight: 500;
		}

		@media (width >= 768px) {
			font-size: 54rem;
			line-height: 89%;
			padding: 0 43rem;
		}

		@media (width >= 1440px) {
			font-size: 62rem;
			line-height: 94%;
			letter-spacing: -0.05em;
			padding: unset;
		}
	}

	.reviews-card-item__image-group {
		display: flex;
		align-items: center;
		justify-content: center;
		column-gap: 8rem;
		margin-top: 24rem;
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
		margin-top: 8rem;
	}

	.benefits-list-1__accounts-card-item {
		grid-column: 1 / -1;
		grid-row: 2 / 3;

		@media (width >= 768px) {
			grid-column: 1 / 2;
			grid-row: 2 / 3;
		}
	}

	.accounts-card-item {
		border-radius: 10px;
		padding: 16rem;
		background: var(--color-white);
		overflow: hidden;

		@media (width >= 768px) {
			padding: 24rem;
		}
	}

	.accounts-card-item__image-group {
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.accounts-card-item__instagram-badge {
		margin-top: -12rem;
		margin-left: -6rem;
		margin-bottom: -36rem;
		user-select: none;
		pointer-events: none;

		@media (width >= 768px) {
			margin-top: -12rem;
			margin-left: 40rem;
			margin-bottom: -36rem;
		}

		@media (width >= 1440px) {
			margin-top: -12rem;
			margin-left: 116rem;
			margin-bottom: -36rem;
		}
	}

	.accounts-card-item__x-badge {
		margin-left: -36rem;
		margin-top: -12rem;
		margin-bottom: -36rem;
		user-select: none;
		pointer-events: none;

		@media (width >= 768px) {
			margin-left: -40rem;
			margin-top: -12rem;
			margin-bottom: -36rem;
		}

		@media (width >= 1440px) {
			margin-left: -44rem;
			margin-top: -12rem;
			margin-bottom: -36rem;
		}
	}

	.accounts-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 26px;
		line-height: 92%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		margin-top: 16rem;

		@media (width >= 768px) {
			font-size: 28rem;
			line-height: 93%;
			text-align: left;
			padding-right: 30rem;
			margin-top: 54rem;
		}

		@media (width >= 1440px) {
			font-size: 32rem;
			line-height: 87%;
			margin-top: 20rem;
			padding-right: unset;
		}
	}

	.benefits-list-1__posting-schedule-card-item {
		grid-column: 1 / -1;
		grid-row: 3 / 4;

		@media (width >= 768px) {
			grid-column: 2 / 3;
			grid-row: 2 / 3;
		}
	}

	.posting-schedule-card-item {
		border-radius: 10rem;
		padding: 16rem 16rem 0 16rem;
		background: var(--color-yellow-500);
		max-height: 216rem;
		overflow: hidden;

		@media (width >= 768px) {
			padding: 24rem 24rem 0 24rem;
			max-height: unset;
		}
	}

	.posting-schedule-card-item__title {
		font-family: var(--font-family),  sans-serif;
		font-weight: 500;
		font-size: 26rem;
		line-height: 92%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		margin-bottom: 16rem;

		@media (width >= 768px) {
			font-size: 28rem;
			line-height: 93%;
		}

		@media (width >= 1440px) {
			font-size: 32rem;
			line-height: 87%;
		}
	}

	.posting-schedule-card-item__image {
		margin-left: -31rem;
		margin-top: -14rem;
		user-select: none;
		pointer-events: none;

		@media (width >= 768px) {
			margin-top: -14rem;
			margin-bottom: -2rem;
		}

		@media (width >= 1440px) {
			margin-top: -12rem;
			margin-bottom: unset;
		}
	}

	.benefits-list-1__social-media-schedule-card-item {
		grid-column: 1 / -1;
		grid-row: 4 / 5;

		@media (width >= 768px) {
			grid-column: 1 / -1;
			grid-row: 3 / 4;
		}

		@media (width >= 1440px) {
			grid-column: 3 / 4;
			grid-row: 1 / 3;
		}
	}

	.social-media-schedule-card-item {
		border-radius: 10px;
		padding: 32rem 17rem 32rem 17rem;
		background: var(--color-purple-100);

		@media (width >= 1440px) {
			padding: 50rem 32rem 50rem 32rem;
			position: relative;
			overflow: hidden;
		}
	}

	.social-media-schedule-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 26rem;
		line-height: 92%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		text-align: center;
		margin-bottom: 24rem;

		@media (width >= 768px) {
			font-size: 28rem;
			line-height: 93%;
		}

		@media (width >= 1440px) {
			font-size: 32rem;
			line-height: 87%;
			text-align: left;
		}
	}

	.social-media-schedule-card-item__image {
		width: 100%;
		height: 272rem;
		user-select: none;
		pointer-events: none;

		@media (width >= 768px) {
			height: 318rem;
		}

		@media (width >= 1440px) {
			width: 357rem;
		}
	}

	.social-media-schedule-card-item__text {
		font-family: var(--font-family), sans-serif;
		font-weight: 400;
		font-size: 18rem;
		line-height: 111%;
		text-align: center;
		color: var(--color-black);
		margin-top: 24rem;

		@media (width >= 768px) {
			padding: 0 140rem;
		}

		@media (width >= 1440px) {
			padding: unset;
			text-align: left;
		}
	}

	.benefits-list-1__followers-growth-card-item {
		grid-column: 1 / -1;
		grid-row: 5 / 6;

		@media (width >= 768px) {
			grid-column: 1 / -1;
			grid-row: 4 / 5;
		}

		@media (width >= 1440px) {
			grid-column: 2 / -1;
			grid-row: 3 / 4;
		}
	}

	.followers-growth-card-item {
		border-radius: 10rem;
		padding: 24rem;
		background: var(--color-purple-500);

		@media (width >= 768px) {
			padding: 23rem 82rem;
			display: flex;
			flex-direction: row;
			align-items: center;
			justify-content: center;
			column-gap: 40rem;
		}

		@media (width >= 1440px) {
			padding: 23rem 24rem;
			column-gap: 7rem;
		}
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

		@media (width >= 768px) {
			font-size: 36rem;
			line-height: 83%;
			margin-top: unset;
			text-align: left;
			padding-right: 14rem;
		}

		@media (width >= 1440px) {
			padding-right: unset;
			font-size: 40rem;
			line-height: 90%;
			letter-spacing: -0.05em;
		}
	}

	.benefits-list-1__audience-growth-card-item {
		grid-column: 1 / -1;
		grid-row: 6 / 7;

		@media (width >= 768px) {
			grid-column: 1 / -1;
			grid-row: 5 / 6;
		}

		@media (width >= 1440px) {
			grid-column: 1 / 2;
			grid-row: 3 / 4;
		}
	}

	.audience-growth-card-item {
		border-radius: 10rem;
		padding: 24rem;
		background: var(--color-white);

		@media (width >= 768px) {
			display: flex;
			flex-direction: row;
			align-items: center;
			justify-content: space-between;
		}

		@media (width >= 1440px) {
			flex-direction: column;
			justify-content: start;
			align-items: start;
		}
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

		@media (width >= 768px) {
			font-size: 54rem;
			line-height: 89%;
		}

		@media (width >= 1440px) {
			font-size: 62rem;
			line-height: 94%;
			letter-spacing: -0.05em;
		}
	}

	.audience-growth-card-item__image-group {
		margin-top: 24rem;
		display: flex;
		align-items: center;
		justify-content: start;

		@media (width >= 768px) {
			margin-top: unset;
		}

		@media (width >= 1440px) {
			margin-top: 38rem;
		}
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

		@media (width >= 1440px) {
			grid-column: 1 / 2;
			grid-row: 1 / -1;
		}
	}

	.benefits-list-2 {
		display: grid;
		grid-template-columns: 100%;
		grid-template-rows: auto;
		row-gap: 32rem;

		@media (width >= 768px) {
			grid-template-columns: repeat(2, 1fr);
			column-gap: 32rem;
		}

		@media (width >= 1440px) {
			grid-template-columns: 100%;
			grid-template-rows: repeat(2, auto);
		}
	}

	.benefits-list-2__create-content-card-item {
		grid-column: 1 / -1;
		grid-row: 1 / 2;

		@media (width >= 768px) {
			grid-column: 1 / 2;
			grid-row: 1 / 2;
		}

		@media (width >= 1440px) {
			grid-column: 1 / -1;
			grid-row: 1 / 2;
		}
	}

	.create-content-card-item {
		border-radius: 10rem;
		padding: 32rem;
		background: var(--color-yellow-100);

		@media (width >= 768px) {
			padding: 75rem 24rem;
		}

		@media (width >= 1440px) {
			padding: 78rem 32rem;
		}
	}

	.create-content-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 32rem;
		line-height: 87%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		margin-bottom: 24rem;

		& em {
			font-style: italic;
			color: var(--color-purple-500);
		}

		@media (width >= 768px) {
			font-size: 36rem;
			line-height: 83%;
		}

		@media (width >= 1440px) {
			font-size: 40rem;
			line-height: 90%;
			letter-spacing: -0.05em;
		}
	}

	.create-content-card-item__image {
		width: auto;
		height: auto;
		user-select: none;
		pointer-events: none;

		@media (width >= 1440px) {
			margin-bottom: -28rem;
		}
	}

	.benefits-list-2__ai-generated-content-card-item {
		grid-column: 1 / -1;
		grid-row: 2 / 3;

		@media (width >= 768px) {
			grid-column: 2 / 3;
			grid-row: 1 / 2;
		}

		@media (width >= 1440px) {
			grid-column: 1 / -1;
			grid-row: 2 / 3;
		}
	}

	.ai-generated-content-card-item {
		border-radius: 10rem;
		padding: 24rem;
		background: var(--color-yellow-500);
		position: relative;

		@media (width >= 1440px) {
			display: flex;
			flex-direction: column;
			align-items: center;
		}
	}

	.ai-generated-content-card-item__title {
		font-family: var(--font-family), sans-serif;
		font-weight: 500;
		font-size: 32rem;
		line-height: 87%;
		letter-spacing: -0.06em;
		color: var(--color-black);
		margin-bottom: 24rem;

		@media (width >= 768px) {
			font-size: 36rem;
			line-height: 83%;
			padding-right: 20rem;
		}

		@media (width >= 1440px) {
			font-size: 40rem;
			line-height: 90%;
			letter-spacing: -0.05em;
			padding-right: 20rem;
			margin-bottom: 55rem;
		}
	}

	.ai-generated-content-card-item__image {
		width: auto;
		height: auto;
		user-select: none;
		pointer-events: none;

		@media (width >= 1440px) {
			display: block;
			margin-right: -32rem;
			margin-bottom: -29rem;
		}
	}
</style>