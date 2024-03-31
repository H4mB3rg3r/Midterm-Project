<template>

    <nav class="navbar navbar-expand-lg sticky-top p-2" style="background-color: #92140c">
        <div class="container-fluid mt-2">
            <a class="navbar-brand fs-3 ms-2 " href="#home">
                <img src="profile-user.png" alt="logo" height="40" class="me-2">
                <span class="text-white" style="font-family: monospace;">Portfolio</span>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                    <ul class="navbar-nav">

                        <li class="nav-item">
                            <a class="nav-link fs-5 contact-link me-5 text-white" href="#about">About</a>
                        </li>
                    </ul>
                </div>
        </div>
    </nav>

    <div id="home" class="container-fluid p-5">
        <div class="container-fluid">
            <div class="row">
                <!-- DESCRIPTION -->
                <div class="col-md-6 p-2" style="margin-top:130px;">
                    <div class="card shadow-lg" style="background-color: #be7c4d;">
                        <div class="card-body p-5 mt-2">
                            <h2 class="fw-bold text-light">Joshua Aro</h2>
                            <div class="mb-5 text-white" style="font-size: 1rem;">Student at Cordova Public College</div>
                            <div class="row">
                                <div class="col-md-12">
                                    <h3 class="text-light text-start">
                                        Welcome to my portfolio! I am pursuing a Bachelor of Science in Information Technology degree, 
                                        with a focus on programming. Through this platform, I aim to present my proficiency in technology 
                                        through innovative projects that exemplify my dedication and expertise.
                                    </h3>
                                </div>
                            </div>
                        </div>
                    </div>

                    <span class="contact-phrase">Contact me on this following accounts</span> <!-- Contact phrase -->
                    
                    <b-row>
                    <b-col><a href="https://www.facebook.com/joshuaGWaro123" target="_blank">
                                <img src="facebook.png" alt="Facebook" class="social-icon">
                            </a></b-col>
                    <b-col><a href="mailto:joshuaaro720@gmail.com" target="_blank">
                                <img src="gmail.png" alt="Gmail" class="social-icon">
                            </a></b-col>
                    <b-col><a href="https://www.instagram.com/juswahong/" target="_blank">
                                <img src="instagram.png" alt="Instagram" class="social-icon">
                            </a></b-col>
                </b-row>
                </div>

                <!-- img -->
                <div class="col-md-6">
                    <img class="img-fluid rounded mb-5" alt="Portrait" src="/test.jpg" style="max-width: 80%; height: auto;">
                </div>

            </div>
        </div>
    </div>

    <div id="about">

        <div class="container-fluid" style="background-color: rgb(20, 19, 1);">
            
            <div class="row p-5 mb-5">
                
                <!-- Header -->
                <div class="col-md-12 mb-3 text-center mb-5 mt-3">
                    
                    <h3 style="font-family: Arial, sans-serif; font-size: 30px; font-weight: bold; color: white; text-transform: uppercase; letter-spacing: 1px; text-align: center; margin-bottom: 30px;">
                        About Me
                    </h3>

                </div>

                <!-- About Me -->
                <div class="col-md-6 p-5">
                    
                    <div class="card p-5 mt-3 shadow-lg">
                        <div class="card-body">

                            <!-- PORTFOLIO DESCRIPTION -->
                            <div class="about-me-text text-start mt-3 text-dark">
                                <p style="font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; line-height: 1.8; font-size: 1.4rem;">

                                    Greetings! I am Joshua Aro, a dedicated enthusiast in computer studies residing in Catarman,Cordova. 
                                    My passion for technology fuels my relentless pursuit of its boundless opportunities.
                                    <br>
                                    <!--  Exploring diverse realms, I delve deep into mastering PHP, JavaScript, Java, and CSS styling (pure CSS and Bootstrap), 
                                    and SQL database management.
                                    <br><br>
                                    Driven by the challenge of innovation, I actively seek collaborative endeavors, delivering solutions 
                                    that redefine conventional norms. My adaptive nature enables me to navigate seamlessly through dynamic environments, 
                                    seizing every opportunity with vigor. -->
                                    My technological journey has honed my capabilities, empowering me to make significant contributions to any project or team. 
                                    With an unwavering commitment to excellence and meticulous attention to detail, I strive to surpass expectations, crafting 
                                    solutions that resonate profoundly with user needs. 
                                
                                </p>
                            </div>
                        </div>
                    </div>
                </div>


                <!-- My Skills -->
                <div class="col-md-6 text-center p-5">
                    <div class="container">
                        <div class="row justify-content-evenly" style="margin-top: 180px;">
                            <h3 class="text-center mb-4 text-white">Services Offered</h3>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">

                                <div class="img-container zoom-in-effect">
                                    <img src="html.png" width="60%" max-width="150px" title="HTML" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5">
                                <div class="img-container zoom-in-effect">                                    
                                    <img src="css.png" width="60%" max-width="150px" title="CSS" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                                <div class="img-container zoom-in-effect">
                                    <img src="js.png" width="60%" max-width="150px" title="Javascript" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                                <div class="img-container zoom-in-effect mt-5">
                                    <img src="php.png" width="60%" max-width="150px" title="PHP" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                                <div class="img-container zoom-in-effect">
                                    <img src="java.png" width="60%" max-width="150px" title="Java" class=" mx-auto">
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-5 my-3">
                                <div class="img-container zoom-in-effect">
                                    <img src="bootstrap.png" width="60%" max-width="150px" title="Bootstrap" class=" mx-auto">
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>

        </div>

    </div>
</template>

<script>

</script>


<style>

.navbar-brand, .nav-link {
  font-family: sans-serif;
  font-size: 10px; 
}

body {
  font-family: 'Times New Roman', Times, serif;
}

h1,
h5 {
  font-size: 15px;
}

.social-icons {
        position: absolute;
        top: 85%;
        left: 50%;
        transform: translate(-50%, -50%);
        display: flex;
        flex-direction: row;
        justify-content: center; /* Center horizontally */
        align-items: center; /* Center vertically */
        gap: 10px;
}

.social-icon {
        width: 40px;
        height: auto;
        margin: 15px; /* Adjust the margin as needed */
}
.contact-phrase {
        display: block;
        text-align: center;
        font-family: monospace;
        color: rgb(12, 12, 12);
        margin-top: 35px; /* Adjust as needed */
    }
</style>
