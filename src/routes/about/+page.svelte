<script>
	import Footer from "$lib/footer.svelte";
	import Header from "$lib/header.svelte";
	import Event from "$lib/horizontal_timeline/event.svelte";
	import Timeline from "$lib/horizontal_timeline/timeline.svelte";

</script>
<Header />
<div class="page_title section-padding">
	<div class="container">
		<div class="row">
			<div class="col-xl-12">
				<div class="page_title-content">
					<p>About Us</p>
					<h3>Who we are</h3>
				</div>
			</div>
		</div>
	</div>
</div>

<div class="about">
	<div class="container">
		<div class="row">
			<div class="col-xl-12">
				<div class="about_content">
					<div class="our_vision">
						<h3>OUR VISION</h3>
						<p>
							The growth of virtual items and microtransactions have been enormous over the last few
							years. The prices for these items or microtransactions are often twice the price of
							the game itself. We understand people want these exclusive in-game rewards, but we
							also see how they are too expensive for many. Therefore we came up with the idea,
							CoinGain.
						</p>
						<p>
							We started providing a service directly targeted towards the game Counter-Strike:
							Global Offensive, however, we quickly came to realize this had the potential to reach
							a much broader audience. Now we have expanded our service for not only gamers, but
							also others that want gift cards to shop at their favorite place, cryptocurrencies to
							start their crypto adventure, or just direct PayPal cash to spend on whatever you
							want.
						</p>
						<p>
							We’re excited for what the future has to bring, and we will continuously be pushing
							out updates and new features to keep CoinGain the leading platform in the GPT industry
						</p>
					</div>
				</div>

				<div class="about_timeline">
					<Timeline>
						<Event date="01/01/2018">
							<div class="timeline_content">
								<div class="row">
									<div class="col-xl-5">
										<div class="timeline_content-left">
											<img src="images/svg/timeline1.svg" alt="" />
											<h2>The idea</h2>
											<p>23 September <br /> <span>2018</span></p>
										</div>
									</div>
									<div class="col-xl-7">
										<div class="timeline_content-right">
											<p>
												With the growth of virtual items and microtransactions we see a problem.
												In-game items & microtransactions are too expensive. The idea of a site
												such as CoinGain is born.
											</p>
										</div>
									</div>
								</div>
							</div>
						</Event>
						<Event date="01/02/2018">
							<div class="timeline_content">
								<div class="row">
									<div class="col-xl-5">
										<div class="timeline_content-left">
											<img src="images/svg/timeline2.svg" alt="" />
											<h2>Development starts</h2>
											<p>October 5 <br /> <span>2018</span></p>
										</div>
									</div>
									<div class="col-xl-7">
										<div class="timeline_content-right">
											<p>The first version of CoinGain is under development.</p>
										</div>
									</div>
								</div>
							</div>
						</Event>
						<Event date="01/03/2018">
							<div class="timeline_content">
										<div class="row">
											<div class="col-xl-5">
												<div class="timeline_content-left">
													<img src="images/svg/timeline3.svg" alt="" />
													<h2>Website launches</h2>
													<p>October 21 <br /> <span>2018</span></p>
												</div>
											</div>
											<div class="col-xl-7">
												<div class="timeline_content-right">
													<p>
														CoinGain has officially launched. Few users start to visit. The growth
														has started, and we’re excited to see the website in action.
													</p>
												</div>
											</div>
										</div>
									</div>
						</Event>
						<Event date="01/04/2018">
									<div class="timeline_content">
										<div class="row">
											<div class="col-xl-5">
												<div class="timeline_content-left">
													<img src="images/svg/timeline4.svg" alt="" />
													<h2>10.000 Users reached</h2>
													<p>February 3 <br /> <span>2021</span></p>
												</div>
											</div>
											<div class="col-xl-7">
												<div class="timeline_content-right">
													<p>
														We reach 10,000+ users on our website. A huge milestone for us at the
														time.
													</p>
												</div>
											</div>
										</div>
									</div>
						</Event>
						<Event date="01/05/2018">
							<div class="timeline_content">
										<div class="row">
											<div class="col-xl-5">
												<div class="timeline_content-left">
													<img src="images/svg/timeline5.svg" alt="" />
													<h2>Major Revamp</h2>
													<p>March 25 <br /> <span>2021</span></p>
												</div>
											</div>
											<div class="col-xl-7">
												<div class="timeline_content-right">
													<p>
														The website’s user interface gets a brand new look and loads of new
														features was added.
													</p>
												</div>
											</div>
										</div>
									</div>
						</Event>
						<Event date="01/06/2018">
							<div class="timeline_content">
								<div class="row">
									<div class="col-xl-5">
										<div class="timeline_content-left">
											<img src="images/svg/timeline6.svg" alt="" />
											<h2>More Functions Added</h2>
											<p>March 29 <br /> <span>2021</span></p>
										</div>
									</div>
									<div class="col-xl-7">
										<div class="timeline_content-right">
											<p>
												Exclusive features such as Daily Reward, more withdrawal options, and
												brand new offer providers gets added.
											</p>
										</div>
									</div>
								</div>
							</div>
						</Event>
						<Event date="01/07/2018">
							<div class="timeline_content">
											<div class="row">
												<div class="col-xl-5">
													<div class="timeline_content-left">
														<img src="images/svg/timeline7.svg" alt="" />
														<h2>50.000 Users reached</h2>
														<p>April 27 <br /> <span>2021</span></p>
													</div>
												</div>
												<div class="col-xl-7">
													<div class="timeline_content-right">
														<p>
															We reached another milestone. 50,000 users registered, and we’re still
															growing.
														</p>
													</div>
												</div>
											</div>
										</div>
						</Event>
						<Event date="01/08/2018">
							<div class="timeline_content">
								<div class="row">
									<div class="col-xl-5">
										<div class="timeline_content-left">
											<img src="images/svg/timeline8.svg" alt="" />
											<h2>The future of CoinGain</h2>
										</div>
									</div>
									<div class="col-xl-7">
										<div class="timeline_content-right">
											<p>
												Today, we have over 70,000 users from all around the globe. We believe
												this is just the beginning. We’ll always keep the website updated and
												make sure we are the leading website in the GPT Industry
											</p>
										</div>
									</div>
								</div>
							</div>
						</Event>
					</Timeline>
				</div>
			</div>
		</div>
	</div>
</div>

<Footer />

<div class="ani-12">
	<img class="a1" src="images/svg/brown_circle.svg" alt="" />
	<img class="a2" src="images/svg/polygon.svg" alt="" />
	<img class="a3" src="images/svg/circleline.svg" alt="" />
</div>
