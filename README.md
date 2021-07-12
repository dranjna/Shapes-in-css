# Shapes-in-css
## add code in css
  .slanted {
        background-color: #1877C3;
        height: 600px;
        -webkit-clip-path: polygon(0 0, 100% 0, 100% 0%, 0 100%);
        clip-path: polygon(0 0, 100% 0, 662% 66%, 0 100%);
        transform: rotate(180deg);
    }
    ## add in html
    <hr>
    
     `<div class="container-fluid slanted px-0">
        <div class="container" style="transform: rotate(180deg);">
            <div class="row  text-center">
                <div class="col col-mobile  ">
                    <div class=" dna-text ">The DNA of e-Commerce</div>
                    <div class="dna-text-2">Unoecom automates<br>
                        every aspect order, inventory and shipping and unifies online and retail seamlessly.
                    </div>
                    <div class="row py-5 px-lg-5 justify-content-center">
                        <div><img src="assets/images/amazon.png" class="img-fluid h-50" alt=""></div>
                        <div><img src="assets/images/shopify.png" class="img-fluid h-50" alt=""></div>
                        <div><img src="assets/images/ebay.png" class="img-fluid h-50" alt=""></div>
                        <div><img src="assets/images/dhl.png" class="img-fluid h-50" alt=""></div>
                        <div><img src="assets/images/fedex.png" class="img-fluid h-50" alt=""></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
