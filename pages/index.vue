<template>
  <div>
    <Navbar></Navbar>
    <section class="section_bg">
    <div class="banner-top banner-top--home with-stars">
  <div class="stars stars--swift"></div>
  <div class="stars stars--fast"></div>
  <div class="stars stars--moderate"></div>
  <div class="stars stars--slow"></div>
  <div class="centered-block">
    <div class="grid-container home">
      <div class="grid-x text-center">
        <div class="small-12 cell">
           <h1 class="banner-top__title-home">O'zingizni kareriyangizni nimadan boshlashni bilmaysizmi!</h1>
          <h2 class="banner-top__subtitle">Bizning platforma sizga yordam beradi</h2>
        </div>
      </div>
    </div>
    <div class="grid-container">
      <div class="row">
        <div class="col-xl-2" v-for="item in 6" :key="item">
        <NuxtLink to="/">
          <div class="card card--careers cell auto fading-block-enter-done">
            <div>
              <div class="card__image" style="background-image: url(&quot;https://www.careerhunter.io/uploads/images/544/small-Archaeologist.jpg&quot;);"></div>
              <div class="card__section card__section--careers">
                <p class="card__name disable-fade-in">Shifokor</p>
                </div>
                <div class="match-tank pulse_8">
                  <div class="inner">
                    <div class="fill fillAction_8" style="transform: translate(0px, 12.92px);">
                        <svg version="1.1" x="0px" y="0px" width="88px" height="88px" viewBox="0 0 88 88" enable-background="new 0 0 88 88"><path class="wave-shape" d="M300,300V2.5c0,0-0.6-0.1-1.1-0.1c0,0-25.5-2.3-40.5-2.4c-15,0-40.6,2.4-40.6,2.4
                            c-12.3,1.1-30.3,1.8-31.9,1.9c-2-0.1-19.7-0.8-32-1.9c0,0-25.8-2.3-40.8-2.4c-15,0-40.8,2.4-40.8,2.4c-12.3,1.1-30.4,1.8-32,1.9
                            c-2-0.1-20-0.8-32.2-1.9c0,0-3.1-0.3-8.1-0.7V300H300z"></path>
                          </svg>
                      </div>
                    </div>
                  <div class="match-percent hidden ">
                    <div class="qm">?</div>
                      Ball
                    </div>
                  </div>
                </div>
              </div>
        </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</div>
    </section>
    <section class="section_two">
            <div class="about_section layout_padding">
    	<div class="container">
    		<div class="row">
    			<div class="col-md-6">
    				<div class="tablet"><img src="../assets/img/tablet-img.png" style="height: 400px;width: 400px;"></div>
    			</div>
    			<div class="col-md-6">
    				<div class="about_taital">
    					<div class="about_text">Platforma <span style="color: #c6610f;">Haqida</span></div>
    					<p class="dolor_text">Bizning platforma orqali siz kelajagingizdagi o'z kasbingizni aniqlab olasiz</p>
    					<div class="read_more"><a href="#">Batafsil</a></div>
    				</div>
    			</div>
    	</div>
    </div>
        </div>
    </section>
    <section>
      <div class="about_section_2 ">
    	<div class="container">
    		<div class="row">
    			<div class="col-sm-12 my-3">
    				<div class="classified_text">Platforma  <span style="color: #c6610f;">Qulayliklari</span></div>
    			</div>	
    		</div>
    		<div class="row front ">
    			<div class="col-md-2">
    				<div class="about_img"><img src="../assets/img/img-1.jpg" style="border-radius: 50%;"></div>
    			</div>
    			<div class="col-md-10">
    				<h1 class="fron_text"><a href="Career_Counseling.html"> CAREER COUSLING</a></h1>
    				<p class="using_text">using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model</p>
    			</div>
    		</div>
        <div class="row front">
          <div class="col-md-2">
            <div class="about_img"><img src="../assets/img/Guidance-1.jpg" style="border-radius: 50%;"></div>
          </div>
          <div class="col-md-10">
            <h1 class="fron_text"> <a href="Guidance.html"> GUIDENESS</a></h1>
            <p class="using_text">using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model</p>
          </div>
          
        </div>        
        <div class="row front">
          <div class="col-md-2">
            <div class="about_img"><img src="../assets/img/test.jpg" style="border-radius: 50%;"></div>
          </div>
          <div class="col-md-10">
            <h1 class="fron_text"><a href="test.html"> TESTS ...</a></h1>
            <p class="using_text">using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model</p>
          </div>
          <div class="red_bt"><a href="#">Read More</a></div>
        </div>
    	</div>
    </div>
    </section>
    <section class="grid-container">
      <div class="grey-shade__container">
  <div class="grid-container our-users--small">
    <div class=" text-center row">
      <div class="small-12 cell">
        <h2 class="blue-blk__title blue-blk__title--with-mrg before-fade-in fade-in">Who can use CareerHunter</h2>
        <h3 class="blue-blk__mini-subtitle mar-bot-60 before-fade-in fade-in">We’ve helped thousands of people find their perfect career!</h3>
      </div>
      <div class="col-xl-4 medium-6 small-12 cell text-left">
        <div class="grid-x text-center ">
          <div class="small-3 cell">
            <img src="../assets/img/school-leavers-mobile.png" width="75" height="81" alt="School leavers" class="our-users--small__img--1 before-fade-in fade-in">
          </div>
          <div class="small-9 cell">
            <h3 class="our-users--small__title before-fade-in fade-in">School leavers</h3>
            <p class="our-users--small__desc before-fade-in fade-in">Take our tests to find the right course of study and appropriate career path.</p>
          </div>
        </div>
      </div>
      <div class="col-xl-4 medium-6 small-12 cell text-left">
        <div class="grid-x text-center">
          <div class="small-3 cell">
            <img src="../assets/img/students-graduates-mobile.png" width="75" height="95" alt="University and college students" class="our-users--small__img--3 before-fade-in fade-in">
          </div>
          <div class="small-9 cell">
            <h3 class="our-users--small__title before-fade-in fade-in">Students and Graduates</h3>
            <p class="our-users--small__desc before-fade-in fade-in">CareerHunter will help you decide what to do after your student years.</p>
          </div>
        </div>
      </div>
      <div class="col-xl-4 medium-6 small-12 cell text-left">
        <div class="grid-x text-center">
          <div class="small-3 cell">
            <img src="../assets/img/workers-mobile.webp" width="75" height="87" alt="Working-Pros.png" class="our-users--small__img--2 before-fade-in fade-in">
          </div>
          <div class="small-9 cell">
            <h3 class="our-users--small__title before-fade-in fade-in">Workers</h3>
            <p class="our-users--small__desc before-fade-in fade-in">Reveal better career options that match your abilities and interests.</p>
          </div>
        </div>
      </div>
      <div class="col-xl-4 medium-6 small-12 cell text-left">
        <div class="grid-x text-center">
          <div class="small-3 cell">
            <img src="../assets/img/professionals-mobile.webp" width="72" height="92" alt="Professionals" class="our-users--small__img--5 before-fade-in fade-in">
          </div>
          <div class="small-9 cell">
            <h3 class="our-users--small__title before-fade-in fade-in">Professionals</h3>
            <p class="our-users--small__desc before-fade-in fade-in">Identify careers that suit your current skillset, traits, and work preferences.</p>
          </div>
        </div>
      </div>
      <div class="col-xl-4 medium-6 small-12 cell text-left">
        <div class="grid-x text-center">
          <div class="small-3 cell">
            <img src="../assets/img/career-changers-mobile.webp" width="75" height="84" alt="Career changers" class="our-users--small__img--4 before-fade-in fade-in">
          </div>
          <div class="small-9 cell">
            <h3 class="our-users--small__title before-fade-in fade-in">Career changers</h3>
            <p class="our-users--small__desc before-fade-in fade-in">Our unique algorithm will help you to decide on a different path that you’ll enjoy.</p>
          </div>
        </div>
      </div>
      <div class="col-xl-4 medium-6 small-12 cell text-left">
        <div class="grid-x text-center">
          <div class="small-3 cell">
            <img src="../assets/img/unemployed-mobile.webp" width="81" height="91" alt="unemployed" class="our-users--small__img--6 before-fade-in fade-in">
          </div>
          <div class="small-9 cell">
            <h3 class="our-users--small__title before-fade-in fade-in">Unemployed</h3>
            <p class="our-users--small__desc before-fade-in fade-in">Ensure your next job sets you on the right journey by making a calculated decision.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
    </section>
    <Footer></Footer>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
import Footer from '../components/Footer.vue';
export default {
    name: "IndexPage",
    components: { Navbar, Footer }
}
</script>
