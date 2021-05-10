<template>
        <section id="contact" class="wrapper">
        <div  class="container">
            <div class="row">
                <div class="col-md-4 contact-item col-sm-6 col-xs-12 wow animated fadeInLeft">
                    <i class="fa fa-map-marker"></i>
                    <h3>Address</h3>
                    <p class="contact">
                        Pranakorn, 9 <br>
                        Utha, USA
                    </p>
                </div>
                <div class="col-md-4 contact-item col-sm-6 col-xs-12 wow animated fadeInLeft">
                    <i class="fa fa-phone"></i>
                    <h3>Phone</h3>
                    <p class="contact">
                        Local: +669-999-9999 <br>
                        Mobile: +668-888-888
                    </p>
                </div>
                <div class="col-md-4 contact-item col-sm-6 col-xs-12 wow animated fadeInRight">
                    <i class="fa fa-envelope"></i>
                    <h3>Email Address</h3>
                    <p class="contact">
                        <a href="mailto:info@homehubdd.com">info@homehubdd.com</a> <br>
                        <a href="www.homehubdd.com">www.homehubdd.com</a>
                    </p>
                </div>
            </div> 
            <form class="row form wrapper">
                <h3>Leave A Message</h3>
                <div class="col-sm-4 col-xs-12 form-group">
                    <label class="sr-only">Name</label>
                    <input name="name" class="form-control" type="text" placeholder="First Name">
                </div>
                <div class="col-sm-4 col-xs-12 form-group">
                    <label class="sr-only">Email</label>
                    <input name="email" class="form-control" type="email" placeholder="Email address">
                </div>
                <div class="col-sm-4 col-xs-12 form-group">
                    <label class="sr-only">Mobile</label>
                    <input name="mobile" class="form-control" type="number" placeholder="Mobile number">
                </div>
                <div class="row">
                    <div class="col-md-12 col-xs-12 form-group">
                        <label class="sr-only">Message</label>
                        <textarea class="message form-control" placeholder="Write message"></textarea>
                    </div>
                    <input class="btn btn-sub" type="submit" value="Send Message">
                </div>
            </form>
        </div>
    </section>
</template>