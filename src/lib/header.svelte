<script>
	import { ArrowDownIcon, ChevronDownIcon, UserIcon } from "svelte-feather-icons";
</script>
<div class="header dashboard @@headerClass">
		<div class="container">
			<div class="row">
				<div class="col-xl-12">
					<nav class="navbar navbar-expand-lg navbar-light">
						<a class="navbar-brand" href="index.html"><img src="images/logo.png" alt="" /></a>
						<button
							class="navbar-toggler"
							type="button"
							data-bs-toggle="collapse"
							data-bs-target="#navbarSupportedContent"
							aria-controls="navbarSupportedContent"
							aria-expanded="false"
							aria-label="Toggle navigation"
						>
							<span class="navbar-toggler-icon"></span>
						</button>

						<div class="collapse navbar-collapse" id="navbarSupportedContent">
							<ul class="navbar-nav menu">
								<li class="nav-item">
									<a class="nav-link" href="shop.html">Shop</a>
								</li>
								<li class="nav-item">
									<a class="nav-link" href="affiliate.html">Affiliates</a>
								</li>
								<li class="nav-item">
									<a class="nav-link" href="leaderboard.html">Leaderboards</a>
								</li>
								<!-- <li class="nav-item">
                                <a class="nav-link" href="dice.html">Dice</a>
                            </li> -->
								<li class="nav-item">
									<a class="nav-link" href="support.html">Support</a>
								</li>
							</ul>
						</div>
						<div class="dashboard_log my-2">
							<div class="d-flex align-items-center">
								<div class="account_money">
									<ul>
										<li class="crypto">
											<span>2500</span>
											<img src="images/icon/gem.svg" alt="" />
										</li>
										<li class="usd">
											<span>4000 USD</span>
										</li>
									</ul>
								</div>
								<div class="profile_log dropdown">
									<div class="user" data-bs-toggle="dropdown">
										<span class="thumb"><UserIcon size={"20"} /> </span>
										<span class="name">Thomas Christ</span>
										<span class="arrow"><ChevronDownIcon /></span>
									</div>
									<div class="dropdown-menu dropdown-menu-end show">
										<a href="profile.html" class="dropdown-item">
											<UserIcon />
											Profile
										</a>
										<a href="history.html" class="dropdown-item">
											<i class="la la-book"></i>
											History
										</a>
										<a href="https://coingain.vercel.app/setting.html" class="dropdown-item">
											<i class="la la-cog"></i>
											Setting
										</a>
										<a href="index.html" class="dropdown-item logout">
											<i class="la la-sign-out"></i>
											Logout
										</a>
									</div>
								</div>
							</div>
						</div>
					</nav>
				</div>
			</div>
		</div>
	</div>