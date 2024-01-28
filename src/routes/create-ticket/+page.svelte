<script lang="ts">
	import Footer from "$lib/footer.svelte";
import Header from "$lib/header.svelte";

    
</script>

<div class="page_title section-padding">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="page_title-content">
                        <p> <span><i class="fa fa-angle-left"></i></span> Support System</p>
                        <h3>Create Ticket</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="create_ticket-default">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="create_ticket-form card">
                        <div class="card-header">
                            <h4 class="card-title">Create</h4>
                            <span>Cancel</span>
                        </div>
                        <div class="card-body">
                            <form action="create-ticket.html#">
                                <div class="form-group">
                                    <label>What the type question do you want?</label>
                                    <div class="drop-menu form-control">
                                        <div class="select">
                                            <span>Please Select</span>
                                            <i class="fa fa-angle-right"></i>
                                        </div>
                                        <input type="hidden" name="gender">
                                        <ul class="dropeddown">
                                            <li> <i class="checkbox"></i> Earning</li>
                                            <li> <i class="checkbox"></i> Withdrawals</li>
                                            <li> <i class="checkbox"></i> Profile</li>
                                            <li> <i class="checkbox"></i> General</li>
                                            <li> <i class="checkbox"></i> Others</li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="form-group">
                                    <label for="">Employe Respond</label>
                                    <div class="drop-menu form-control">
                                        <div class="select">
                                            <span>Please Select</span>
                                            <i class="fa fa-angle-right"></i>
                                        </div>
                                        <input type="hidden" name="gender">
                                        <ul class="dropeddown">
                                            <li> <i class="checkbox"></i> Earning</li>
                                            <li> <i class="checkbox"></i> Withdrawals</li>
                                            <li> <i class="checkbox"></i> Profile</li>
                                            <li> <i class="checkbox"></i> General</li>
                                            <li> <i class="checkbox"></i> Others</li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="form-group">
                                    <label for="">What language do you prefer to be answered?</label>
                                    <div class="drop-menu form-control">
                                        <div class="select">
                                            <span>Please Select</span>
                                            <i class="fa fa-angle-right"></i>
                                        </div>
                                        <input type="hidden" name="gender">
                                        <ul class="dropeddown">
                                            <li> <i class="checkbox"></i> Earning</li>
                                            <li> <i class="checkbox"></i> Withdrawals</li>
                                            <li> <i class="checkbox"></i> Profile</li>
                                            <li> <i class="checkbox"></i> General</li>
                                            <li> <i class="checkbox"></i> Others</li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="form-group">
                                    <label for="">Please provide a description of the problem you are
                                        encountering</label>
                                    <textarea name="" id="" rows="5" class="form-control"></textarea>
                                </div>
                                <div class="text-center">
                                    <button class="btn btn-primary">Create</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

     <div class="ani-22">
        <img src="images/svg/ani-22.png" alt="">
    </div>
    <div class="ani-23">
        <img src="images/svg/ani-23.png" alt="">
    </div>