---
layout: default
---

<div class="business-hero">
    <div class="container">
        <h2 class="customFadeInUp">
            A blockchain interoperability platform for a new world.
        </h2>
        <p class="customFadeInUp">
            We are building a developer friendly blockchain interoperability platform 
            to unleash the full potential of the crypto revolution.
        </p>

        <div class="actions customFadeInUp" data-toggle="modal" data-target="#video-modal">
            <button class="btn-shadow btn-shadow-info mr-md-1">Watch Intro Video</button>
        </div>

    </div>
</div>

<div class="modal fade" tabindex="-1" role="dialog" id="video-modal">
  <div class="modal-dialog modal-lg modal-xlg">
    <div class="modal-content">
        <div class="modal-body">
        <div class="embed-responsive  embed-responsive-16by9">
            <iframe id="youtube_player" class="yt_player_iframe" type="text/html" src="https://www.youtube.com/embed/X94qHbZBYA8?enablejsapi=1&version=3&playerapiid=ytplayer" 
            frameborder="0" allowscriptaccess="always">
            </iframe>
        </div>
      </div>
    </div>
  </div>
</div>
<script>
$('#video-modal').on('hide.bs.modal', function (e) {
   $('.yt_player_iframe')[0].contentWindow.postMessage('{"event":"command","func":"' + 'stopVideo' + '","args":""}', '*');
});
</script>



<div class="spacial-features" data-scroll style="    margin: 80px auto 0;
                                                     max-width: 1400px;">
    <section class="container">
        <div class="row">
            <div class="col-12">
                <div class="header">
                    <h2>Blockchain Interoperability Platform</h2>
                    <p>
                        ARK Contract Execution Services (ACES) provides simple protocols and 
                        tools for building a robust blockchain service marketplace.
                    </p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-4">
                <div class="feature">
                    <h3>
                        ACES Listeners
                    </h3>
                    <p>
                        ACES Listeners provide a way for all the different blockchain transaction events 
                        to be easily consumed via a common REST-ful API. The API allows consumers to create 
                        subscriptions and receive blockchain events in real-time using Webhook callbacks.
                    </p>
                    <p>
                        <a class="btn-sm btn-shadow btn-shadow-info" href="listeners">
                            Learn More
                        </a>
                    </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="feature">
                    <h3>
                        ACES Services
                    </h3>
                    <p>
                        ACES Services create and excute Service Contracts, which can be anything from uploading a 
                        file to a storage blockchain, 
                        performing value transfers, creating smart contracts, executing code on blockchain based 
                        computing platforms, or interacting with IoT hardware.
                    </p>
                    <p>
                        <a class="btn-sm btn-shadow btn-shadow-info" href="services">
                            Learn More
                        </a>
                    </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="feature">
                    <h3>
                        ACES Marketplace Console
                    </h3>
                    <p>
                        The ACES Marketplace Console is a consumer dashboard for searching and executing
                        service contracts listed on the Marketplace.
                        ACES Service providers can list their service nodes using the Marketplace API.
                    </p>
                    <p>
                        <a class="btn-sm btn-shadow btn-shadow-info" href="/marketplace">
                            Learn More
                        </a>
                    </p>
                </div>
            </div>
        </div>
    </section>

</div>


<div class="index-clients">
    <div class="container">
        <header>
            <h4>Platform Statistics</h4>
        </header>
        <div class="about-2-stats">

            <div class="container">
                <div class="row">
                    <div class="col-md-3 text-center">
                        <span>4</span>
                        <p>Listeners</p>
                    </div>
                    <div class="col-md-3 text-center">
                        <span>3</span>
                        <p>Services</p>
                    </div>
                    <div class="col-md-3 text-center">
                        <span>1</span>
                        <p>Marketplaces</p>
                    </div>
                    <div class="col-md-3 text-center">
                        <span>0 BTC</span>
                        <p>Volume</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="index-features" data-scroll>
    <div class="container">
        <header>
            <h3>Platform Features</h3>
        </header>
        <section class="features">
            <div class="row">
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Open Source
                        </h4>
                        <p>
                            Everything on the ACES platform is open source and uses a permissive free software license (MIT).
                        </p>
                    </section>
                </div>
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            REST-ful APIs
                        </h4>
                        <p>
                            The ACES platform uses simple REST-ful APIs for easy integration.
                        </p>
                    </section>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Decentrallized
                        </h4>
                        <p>
                            A marketplace platform that allows users to consume blockchain services offered by a 
                            decentralized collection of service providers. 
                        </p>
                    </section>
                </div>
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Service Composition
                        </h4>
                        <p>
                            Use functional composition to chain ACES Services together.
                        </p>
                    </section>
                </div>
            </div>
            <div class="row">
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Incentivized
                        </h4>
                        <p>
                            The ACES platform provides an open fee model that allows service providers
                            to compete in a free market.
                        </p>
                    </section>
                </div>
                <div class="col-md-6 feature">
                    <img src="assets/images/ark-block-logo.png" class="icon" />
                    <section>
                        <h4>
                            Programming Languages
                        </h4>
                        <p>
                            Built using light-weight microservices that are easy for providers
                            to implement in different programming languages and frameworks.
                        </p>
                    </section>
                </div>
            </div>
        </section>
    </div>
</div>


<div class="index-devices" data-scroll>
    <section class="clearfix">
        <img src="assets/images/aces-marketplace-contract-form.png" class="img-fluid devices"  style="border:1px solid #ddd"/>

        <h4>ACES Marketplace Console</h4>
        <p>
            The ACES Marketplace Console provides a simple web interface for tapping into available 
            ACES Services listed on the public marketplace directory. An integrated payment wallet allows
            service contracts to be executed and payed for directly though the Marketplace Console.
        </p>

        <p>
            <a class="btn-shadow btn-shadow-info mr-md-1" href="marketplace">
                Learn More
            </a>
        </p>
    </section>
</div>


<div class="business-single-client" style="height: 400px" data-scroll>
    <div class="quote-wrapper">
        <p>
            "The future will be driven by many thousands of product specific blockchains. It is going to be 
            exceedingly frustrating to consumers if we don’t do something about disconnected blockchains soon, 
            because the technologies are coming around the corner at blazing speeds."
        </p>
    </div>
</div>



<div class="agency-from-the-blog" style="display:none">
    <div class="container">
        <h3>Latest Posts</h3>
        <div class="row">
            <div class="col-md-4">
                <div class="post">
                    <a href="#" class="pic" style="background-image:url('images/unsplash/photo-1422665717225-1a37f226c92a.jpg');">
                    </a>
                    <div class="title">
                        A Future of Cryptocurrencies and Blockchains
                    </div>
                    <div class="min-read">
                        3 min read
                    </div>
                    <p>
                        What is the real world use case for ACES? The real world use case may not have arrived quite yet, but it’s fast approaching.
                    </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="post">
                    <a href="#" class="pic" style="background-image:url('images/unsplash/photo-1424873380396-9580028d74db.jpg');">
                    </a>
                    <div class="title">
                        ACES Completes ARK Authentication Listeners for ARK, Bitcoin, Ethereum, and Litecoin
                    </div>
                    <div class="min-read">
                        4 min read
                    </div>
                    <p>
                        This release is an expansion and improvement to our existing listener protocol, providing high 
                        quality features that will support a robust blockchain service ecosystem. This release also includes
                        deployment of stake-based listeners for ARK and Ethereum, which you can begin using immediately to 
                        build services. We will be deploying two additional listeners for Bitcoin and Litecoin alongside 
                        our release of services in the coming weeks.
                    </p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="post">
                    <a href="#" class="pic" style="background-image:url('images/unsplash/photo-1478059425650-ca13d6d422f4.jpg');">
                    </a>
                    <div class="title">
                        Development of the ARK and Bitcoin Listeners Completed
                    </div>
                    <div class="min-read">
                        3 min read
                    </div>
                    <p>
                        The listener is the component that plugs into a blockchain (such as Bitcoin) and provides 
                        standardized API access for ARK services to receive data from a blockchain. The listener stands 
                        on its own, and does not necessarily need to be run by the same person running a service.
                    </p>
                </div>
            </div>
        </div>
    </div>
</div>


<div class="index-clients">
    <div class="container">
        <header>
            <h4>Connecting the best blockchain technologies</h4>
        </header>
        <div class="row justify-content-center icons">
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc ARK" title="ARK"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc BTC" title="BTC"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc LTC" title="LTC"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc XMR" title="XMR"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc ETH" title="ETH"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc IOTA" title="IOTA"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc NEO" title="NEO"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc SIA" title="SIA"></i>
            </div>
            <div class="col-12 col-md-3 col-lg">
                <i class="img-fluid mb-4 cc GNT" title="GNT"></i>
            </div>
        </div>
    </div>
</div>