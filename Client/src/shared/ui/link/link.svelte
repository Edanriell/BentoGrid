<script>
	export const text = "Go Back to Home";
	export const href = "/";
</script>

<a class="link" href={href}>{text}</a>

<style>
	.link {
		border-radius: 43rem;
		padding: 17rem 25rem;
		background-color: var(--color-yellow-500);
		font-family: var(--second-family), sans-serif;
		font-weight: 600;
		font-size: 19rem;
		color: var(--color-purple-500);
		transition: background-color 0.6s cubic-bezier(0.165, 0.84, 0.44, 1), transform 0.6s cubic-bezier(0.165, 0.84, 0.44, 1), box-shadow 0.6s cubic-bezier(0.165, 0.84, 0.44, 1);
		will-change: background-color, transform, box-shadow;

		&:hover {
			background-color: hsl(39, 100%, 64%);
			transform: scale(1.05);
			box-shadow: 0 10rem 20rem 2rem rgba(0, 0, 0, 0.1);
		}

		&:focus {
			background-color: hsl(39, 100%, 64%);
			transform: scale(1.05);
			box-shadow: 0 10rem 20rem 2rem rgba(0, 0, 0, 0.1);
		}

		&:active {
			&:focus {
				background-color: hsl(39, 100%, 64%);
				transform: scale(0.95);
				box-shadow: 0 10rem 30rem 2rem rgba(0, 0, 0, 0.1);
			}
		}
	}
</style>