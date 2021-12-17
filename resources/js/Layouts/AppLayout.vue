<template>
    <div>
        <Head :title="title" />

        <jet-banner />


			<div class="header header-light">
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
												<li><a href="login.html"></a></li> 
											</ul>
										</li>
										
										<li><a href="contact.html">Contacts</a></li>
						
									</ul>


                              
									<ul class="nav-menu nav-menu-social align-to-right">
								    	<li>
											<a href="javascript:void(0);" onclick="openRightMenu()" class="urip_list_cart">
												<i class="fa fa-shopping-cart"></i><span class="urip_product_count">4</span>
											</a>
										</li>
										<li class="add-listing green-bg">
                                             <Link v-if="canRegister" :href="route('register')">
                                                Unirse Gratis
                                            </Link>

                                            <Link v-else>Mi cuenta</Link>
										</li>
									</ul>
								</div>
							</nav>
						</div>
					</div>
				</div>
			</div>
			<div class="clearfix"></div>

            <header  v-if="$slots.header">
                    <slot name="header"></slot>
            </header>

            	<footer class="dark-footer skin-dark-footer">
				<div>
					<div class="container">
						<div class="row">
							
							<div class="col-lg-4 col-md-6">
								<div class="footer-widget">
									<img src="assets/img/logo-light.png" class="img-fluid f-logo" width="120" alt="">
									<p>407-472 Rue Saint-Sulpice, Montreal<br>Quebec, H2Y 2V8</p>
									<ul class="footer-bottom-social">
										<li><a href="#"><i class="ti-facebook"></i></a></li>
										<li><a href="#"><i class="ti-twitter"></i></a></li>
										<li><a href="#"><i class="ti-instagram"></i></a></li>
										<li><a href="#"><i class="ti-linkedin"></i></a></li>
									</ul>
								</div>
							</div>		
							<div class="col-lg-2 col-md-4">
								<div class="footer-widget">
									<h4 class="widget-title">Useful links</h4>
									<ul class="footer-menu">
										<li><a href="about.html">About Us</a></li>
										<li><a href="faq.html">FAQs Page</a></li>
										<li><a href="billing.html">Checkout</a></li>
										<li><a href="login.html">Login</a></li>
									</ul>
								</div>
							</div>
							
							<div class="col-lg-2 col-md-4">
								<div class="footer-widget">
									<h4 class="widget-title">Developers</h4>
									<ul class="footer-menu">
										<li><a href="#">Booking</a></li>
										<li><a href="#l">Stays</a></li>
										<li><a href="#">Adventures</a></li>
										<li><a href="#">Author Detail</a></li>
									</ul>
								</div>
							</div>
							
							<div class="col-lg-2 col-md-4">
								<div class="footer-widget">
									<h4 class="widget-title">Useful links</h4>
									<ul class="footer-menu">
										<li><a href="about.html">About Us</a></li>
										<li><a href="faq.html">Jobs</a></li>
										<li><a href="#">Events</a></li>
										<li><a href="#">Press</a></li>
									</ul>
								</div>
							</div>
									
							<div class="col-lg-2 col-md-4">
								<div class="footer-widget">
									<h4 class="widget-title">Useful links</h4>
									<ul class="footer-menu">
										<li><a href="#">Support</a></li>
										<li><a href="contact.html">Contact Us</a></li>
										<li><a href="#">Privacy &amp; Terms</a></li>
									</ul>
								</div>
							</div>
							
						</div>
					</div>
				</div>
				
				<div class="footer-bottom">
					<div class="container">
						<div class="row align-items-center">
							
							<div class="col-lg-12 col-md-12 text-center">
								<p class="mb-0">©Copyright ECONOMIC Todos los derechos reservados.</p>
							</div>
							
						</div>
					</div>
				</div>
			</footer>
    </div>
</template>

<script>
    import { defineComponent } from 'vue'
    import JetApplicationMark from '@/Jetstream/ApplicationMark.vue'
    import JetBanner from '@/Jetstream/Banner.vue'
    import JetDropdown from '@/Jetstream/Dropdown.vue'
    import JetDropdownLink from '@/Jetstream/DropdownLink.vue'
    import JetNavLink from '@/Jetstream/NavLink.vue'
    import JetResponsiveNavLink from '@/Jetstream/ResponsiveNavLink.vue'
    import { Head, Link } from '@inertiajs/inertia-vue3';

    export default defineComponent({
        props: {
            title: String,
        },

        components: {
            Head,
            JetApplicationMark,
            JetBanner,
            JetDropdown,
            JetDropdownLink,
            JetNavLink,
            JetResponsiveNavLink,
            Link,
        },

        data() {
            return {
                showingNavigationDropdown: false,
            }
        },

        methods: {
            switchToTeam(team) {
                this.$inertia.put(route('current-team.update'), {
                    'team_id': team.id
                }, {
                    preserveState: false
                })
            },

            logout() {
                this.$inertia.post(route('logout'));
            },
        }
    })
</script>
