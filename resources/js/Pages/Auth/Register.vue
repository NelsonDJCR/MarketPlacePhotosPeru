<template>

    <Head title="Register" />

    <app-layout title="Dashboard">
        <template #header>

            <body class="blue-skin">
                <div id="main-wrapper">

                    <div class="_agt_dash dark" style="background:#675bca url(assets/img/tag-light.png) no-repeat;">
                        <div class="container">
                            <div class="row">
                                <div class="col-lg-12 col-md-12 col-sm-12">
                                    <div class="_capt9oi">
                                        <h1 class="text-light">Create An Account</h1>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <section class="gray-light">
                        <div class="container">
                            <div class="row justify-content-center">
                                <div class="col-lg-11 col-md-11">

                                    <div class="row no-gutters position-relative log_rads">
                                        <div class="col-lg-5 col-md-5 theme-bg">
                                            <div class="lui_9okt6">
                                                <h2 class="text-light">Check Out<br>Customers Reviews</h2>
                                                <p class="text-light">At vero eos et accusamus et iusto odio
                                                    dignissimos ducimus qui blanditiis praesentium.</p>
                                                <div class="_loh_revu97">
                                                    <div class="owl-carousel owl-theme middle-arrow-hover"
                                                        id="reviews-login">

                                                        <div class="_loh_r96">
                                                            <div class="_bloi_quote"><i class="fa fa-quote-left"></i>
                                                            </div>
                                                            <div class="_loh_r92">
                                                                <h4>Good Services</h4>
                                                            </div>
                                                            <div class="_loh_r93">
                                                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing
                                                                    elit, sed do eiusmod tempor incididunt ut labore et
                                                                    dolore magna aliqua.</p>
                                                            </div>
                                                            <div class="_loh_foot_r93">
                                                                <h4>Shilpa D. Setty</h4>
                                                                <span>Team Leader</span>
                                                            </div>
                                                        </div>

                                                        <div class="_loh_r96">
                                                            <div class="_bloi_quote"><i class="fa fa-quote-left"></i>
                                                            </div>
                                                            <div class="_loh_r92">
                                                                <h4>Good Services</h4>
                                                            </div>
                                                            <div class="_loh_r93">
                                                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing
                                                                    elit, sed do eiusmod tempor incididunt ut labore et
                                                                    dolore magna aliqua.</p>
                                                            </div>
                                                            <div class="_loh_foot_r93">
                                                                <h4>Adam Wilsom</h4>
                                                                <span>Mak Founder</span>
                                                            </div>
                                                        </div>

                                                        <!-- Single Reviews -->
                                                        <div class="_loh_r96">
                                                            <div class="_bloi_quote"><i class="fa fa-quote-left"></i>
                                                            </div>
                                                            <div class="_loh_r92">
                                                                <h4>Customer Support</h4>
                                                            </div>
                                                            <div class="_loh_r93">
                                                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing
                                                                    elit, sed do eiusmod tempor incididunt ut labore et
                                                                    dolore magna aliqua.</p>
                                                            </div>
                                                            <div class="_loh_foot_r93">
                                                                <h4>Kunal M. Wilsom</h4>
                                                                <span>CEO & Founder</span>
                                                            </div>
                                                        </div>

                                                        <!-- Single Reviews -->
                                                        <div class="_loh_r96">
                                                            <div class="_bloi_quote"><i class="fa fa-quote-left"></i>
                                                            </div>
                                                            <div class="_loh_r92">
                                                                <h4>Ultimate Services</h4>
                                                            </div>
                                                            <div class="_loh_r93">
                                                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing
                                                                    elit, sed do eiusmod tempor incididunt ut labore et
                                                                    dolore magna aliqua.</p>
                                                            </div>
                                                            <div class="_loh_foot_r93">
                                                                <h4>Mark Jugermark</h4>
                                                                <span>MCL Founder</span>
                                                            </div>
                                                        </div>
                                                        <div class="_loh_r96">
                                                            <div class="_bloi_quote"><i class="fa fa-quote-left"></i>
                                                            </div>
                                                            <div class="_loh_r92">
                                                                <h4>Item Support</h4>
                                                            </div>
                                                            <div class="_loh_r93">
                                                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing
                                                                    elit, sed do eiusmod tempor incididunt ut labore et
                                                                    dolore magna aliqua.</p>
                                                            </div>
                                                            <div class="_loh_foot_r93">
                                                                <h4>Kirti Washinton</h4>
                                                                <span>Web Designer</span>
                                                            </div>
                                                        </div>

                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="col-lg-7 col-md-7 position-static p-4 pl-md-0">
                                            <div class="log_wraps">
                                                <div class="log__heads">
                                                    <h4 class="mt-0 logs_title">Sign <span
                                                            class="theme-cl">Up</span></h4>
                                                </div>



                                                <form @submit.prevent="submit">
                                                    <div class="form-group">
                                                        <jet-label for="name" value="Name" />
                                                        <jet-input id="name" type="text" class="form-control"
                                                            v-model="form.name" autofocus autocomplete="name" />
                                                    </div>

                                                    <div class="form-group">
                                                        <jet-label for="email" value="Email" />
                                                        <jet-input id="email" type="email" class="form-control"
                                                            v-model="form.email" />
                                                    </div>

                                                    <div class="form-group">
                                                        <jet-label for="password" value="Password" />
                                                        <jet-input id="password" type="password" class="form-control"
                                                            v-model="form.password" autocomplete="new-password" />
                                                    </div>


                                                    <div class=""
                                                        v-if="$page.props.jetstream.hasTermsAndPrivacyPolicyFeature">
                                                        <div class="flex items-center">

                                                        </div>
                                                    </div>


                                                    <div class="logs_foot_first">

                                                    </div>



                                                    <div class="logs_foot mb-3">
                                                        <div class="logs_foot_first">
                                                            <jet-checkbox name="terms" class="checkbox-custom"
                                                                id="terms" v-model:checked="form.terms" />
                                                            <label for="terms" class="checkbox-custom-label">I agree
                                                                with terms.</label>
                                                        </div>
                                                        <div class="logs_foot_last">
                                                            Already registered?
                                                            <Link :href="route('login')" class="theme-cl">
                                                            Login
                                                            </Link>
                                                        </div>
                                                    </div>



                                                    <div class="flex items-center justify-end mt-4">


                                                    </div>
                                                    <div class="form-group">
                                                        <jet-button style="background: #675bca;"
                                                            class="btn btn_apply w-100">
                                                            Register XD
                                                        </jet-button>
                                                    </div>

                                                </form>

                                                <jet-validation-errors class="mb-4" />








                                            </div>
                                        </div>
                                    </div>

                                </div>
                            </div>
                        </div>
                    </section>



                    <div class="w3-ch-sideBar w3-bar-block w3-card-2 w3-animate-right" style="display:none;right:0;"
                        id="rightMenu">
                        <div class="_oli987">
                            <h4 class="cart_heading">Your cart</h4>
                            <button onclick="closeRightMenu()" class="w3-bar-item w3-button w3-large"><i
                                    class="ti-close"></i></button>
                        </div>
                        <div class="rightMenu-scroll">
                            <div class="right-ch-sideBar" id="side-scroll">

                                <div class="cart_select_items">
                                    <div class="cart_selected_single">
                                        <div class="cart_selected_single_thumb">
                                            <a href="#"><img src="assets/img/logos-4.png" class="img-fluid"
                                                    alt="" /></a>
                                        </div>
                                        <div class="cart_selected_single_caption">
                                            <h4 class="product_title">Orio - Online Multipurpose WordPress Theme</h4>
                                            <span class="numberof_item">$59</span>
                                            <a href="#" class="text-danger">Remove</a>
                                        </div>
                                    </div>
                                    <div class="cart_selected_single">
                                        <div class="cart_selected_single_thumb">
                                            <a href="#"><img src="assets/img/logos-3.png" class="img-fluid"
                                                    alt="" /></a>
                                        </div>
                                        <div class="cart_selected_single_caption">
                                            <h4 class="product_title">LearnUp - Online LMS WordPress Theme</h4>
                                            <span class="numberof_item">$39</span>
                                            <a href="#" class="text-danger">Remove</a>
                                        </div>
                                    </div>
                                    <div class="cart_selected_single">
                                        <div class="cart_selected_single_thumb">
                                            <a href="#"><img src="assets/img/logos-2.png" class="img-fluid"
                                                    alt="" /></a>
                                        </div>
                                        <div class="cart_selected_single_caption">
                                            <h4 class="product_title">Cario - Digital WordPress Theme</h4>
                                            <span class="numberof_item">$15x2</span>
                                            <a href="#" class="text-danger">Remove</a>
                                        </div>
                                    </div>
                                </div>

                                <div class="cart_subtotal">
                                    <h6>Subtotal<span class="theme-cl">$120.47</span></h6>
                                </div>

                                <div class="cart_action">
                                    <ul>
                                        <li><a href="#" class="btn btn_checkout">Checkout Now</a></li>
                                    </ul>
                                </div>

                            </div>
                        </div>
                    </div>

                    <!-- Log In Modal -->
                    <div class="modal fade" id="login" tabindex="-1" role="dialog" aria-labelledby="registermodal"
                        aria-hidden="true">
                        <div class="modal-dialog modal-dialog-centered login-pop-form" role="document">
                            <div class="modal-content" id="registermodal">
                                <div class="modal-header">
                                    <h4>Close Window</h4>
                                    <button type="button" class="close" data-dismiss="modal"
                                        aria-label="Close"><span aria-hidden="true"><i
                                                class="ti-close"></i></span></button>
                                </div>
                                <div class="modal-body">
                                    <h4 class="modal-header-title">Sign <span class="theme-cl">In</span></h4>

                                    <div class="login-form">
                                        <form>

                                            <div class="form-group">
                                                <label>User Name</label>
                                                <div class="input-with-gray light">
                                                    <input type="text" class="form-control" placeholder="Username">
                                                </div>
                                            </div>


                                            <div class="form-group">
                                                <label>Password</label>
                                                <div class="input-with-gray light">
                                                    <input type="password" class="form-control"
                                                        placeholder="*******">
                                                </div>
                                            </div>

                                            <div class="form-group">
                                                <button type="submit"
                                                    class="btn theme-bg btn-md full-width pop-login">Login</button>
                                            </div>

                                        </form>
                                    </div>

                                    <div class="form-group text-center">
                                        <span>Or Signup with</span>
                                    </div>

                                    <div class="social_logs mb-4">
                                        <ul>
                                            <li class="fb-login"><a href="#"><i class="fa fa-facebook"></i></a>
                                            </li>
                                            <li class="gp-login"><a href="#"><i
                                                        class="fa fa-google-plus"></i></a></li>
                                            <li class="ln-login"><a href="#"><i class="fa fa-linkedin"></i></a>
                                            </li>
                                        </ul>
                                    </div>

                                </div>
                                <div class="modal-footer">
                                    <div class="mf-link"><i class="ti-user"></i>Haven't An Account?<a
                                            href="javascript:void(0)" class="theme-cl"> Sign Up</a></div>
                                    <div class="mf-forget"><a href="#"><i class="ti-help"></i>Forget
                                            Password</a></div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>


            </body>




        </template>
    </app-layout>
</template>

<script>
    import {
        defineComponent
    } from 'vue'
    import JetAuthenticationCard from '@/Jetstream/AuthenticationCard.vue'
    import JetAuthenticationCardLogo from '@/Jetstream/AuthenticationCardLogo.vue'
    import JetButton from '@/Jetstream/Button.vue'
    import JetInput from '@/Jetstream/Input.vue'
    import JetCheckbox from '@/Jetstream/Checkbox.vue'
    import AppLayout from '@/Layouts/AppLayout.vue'
    import JetLabel from '@/Jetstream/Label.vue'
    import JetValidationErrors from '@/Jetstream/ValidationErrors.vue'
    import {
        Head,
        Link
    } from '@inertiajs/inertia-vue3';

    export default defineComponent({
        components: {
            AppLayout,
            Head,
            JetAuthenticationCard,
            JetAuthenticationCardLogo,
            JetButton,
            JetInput,
            JetCheckbox,
            JetLabel,
            JetValidationErrors,
            Link,
        },

        data() {
            return {
                form: this.$inertia.form({
                    name: '',
                    email: '',
                    password: '',
                    terms: false,
                }),
            }
        },

        methods: {
            submit() {


                if (this.form.name == '') {
                    Swal.fire('El campo nombre es obligatorio', '', 'error')
                    return false;
                } else if (this.form.email == '') {
                    Swal.fire('El campo correo es obligatorio', '', 'error')
                    return false;
                } else if (this.form.password == '') {
                    Swal.fire('El campo contraseña es obligatorio', '', 'error')
                    return false;
                }


                axios.post(`/register`, this.form).then((r) => {

                    this.$inertia.get('/dashboard')


                }).catch(function(error) {


                    // error.response.data.errors.errors -> v-for="(err, ke) in errors" = `Error en ${ke}: ${err[0]}`




                    if (error.response.status == 422) {
                        var msg = error.response.data.errors
                    }

                    console.log(msg);

                });

            }
        }
    })
</script>
