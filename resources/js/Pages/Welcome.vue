<template>
    <!-- <Head title="Inicio" /> -->
    <app-layout title="Inicio">
    <template #header>
        <!-- <div v-if="canLogin">
            <Link v-if="$page.props.user" :href="route('dashboard')">
                Dashboard
            </Link>

            <template v-else>
                <Link :href="route('login')"> Log in </Link>

                <Link v-if="canRegister" :href="route('register')">
                    Register
                </Link>
            </template>
        </div> -->

        <body class="blue-skin">
            <div id="main-wrapper">
		
            <!-- ============================================================== -->
            <!-- Top header  -->
            <!-- ============================================================== -->
            <!-- Start Navigation -->


            <!-- **************** -->
			<!-- <div class="header header-light">
				<div class="container">
					<div class="row">
						<div class="col-lg-12 col-md-12 col-sm-12">
							<nav id="navigation" class="navigation navigation-landscape">
								<div class="nav-header">
									<a class="nav-brand" href="#">
										<img src="assets/img/logo.png" class="logo" alt="" />
									</a>
									<div class="nav-toggle"></div>
								</div>
								<div class="nav-menus-wrapper">
									<ul class="nav-menu">
									
										<li class="active"><a href="#">Home<span class="submenu-indicator"></span></a>
											<ul class="nav-dropdown nav-submenu">
												<li><a href="index.html" class="active">Home Style 1</a></li>                                    
												<li><a href="home-2.html">Home Style 2</a></li>                                    
												<li><a href="home-3.html">Home Style 3</a></li> 
												<li><a href="home-4.html">Home Style 4</a></li> 
												<li><a href="home-5.html">Home Style 5</a></li> 
												<li><a href="home-6.html">Home Style 6</a></li> 
												<li><a href="home-7.html">Home Style 7</a></li>
											</ul>
										</li>
										
										<li><a href="#">Explore<span class="submenu-indicator"></span></a>
											<ul class="nav-dropdown nav-submenu">
												<li><a href="#">Search Product<span class="submenu-indicator"></span></a>
													<ul class="nav-dropdown nav-submenu">
														<li><a href="search-product.html">Search Product By Grid</a></li>                                    
														<li><a href="list-search-product.html">Search Product By List</a></li>  
														<li><a href="search-product-full.html">Search Product 3 Column</a></li>  														
													</ul>
												</li>
												<li><a href="#">Product Detail<span class="submenu-indicator"></span></a>
													<ul class="nav-dropdown nav-submenu">
														<li><a href="item-detail.html">Item Detail 1</a></li>                                    
														<li><a href="item-detail-2.html">Item Detail 2</a></li> 
														<li><a href="item-detail-3.html">Item Detail 3</a></li> 
														<li><a href="photo-detail.html">Photo Detail</a></li> 
														<li><a href="video-detail.html">Video Detail</a></li> 
														<li><a href="font-detail.html">Font Detail</a></li>
														<li><a href="premium-stock-detail.html">Premium Detail</a></li>														
													</ul>
												</li>
												<li><a href="#">User Admin<span class="submenu-indicator"></span></a>
													<ul class="nav-dropdown nav-submenu">
														<li><a href="add-to-cart.html">Add To Cart</a></li>
														<li><a href="billing.html">Billing</a></li>
														<li><a href="confirmation.html">Confirmation</a></li>
														<li><a href="dashboard.html">Dashboard</a></li>
													</ul>
												</li>
											</ul>
										</li>
										
										<li><a href="#">Pages<span class="submenu-indicator"></span></a>
											<ul class="nav-dropdown nav-submenu">
												<li><a href="about.html">About Us</a></li> 
												<li><a href="blog.html">Blogs Page</a></li>                                    
												<li><a href="blog-detail.html">Blog Detail</a></li>                                     
												<li><a href="pricing.html">Pricing</a></li>  
												<li><a href="faq.html">FAQ's</a></li>
												<li><a href="signup.html">Signup</a></li>
												<li><a href="login.html">LogIn</a></li> 
											</ul>
										</li>
										
										<li><a href="contact.html">Contacts</a></li>
										
									</ul>
									
									<ul class="nav-menu nav-menu-social align-to-right">
								
										<li class="header-search">
											<div class="input-group ">
												<div class="input-group-prepend">
													<span class="input-group-text"><i class="ti-search"></i></span>
												</div>
											  <input type="text" class="form-control" placeholder="Search free photos">
											</div>
										</li>
										<li class="add-listing green-bg">
                                             <Link v-if="canRegister" :href="route('register')">
                                                Unirse Gratis
                                            </Link>
										</li>
									</ul>
								</div>
							</nav>
						</div>
					</div>
				</div>
			</div>
			<div class="clearfix"></div> -->
			<!-- End Navigation -->
			<!-- ============================================================== -->
			<!-- Top header  -->
			<!-- ============================================================== -->
			
			<!-- ============================ Hero Banner  Start================================== -->
			<div class="hero-banner bg-cover center" style="background:#93d4f0 url(assets/img/banner.jpg) no-repeat;" data-overlay="4">
				<div class="container">
					<h1 class="small">Stunning free images & royalty free stock</h1>
					<p class="lead">World Best Place For Graphics & Designs Availabel on Pecozo</p>
					<form class="mt-4">
						<div class="row justify-content-center">
							<div class="col-lg-8 col-md-10 col-sm-12">
								<div class="banner-search style-1">
									<div class="input-group">
										<div class="input-group-append hime_m">
											<div class="form-group b-r">
												<select id="category" class="js-states form-control">
													<option value="">&nbsp;</option>
													<option value="1">Resources</option>
													<option value="2">Collections</option>
													<option value="3">Freebies</option>
													<option value="4">Vectors</option>
													<option value="5">Photos</option>
													<option value="6">Icons</option>
												</select>
											</div>
										</div>
										<input type="text" class="form-control lio-rad" placeholder="Search free high-resolution photos">
										<div class="input-group-append">
											<button type="button" class="btn bt-round"><i class="ti-search"></i></button>
										</div>
									</div>
								</div>
							</div>
						</div>
					</form>
				</div>
			</div>
			<!-- ============================ Hero Banner End ================================== -->
			
			
			<!-- ============================ All Images List Start ================================== -->
			<section>
				<div class="container">
					<div class="row">
						<div class="col-lg-12 col-md-12">
							
							<div class="urip_column_wrap">
								
								<div class="urip_column_single">
									<!-- Single Image Product -->
									<div class="urip_column_three">
										<div class="item_image_urip">
											<a href="photo-detail.html" class="urip_link download"><i class="fa fa-download"></i></a>
											<a href="photo-detail.html" class="item-img">
												<img src="assets/img/i-1.jpg" class="img-fluid" alt="" />
											</a>
											<div class="image_urip_caption">
												<div class="urip_caption_flex">
													<div class="urip_author">
														<div class="urip_avater">
															<a href="author-detail.html.html" class="author-img">
																<img src="assets/img/author.png" class="img-fluid" alt="" />
															</a>
														</div>
														<div class="urip_avater_place">
															<h3 class="urip_title"><a href="author-detail.html.html">Adam vilson</a></h3>
															<span>Liverpool, London</span>
														</div>
													</div>
												</div>
												<div class="urip_caption_last">
													<div class="item_list_links">
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-plus-circle"></i></a>
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-heart"></i></a>
													</div>
												</div>
											</div>
										</div>
									</div>
									
									<!-- Single Image Product -->
									<div class="urip_column_three">
										<div class="item_image_urip">
											<a href="photo-detail.html" class="urip_link download"><i class="fa fa-download"></i></a>
											<a href="photo-detail.html" class="item-img">
												<img src="assets/img/i-2.jpg" class="img-fluid" alt="" />
											</a>
											<div class="image_urip_caption">
												<div class="urip_caption_flex">
													<div class="urip_author">
														<div class="urip_avater">
															<a href="author-detail.html.html" class="author-img">
																<img src="assets/img/author.png" class="img-fluid" alt="" />
															</a>
														</div>
														<div class="urip_avater_place">
															<h3 class="urip_title"><a href="author-detail.html.html">Adam vilson</a></h3>
															<span>Liverpool, London</span>
														</div>
													</div>
												</div>
												<div class="urip_caption_last">
													<div class="item_list_links">
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-plus-circle"></i></a>
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-heart"></i></a>
													</div>
												</div>
											</div>
										</div>
									</div>
									
									<!-- Single Image Product -->
									<div class="urip_column_three">
										<div class="item_image_urip">
											<a href="photo-detail.html" class="urip_link download"><i class="fa fa-download"></i></a>
											<a href="photo-detail.html" class="item-img">
												<img src="assets/img/i-3.jpg" class="img-fluid" alt="" />
											</a>
											<div class="image_urip_caption">
												<div class="urip_caption_flex">
													<div class="urip_author">
														<div class="urip_avater">
															<a href="author-detail.html.html" class="author-img">
																<img src="assets/img/author.png" class="img-fluid" alt="" />
															</a>
														</div>
														<div class="urip_avater_place">
															<h3 class="urip_title"><a href="author-detail.html.html">Adam vilson</a></h3>
															<span>Liverpool, London</span>
														</div>
													</div>
												</div>
												<div class="urip_caption_last">
													<div class="item_list_links">
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-plus-circle"></i></a>
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-heart"></i></a>
													</div>
												</div>
											</div>
										</div>
									</div>
								
								</div>
								
								<div class="urip_column_single">
									<!-- Single Image Product -->
									<div class="urip_column_three">
										<div class="item_image_urip">
											<a href="photo-detail.html" class="urip_link download"><i class="fa fa-download"></i></a>
											<a href="photo-detail.html" class="item-img">
												<img src="assets/img/i-4.jpg" class="img-fluid" alt="" />
											</a>
											<div class="image_urip_caption">
												<div class="urip_caption_flex">
													<div class="urip_author">
														<div class="urip_avater">
															<a href="author-detail.html.html" class="author-img">
																<img src="assets/img/author.png" class="img-fluid" alt="" />
															</a>
														</div>
														<div class="urip_avater_place">
															<h3 class="urip_title"><a href="author-detail.html.html">Adam vilson</a></h3>
															<span>Liverpool, London</span>
														</div>
													</div>
												</div>
												<div class="urip_caption_last">
													<div class="item_list_links">
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-plus-circle"></i></a>
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-heart"></i></a>
													</div>
												</div>
											</div>
										</div>
									</div>
									
									<!-- Single Image Product -->
									<div class="urip_column_three">
										<div class="item_image_urip">
											<a href="photo-detail.html" class="urip_link download"><i class="fa fa-download"></i></a>
											<a href="photo-detail.html" class="item-img">
												<img src="assets/img/i-5.jpg" class="img-fluid" alt="" />
											</a>
											<div class="image_urip_caption">
												<div class="urip_caption_flex">
													<div class="urip_author">
														<div class="urip_avater">
															<a href="author-detail.html.html" class="author-img">
																<img src="assets/img/author.png" class="img-fluid" alt="" />
															</a>
														</div>
														<div class="urip_avater_place">
															<h3 class="urip_title"><a href="author-detail.html.html">Adam vilson</a></h3>
															<span>Liverpool, London</span>
														</div>
													</div>
												</div>
												<div class="urip_caption_last">
													<div class="item_list_links">
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-plus-circle"></i></a>
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-heart"></i></a>
													</div>
												</div>
											</div>
										</div>
									</div>
									
									<!-- Single Image Product -->
									<div class="urip_column_three">
										<div class="item_image_urip">
											<a href="photo-detail.html" class="urip_link download"><i class="fa fa-download"></i></a>
											<a href="photo-detail.html" class="item-img">
												<img src="assets/img/i-6.jpg" class="img-fluid" alt="" />
											</a>
											<div class="image_urip_caption">
												<div class="urip_caption_flex">
													<div class="urip_author">
														<div class="urip_avater">
															<a href="author-detail.html.html" class="author-img">
																<img src="assets/img/author.png" class="img-fluid" alt="" />
															</a>
														</div>
														<div class="urip_avater_place">
															<h3 class="urip_title"><a href="author-detail.html.html">Adam vilson</a></h3>
															<span>Liverpool, London</span>
														</div>
													</div>
												</div>
												<div class="urip_caption_last">
													<div class="item_list_links">
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-plus-circle"></i></a>
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-heart"></i></a>
													</div>
												</div>
											</div>
										</div>
									</div>
								
								</div>
								
								<div class="urip_column_single">
									<!-- Single Image Product -->
									<div class="urip_column_three">
										<div class="item_image_urip">
											<a href="photo-detail.html" class="urip_link download"><i class="fa fa-download"></i></a>
											<a href="photo-detail.html" class="item-img">
												<img src="assets/img/i-7.jpg" class="img-fluid" alt="" />
											</a>
											<div class="image_urip_caption">
												<div class="urip_caption_flex">
													<div class="urip_author">
														<div class="urip_avater">
															<a href="author-detail.html.html" class="author-img">
																<img src="assets/img/author.png" class="img-fluid" alt="" />
															</a>
														</div>
														<div class="urip_avater_place">
															<h3 class="urip_title"><a href="author-detail.html.html">Adam vilson</a></h3>
															<span>Liverpool, London</span>
														</div>
													</div>
												</div>
												<div class="urip_caption_last">
													<div class="item_list_links">
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-plus-circle"></i></a>
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-heart"></i></a>
													</div>
												</div>
											</div>
										</div>
									</div>
									
									<!-- Single Image Product -->
									<div class="urip_column_three">
										<div class="item_image_urip">
											<a href="photo-detail.html" class="urip_link download"><i class="fa fa-download"></i></a>
											<a href="photo-detail.html" class="item-img">
												<img src="assets/img/i-8.jpg" class="img-fluid" alt="" />
											</a>
											<div class="image_urip_caption">
												<div class="urip_caption_flex">
													<div class="urip_author">
														<div class="urip_avater">
															<a href="author-detail.html.html" class="author-img">
																<img src="assets/img/author.png" class="img-fluid" alt="" />
															</a>
														</div>
														<div class="urip_avater_place">
															<h3 class="urip_title"><a href="author-detail.html.html">Adam vilson</a></h3>
															<span>Liverpool, London</span>
														</div>
													</div>
												</div>
												<div class="urip_caption_last">
													<div class="item_list_links">
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-plus-circle"></i></a>
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-heart"></i></a>
													</div>
												</div>
											</div>
										</div>
									</div>
									
									<!-- Single Image Product -->
									<div class="urip_column_three">
										<div class="item_image_urip">
											<a href="photo-detail.html" class="urip_link download"><i class="fa fa-download"></i></a>
											<a href="photo-detail.html" class="item-img">
												<img src="assets/img/i-9.jpg" class="img-fluid" alt="" />
											</a>
											<div class="image_urip_caption">
												<div class="urip_caption_flex">
													<div class="urip_author">
														<div class="urip_avater">
															<a href="author-detail.html.html" class="author-img">
																<img src="assets/img/author.png" class="img-fluid" alt="" />
															</a>
														</div>
														<div class="urip_avater_place">
															<h3 class="urip_title"><a href="author-detail.html.html">Adam vilson</a></h3>
															<span>Liverpool, London</span>
														</div>
													</div>
												</div>
												<div class="urip_caption_last">
													<div class="item_list_links">
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-plus-circle"></i></a>
														<a href="photo-detail.html" class="urip_link"><i class="fa fa-heart"></i></a>
													</div>
												</div>
											</div>
										</div>
									</div>
								
								</div>
							
							</div>
							
						</div>
					</div>
					
					<div class="row">
						<div class="col-lg-12 col-md-12 text-center">
							<a href="#" class="ure09w">Browse More</a>
						</div>
					</div>
					
				</div>
			</section>
			<!-- ============================ All Images List End ================================== -->
			
			<!-- ============================ Authors List ================================== -->
			<section class="gray-light min-sec">
				<div class="container">
					
					<div class="row justify-content-center">
						<div class="col-lg-7 col-md-9">
							<div class="sec-heading">
								<h2>Top & Featured Authors</h2>
								<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
							</div>
						</div>
					</div>
					
					<div class="row">
						
						<!-- Single -->
						<div class="col-lg-4 col-md-4 col-sm-6">
							<div class="blox_instagram_preview">
								<div class="padd-10 blox_instagram_preview_container">
									<div class="blox_image_box">
										<ul class="blox_image_list">
											<li><img src="assets/img/thumb-sm-1.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-6.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-3.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-7.jpg" alt=""></li>
										</ul>
									</div>
									
									<div class="blox_instagram_info">
										<div class="blox_profile_pic">
											<img src="assets/img/user-1.jpg" alt="">
										</div>
										<div class="blox_profile_name">@ashleybenson</div>
										<div class="blox_follow_count">17m followers</div>
										<div class="blox_follow_btn">
											<a class="ure09w" href="#">Follow</a>
										</div>
									</div>
								</div>
							</div>
						</div>
						
						<!-- Single -->
						<div class="col-lg-4 col-md-4 col-sm-6">
							<div class="blox_instagram_preview">
								<div class="padd-10 blox_instagram_preview_container">
									<div class="blox_image_box">
										<ul class="blox_image_list">
											<li><img src="assets/img/thumb-sm-5.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-2.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-8.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-4.jpg" alt=""></li>
										</ul>
									</div>
									
									<div class="blox_instagram_info">
										<div class="blox_profile_pic">
											<img src="assets/img/user-2.jpg" alt="">
										</div>
										<div class="blox_profile_name">@digital_745</div>
										<div class="blox_follow_count">12m followers</div>
										<div class="blox_follow_btn">
											<a class="ure09w" href="#">Follow</a>
										</div>
									</div>
								</div>
							</div>
						</div>
						
						<!-- Single -->
						<div class="col-lg-4 col-md-4 col-sm-6">
							<div class="blox_instagram_preview">
								<div class="padd-10 blox_instagram_preview_container">
									<div class="blox_image_box">
										<ul class="blox_image_list">
											<li><img src="assets/img/thumb-sm-1.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-9.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-10.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-3.jpg" alt=""></li>
										</ul>
									</div>
									
									<div class="blox_instagram_info">
										<div class="blox_profile_pic">
											<img src="assets/img/user-3.jpg" alt="">
										</div>
										<div class="blox_profile_name">@akshay_78</div>
										<div class="blox_follow_count">09m followers</div>
										<div class="blox_follow_btn">
											<a class="ure09w" href="#">Follow</a>
										</div>
									</div>
								</div>
							</div>
						</div>
						
						<!-- Single -->
						<div class="col-lg-4 col-md-4 col-sm-6">
							<div class="blox_instagram_preview">
								<div class="padd-10 blox_instagram_preview_container">
									<div class="blox_image_box">
										<ul class="blox_image_list">
											<li><img src="assets/img/thumb-sm-9.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-10.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-4.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-6.jpg" alt=""></li>
										</ul>
									</div>
									
									<div class="blox_instagram_info">
										<div class="blox_profile_pic">
											<img src="assets/img/user-4.jpg" alt="">
										</div>
										<div class="blox_profile_name">@ashleybenson</div>
										<div class="blox_follow_count">522k followers</div>
										<div class="blox_follow_btn">
											<a class="ure09w" href="#">Follow</a>
										</div>
									</div>
								</div>
							</div>
						</div>
						
						<!-- Single -->
						<div class="col-lg-4 col-md-4 col-sm-6">
							<div class="blox_instagram_preview">
								<div class="padd-10 blox_instagram_preview_container">
									<div class="blox_image_box">
										<ul class="blox_image_list">
											<li><img src="assets/img/thumb-sm-7.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-4.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-2.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-9.jpg" alt=""></li>
										</ul>
									</div>
									
									<div class="blox_instagram_info">
										<div class="blox_profile_pic">
											<img src="assets/img/user-5.jpg" alt="">
										</div>
										<div class="blox_profile_name">@kumar_preet7</div>
										<div class="blox_follow_count">99km followers</div>
										<div class="blox_follow_btn">
											<a class="ure09w" href="#">Follow</a>
										</div>
									</div>
								</div>
							</div>
						</div>
						
						<!-- Single -->
						<div class="col-lg-4 col-md-4 col-sm-6">
							<div class="blox_instagram_preview">
								<div class="padd-10 blox_instagram_preview_container">
									<div class="blox_image_box">
										<ul class="blox_image_list">
											<li><img src="assets/img/thumb-sm-8.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-6.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-11.jpg" alt=""></li>
											<li><img src="assets/img/thumb-sm-12.jpg" alt=""></li>
										</ul>
									</div>
									
									<div class="blox_instagram_info">
										<div class="blox_profile_pic">
											<img src="assets/img/author.png" alt="">
										</div>
										<div class="blox_profile_name">@ashleybenson</div>
										<div class="blox_follow_count">17m followers</div>
										<div class="blox_follow_btn">
											<a class="ure09w" href="#">Follow</a>
										</div>
									</div>
								</div>
							</div>
						</div>
						
					</div>
					
				</div>
			</section>
			<!-- ============================ Author Lists End ================================== -->
			
			<!-- ============================ Pricing List ================================== -->
			<section class="min-sec">
				<div class="container">
					
					<div class="row justify-content-center">
						<div class="col-lg-7 col-md-9">
							<div class="sec-heading">
								<h2>Great Price For You</h2>
								<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
							</div>
						</div>
					</div>
					
					<div class="row">
						<!-- Single Pricing Box -->
						<div class="col-lg-4 col-md-4">
							<div class="pricing_boxes">
								<div class="pricing_boxes_header">
									<div class="pricing_thumb_title">
										<h4>Basic</h4>
										<p>For organising every corner of your life</p>
									</div>
								</div>
								<div class="pricing_boxes_middle">
									<h2 class="pricing_rate">$29</h2>
									<span class="time_esti">per month</span>
									<a href="#" class="btn pricing_btn">Get Started</a>
								</div>
								<div class="pricing_boxes_detail">
									<ul class="pricing_lists">
										<li>Access Whole Items</li>
										<li>Sync across device</li>
										<li>Share with 5 guests</li>
										<li>24x7 Email Support</li>
									</ul>
								</div>
							</div>
						</div>
						
						<!-- Single Pricing Box -->
						<div class="col-lg-4 col-md-4">
							<div class="pricing_boxes featured">
								<div class="pricing_boxes_header">
									<div class="pricing_thumb_title">
										<h4>Professional</h4>
										<p>For organising every corner of your life</p>
									</div>
								</div>
								<div class="pricing_boxes_middle">
									<h2 class="pricing_rate">$99</h2>
									<span class="time_esti">Per 1 Year</span>
									<a href="#" class="btn pricing_btn">Get Started</a>
								</div>
								<div class="pricing_boxes_detail">
									<ul class="pricing_lists">
										<li>Access Whole Items</li>
										<li>Sync across device</li>
										<li>Share with 10 guests</li>
										<li>24x7 Email Support</li>
									</ul>
								</div>
							</div>
						</div>
						
						<!-- Single Pricing Box -->
						<div class="col-lg-4 col-md-4">
							<div class="pricing_boxes">
								<div class="pricing_boxes_header">
									<div class="pricing_thumb_title">
										<h4>Organisation</h4>
										<p>For organising every corner of your life</p>
									</div>
								</div>
								<div class="pricing_boxes_middle">
									<h2 class="pricing_rate">$199</h2>
									<span class="time_esti">Lifetime</span>
									<a href="#" class="btn pricing_btn">Get Started</a>
								</div>
								<div class="pricing_boxes_detail">
									<ul class="pricing_lists">
										<li>Access Whole Items</li>
										<li>Sync across device</li>
										<li>Share with 5 guests</li>
										<li>24x7 Email Support</li>
									</ul>
								</div>
							</div>
						</div>				
					</div>
					
				</div>
			</section>
			<!-- ============================ Pricing End ================================== -->
			
			<!-- ============================ Call To Action Start ================================== -->
			<section class="call-to-act" style="background:#5d47dd url(assets/img/landing-bg.png) no-repeat">
				<div class="container">
					<div class="row justify-content-center">
					
						<div class="col-lg-7 col-md-8">
							<div class="clt-caption text-center mb-4">
								<h3>Subscribe Now!</h3>
								<p>Simple pricing plans. Unlimited web maintenance service</p>
							</div>
							<div class="inner-flexible-box subscribe-box">
								<div class="input-group">
									<input type="text" class="form-control large" placeholder="Enter your mail here">
									<button class="btn btn-subscribe" type="button"><i class="fa fa-arrow-right"></i></button>
								</div>
							</div>
						</div>				
					</div>
				</div>
			</section>
			<!-- ============================ Call To Action End ================================== -->
			
			<!-- =========================== Footer Start ========================================= -->
		
			<!-- =========================== Footer End ========================================= -->		

		</div>
        </body>
		</template>
     </app-layout>
</template>

<script>
import { defineComponent } from "vue";
import AppLayout from '@/Layouts/AppLayout.vue'
import { Head, Link } from "@inertiajs/inertia-vue3";

export default defineComponent({
    components: {
        AppLayout,
        Head,
        Link,
    },

    props: {
        canLogin: Boolean,
        canRegister: Boolean,
        laravelVersion: String,
        phpVersion: String,
    },
});
</script>
