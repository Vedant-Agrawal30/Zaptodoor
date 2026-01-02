 



    <section class="cta_section new white_text" id="support_sec">
      <!-- container start -->
      <div class="container">
          <div class="cta_box"> 
          	<div class="element">
            <span class="element1"> <img src="images/element_white_3.webp" alt="image"> </span>
            <span class="element2"> <img src="images/element_white_4.webp" alt="image"> </span>
          </div>         	
      		<div class="left">

            <!-- section title -->
      			<div class="section_title" data-aos="fade-in" data-aos-duration="1500" data-aos-delay="100">
            	 <img src="images/CAll.png" class="customer_icon" alt="image">
              	<!-- h2 -->
                 <h3>Need support?</h3>
                <!-- p -->
                <p>Lorem Ipsum is simply dummy text of the printing.</p>
            </div>

      		</div>	
          <!-- cta buttons -->
      		<div class="right">     		
      			<div class="btn_block ">
                    <a href="tel:123-456-7890" class="btn aos-init aos-animate email_btn" ><i class="icofont-envelope-open"></i> Call us now</a>
                    <a href="mailto:someone@example.com" class="btn aos-init aos-animate email_btn" ><i class="icofont-envelope-open"></i> Email us</a>
        		</div>	
      		</div>	          	
          </div>
      </div>
      <!-- container end -->
    </section>

    <style>
      .ctr_cta {
    margin: 0 auto;
    margin-top: 50px;
    text-align: center;
}



/* ------  CTA section ------------- */

.cta_section.new {
    padding-top: 50px;
}

.cta_section.new .cta_box{
    background: var(--primery);
    position: relative; 
    z-index: 99;
    border-radius: 20px;
    padding: 60px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: -100px;
}

.cta_section.new .cta_box .section_title{
    position: relative;
    display: flex;
    flex-wrap:wrap;
    width: 100%;
    padding-left: 80px;
}

.cta_section.new .cta_box .section_title h3{
    margin-bottom: 0;
    line-height: 1.2;
}

.cta_section.new .cta_box .section_title p {
    padding: 0;
}

.cta_section.new .cta_box .section_title .customer_icon{
    position: absolute;
    left:0;
    top:10%;
}

.cta_section.new .cta_box .btn_block{
    display: flex;
    justify-content: flex-end;
    align-items: center;
    gap: 15px;          /* buttons ke beech gap */
    flex-wrap: nowrap; /* ✅ ek hi line */
}

/* FIX: Button text cut issue */
.cta_section.new .cta_box .btn {
    width: auto;              /* 🔥 text ke hisaab se width */
    min-width: 150px;         /* 🔥 dono buttons same feel */
    padding: 15px 28px;
    display: inline-flex;     /* icon + text proper */
    align-items: center;
    justify-content: center;
    gap: 10px;                /* icon-text gap */
    white-space: nowrap;      /* text break na ho */
}

@media (max-width: 600px) {
  .cta_section.new .cta_box .btn_block {
    flex-direction: column;
  }

  .cta_section.new .cta_box .btn {
    width: 100%;
    min-width: unset;
  }
}


.cta_section.new .cta_box .btn{
    /* float: left;  ❌ remove */
    padding: 15px 30px;
    background-color: var(--white);
    border-radius: 12px;
    white-space: nowrap;   /* ✅ text ek line me rahe */
}


.cta_section.new .cta_box .call_btn {
    background-color: var(--black);
    margin-right: 15px;
    font-weight: 700;
    border-radius: 12px;
}

.cta_section.new .cta_box .email_btn:hover {
    background-color: var(--black);
    transition: all ease-in-out .5s;
    color: var(--white);
}
.cta_section.new .cta_box .call_btn:hover {
    background-color: var(--black); 
    transition: all ease-in-out .5s;
    color: var(--white); 
}


.cta_section.new .cta_box .right{
    width: 54%;
}

.cta_section.new .cta_box .element .element1, .t_element2 {
    position: absolute;
}

.cta_section.new .cta_box .element .element1 {
    right: 35%;
    top: 10%;
    animation: mymove 15s infinite;
}

.cta_section.new .cta_box .element .element2 {
    left: 20%;
    bottom: 6%;
    animation: mymove 8s infinite;
}

.cta_section.new .cta_box {
    transform: translateY(-101px); /* 🔥 CTA thoda upar aa jayegi */
}

/* ===== CTA COLOR FIX ===== */

/* CTA background purple */
.cta_section.new .cta_box {
    background-color: #5b159a;   /* same purple as footer */
    color: #ffffff;
}

/* CTA heading & paragraph */
.cta_section.new .cta_box h3,
.cta_section.new .cta_box p {
    color: #ffffff;
}

/* Buttons text color */
.cta_section.new .cta_box .btn {
    color: #5b159a;              /* default button text */
}

/* Call button (black → optional, agar white text chahiye) */
.cta_section.new .cta_box .call_btn {
    background-color: #000000;
    color: #ffffff;
}

/* Email button */
.cta_section.new .cta_box .email_btn {
    background-color: #ffffff;
    color: #5b159a;
}

/* Email button hover */
.cta_section.new .cta_box .email_btn:hover {
    background-color: #000000;
    color: #ffffff;
}


/* Call Us Now - Hover Effect */
.cta_section.new .cta_box .call_btn {
    background-color: #ffffff;
    color: #5b159a;
    transition: all 0.3s ease;
}


/* ===== FINAL Call Us Now Button ===== */
.cta_section.new .cta_box .call_btn {
    background-color: #ffffff;
    color: #5b159a;
    font-weight: 700;
    transition: all 0.3s ease;
}

.cta_section.new .cta_box .call_btn:hover,
.cta_section.new .cta_box .call_btn:focus {
    background-color: #000000;   /* 🔥 BLACK ON HOVER */
    color: #ffffff;
    transform: translateY(-2px);
}



    </style>