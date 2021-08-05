# #EXP
>eXpect Tokens adalah coin crypto yang di harapkan di masa depan.

![Screenshot](https://media.cssninja.io/products/krypton/product.png "Krypton")

## ✌️ preview

Lihat demo langsung dengan mengklik [di sini] (https://cssninjastudio.github.io/krypton/) .
Krypton dibangun dengan [Bulma] ( https://bulma.io ) dan [Alpine JS] ( https://github.com/alpinejs/alpine 

## 👍 Features

* Gulp 4 and nodejs 12.13.0 (minimum)
* Bulma 0.9.1
* ES6 support
* Alpine JS

## 👌 Usage

1. Install Dev Depedencies

```sh
npm install
```

2. To start development server

```sh
npm run dev
```

## 🍔 Issues

If you've found an issue or a bug, you can report it in the issues section of this repository. Please try to follow these simple guidelines to report your issue:

* Issue definition
* Expected behaviour
* Actual behaviour
* steps to reproduce
* Already tried fixes (if relevant)

## 🎉 More

You liked Krypton? Check also our other premium Envato bulma themes [Css Ninja](https://cssninja.io/themes).

Find more premium bulma templates on [Css Ninja](https://cssninja.io/category/all).

## 🚀 About Us

Css Ninja adalah studio desain web. Kami membuat template buatan tangan dan dipoles yang akan memberikan sensasi pada startup Anda atau proyek Anda berikutnya.
---

layout: default

title: Home

---

<div class="dark-wrapper">

    <!-- Landing page Hero -->

    <section class="hero is-fullheight is-transparent">

        <div class="hero-head">

            <!-- Cloned navbar -->

            {{> navbar-clone}}

            <!-- Static navbar -->

            {{> navbar}}

        </div>

        <!-- Animated particles -->

        <div x-data="initHero()" x-init="initParticles()" id="particles-js"></div>

        <!-- Hero Image and Title -->

        <div class="hero-body">

            <div class="container">

                <div class="columns is-vcentered">

                    <!-- Landing page Title -->

                    <div class="column is-5 landing-caption">

                        <h1 class="title is-1 is-light is-semibold is-spaced main-title">Cryptocurrency Exchange Market</h1>

                        <h2 class="subtitle is-5 is-light is-thin">

                            Cryptocurrency brought to the next level. Join our ICO for supercharged rates.

                        </h2>

                        <!-- CTA -->

                        <p class="buttons">

                            <a href="#start" class="button k-button k-primary raised has-gradient is-fat is-bold">

                                <span class="text">Get Started</span>

                                <span class="front-gradient"></span>

                            </a>

                            <a href="#" class="button k-button k-primary raised has-gradient is-fat is-bold">

                                <span class="text">Learn More</span>

                                <span class="front-gradient"></span>

                            </a>

                        </p>

                    </div>

                    <!-- Hero image -->

                    <div class="column is-7">

                        <figure class="image">

                            <img src="/img/illustrations/buildings.svg" alt="">

                        </figure>

                    </div>

                </div>

            </div>

        </div>

        <!-- Hero footer -->

        <div class="hero-foot">

            <div class="container">

                <div class="tabs is-centered">

                    <!-- Client / partner list -->

                    <ul>

                        <li><a><img class="hero-logo" src="/img/clients/cryptomarket.svg" alt=""></a></li>

                        <li><a><img class="hero-logo" src="/img/clients/bitit.svg" alt=""></a></li>

                        <li><a><img class="hero-logo" src="/img/clients/coin.svg" alt=""></a></li>

                    </ul>

                </div>

            </div>

        </div>

    </section>

    <!-- /Landing page Hero -->

    <!-- Icon Features section -->

    <section id="start" class="section is-transparent is-relative">

        <!-- Container -->

        <div class="container">

            <div class="has-text-centered">

                <a class="button k-button k-secondary raised has-gradient is-fat is-bold rounded">

                    <span class="text">Buy Tokens 20% off</span>

                    <span class="front-gradient"></span>

                </a>

                

                <div class="buy-title">We Accept</div>

                

                <div class="accepted-currencies">

                    <div>

                        <i class="cf cf-btc"></i>

                    </div>

                    <div>

                        <i class="cf cf-eth"></i>

                    </div>

                    <div>

                        <i class="cf cf-ltc"></i>

                    </div>

                    <div>

                        <i class="cf cf-xem"></i>

                    </div>

                </div>

            </div>

            <!-- Content wrapper -->

            <div class="content-wrapper is-medium">

                <div class="columns is-vcentered">

                    <!-- Feature -->

                    <div class="column is-4">

                        <div class="feature">

                            <img src="/img/icons/chained.svg" alt="" data-aos="fade-up" data-aos-delay="100" data-aos-offset="200" data-aos-easing="ease-out-quart">

                            <h4 class="title is-6 is-tight is-light">Chaining</h4>

                            <p>Supercharged features to make you happy and lorem ipsum sit dolor amet</p>

                        </div>

                    </div>

                    <!-- Feature -->

                    <div class="column is-4">

                        <div class="feature">

                            <img src="/img/icons/stacked.svg" alt="" data-aos="fade-up" data-aos-delay="300" data-aos-offset="200" data-aos-easing="ease-out-quart">

                            <h4 class="title is-6 is-tight is-light">Stacking</h4>

                            <p>Supercharged features to make you happy and lorem ipsum sit dolor amet</p>

                        </div>

                    </div>

                    <!-- Feature -->

                    <div class="column is-4">

                        <div class="feature">

                            <img src="/img/icons/compact.svg" alt="" data-aos="fade-up" data-aos-delay="500" data-aos-offset="200" data-aos-easing="ease-out-quart">

                            <h4 class="title is-6 is-tight is-light">Managing</h4>

                            <p>Supercharged features to make you happy and lorem ipsum sit dolor amet</p>

                        </div>

                    </div>

                </div>

                <!-- Play video button -->

                <div class="cta-wrapper has-text-centered">

                    <div class="video-button levitate js-modal-btn" data-video-id="6WG7D47tGb0">

                        <img src="/img/icons/play.svg" alt="">

                    </div>

                </div>

            </div>

            <!-- Content wrapper -->

        </div>

        <!-- /Container -->

    </section>

    <!-- /Icon Features section -->

    <!-- Side Features section -->

    <section id="big-gradient" class="section is-transparent">

        <!-- Container -->

        <div class="container">

            <!-- Divider -->

            <div class="divider is-centered"></div>

            <!-- Title & subtitle -->

            <h2 class="title is-light is-semibold has-text-centered is-spaced">Decentralized Exchange</h2>

            <h4 class="subtitle is-6 is-light has-text-centered is-compact">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Ut sea pertinax perpetua, eruditi volumus quaestio ex mel, has ei tota homero.</h4>

            <!-- Content wrapper -->

            <div class="content-wrapper is-large">

                <div class="columns is-vcentered">

                    <!-- Feature content -->

                    <div class="column is-5 is-offset-1">

                        <div class="side-feature-content">

                            <h3 class="title is-4 is-light"><img src="/img/icons/ico/bitbanner.svg" alt=""> <span>Token Building</span></h3>

                            <div class="divider is-long"></div>

                            <p class="is-light">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Eu impetus perfecto sit, no sea labore detraxit.</p>

                            <div class="cta-wrapper">

                                <a href="token.html" class="button k-button k-primary raised has-gradient is-bold">

                                    <span class="text">Learn More</span>

                                    <span class="front-gradient"></span>

                                </a>

                            </div>

                        </div>

                    </div>

                    <!-- Feature image -->

                    <div class="column is-7">

                        <img class="side-feature" src="/img/illustrations/token.svg" alt="">

                    </div>

                </div>

                <div class="columns is-vcentered">

                    <!-- Feature image desktop -->

                    <div class="column is-7 is-hidden-mobile">

                        <img class="side-feature" src="/img/illustrations/blockchain-blocks.svg" alt="">

                    </div>

                    <!-- Feature content -->

                    <div class="column is-5">

                        <div class="side-feature-content">

                            <h3 class="title is-4 is-light"><img src="/img/icons/ico/bitnetwork.svg" alt=""> <span>Cascading Blockchain</span></h3>

                            <div class="divider is-long"></div>

                            <p class="is-light">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Eu impetus perfecto sit, no sea labore detraxit.</p>

                            <div class="cta-wrapper">

                                <a href="#" class="button k-button k-primary raised has-gradient is-bold">

                                    <span class="text">Whitepaper</span>

                                    <span class="front-gradient"></span>

                                </a>

                            </div>

                        </div>

                    </div>

                    <!-- Feature image only for mobile -->

                    <div class="column is-7 is-hidden-desktop is-hidden-tablet">

                        <img class="side-feature" src="/img/illustrations/blockchain-blocks.svg" alt="">

                    </div>

                </div>

                <div class="columns is-vcentered">

                    <!-- Feature content -->

                    <div class="column is-5 is-offset-1">

                        <div class="side-feature-content">

                            <h3 class="title is-4 is-light"><img src="/img/icons/ico/bitmining.svg" alt=""> <span>Crypto Farming</span></h3>

                            <div class="divider is-long"></div>

                            <p class="is-light">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Eu impetus perfecto sit, no sea labore detraxit.</p>

                            <div class="cta-wrapper">

                                <a href="#" class="button k-button k-primary raised has-gradient is-bold">

                                    <span class="text">Join the ICO</span>

                                    <span class="front-gradient"></span>

                                </a>

                            </div>

                        </div>

                    </div>

                    <!-- Feature image -->

                    <div class="column is-7">

                        <img class="side-feature" src="/img/illustrations/crypto-mining.svg" alt="">

                    </div>

                </div>

            </div>

            <!-- /Content wrapper -->

        </div>

        <!-- /Container -->

    </section>

    <!-- /Side Features section -->

    <!-- ICO section -->

    <section class="section is-medium is-end">

        <!-- Container -->

        <div class="container">

            <!-- Divider -->

            <div class="divider is-centered"></div>

            <!-- Title & subtitle -->

            <h2 class="title is-light is-semibold has-text-centered is-spaced">Join our ICO Now</h2>

            <h4 class="subtitle is-6 is-light has-text-centered is-compact">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Ut sea pertinax perpetua, eruditi volumus quaestio ex mel, has ei tota homero.</h4>

            <!-- Content wrapper -->

            <div class="content-wrapper is-large">

                <!-- Flying tabs wrapper -->

                <div x-data="initTabs()" x-init="setupCountdown()" class="flying-wrapper">

                    <!-- Tabs container -->

                    <div class="flying-tabs-container">

                        <!-- Tabs -->

                        <div class="flying-tabs">

                            <div @click="switchTabs($event)" class="flying-child tab-1" data-tab="tab-1" :class="{

                                'is-active': activeTab === 'tab-1',

                                '': activeTab != 'tab-1'

                            }"><a href="javascript:void(0);">ICO</a></div>

                            <div @click="switchTabs($event)" class="flying-child tab-2" data-tab="tab-2" :class="{

                                'is-active': activeTab === 'tab-2',

                                '': activeTab != 'tab-2'

                            }"><a href="javascript:void(0);">TOKEN</a></div>

                            <div @click="switchTabs($event)" class="flying-child tab-3" data-tab="tab-3" :class="{

                                'is-active': activeTab === 'tab-3',

                                '': activeTab != 'tab-3'

                            }"><a href="javascript:void(0);">PROFIT</a></div>

                            <div @click="switchTabs($event)" class="flying-child tab-4" data-tab="tab-4" :class="{

                                'is-active': activeTab === 'tab-4',

                                '': activeTab != 'tab-4'

                            }"><a href="javascript:void(0);">BOUNTY</a></div>

                            <div class="slider"></div>

                        </div>

                    </div>

                    <!-- Tabs content wrapper -->

                    <div class="flying-tabs-content">

                        <!-- Tab 1 -->

                        <div  class="tab-content" :class="{

                                'is-active': activeTab === 'tab-1',

                                '': activeTab != 'tab-1'

                            }">

                            <div class="columns is-vcentered tab-content-wrapper">

                                <!-- ICO Terms -->

                                <div class="column is-5 is-offset-1">

                                    <div class="text-content">

                                        <h4 class="title is-6 is-light animated preFadeInUp fadeInUp">ICO TERMS</h4>

                                        <ul class="custom-bullet-list">

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Presale</span>

                                                <br>

                                                <span class="item-content">Presale starts on Apr 8 2021 (9:00am GMT)</span>

                                            </li>

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Sale</span>

                                                <br>

                                                <span class="item-content">Token sales starts on Jun 8 2021 (12:00am GMT)</span>

                                            </li>

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Bonus</span>

                                                <br>

                                                <span class="item-content">Bonus starts on July 29 2021 (12:00am GMT)</span>

                                            </li>

                                        </ul>

                                    </div>

                                </div>

                                <!-- ICO COuntdown -->

                                <div class="column is-5">

                                    <!-- Card -->

                                    <div class="ico-card animated preFadeInUp fadeInUp">

                                        <!-- Countdown -->

                                        <ul id="countdown" class="is-ico">

                                            <li id="days">

                                                <div id="days-count" class="timer-number">00</div>

                                                <div class="label">Days</div>

                                            </li>

                                            <li id="hours">

                                                <div id="hours-count" class="timer-number">00</div>

                                                <div class="label">Hours</div>

                                            </li>

                                            <li id="minutes">

                                                <div id="minutes-count" class="timer-number">00</div>

                                                <div class="label">Minutes</div>

                                            </li>

                                            <li id="seconds">

                                                <div id="seconds-count" class="timer-number">00</div>

                                                <div class="label">Seconds</div>

                                            </li>

                                        </ul>

                                        <!-- Progress bar -->

                                        <div class="progress-block">

                                            <!-- Tags -->

                                            <div class="progress-tags">

                                                <div>Presale</div>

                                                <div>Soft Cap</div>

                                                <div>Bonus</div>

                                            </div>

                                            <progress class="progress ico-progress" value="65" max="100">65%</progress>

                                        </div>

                                        <!-- Button -->

                                        <div class="button-block">

                                            <a href="#" class="button k-button k-secondary raised has-gradient is-bold is-fullwidth rounded">

                                                <span class="text">Join the ICO Now</span>

                                                <span class="front-gradient"></span>

                                            </a>

                                        </div>

                                        <!-- Icons -->

                                        <div class="icon-block">

                                            <i class="cf cf-btc"></i>

                                            <i class="cf cf-eth"></i>

                                            <i class="cf cf-ltc"></i>

                                        </div>

                                    </div>

                                </div>

                            </div>

                        </div>

                        <!-- /Tab 1 -->

                        <!-- Tab 2 -->

                        <div class="tab-content" :class="{

                                'is-active': activeTab === 'tab-2',

                                '': activeTab != 'tab-2'

                            }">

                            <div class="columns is-vcentered tab-content-wrapper">

                                <!-- Tab content -->

                                <div class="column is-5 is-offset-1">

                                    <div class="text-content">

                                        <h4 class="title is-6 is-light animated preFadeInUp fadeInUp">TOKEN RATES</h4>

                                        <ul class="custom-bullet-list">

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Tokens Sales</span>

                                                <br>

                                                <span class="item-content">1 200 000 KP (22%)</span>

                                            </li>

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Token Exchange</span>

                                                <br>

                                                <span class="item-content">1 BTC = 2200 KP, 1 ETH = 825 KP</span> 

                                            </li>

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Transations</span>

                                                <br>

                                                <span class="item-content">Minimal transaction amount is 1 BTC, 1 ETH, 1 LTC</span>

                                            </li>

                                        </ul>

                                    </div>

                                </div>

                                <!-- Tab image -->

                                <div class="column is-5">

                                    <img class="animated preFadeInUp fadeInUp" src="/img/illustrations/tokens.svg" alt="">

                                </div>

                            </div>

                        </div>

                        <!-- /Tab 2 -->

                        <!-- Tab 3 -->

                        <div class="tab-content" :class="{

                                'is-active': activeTab === 'tab-3',

                                '': activeTab != 'tab-3'

                            }">

                            <div class="columns is-vcentered tab-content-wrapper">

                                <!-- Tab content -->

                                <div class="column is-5 is-offset-1">

                                    <div class="text-content">

                                        <h4 class="title is-6 is-light animated preFadeInUp fadeInUp">PROFIT</h4>

                                        <ul class="custom-bullet-list">

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Tokens Sales</span>

                                                <br>

                                                <span class="item-content">1 200 000 KP (22%)</span>

                                            </li>

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Token Exchange</span>

                                                <br>

                                                <span class="item-content">1 BTC = 2200 KP, 1 ETH = 825 KP</span> 

                                            </li>

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Transations</span>

                                                <br>

                                                <span class="item-content">Minimal transaction amount is 1 BTC, 1 ETH, 1 LTC</span>

                                            </li>

                                        </ul>

                                    </div>

                                </div>

                                <!-- Tab image -->

                                <div class="column is-5">

                                    <img class="animated preFadeInUp fadeInUp" src="/img/illustrations/charts.svg" alt="">

                                </div>

                            </div>

                        </div>

                        <!-- /Tab 3 -->

                        <!-- Tab 4 -->

                        <div class="tab-content" :class="{

                                'is-active': activeTab === 'tab-4',

                                '': activeTab != 'tab-4'

                            }">

                            <div class="columns is-vcentered tab-content-wrapper">

                                <!-- Tab content -->

                                <div class="column is-5 is-offset-1">

                                    <div class="text-content">

                                        <h4 class="title is-6 is-light animated preFadeInUp fadeInUp">REWARDS & BOUNTIES</h4>

                                        <ul class="custom-bullet-list">

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Tokens Sales</span>

                                                <br>

                                                <span class="item-content">1 200 000 KP (22%)</span>

                                            </li>

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Token Exchange</span>

                                                <br>

                                                <span class="item-content">1 BTC = 2200 KP, 1 ETH = 825 KP</span> 

                                            </li>

                                            <li class="animated preFadeInUp fadeInUp">

                                                <span>Transations</span>

                                                <br>

                                                <span class="item-content">Minimal transaction amount is 1 BTC, 1 ETH, 1 LTC</span>

                                            </li>

                                        </ul>

                                    </div>

                                </div>

                                <!-- Tab image -->

                                <div class="column is-5">

                                    <img class="animated preFadeInUp fadeInUp" src="/img/illustrations/bounty.svg" alt="">

                                </div>

                            </div>

                        </div>

                        <!-- /Tab 4 -->

                    </div>

                </div>

            </div>

            <!-- Content wrapper -->

        </div>

        <!-- /Container -->

    </section>

    <!-- /ICO section -->

    <!-- App section -->

    <section class="section is-medium is-darkest">

        <!-- Container -->

        <div class="container">

            <!-- Divider -->

            <div class="divider is-centered"></div>

            <!-- Title -->

            <h2 class="title is-light is-semibold has-text-centered is-spaced">Live Tracking</h2>

            <h4 class="subtitle is-6 is-light has-text-centered is-compact">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Ut sea pertinax perpetua, eruditi volumus quaestio ex mel, has ei tota homero.</h4>

            <!-- Content wrapper -->

            <div class="content-wrapper is-large">

                <!-- Row -->

                <div class="columns is-vcentered">

                    <div class="column is-5">

                        <!-- Side feature -->

                        <div class="side-feature-content">

                            <!-- Title -->

                            <h3 class="title is-4 is-light"><img src="/img/icons/ico/bitnetwork.svg" alt=""> <span>Track everything with the App</span></h3>

                            <!-- Divider -->

                            <div class="divider is-long"></div>

                            <p class="is-light">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Eu impetus perfecto sit, no sea labore detraxit.</p>

                            <!-- CTA -->

                            <div class="cta-wrapper">

                                <a href="#" class="button k-button k-primary raised has-gradient is-fat is-bold">

                                    <span class="text">Download App</span>

                                    <span class="front-gradient"></span>

                                </a>

                            </div>

                        </div>

                    </div>

                    <!-- Featured image -->

                    <div class="column is-7">

                        <img class="side-feature" src="/img/illustrations/krypton-app.svg" alt="">

                    </div>

                </div>

            </div>

            <!-- /Content wrapper -->

        </div>

        <!-- /Container -->

    </section>

    <!-- /App section -->

    <!-- Company section -->

    <section class="section is-medium has-big-dark-gradient">

        <!-- Container -->

        <div class="container">

            <!-- Divider -->

            <div class="divider is-centered"></div>

            <!-- Title & subtitle -->

            <h2 class="title is-light is-semibold has-text-centered is-spaced">Our Team</h2>

            <h4 class="subtitle is-6 is-light has-text-centered is-compact">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Ut sea pertinax perpetua, eruditi volumus quaestio ex mel, has ei tota homero.</h4>

            <!-- Content wrapper -->

            <div class="content-wrapper is-large">

                <div class="columns is-vcentered">

                    <div class="column is-hidden-mobile"></div>

                    <!-- Team member -->

                    <div class="column is-3">

                        <div class="team-member-container">

                            <!-- Card -->

                            <div class="dark-card">

                                <!-- Avatar wrapper -->

                                <div class="avatar">

                                    <!-- Svg circle -->

                                    <svg class="circle-chart" viewbox="0 0 33.83098862 33.83098862" width="140" height="140" xmlns="http://www.w3.org/2000/svg">

                                        <!-- Track -->

                                        <circle class="circle-chart-background" stroke-width="1" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                        <!-- Stroke -->

                                        <circle class="circle-chart-circle" stroke-width="1" stroke-dasharray="33,100" stroke-linecap="round" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                    </svg>

                                    <!-- Sketeched face -->

                                    <img class="is-sketch" src="/img/team/john.svg" alt="">

                                    <!-- Real face -->

                                    <img class="is-real" src="/img/team/john.jpg" alt="">

                                </div>

                                <!-- Member meta -->

                                <div class="member-info">

                                    <h4 class="title is-light is-6 is-tight">John Cambell</h4>

                                    <div class="position">Founder / Ceo</div>

                                    <p class="description">John is a Crypto enthusiast. He was one of the first bolckchain actors in the world.</p>

                                </div>

                            </div>

                        </div>

                    </div>

                    <!-- Team member -->

                    <div class="column is-3">

                        <div class="team-member-container">

                            <div class="dark-card">

                                <div class="avatar">

                                    <svg class="circle-chart" viewbox="0 0 33.83098862 33.83098862" width="140" height="140" xmlns="http://www.w3.org/2000/svg">

                                        <circle class="circle-chart-background" stroke-width="1" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                        <circle class="circle-chart-circle" stroke-width="1" stroke-dasharray="33,100" stroke-linecap="round" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                    </svg>

                                    <img class="is-sketch" src="/img/team/lucy.svg" alt="">

                                    <img class="is-real" src="/img/team/lucy.jpg" alt="">

                                </div>

                                <div class="member-info">

                                    <h4 class="title is-light is-6 is-tight">Lucy Wong</h4>

                                    <div class="position">Founder / Cfo</div>

                                    <p class="description">Lucy is a Crypto enthusiast. He was one of the first bolckchain actors in the world.</p>

                                </div>

                            </div>

                        </div>

                    </div>

                    <!-- Team member -->

                    <div class="column is-3">

                        <div class="team-member-container">

                            <div class="dark-card">

                                <div class="avatar">

                                    <svg class="circle-chart" viewbox="0 0 33.83098862 33.83098862" width="140" height="140" xmlns="http://www.w3.org/2000/svg">

                                        <circle class="circle-chart-background" stroke-width="1" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                        <circle class="circle-chart-circle" stroke-width="1" stroke-dasharray="33,100" stroke-linecap="round" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                    </svg>

                                    <img class="is-sketch" src="/img/team/joshua.svg" alt="">

                                    <img class="is-real" src="/img/team/joshua.jpg" alt="">

                                </div>

                                <div class="member-info">

                                    <h4 class="title is-light is-6 is-tight">Joshua Stevens</h4>

                                    <div class="position">Engineer</div>

                                    <p class="description">Joshua is a Crypto enthusiast. He was one of the first bolckchain actors in the world.</p>

                                </div>

                            </div>

                        </div>

                    </div>

                    <div class="column is-hidden-mobile"></div>

                </div>

                <div class="columns is-vcentered">

                    <div class="column is-hidden-mobile"></div>

                    <!-- Team member -->

                    <div class="column is-3">

                        <div class="team-member-container">

                            <div class="dark-card">

                                <div class="avatar">

                                    <svg class="circle-chart" viewbox="0 0 33.83098862 33.83098862" width="140" height="140" xmlns="http://www.w3.org/2000/svg">

                                        <circle class="circle-chart-background" stroke-width="1" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                        <circle class="circle-chart-circle" stroke-width="1" stroke-dasharray="33,100" stroke-linecap="round" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                    </svg>

                                    <img class="is-sketch" src="/img/team/sara.svg" alt="">

                                    <img class="is-real" src="/img/team/sara.jpg" alt="">

                                </div>

                                <div class="member-info">

                                    <h4 class="title is-light is-6 is-tight">Sara Jackson</h4>

                                    <div class="position">Founder / Ceo</div>

                                    <p class="description">Sara is a Crypto enthusiast. He was one of the first bolckchain actors in the world.</p>

                                </div>

                            </div>

                        </div>

                    </div>

                    <!-- Team member -->

                    <div class="column is-3">

                        <div class="team-member-container">

                            <div class="dark-card">

                                <div class="avatar">

                                    <svg class="circle-chart" viewbox="0 0 33.83098862 33.83098862" width="140" height="140" xmlns="http://www.w3.org/2000/svg">

                                        <circle class="circle-chart-background" stroke-width="1" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                        <circle class="circle-chart-circle" stroke-width="1" stroke-dasharray="33,100" stroke-linecap="round" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                    </svg>

                                    <img class="is-sketch" src="/img/team/mike.svg" alt="">

                                    <img class="is-real" src="/img/team/mike.jpg" alt="">

                                </div>

                                <div class="member-info">

                                    <h4 class="title is-light is-6 is-tight">Mike Kovalsky</h4>

                                    <div class="position">Founder / Ceo</div>

                                    <p class="description">Sara is a Crypto enthusiast. He was one of the first bolckchain actors in the world.</p>

                                </div>

                            </div>

                        </div>

                    </div>

                    <!-- Team member -->

                    <div class="column is-3">

                        <div class="team-member-container">

                            <div class="dark-card">

                                <div class="avatar">

                                    <svg class="circle-chart" viewbox="0 0 33.83098862 33.83098862" width="140" height="140" xmlns="http://www.w3.org/2000/svg">

                                        <circle class="circle-chart-background" stroke-width="1" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                        <circle class="circle-chart-circle" stroke-width="1" stroke-dasharray="33,100" stroke-linecap="round" fill="none" cx="16.91549431" cy="16.91549431" r="15.91549431" />

                                    </svg>

                                    <img class="is-sketch" src="/img/team/sandra.svg" alt="">

                                    <img class="is-real" src="/img/team/sandra.jpg" alt="">

                                </div>

                                <div class="member-info">

                                    <h4 class="title is-light is-6 is-tight">Sandra Bernard</h4>

                                    <div class="position">Founder / Ceo</div>

                                    <p class="description">Sandra is a Crypto enthusiast. He was one of the first bolckchain actors in the world.</p>

                                </div>

                            </div>

                        </div>

                    </div>

                    <div class="column is-hidden-mobile"></div>

                </div>

                <!-- Spaced divider -->

                <div class="divider is-centered is-spacer"></div>

                <!-- Title & subtitle -->

                <h2 class="title is-light is-semibold has-text-centered is-spaced">Advisors</h2>

                <h4 class="subtitle is-6 is-light has-text-centered is-compact">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Ut sea pertinax perpetua, eruditi volumus quaestio ex mel, has ei tota homero.</h4>

                <!-- Content wrapper -->

                <div class="content-wrapper is-large">

                    <div class="columns is-vcentered is-multiline">

                        <!-- Advisor -->

                        <div class="column is-one-fifth">

                            <div class="advisor-container has-text-centered">

                                <!-- Picture -->

                                <div class="photo">

                                    <img src="/img/team/a1.jpg" alt="" data-aos="fade-down" data-aos-delay="100" data-aos-offset="200" data-aos-easing="ease-out-quart">

                                </div>

                                <!-- Meta -->

                                <div class="info">

                                    <div class="subtitle is-6 is-light is-compressed">Rafael Agostino</div>

                                    <div class="position">Board Member</div>

                                </div>

                            </div>

                        </div>

                        <!-- Advisor -->

                        <div class="column is-one-fifth">

                            <div class="advisor-container has-text-centered">

                                <div class="photo">

                                    <img src="/img/team/a2.jpg" alt="" data-aos="fade-down" data-aos-delay="300" data-aos-offset="200" data-aos-easing="ease-out-quart">

                                </div>

                                <div class="info">

                                    <div class="subtitle is-6 is-light is-compressed">Marysa Vosniak</div>

                                    <div class="position">Board Member</div>

                                </div>

                            </div>

                        </div>

                        <!-- Advisor -->

                        <div class="column is-one-fifth">

                            <div class="advisor-container has-text-centered">

                                <div class="photo">

                                    <img src="/img/team/a3.jpg" alt="" data-aos="fade-down" data-aos-delay="500" data-aos-offset="200" data-aos-easing="ease-out-quart">

                                </div>

                                <div class="info">

                                    <div class="subtitle is-6 is-light is-compressed">Glenn Mitchells</div>

                                    <div class="position">Board Member</div>

                                </div>

                            </div>

                        </div>

                        <!-- Advisor -->

                        <div class="column is-one-fifth">

                            <div class="advisor-container has-text-centered">

                                <div class="photo">

                                    <img src="/img/team/a4.jpg" alt="" data-aos="fade-down" data-aos-delay="700" data-aos-offset="200" data-aos-easing="ease-out-quart">

                                </div>

                                <div class="info">

                                    <div class="subtitle is-6 is-light is-compressed">Gary Simmons</div>

                                    <div class="position">Crypto Finance Analyst</div>

                                </div>

                            </div>

                        </div>

                        <!-- Advisor -->

                        <div class="column is-one-fifth">

                            <div class="advisor-container has-text-centered">

                                <div class="photo">

                                    <img src="/img/team/a5.jpg" alt="" data-aos="fade-down" data-aos-delay="900" data-aos-offset="200" data-aos-easing="ease-out-quart">

                                </div>

                                <div class="info">

                                    <div class="subtitle is-6 is-light is-compressed">Olga Broniszewska</div>

                                    <div class="position">Crypto Finance Analyst</div>

                                </div>

                            </div>

                        </div>

                    </div>

                </div>

                <!-- /Content wrapper -->

                <!-- Spaced divider -->

                <div class="divider is-centered is-spacer"></div>

                <!-- Title & subtitle -->

                <h2 class="title is-light is-semibold has-text-centered is-spaced">FAQ</h2>

                <h4 class="subtitle is-6 is-light has-text-centered is-compact">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Ut sea pertinax perpetua, eruditi volumus quaestio ex mel, has ei tota homero.</h4>

                <!-- Content wrapper -->

                <div class="content-wrapper is-large">

                    <div class="columns">

                        <div class="column is-5 is-offset-1">

                            <!-- Accordion -->

                            <div class="accordion">

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle1" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle1">

                                        What is Blockchain ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle2" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle2">

                                        What is ICO ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle3" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle3">

                                        Where to get the Whitepaper ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle4" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle4">

                                        What is Krypton Core Innovation ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle5" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle5">

                                        When will be the platform released ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                            </div>

                            <!-- /Accordion -->

                        </div>

                        <div class="column is-5">

                            <!-- Accordion -->

                            <div class="accordion">

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle6" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle6">

                                        How much tokens will be sold ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle7" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle7">

                                        What happens if Soft Cap isn't reached ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle8" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle8">

                                        How much do you want to raise with the ICO ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle9" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle9">

                                        When will the tokens be distributed ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                                <!-- Option -->

                                <div class="accordion-option">

                                    <input type="checkbox" id="toggle10" class="accordion-toggle" />

                                    <label class="accordion-title" for="toggle10">

                                        Will their be Bounties ?

                                    </label>

                                    <div class="accordion-content">

                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>

                                    </div>

                                </div>

                            </div>

                            <!-- /Accordion -->

                        </div>

                    </div>

                </div>

                <!-- /Content wrapper -->

                <!-- Spaced divider -->

                <div class="divider is-centered is-spacer"></div>

                <!-- Title & subtitle -->

                <h2 class="title is-light is-semibold has-text-centered is-spaced">Media & Partners</h2>

                <h4 class="subtitle is-6 is-light has-text-centered is-compact">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Ut sea pertinax perpetua, eruditi volumus quaestio ex mel, has ei tota homero.</h4>

                <!-- Content wrapper -->

                <div class="content-wrapper is-large">

                    <div class="columns">

                        <!-- Media section -->

                        <div class="column is-10 is-offset-1">

                            <!-- Post -->

                            <div class="blog-post">

                                <a href="#">

                                    <!-- Featured image -->

                                    <div class="featured-image">

                                        <img src="/img/media/post1.svg" alt="">

                                    </div>

                                    <!-- Content -->

                                    <div class="content">

                                        <div class="post-title">Blockchain for dummies  <span class="blog-date">27.05.2021</span></div>

                                        <p>

                                            Lorem Ipsum, dizgi ve baskı endüstrisinde kullanılan mıgır metinlerdir. Lorem Ipsum, adı

                                            bilinmeyen bir matbaacının bir hurufat numune kitabı...

                                        </p>

                                        <!-- Meta -->

                                        <div class="post-meta">

                                            <div class="author-block">

                                                <div class="image is-32x32">

                                                    <img src="/img/team/john.jpg" alt="">

                                                </div>

                                                <div class="author-name">by John Cambell</div>

                                            </div>

                                            <div class="stats-block">

                                                <div class="comments">

                                                    <i data-feather="message-circle"></i>

                                                    <span>3</span>

                                                </div>

                                                <div class="likes">

                                                    <i data-feather="heart"></i>

                                                    <span>9</span>

                                                </div>

                                            </div>

                                        </div>

                                    </div>

                                </a>

                            </div>

                            <!-- Post -->

                            <div class="blog-post">

                                <a href="#">

                                    <!-- Featured image -->

                                    <div class="featured-image">

                                        <img src="/img/media/post2.svg" alt="">

                                    </div>

                                    <!-- Content -->

                                    <div class="content">

                                        <div class="post-title">The Krypton chain algorythm  <span class="blog-date">15.04.2021</span></div>

                                        <p>

                                            Lorem Ipsum, dizgi ve baskı endüstrisinde kullanılan mıgır metinlerdir. Lorem Ipsum, adı

                                            bilinmeyen bir matbaacının bir hurufat numune kitabı...

                                        </p>

                                        <!-- Meta -->

                                        <div class="post-meta">

                                            <div class="author-block">

                                                <div class="image is-32x32">

                                                    <img src="/img/team/joshua.jpg" alt="">

                                                </div>

                                                <div class="author-name">by Joshua Stevens</div>

                                            </div>

                                            <div class="stats-block">

                                                <div class="comments">

                                                    <i data-feather="message-circle"></i>

                                                    <span>7</span>

                                                </div>

                                                <div class="likes">

                                                    <i data-feather="heart"></i>

                                                    <span>29</span>

                                                </div>

                                            </div>

                                        </div>

                                    </div>

                                </a>

                            </div>

                            <!-- Post -->

                            <div class="blog-post">

                                <a href="#">

                                    <!-- Featured image -->

                                    <div class="featured-image">

                                        <img src="/img/media/post3.svg" alt="">

                                    </div>

                                    <!-- Content -->

                                    <div class="content">

                                        <!--div class="rounded"></div-->

                                        <div class="post-title">What is Crypto mining ?  <span class="blog-date">02.04.2021</span></div>

                                        <p>

                                            Lorem Ipsum, dizgi ve baskı endüstrisinde kullanılan mıgır metinlerdir. Lorem Ipsum, adı

                                            bilinmeyen bir matbaacının bir hurufat numune kitabı...

                                        </p>

                                        <!-- Meta -->

                                        <div class="post-meta">

                                            <div class="author-block">

                                                <div class="image is-32x32">

                                                    <img src="/img/team/sandra.jpg" alt="">

                                                </div>

                                                <div class="author-name">by Sandra Bernard</div>

                                            </div>

                                            <div class="stats-block">

                                                <div class="comments">

                                                    <i data-feather="message-circle"></i>

                                                    <span>31</span>

                                                </div>

                                                <div class="likes">

                                                    <i data-feather="heart"></i>

                                                    <span>48</span>

                                                </div>

                                            </div>

                                        </div>

                                    </div>

                                </a>

                            </div>

                        </div>

                        <!-- /Media section -->

                    </div>

                    <!-- CTA -->

                    <div class="cta-wrapper has-text-centered">

                        <a href="#" class="button k-button k-primary raised has-gradient is-fat is-bold">

                            <span class="text">More Articles</span>

                            <span class="front-gradient"></span>

                        </a>

                    </div>

                    <!-- Partner logos -->

                    <div class="partners">

                        <!-- Partner -->

                        <div class="partner-item">

                            <img src="/img/clients/cryptomarket.svg" alt="">

                        </div>

                        <!-- Partner -->

                        <div class="partner-item">

                            <img src="/img/clients/bitit.svg" alt="">

                        </div>

                        <!-- Partner -->

                        <div class="partner-item">

                            <img src="/img/clients/coin.svg" alt="">

                        </div>

                    </div>

                </div>

                <!-- /Content wrapper -->

            </div>

            <!-- /Content wrapper -->

        </div>

    </section>

    <!-- /Company section -->

    <!-- Contact section -->

    <section class="section is-medium is-darkest">

        <!-- Container -->

        <div class="container">

            <!-- Divider -->

            <div class="divider is-centered"></div>

            <!-- Title & subtitle -->

            <h2 class="title is-light is-semibold has-text-centered is-spaced">Get in Touch</h2>

            <h4 class="subtitle is-6 is-light has-text-centered is-compact">Viderer malorum sadipscing cum ei. Eu impetus perfecto sit, no sea labore detraxit. Primis mediocrem necessitatibus an vis. Ut sea pertinax perpetua, eruditi volumus quaestio ex mel, has ei tota homero.</h4>

            <!-- Content wrapper -->

            <div class="content-wrapper is-large">

                <div class="columns">

                    <div class="column is-8 is-offset-2">

                        <!-- Contact icons -->

                        <div class="contact-icons">

                            <!-- Phone -->

                            <a class="contact-icon" data-aos="fade-up" data-aos-delay="100" data-aos-offset="200" data-aos-easing="ease-out-quart">

                                <img class="is-phone" src="/img/icons/phone.svg" alt="">

                            </a>

                            <!-- Mail -->

                            <a class="contact-icon" data-aos="fade-up" data-aos-delay="300" data-aos-offset="200" data-aos-easing="ease-out-quart">

                                <img class="is-phone" src="/img/icons/mail.svg" alt="">

                            </a>

                            <!-- Telegram -->

                            <a class="contact-icon" data-aos="fade-up" data-aos-delay="500" data-aos-offset="200" data-aos-easing="ease-out-quart">

                                <img class="is-telegram" src="/img/logo/telegram.svg" alt="">

                            </a>

                        </div> 

                    </div>

                </div>

                <div class="columns">

                    <div class="column is-6 is-offset-3">

                        <!-- Form -->

                        <form class="contact-form">

                            <!-- Field -->

                            <div class="control-material is-secondary">      

                                <input class="material-input " type="text" required>

                                <span class="material-highlight"></span>

                                <span class="bar"></span>

                                <label>Name</label>

                            </div>

                            <!-- Field -->

                            <div class="control-material is-secondary">      

                                <input class="material-input " type="email" required>

                                <span class="material-highlight"></span>

                                <span class="bar"></span>

                                <label>Email</label>

                            </div>

                            <!-- Field -->

                            <div class="control-material is-secondary">  

                                <textarea rows="3"></textarea>

                                <span class="material-highlight"></span>

                                <span class="bar"></span>

                                <label>Message </label>

                            </div>

                            <!-- Submit -->

                            <div class="has-text-centered">

                                <button class="button is-button k-button k-primary raised has-gradient is-fat is-bold is-submit">

                                    <span class="text">Send message</span>

                                    <span class="front-gradient"></span>

                                </button>

                            </div>

                        </form>

                        <!-- /Form -->

                    </div>

                </div>

            </div>

            <!-- Content wrapper -->

        </div>

        <!-- Container -->

    </section>

    <!-- Contact section -->

</d
