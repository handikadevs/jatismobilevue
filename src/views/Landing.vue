<template>
    <div>
        <div class="position-relative" id="about">
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 bg-gradient-warning shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-6">
                                <h1 class="display-3  text-white">Welcome to,
                                    <span>Jatis Mobile</span>
                                </h1>
                                <p class="lead text-white">Cillum ipsum deserunt voluptate pariatur pariatur consequat consectetur ipsum deserunt. Cupidatat id sint nisi ad irure. Laborum qui sit occaecat deserunt. Proident consectetur incididunt nisi pariatur qui fugiat Lorem. Excepteur reprehenderit culpa pariatur sunt pariatur nulla occaecat mollit exercitation. Labore ut id dolore eu pariatur ullamco pariatur commodo esse voluptate officia exercitation.</p>
                            </div>
                            <div class="col-lg-6">
                                <div class="btn-wrapper">
                                    <div class="align-items-sm-center">
                                        <img src="img/ill/ill-2.svg" class="img-center img-fluid floating">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        <section class="section section-lg pt-lg-0 mt--50">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">       
                        <div class="row">
                            <div class="col-md-6 align-items-sm-center">
                                <div class="px-4">
                                    <img v-lazy="'img/theme/pak-asrul.jpg'"
                                        class="rounded-circle img-center img-fluid shadow shadow-lg--hover">
                                    <div class="pt-4 text-center">
                                        <h5 class="title">
                                            <span class="d-block mb-1">Asrul Abdillah Ali</span>
                                            <small class="h6 text-muted">Chief Commercial Officer</small>
                                        </h5>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6 align-items-sm-center">
                                <div class="px-4">
                                    <img v-lazy="'img/theme/foto-pak-erik.jpg'"
                                        class="rounded-circle img-center img-fluid shadow shadow-lg--hover">
                                    <div class="pt-4 text-center">
                                        <h5 class="title">
                                            <span class="d-block mb-1">Erik Rivai Ridzal</span>
                                            <small class="h6 text-muted">Chief Executive Officer (CEO)</small>
                                        </h5>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <h3 class="mb-3 text-warning"><strong>Our Team<hr style="height:1px;"></strong></h3>
                            <p>Labore duis nulla esse reprehenderit excepteur incididunt labore. Elit aute eu veniam enim proident voluptate anim aliquip. Irure cillum elit do cupidatat veniam elit cupidatat dolor pariatur laboris mollit non sint. In cillum sunt eu do irure enim quis officia eu cillum duis ut velit.</p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-settings-gear-65"></badge>
                                        <h6 class="mb-0">Aute deserunt aute nulla veniam sit.</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-html5"></badge>
                                        <h6 class="mb-0">Nisi dolor excepteur nulla est aliquip enim ad mollit officia aliquip in ipsum eu.</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-satisfied"></badge>
                                        <h6 class="mb-0">Elit ex qui id aute id eiusmod officia quis cillum veniam ut laborum non.</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section-shaped my-0 section-lg p-lg-0 mt--50" id="product">
            <div class="shape shape-style-1 bg-gradient-secondary shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            <div class="container">
                <h3 class="mb-3 text-warning text-center"><strong>Our Products <hr style="height:1px;"></strong></h3>
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-3">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-primary text-uppercase">Whatsapp Business</h6>
                                    <p class="description mt-3">WhatsApp now open for Corporate Usage. Jatis Mobile is officially appointed as WhatsApp Business implementation partner. Corporate can do WA push, WA interactive (rich contents), and Chat Bot on WA.</p>
                                    <div class="text-center">
                                        <badge type="primary" rounded>Further info – contact <br> rbi-team.bum-gh@jatis.com</badge>
                                    </div>
                                </card>
                            </div>
                            <div class="col-lg-3">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-success text-uppercase">SMS Corporate</h6>
                                    <p class="description mt-3">SMS Push : SMS outbound using masking sender ID <br> SMS Pull : SMS inbound using SMS inbound using Jatis shortcode (99123 and 99333).</p><br><br><br>
                                    <div class="text-center">
                                        <badge type="success" rounded>Further info – contact <br> rbi-team.bum-gh@jatis.com</badge>
                                    </div>
                                </card>
                            </div>
                            <div class="col-lg-3">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-shop" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">SMS Retail</h6>
                                    <p class="description mt-3">SMS Retail is a platform to enable Retailer / Outlets to run SMS Business. <br> Especially for individual customers and Small Businesses, such as info and promo.</p><br><br>
                                    <div class="text-center">
                                        <badge type="warning" rounded>Further info – contact <br> rbi-team.bum-gh@jatis.com</badge>
                                    </div>
                                </card>
                            </div>
                            <div class="col-lg-3">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-planet" type="info" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-info text-uppercase">Emailblast</h6>
                                    <p class="description mt-3">The future of email integration with the rest of marketing activities to increase relevancy and engagement for the customers.</p><br><br><br>
                                    <div class="text-center">
                                        <badge type="info" rounded>Further info – contact <br> rbi-team.bum-gh@jatis.com</badge>
                                    </div>
                                </card>
                            </div>
                        </div>
                        <div class="row row-grid">
                            <div class="col-lg-3">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-primary text-uppercase">USSD</h6>
                                    <p class="description mt-3">Unstructured Service Supplementary Data is a GSM technology originally intended for use where the handset needed to access supplementary services, USSD Push is also known as Network Initiated USSD (NI USSD) or Mobile Terminating USSD (MT USSD).</p>
                                    <div class="text-center">
                                        <badge type="primary" rounded>Further info – contact <br> rbi-team.bum-gh@jatis.com</badge>
                                    </div>
                                </card>
                            </div>
                            <div class="col-lg-3">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-success text-uppercase">Complaint Master</h6>
                                    <p class="description mt-3">Coster is omni channel in one dashboard for corporate to get more engagement with their customers thru WhatsApp, Telegram, Facebook Messager, Line, Ngobrol, Twitter, Instagram, SMS, Email.</p><br>
                                    <div class="text-center">
                                        <badge type="success" rounded>Further info – contact <br> rbi-team.bum-gh@jatis.com</badge>
                                    </div>
                                </card>
                            </div>
                            <div class="col-lg-3">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-planet" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">Contact Center</h6>
                                    <p class="description mt-3">Handles inbound and outbound customer communication over multiple channels such as messaging apps, telephone, email, social media.</p><br><br><br><br>
                                    <div class="text-center">
                                        <badge type="warning" rounded>Further info – contact <br> rbi-team.bum-gh@jatis.com</badge>
                                    </div>
                                </card>
                            </div>
                            <div class="col-lg-3">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-shop" type="info" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-info text-uppercase">Asuransi Motor</h6>
                                    <p class="description mt-3">Now mass consumers can enjoy Motor Insurance with affordable monthly premi (only IDR 20 K per month) covering losses, hospital and third party liabilities.</p><br><br><br><br>
                                    <div class="text-center">
                                        <badge type="info" rounded>Further info – contact <br> rbi-team.bum-gh@jatis.com</badge>
                                    </div>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg" id="service">
            <div class="container">
                <h3 class="mb-3 text-warning text-right"><strong>Our Services<hr style="height:1px;"></strong></h3>
                <div class="row justify-content-center">
                    <div class="row">  
                        <div class="col-md-6 mb-5">
                            <div class="media h-100 shadow rounded p-4">
                                <icon name="ni ni-settings-gear-65" class="mr-3" size="sm" type="success" shadow
                            rounded></icon>

                                <div class="media-body">
                                    <h5 class="mb-1"><a class="link-dark" href="#">Messaging Business</a></h5>
                                    <p class="mb-0">Cupidatat exercitation in Lorem est mollit.</p>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-6 mb-5">
                            <div class="media h-100 shadow rounded p-4">
                                <icon name="ni ni-settings-gear-65" class="mr-3" size="sm" type="success" shadow
                            rounded></icon>

                                <div class="media-body">
                                    <h5 class="mb-1"><a class="link-dark" href="#">Switching Business</a></h5>
                                    <p class="mb-0">Occaecat ea proident ut dolor ullamco ea id aliquip adipisicing laborum.</p>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-6 mb-5">
                            <div class="media h-100 shadow rounded p-4">
                                <icon name="ni ni-settings-gear-65" class="mr-3" size="sm" type="success" shadow
                            rounded></icon>

                                <div class="media-body">
                                    <h5 class="mb-1"><a class="link-dark" href="#">Contact Center</a></h5>
                                    <p class="mb-0">Aliqua magna adipisicing minim aute.</p>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-6 mb-5">
                            <div class="media h-100 shadow rounded p-4">
                                <icon name="ni ni-settings-gear-65" class="mr-3" size="sm" type="success" shadow
                            rounded></icon>

                                <div class="media-body">
                                    <h5 class="mb-1"><a class="link-dark" href="#">Custom Development</a></h5>
                                    <p class="mb-0">Aute eu consectetur est minim anim duis duis irure.</p>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-6 mb-5">
                            <div class="media h-100 shadow rounded p-4">
                                <icon name="ni ni-settings-gear-65" class="mr-3" size="sm" type="success" shadow
                            rounded></icon>

                                <div class="media-body">
                                    <h5 class="mb-1"><a class="link-dark" href="article.html">Omni Channel Contact Center (COSTER)</a>
                                    </h5>
                                    <p class="mb-0">Pariatur ipsum excepteur id exercitation non consequat cillum incididunt anim.</p>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-6 mb-5">
                            <div class="media h-100 shadow rounded p-4">
                                <icon name="ni ni-settings-gear-65" class="mr-3" size="sm" type="success" shadow
                            rounded></icon>

                                <div class="media-body">
                                    <h5 class="mb-1"><a class="link-dark" href="#">Chartbot (CORAL)</a></h5>
                                    <p class="mb-0">Nostrud sint id eiusmod enim laboris consectetur magna sint eu deserunt culpa.</p>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-6 mb-5">
                            <div class="media h-100 shadow rounded p-4">
                                <icon name="ni ni-settings-gear-65" class="mr-3" size="sm" type="success" shadow
                            rounded></icon>

                                <div class="media-body">
                                    <h5 class="mb-1"><a class="link-dark" href="article.html">Collaborative Commerce</a>
                                    </h5>
                                    <p class="mb-0">Pariatur pariatur cillum tempor duis excepteur laborum deserunt ut.</p>
                                </div>
                            </div>
                        </div>

                        <div class="col-md-6 mb-5">
                            <div class="media h-100 shadow rounded p-4">
                                <icon name="ni ni-settings-gear-65" class="mr-3" size="sm" type="success" shadow
                            rounded></icon>

                                <div class="media-body">
                                    <h5 class="mb-1"><a class="link-dark" href="#">Managed Services</a></h5>
                                    <p class="mb-0">Laboris do consectetur officia fugiat ea ullamco.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section bg-secondary" id="event">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div class="card bg-gradient-warning shadow border-0">
                            <img v-lazy="'img/theme/img-1-1200x1000.jpg'" class="card-img-top">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                     class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="fill-warning"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-warning"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">Jatis Whatsapp Day 2018</h4>
                                <p class="lead text-italic text-white">Nulla labore excepteur qui laboris incididunt. Nisi labore cillum Lorem tempor dolor nulla veniam. Velit aliquip elit ex excepteur quis culpa ullamco Lorem do ad pariatur magna.</p>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <h3 class="mb-3 text-warning"><strong>EVENT and CSR <hr style="height:1px;"></strong></h3>
                            <p class="lead">Don't let your uses guess by attaching tooltips and popoves to any element.
                                Just make sure you enable them first via JavaScript.</p>
                            <p>The kit comes with three pre-built pages to help you get started faster. You can change
                                the text and images and you're good to go.</p>
                            <p>The kit comes with three pre-built pages to help you get started faster. You can change
                                the text and images and you're good to go.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section section-shaped my-0 overflow-hidden" id="partner">
            <div class="shape shape-style-1 bg-secondary shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            <div class="container mt--50">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-lg-2 ml-lg-auto">
                        <div class="position-relative pl-md-5">
                            <img src="img/theme/klien_partner.jpg" class="img-center img-thumbnail floating">
                        </div>
                    </div>
                    <div class="col-lg-6 order-lg-1">
                        <div class="d-flex px-3">
                            <div class="pl-4">
                                <h3 class="mb-3 text-warning"><strong>Our Partners<hr style="height:1px;"></strong></h3>
                                <p>As digital distribution company, we support +400 conventional clients & +100 digital clients.
Conventional clients include Banks, Insurance, Multi-fiinance, Retailer, Consumer Goods, Transportation. Those clients now aggressively moving into digital services.
Digital clients include e-commerce, transport online, logistic & fintech. </p><br><br>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-lg-0 mt--50" id="join">
            <div class="container">
                <div class="row justify-content-center text-center">
                    <div class="col-lg-8">
                        <h3 class="mb-3 text-warning"><strong>Join Us<hr style="height:1px;"></strong></h3>
                    </div>
                    <card gradient="secondary"
                      no-body
                      shadow-size="lg"
                      class="border-0">
                        <div class="p-5">
                            <div class="row align-items-center">
                                <div class="col-lg-8">
                                    <h3>ARE YOU READY TO JOIN WITH US ?</h3>
                                    <p class="lead mt-3">Send the application form for a free call, <br> Our manager will contact with you.</p>
                                </div>
                                <div class="col-lg-3 ml-lg-auto">
                                    <base-button tag="a" href="#"
                                                type="warning" block size="lg">
                                        Send your CV
                                    </base-button>
                                </div>
                                <div class="col-lg-12 pt-4">    
                                    <div class="row">
                                        <div class="col-lg-4">
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Group Head Account Executive (GH AE)</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Account Executive (AE)</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Mobile App. Developer (Android/iOS)</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Java Developer</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">IT System</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">SIT (System Internal Testing)</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">IT Support 247</button>
                                        </div>
                                        <div class="col-lg-4">
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">IT Security</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">.NET Developer</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Business Analyst</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Presales</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">IT Database Administrator</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">IT MIS Reporting</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Software QA & QC</button>
                                        </div>
                                        <div class="col-lg-4">
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">IT Switching Business Admin</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Finance Officer</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">IT Project Management & Manager</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Technical Writer</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Creative Content Writer</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Recruitment Officer</button>
                                            <button class="btn btn-sm btn-outline-default col-12 ml-4 mr-4 mb-4">Report Designer</button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </card>
                </div>
            </div>
        </section>
        <section class="section section-shaped my-0" id="contact">
            <div class="shape shape-style-3 bg-gradient-warning shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt--50 pb-250">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h3 class="mb-3 text-white"><strong>Contact Us<hr style="height:1px;border:none;color:#fff;background-color:#fff;" ></strong></h3>
                        <p class="lead text-white">Culpa consequat veniam deserunt laboris ullamco amet eiusmod ipsum laborum ullamco cupidatat excepteur veniam. Ullamco anim adipisicing velit Lorem laboris.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Want to collaborate with us?</h4>
                            <p class="mt-0">Your project is very important to us.</p>
                            <base-input class="mt-5"
                                        alternative
                                        placeholder="Your name"
                                        addon-left-icon="ni ni-user-run">
                            </base-input>
                            <base-input alternative
                                        placeholder="Email address"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                              cols="80" placeholder="Type a message..."></textarea>
                            </base-input>
                            <base-button type="warning" round block size="lg">
                                Send Message
                            </base-button>
                        </card>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
  name: "home",
  components: {}
};
</script>
