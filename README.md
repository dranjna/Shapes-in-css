# Shapes-in-css
## add code in css
  <div>
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

  
  ## grey slant background
  #add in css
  <hr>
  .slant{
    background-color: white;
    position: relative;
    text-align: center;
   height: 800px;
  }
  .slant-img{
    background-color: #f5f5f5;
    position: absolute;
    width: 100%;
    height: 953px;
    top: 0px;
    /* left: 6px; */
    transform: skewY(-7deg);
}
  #add in html
  <hr>
  
  
  `<div class="container-fluid  enable-delivery px-0 mt-5 pt-5">
        <div class="slant">
            <div class="slant-img">
                <div class="container py-lg-0 my-lg-0" style="transform: skewY(6deg)">
                    <div class="row">
                        <div class="col ">
                            <div class="row justify-content-center">
                                <hr style="margin-right: 0px;" class="d-lg-block d-none">
                                <div class="text mx-3 pt-lg-5 pt-5  text-center">Enable Expedited Delivery</div>
                                <hr style="margin-left: 0;" class="d-lg-block d-none">
                            </div>
                            <div class="row justify-content-center">
                                <div class="same-text text-center">Same Day, Next Day, Two-Day Fulfillment with
                                </div>
                                <div class="free-text captilize ml-2">FREE Storage</div>
                            </div>
                            <div class="row px-lg-4 px-1 my-4 justify-content-center">
                                <div class="col-lg-6 py-md-5">
                                    <div class="row pt-lg-5  pb-lg-3 mb-lg-3 ">
                                        <div><img src="assets/images/bullets.png" alt="" class="h-100 w-75"></div>
                                        <div class="mx-1 bullet-text uppercase">Store Goods across our US warehouses
                                            for FREE
                                        </div>
                                    </div>
                                    <div class="row py-lg-3 my-lg-3 ">
                                        <div><img src="assets/images/bullets.png" alt="" class="h-100 w-75"></div>
                                        <div class="mx-1 bullet-text uppercase">Enable Expedited Delivery at No
                                            EXTRA Cost</div>
                                    </div>
                                    <div class="row py-lg-3 my-lg-3 ">
                                        <div><img src="assets/images/bullets.png" alt="" class="h-100 w-75"></div>
                                        <div class="mx-1 bullet-text uppercase">Lowest Fulfilment Cost, No Volume
                                            Requirements
                                        </div>
                                    </div>
                                    <div class="row py-lg-3 my-lg-3 ">
                                        <div><img src="assets/images/bullets.png" alt="" class="h-100 w-75"></div>
                                        <div class="mx-1 bullet-text uppercase">Store Goods Closer to your customers
                                        </div>
                                    </div>
                                    <div class="row py-lg-3 my-lg-3 ">
                                        <div><img src="assets/images/bullets.png" alt="" class="h-100 w-75"></div>
                                        <div class="mx-1 bullet-text uppercase">Increase Sales via Social Selling*
                                        </div>
                                    </div>
                                </div>
                                <div class="col-lg-6 py-lg-5 mb-5 pb-5">
                                    <img src="assets/images/Vector Smart Object@1X.png" class="img-fluid" alt="">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>`
