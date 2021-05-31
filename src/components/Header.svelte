<script>
  
    import { link } from "svelte-spa-router";
</script>

<!-- Header
		============================================= -->
<header id="header" class="header-size-sm" data-sticky-shrink="false">
    <div class="container">
        <div class="header-row">
            <!-- Logo
					============================================= -->
            <div id="logo" class="ml-auto ml-lg-0 mr-lg-auto">
                <a href="index.html" class="standard-logo"
                    ><img
                        src="./favicon.ico"
                        style="height:81px;"
                        alt="Canvas Logo"
                    />JIKYUNG SOLUTEC</a
                >
            </div>
            <!-- #logo end -->

            <div class="header-misc d-none d-lg-flex">
                <ul class="header-extras">
                    <li>
                        <i class="i-plain icon-call m-0" />
                        <div class="he-text">
                            Call Us
                            <span>(1) 22 54215821</span>
                        </div>
                    </li>
                    <li>
                        <i class="i-plain icon-line2-envelope m-0" />
                        <div class="he-text">
                            Email Us
                            <span>info@canvas.com</span>
                        </div>
                    </li>
                    <li>
                        <i class="i-plain icon-line-clock m-0" />
                        <div class="he-text">
                            We'are Open
                            <span>Mon - Sat, 10AM to 6PM</span>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </div>

    <div id="header-wrap">
        <div class="container">
            <div
                class="header-row justify-content-between flex-row-reverse flex-lg-row justify-content-lg-center"
            >
                <div class="header-misc">
                    <!-- Top Search
							============================================= -->
                    <div id="top-search" class="header-misc-icon">
                        <a href="#" id="top-search-trigger"
                            ><i class="icon-line-search" /><i
                                class="icon-line-cross"
                            /></a
                        >
                    </div>
                    <!-- #top-search end -->
                </div>

                <div id="primary-menu-trigger">
                    <svg class="svg-trigger" viewBox="0 0 100 100"
                        ><path
                            d="m 30,33 h 40 c 3.722839,0 7.5,3.126468 7.5,8.578427 0,5.451959 -2.727029,8.421573 -7.5,8.421573 h -20"
                        /><path d="m 30,50 h 40" /><path
                            d="m 70,67 h -40 c 0,0 -7.5,-0.802118 -7.5,-8.365747 0,-7.563629 7.5,-8.634253 7.5,-8.634253 h 20"
                        /></svg
                    >
                </div>

                <!-- Primary Navigation
						============================================= -->
                <nav class="primary-menu with-arrows">
                    <ul class="menu-container">
                        <li class="menu-item current">
                            <a class="menu-link" href="demo-construction.html"
                                ><div>회사소개</div></a
                            >
                        </li>
                        <li class="menu-item">
                            <a
                                class="menu-link"
                                href="demo-construction-services.html"
                                ><div>제품소개</div></a
                            >
                            <ul class="sub-menu-container">
                                <li class="menu-item">
                                    <a href="#" class="menu-link"
                                        ><div>PLM</div></a
                                    >
                                </li>
                                <li class="menu-item">
                                    <a class="menu-link" use:link href="/solidEdge">
                                        <div>Solid Edge</div>
                                    </a>
                                </li>
                                <li class="menu-item">
                                    <a class="menu-link" href="#"
                                        ><div>Solid works</div></a
                                    >
                                </li>
                                <li class="menu-item">
                                    <a class="menu-link" href="#"
                                        ><div>기타</div></a
                                    >
                                </li>
                            </ul>
                        </li>
                        <li class="menu-item">
                            <a
                                class="menu-link"
                                href="demo-construction-about-us.html"
                                ><div>제품문의</div></a
                            >
                        </li>
                        <li class="menu-item">
                            <a
                                class="menu-link"
                                href="demo-construction-projects.html"
                                ><div>기술자료실</div></a
                            >
                            <ul class="sub-menu-container">
                                <li class="menu-item">
                                    <a
                                        class="menu-link"
                                        href="demo-construction-projects-2.html"
                                        ><div>PLM</div></a
                                    >
                                </li>
                                <li class="menu-item">
                                    <a
                                        class="menu-link"
                                        href="demo-construction-projects-3.html"
                                        ><div>Solid Edge</div></a
                                    >
                                </li>
                                <li class="menu-item">
                                    <a
                                        class="menu-link"
                                        href="demo-construction-projects.html"
                                        ><div>Solid Works</div></a
                                    >
                                </li>
                            </ul>
                        </li>
                        <li class="menu-item">
                            <a
                                class="menu-link"
                                href="demo-construction-investors.html"
                                ><div>커뮤니티</div></a
                            >
                        </li>
                        <!-- <li class="menu-item">
                            <a
                                class="menu-link"
                                href="demo-construction-blog.html"
                                ><div>News</div></a
                            >
                        </li>
                        <li class="menu-item">
                            <a
                                class="menu-link"
                                href="demo-construction-careers.html"
                                ><div>Careers</div></a
                            >
                        </li>
                        <li class="menu-item">
                            <a
                                class="menu-link"
                                href="demo-construction-contact.html"
                                ><div>Contact</div></a
                            >
                        </li> -->
                    </ul>
                </nav>
                <!-- #primary-menu end -->

                <form class="top-search-form" action="search.html" method="get">
                    <input
                        type="text"
                        name="q"
                        class="form-control"
                        value=""
                        placeholder="Type &amp; Hit Enter.."
                        autocomplete="off"
                    />
                </form>
            </div>
        </div>
    </div>
    <div class="header-wrap-clone" />
</header>
<!-- #header end -->

<section
    id="slider"
    class="slider-element slider-parallax swiper_wrapper min-vh-75"
    data-loop="true"
>
    <div class="swiper-container swiper-parent">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                <div class="container">
                    <div class="slider-caption">
                        <div>
                            <h2>Welcome to Canvas</h2>
                            <p class="d-none d-sm-block">
                                Create just what you need for your Perfect
                                Website. Choose from a wide range of Elements
                                &amp; simply put them on your own Canvas.
                            </p>
                        </div>
                    </div>
                </div>
                <div
                    class="swiper-slide-bg"
                    style="background-image: url('demos/construction/images/slider/2.jpg'); background-position: center top;"
                />
            </div>
            <div class="swiper-slide">
                <div class="container">
                    <div class="slider-caption slider-caption-right">
                        <div>
                            <h2>Beautifully Flexible</h2>
                            <p class="d-none d-sm-block">
                                Looks beautiful &amp; ultra-sharp on Retina
                                Screen Displays. Powerful Layout with Responsive
                                functionality that can be adapted to any screen
                                size.
                            </p>
                        </div>
                    </div>
                </div>
                <div class="video-wrap">
                    <video
                        id="slide-video"
                        poster="demos/construction/images/videos/1.jpg"
                        preload="auto"
                        loop
                        autoplay
                        muted
                    >
                        <source
                            src="demos/construction/images/videos/1.webm"
                            type="video/webm"
                        />
                        <source
                            src="demos/construction/images/videos/1.mp4"
                            type="video/mp4"
                        />
                    </video>
                    <div
                        class="video-overlay"
                        style="background-color: rgba(0,0,0,0.1);"
                    />
                </div>
            </div>
            <div class="swiper-slide">
                <div class="container">
                    <div class="slider-caption">
                        <div>
                            <h2>Premium Constructions</h2>
                            <p class="d-none d-sm-block">
                                You'll be surprised to see the Final Results of
                                your Creation &amp; would crave for more.
                            </p>
                        </div>
                    </div>
                </div>
                <div
                    class="swiper-slide-bg"
                    style="background-image: url('demos/construction/images/slider/1.jpg'); background-position: center bottom;"
                />
            </div>
        </div>
        <div class="slider-arrow-left"><i class="icon-angle-left" /></div>
        <div class="slider-arrow-right"><i class="icon-angle-right" /></div>
    </div>
</section>

<!-- #Slider end -->
<style lang="scss"></style>
