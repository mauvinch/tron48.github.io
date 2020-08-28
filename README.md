# tron48.github.io
TRON48 smart contract generates dividends per day based on your investment and distribute your dividends to your balance. For example, if you invest in the 4% plan, then you will get over 100% of your first deposit in twenty eight days. The dividends generate every second and you can withdraw or reinvest your dividends each second. When you reinvest, the total investment would increase and you will get more dividends.

<!DOCTYPE html>
<html lang="en">

<!-- Mirrored from bank-of-tron.com/btt_eng.html by HTTrack Website Copier/3.x [XR&CO'2017], Fri, 28 Aug 2020 21:21:23 GMT -->
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1"/>
	<title>Tron | TRON48 | The best investment game on TRON blockchain.</title>
	<link rel="stylesheet" href="assets/lib/bootstrap/css/bootstrap.min.css">
	<link rel="stylesheet" href="assets/lib/slick/slick.css">
	<link rel="stylesheet" href="../external.html?link=https://fonts.googleapis.com/css?family=Montserrat:300,400,500,600,700%7CWork+Sans:400,500,600,700%7CPlayfair+Display:400,700">
	<link rel="stylesheet" href="../use.fontawesome.com/releases/v5.5.0/css/all.css"  crossorigin="anonymous">
	<link rel="stylesheet" href="assets/css/maindd77.css">
	<link rel="icon" href="assets/images/favicon.png">
</head>
<body>
	<!-- <div id="page-loader"> -->
		<!-- <i class="fab fa-cog fa-spin grad-text grad-2"></i> -->
	<!-- </div> -->

	<header>
		<nav class="side-menu-container" id="mobile-menu">
			<ul class="mx-auto top-level clearfix">
				<li class="with-submenu">
					<a href="index.html">HOME</a>
				</li>
				<li class="with-submenu">
					<a href="#about">ABOUT</a>
				</li>

				<li class="with-submenu">
					<a href="../external.html?link=https://tronscan.org/#/contract/TKHNnSAu9MZB5VgmuEAPxciMY6HFDAEzx5">CONTRACT [TRONSCAN]</a>
				</li>

			</ul>
		</nav>
		<div class="pos-r">
			<div id="topbar" class="clearfix">

				<div class="top-util pull-right">
					<div class="socialnet" >
						<a href="../external.html?link=https://t.me/BankOfTron_ENG" class="socialnet" target="_blank" style="margin-right:15px;"><i class="fab fa-telegram-plane zmdi-lg"></i></a>
						<a href="../external.html?link=https://discord.gg/bGWCsHm" class="socialnet" target="_blank" style="margin-right:15px;"><i class="fab fa-discord zmdi-lg"></i></a>

					</div>
					<div class="lang-selection">
						<a href="#"><img src="assets/images/flag-us.png" alt="us">EN</a>
						<ul class="lang">
							<li><a href="btt_cn.html" style='white-space:nowrap;'><img src="assets/images/flag-cn.png" alt="cn">中文</a></li>
							<li><a href="btt_rus.html"><img src="assets/images/flag-ru.png" alt="ru">RU</a></li>
						</ul>
					</div>
					



					<div class="side-menu">
						<a href="#" class="side-menu-button"><span></span><span></span><span></span></a>
					</div>

				</div>

				<div class="logo pull-left">
					<a href="index.html">
						<h1><img src="assets/images/top-logo.png" alt="logo"></h1>
					</a>
				</div>
				<nav id="desktop-menu">
					<ul class="mx-auto top-level clearfix">
						<li class="with-submenu">
							<a href="index.html" class="link-hover">HOME</a>
						</li>
						<li class="with-submenu">
							<a href="#about" class="link-hover">ABOUT</a>
						</li>

						<li class="with-submenu">
							<a href="../external.html?link=https://tronscan.org/#/contract/TWgRETPF1Gig85vC95eqevAjs5QV7EaV5y" class="link-hover" target="_blank">CONTRACT [TRONSCAN]</a>
						</li>
					
					</ul>

				</nav>
			</div>
		</div>
		<div class="header-content fullheight">
			<div class="slick-header fullheight">

				<div class="header-slide slide-1">
					<img src="assets/images/slider-bg-3.jpg" alt="Slider Background" class="slider-background">
					<div class="container">
						<div class="row">
							<div class="col-md-6 offset-md-6">
								<h2><span class="nowrapped">Get 4% - 7%</span><br><span class="nowrapped">per day!</span></h2>
							</div>
							<div class="col-md-6 offset-md-6">
								<p>
									Decentralized & Secure Smart Contract Fund.
									
								</p>
							</div>
							<div class="col-lg-6 offset-lg-6">
								<a href="#investPlans" class="button-link-1 style-3 pushtop-30">INVEST NOW <i class="fas fa-caret-right"></i></a>	
							</div>
						</div>	
					</div>
				</div>
			</div>
		</div>
	</header>


	<main>
		<div class="widget-9">
			<div class="container">
				<div class="row">
					<div class="col-md-12">
						<div class="portfolio-widget-tabs clearfix text-center">
							<ul class="clearfix pushtop-10">
								<li><a href="index.html" class="link-hover">TRX BANK</a></li>
								<li><a href="#" class="active link-hover">BTT BANK</a></li>
								<li><a class="link-hover" style="">NEW PROJECT [coming soon]</a></li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="widget-20 text-center pushtop-10">
			<p class="pretitle">Bank reserve</p>
			<h3 id="contractBalance" style="color:#666"><i class="fas fa-spinner fa-spin"></i> TRX</h3>
			<br>Your TRON wallet: <b id="yourAcc"><i class="fas fa-spinner fa-spin"></i></b>
			<br>Your wallet balance: <b id="accBalance"><i class="fas fa-spinner fa-spin"></i></b> TRX
			

			<div class="container" id="investPlans">
				<div class="row pushtop-50">

					<div class="col-lg-6 col-xl-3">
						<div class="plan-box box-1 pushtop-30" style="background:#333;color:#f4fbfd">
							<p class="pretitle">Diamond Plan<br>[ <span class="text-orange">Daily ROI</span> ]</p>
							<p class="price-main"><span class="price">4%</span></p>
							<ul class="text-left">
								<li>Dividends every second</li>
								<li><b>100</b></li>
								<li>Total return <b> 300 </b></b></li>
								<li>Min. investment is 30TRX</li>								
								<br><br>
								<div class="input-group mb-2 mr-sm-2" style="position:relative; left:23px;">							
									<input type="text" autocomplete="off" placeholder="0" min="10" class="form-control text-center" id="trxForPlan0">
									<div class="input-group-append text-orange">
									 
									</div>				
								</div>									
							</ul>
							<div class="text-center text-orange">
							You should have ~3 TRX<br>for the transaction fee 
							</div>									
							<a href="javascript: invest(0)" class="button-link-1">INVEST</a>
							
							
						</div>
					</div>

					<div class="col-lg-6 col-xl-3">
						<div class="plan-box box-2 pushtop-30" style="background:#333;color:#f4fbfd">
							<p class="pretitle"> GOLDEN Plan<br>[ <span class="text-orange">Daily ROI</span> ]</p>
							<p class="price-main"><span class="price">5%</span></p>
							<ul>
								<li>Dividends every second</li>
								<li><b>50days</b></li>
								<li>Total return <b>220%</b></li>
								<li>Min. investment is 30TRX</li>								
								<br><br>
								<div class="input-group mb-2 mr-sm-2" style="position:relative; left:23px;">							
									<input type="text" autocomplete="off" placeholder="0" min="10" class="form-control text-center" id="trxForPlan1">
									<div class="input-group-append text-orange">
									</div>				
								</div>	
							</ul>
							<div class="text-center text-orange">
							You should have ~3 TRX TRX<br>for the transaction fee 
							</div>									
							<a href="javascript: invest(1)" class="button-link-1">INVEST</a>
							
						</div>
					</div>

					<div class="col-lg-6 col-xl-3">
						<div class="plan-box box-3 pushtop-30" style="background:#333;color:#f4fbfd">
							<p class="pretitle">SILVER Plan<br>[ <span class="text-orange">Daily ROI</span> ]</p>
							<p class="price-main"><span class="price">6%</span></p>
							<ul>
								<li>Dividends every second</li>
								<li><b>30 days</b></li>
								<li>Total return <b>145%</b></li>
								<li>Min. investment is 30TRX </li>								
								<br><br>
								<div class="input-group mb-2 mr-sm-2" style="position:relative; left:23px;">							
									<input type="text" autocomplete="off" placeholder="0" min="10" class="form-control text-center" id="trxForPlan2">
									<div class="input-group-append text-orange">
									</div>				
								</div>	
							</ul>
							<div class="text-center text-orange">
							You should have 3 TRX<br>for the transaction fee 
							</div>									
							<a href="javascript: invest(2)" class="button-link-1">INVEST</a>
							
						</div>
					</div>

					<div class="col-lg-6 col-xl-3">
						<div class="plan-box box-4 pushtop-30" style="background:#333;color:#f4fbfd"> 
							<p class="pretitle"> NOOBIE Plan<br>[ <span class="text-orange">Daily ROI</span> ]</p>
							<p class="price-main"><span class="price">7%</span></p>
							<ul>
								<li>Dividends every second</li>
								<li><b>21days</b></li>
								<li>Total return <b>125</b></li>
								<li>Min. investment is 30 TRX</li>								
								<br><br>
								<div class="input-group mb-2 mr-sm-2" style="position:relative; left:23px;">							
									<input type="text" autocomplete="off" placeholder="0" min="10" class="form-control text-center" id="trxForPlan3">
									<div class="input-group-append text-orange">
									</div>				
								</div>	
							</ul>
							<div class="text-center text-orange">
							You should have ~3 TRX<br>for the transaction fee 
							</div>									
							<a href="javascript: invest(3)" class="button-link-1">INVEST</a>
							
						</div>
					</div>					

				</div>
			</div>
		</div>
		
		<div class="widget-4 pushtop-130 drag-this-up">
			<div class="container">
				<div class="widget4-wrapper">

					<div class="widget-4-progress-detail">
						<div class="widget-4-progress-item item-1 active">
							<div class="row">
								<div class="col-md-6">
									<h4><i class="fas fa-coins"></i> Dividents</h4>
									<br>Referral rewards
									<br><b id="availableReferrerEarnings">0.00</b> TRX
									<br><br>Withdrawable(referral rewards included)
									<br><b id="withdrawable">0.00</b> TRX
									<a href="javascript:withdraw()" class="button-link-1 pushtop-30" id="withdrawButton">WITHDRAW</a>
									<br>
									My total investment <b class="totalInvestment" id="totalInvestment">0.00</b> TRX
									<br>
									Total dividends so far <b class="totalDivs" id="totalDivs">0.00</b> TRX
								</div>
								<div class="col-md-6">
									<h4><i class="fas fa-user-friends"></i> Referral program</h4>
									<br>Your referral link [<a href='javascript:copyRef()' id="copy">COPY LINK</a>]: 
									<div id="yourRefLink" style="font-weight:bold;">no link...</div>
									You can get your referral link after investing.<br>
									
									<br>1 referral （5% Referral rewards） - <b id="level1RefCount">0</b>
									<br>2 referral （2% Referral rewards） - <b id="level2RefCount">0</b>
									<br>3 referral （0.5% Referral rewards） - <b id="level3RefCount">0</b>
									<br>Invitee (0.5% of the investment)
									<br><br>Total referral rewards payout - <b id="referrerEarnings">0.00</b> TRX
								</div>
							</div>
						</div>
						
					</div>
				</div>
			</div>
		</div>		

		<div class="widget-2 text-left pushtop-100 drag-this-up" id="widget-2">
			<div class="container">
				<div class="row">
					<div class="col-lg-6">
						
						<h3><i class="fas fa-university"></i> My investments</h3><br><br>
						<div id="myIvestments"></div>
						My total investment <b class="totalInvestment">0.00</b> TRX
						<br>
						Total dividends so far <b class="totalDivs">0.00</b> TRX						
						<br>						
						<a href="#investPlans" class="button-link-1 style-3 pushtop-30">INVEST NOW <i class="fas fa-caret-right"></i></a>
					</div>
					<div class="col-lg-6">
						<img src="assets/images/widget-2-1.png" alt="widget-image">
					</div>
				</div>
			</div>
		</div>
		<div class="widget-1 text-center pushtop-80" id="about">
			<div class="container">
				<div class="row">
					<div class="col-md-4 drag-this-left">
						<section>
							<div class="image-holder">
								<img src="assets/images/widget-1-1.png" alt="widget-image">
							</div>
							<h6>Safe and reliable project</h6>
							<p>
								   TRON48 runs automatically on the blockchain and its smart contract is uploaded to the TRON blockchain. No one is able to edit or delete the smart contract, nor influence its autonomous operation. The dividends are also automatically paid through the smart contract.
							</p>
						</section>
					</div>
					<div class="col-md-4 drag-this-up">
						<section>
							<div class="image-holder">
								<img src="assets/images/widget-1-2.png" alt="widget-image">
							</div>
							<h6>Dividend distribute</h6>
							<p>
								  TRON48 smart contract generates 4%-7% dividends per day based on your investment and distribute your dividends to your balance. For example, if you invest in the 4% plan, then you will get over 100% of your first deposit in 28 days. The dividends generate every second and you can withdraw or reinvest your dividends each second. When you reinvest, the total investment would increase and you will get more dividends.
							</p>
						</section>
					</div>
					<div class="col-md-4 drag-this-right">
						<section>
							<div class="image-holder">
								<img src="assets/images/widget-1-3.png" alt="widget-image">
							</div>
							<h6>Referral program</h6>
							<p>
								TRON48 smart contract set 3 tiers of referral rewards, which are 8%, 3%, and 1.5% respectively. Moreover, the invitee can also get 1.5% of his/her own investment as rewards. The referral rewards are distributed to your balance automatically and you can withdraw at anytime.
							</p>
						</section>
					</div>
				</div>
			</div>
		</div>




	



		<div class="widget-7">
			<div class="rising-elements text-center">
				<div class="rising-elm elm-1" data-trigger="400">
					<div class="rising-inner">
						<img src="assets/images/widget-7-elm-1.png" alt="element-image">
						<h6>How to invest on desktop?</h6>
						<p>You can install the <a href="../external.html?link=https://chrome.google.com/webstore/detail/tronlink/ibnejdfjmmkpcnlpebklmnkoeoihofec?utm_source=chrome-ntp-icon" target="_blank">TronLink</a> or <a href="../external.html?link=https://chrome.google.com/webstore/detail/tronpay/gjTWgRETPF1Gig85vC95eqevAjs5QV7EaV5=zh-CN" target="_blank">TronPay</a> extension on Chrome. After the installation, you can create a new BTT wallet or import an existing BTT wallet, and then transfer the BTT from the exchange to the wallet. Finally, login on TronLink or TronPay to browse this website and invest.</p>
					</div>
					<div class="img-pin"></div>
				</div><div class="rising-elm elm-2" data-trigger="800">
					<div class="rising-inner">
						<img src="assets/images/widget-7-elm-2.png" alt="element-image">
						<h6>How to invest on mobile?</h6>
						<p>You can download <a href="../external.html?link=https://www.bankowallet.com/" target="_blank">Banko Wallet</a>、<a href="../external.html?link=http://www.mathwallet.org/en/" target="_blank">Math Wallet</a> or <a href="../external.html?link=https://www.tronwallet.me/" target="_blank">TronWallet</a> app from application store. After the installation, you can create a new TRX wallet or import an existing TRX wallet, and then transfer the TRX from the exchange to the wallet. Finally, find TRON48 within the wallet app or browse our site with the browser in the app, and then go to invest or withdraw.</p>
					</div>
					<div class="img-pin"></div>
				</div><div class="rising-elm elm-3" data-trigger="600">
					<div class="rising-inner">
						<img src="assets/images/widget-7-elm-4.png" alt="element-image">
						<h6>How is the fund distributed?</h6>
						<p>Technical support: 4% Marketing: 4% Referral: 6%-3%-1.5% Invitee: 1.5%</p>
					</div>					
					<div class="img-pin"></div>
				</div><div class="rising-elm elm-4" data-trigger="400">
					<div class="rising-inner">
						<img src="assets/images/widget-7-elm-3.png" alt="element-image">
						<h6>What is the referral program?</h6>
						<p>TRON48 smart contract set 3 tiers of referral rewards, which are 4%, 3%, and 1.5% respectively. Moreover, the invitee can also get 1.5% of his/her own investment as rewards. The referral rewards are distributed to your balance automatically and you can withdraw at anytime.</p>
					</div>
					<div class="img-pin"></div>
				</div>
			</div>

			<div class="widget-7-main text-center">
				<div class="container">
					<h3><img src="assets/images/logo.png" alt="logo" style="position:relative; top: -5px;">  TRON48</h3>
					<p class="mx-auto">
						Contact us
					</p>
				</div>
				<div class="buttons pushtop-10">
					<a href="../external.html?link=https://t.me/Tron48_ENG" target="_blank" class="socialnet" style="font-size: 2em; color:#fff"><i class="fab fa-telegram-plane"></i></a>
					&nbsp;&nbsp;&nbsp;
					<a href="../external.html?link=https://discord.gg/bGWCsHm" target="_blank" class="socialnet" style="font-size: 2em; color:#fff"><i class="fab fa-discord"></i></a>
				</div>
			</div>
		</div>

		<a href="#"></a>

	</main>







<script>
var lang="eng";
var inProcessing="In the processing...";
var error1="Error: It wasn't a number";
</script>
<script src="assets/lib/jquery/jquery.js"></script>
<script src="assets/lib/jquery-ui/jquery-ui.min.js"></script>
<script src="assets/lib/visible/visible.js"></script>
<script src="assets/lib/imagesLoaded/imagesLoaded.min.js"></script>
<script src="assets/js/main.js"></script>
<script src="assets/js/TronWeb.js"></script>
<script src="assets/js/bttc5b6.js"></script>
</body>

<!-- Mirrored from bank-of-tron.com/btt_eng.html by HTTrack Website Copier/3.x [XR&CO'2017], Fri, 28 Aug 2020 21:21:23 GMT -->
</html>
