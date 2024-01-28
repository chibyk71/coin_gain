<script lang="ts">
    import type { PageData } from './$types';
    
    export let data: PageData;
</script>


    <div class="page_title section-padding">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="page_title-content">
                        <a href="shop.html">
                            <p><span><i class="fa fa-angle-left"></i></span> Back to Shop</p>
                        </a>
                        <h3>Withdraw to PayPal</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="shop_withdraw">
        <div class="container">
            <div class="row">
                <div class="col-xl-3">
                    <div class="shop_card_desc">
                        <div class="card">
                            <div class="card-header">
                                <div class="icon paypal">
                                    <span><img src="images/svg/paypal.svg" alt=""></span>
                                </div>
                                <h4 class="card-title">Paypal</h4>
                            </div>
                            <div class="card-body">
                                <h5>Description :</h5>
                                <p>PayPal is accepted where you shop - on over 75% of online merchants, from big
                                    brands
                                    to boutique sites. We send USD balance to your PayPal account. Start shopping
                                    now!
                                </p>
                            </div>
                            <div class="card-footer">
                                <div class="website">
                                    <span><img src="images/svg/plane.svg" alt=""></span>
                                    <a href="shop-paypal-withdraw.html#">
                                        <p>Website</p>
                                    </a>
                                </div>
                                <div class="help">
                                    <span><img src="images/svg/help.svg" alt=""></span>
                                    <a href="shop-paypal-withdraw.html#">
                                        <p>Help</p>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-xl-9">
                    <div class="shop_card_content">
                        <div class="card">
                            <div class="card-header">
                                <h4 class="card-title">Paypal</h4>
                            </div>
                            <div class="card-body">
                                <form>
                                    <div class="form-group">
                                        <label>Choose Amount</label>
                                        <ul class="choose_amount">
                                            <li class="wave-effect active">$2.50</li>
                                            <li class="wave-effect">$2.50</li>
                                            <li class="wave-effect">$2.50</li>
                                            <li class="wave-effect">$2.50</li>
                                            <li class="wave-effect">$2.50</li>
                                            <li class="wave-effect">$2.50</li>
                                            <li class="wave-effect">$2.50</li>
                                        </ul>
                                    </div>
                                    <div class="form-group">
                                        <label for="">Set PayPal address</label>
                                        <input type="text" class="form-control" placeholder="Enter paypal address">
                                    </div>
                                    <div class="form-button">
                                        <p>USD account balance will be sent to your PayPal account. PayPal charges
                                            you a
                                            transaction fee of 2.9% + $0.30.</p>
                                        <button type="button" class="btn btn-primary" data-bs-toggle="modal"
                                            data-bs-target="#popup_claim">Withdraw</button>
                                    </div>
                                </form>
                                <div class="alert alert-warning alert-dismissible fade show" role="alert">
                                    Payment of 30,000G will be equivalent to $2.50 withdrawals
                                    <div class="close" data-bs-dismiss="alert" aria-label="Close">
                                        <span><i class="la la-close"></i></span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="popup_claim modal fade" id="popup_claim">
        <div class="modal-dialog modal-dialog-centered" role="document">
            <div class="popup_content modal-content withdraw_form">
                <span class="popup_close" data-bs-dismiss="modal"><i class="la la-close"></i></span>
                <!-- <span class="popup_claim-icon">
                        <img src="./images/popup/success-buy.png" alt="">
                    </span> -->
                <h4>Are you sure you want
                    to withdraw?</h4>

                <form action="shop-paypal-withdraw.html#">
                    <div class="total_amount_spend">
                        <h5 class="ta_text">Total Amount</h5>
                        <h5 class="ta_digit">$2.50</h5>
                    </div>
                    <div class="total_spend">
                        <p class="ta_text">Total Amount</p>
                        <p class="ta_digit">$25.50 = 2500 <img src="images/svg/gem.svg" alt=""></p>
                    </div>
                    <div class="total_fee">
                        <h5 class="fee_text">Fee</h5>
                        <h5 class="fee_digit">$1.25</h5>
                    </div>
                    <div class="amount_address">
                        <div class="total_amount_get">
                            <div>
                                <h4 class="ta_text">Total Amount</h4>
                                <p>you’ll get</p>
                            </div>
                            <h5 class="ta_digit">$1.25</h5>
                        </div>
                        <div class="email_address">
                            <div>
                                <p>Address</p>
                                <h5>Henryjohnthom@gmail.com</h5>
                            </div>
                            <div class="change">Change</div>
                        </div>
                    </div>
                    <button type="button" class="btn btn-primary">WITHDRAW $1.25</button>
                </form>
            </div>
        </div>
    </div>

    <div class="ani-25">
        <img src="images/svg/ani-24.png" alt="">
    </div>

    <div class="ani-26">
        <img src="images/svg/ani-25.png" alt="">
    </div>