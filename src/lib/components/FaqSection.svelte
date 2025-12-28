<script>
	import { FaqItem, Button } from '$components';
	import twitterIcon from '$assets/icons/twitter.webp';
</script>

<section class="landing-page-section">
	<h2 class="mb-l">Frequently asked questions</h2>
	<div class="faq-container">
		<FaqItem />
	</div>
	<div class="additional-info">
		<Button class="mt-s">BUY NOW</Button>
		<p class="mt-m">Any other questions?</p>
		<a href="https://x.com/KIZO_ES">
			<p>Hit me up on twitter <img src={twitterIcon} alt="" class="twitter-icon" /></p></a
		>
	</div>
</section>

<style>
  .additional-info {
    display: flex;
    flex-direction: column;
    align-items: center;
    color: gray;
  }

  .twitter-icon {
    width: 16px;
    height: 16px;
  }

  .additional-info a {
    text-decoration: underline;
  }
</style>
