<template>
<q-page style="background-color: rgb(186, 225, 250) ;">
    <div class="row " style="background-color:;">
        <div class="col-12 col-md-6 first">
            <p class="text-h1 cname q-pa-lg" style="font-size: 9vw;">
                TNPSC Group IV
            </p>
            <q-btn class="trial q-pr-lg">Click & Register For Free Session</q-btn>
            <h6 class="q-pa-lg">TNPSC Group 4 is an objective-type paper (OMR Method). The minimum qualifying mark is 90 for all the categories. The questions in Part-A will be set in Tamil only and the questions on the General Studies & Aptitude & Mental Ability Test will be available in both English and Tamil.
                <space />
            </h6>

        </div>
        <space />
        <div class="col-12 col-md-6 q-pl-lg">
            <br><br>
            <q-image class="relative-position"><img class="image1" height="500px" src="../assets/main.png" /></q-image>
            <br>
        </div>

    </div>
    <!-- About -->
    <div>
        <div id="abou">
            <h4 class="text-center about">About</h4>
        </div>

        <div style="display: flex; justify-content: space-evenly;" class="row">
            <q-card class="my-card text-white col-12 col-md-6 q-pl-lg card" style="background-color: lightcoral;  width: 500px; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">
                <q-card-section>
                    <br>
                    <div class="text-h6 text-center">Highlights Of this Course</div><br>
                    <div class="text-subtitle1"><u>TNPSC</u></div>
                </q-card-section>

                <q-card-section class="q-pt-none">
                    <ul>
                        <li>Know the TNPSC Group IV Written Exam Pattern. ...</li><br>
                        <li>Analyze Topics from TNPSC Group IV Exam Syllabus. ...</li><br>
                        <li>Make a Day-Wise TNPSC Group IV Study Plan. ...</li><br>
                        <li>Make Notes. ...</li><br>
                        <li>Consistent Practice and Revision with Mock Papers.</li><br>
                        <li>Practise TNPSC Group 4 previous year question papers.</li><br>
                        <li>Read newspaper daily.</li><br>
                        <li>Study Many GK books to gain knowledge.</li><br>
                        <li>Get Study in low noise Environment..</li>
                    </ul>
                </q-card-section>
            </q-card>
            <br>
            <q-card class="my-card text-white col-12 col-md-6 q-pl-lg card" style="background: lightcoral; width: 500px; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">
                <q-card-section>
                    <br>
                    <div class="text-h6 text-center">ELIGIBILITY</div><br>
                    <div class="text-subtitle1"><u>TNPSC</u></div>
                </q-card-section>

                <q-card-section class="q-pt-none">
                    <ul>
                        <li>Must have a minimum general educational qualification, i.e., must have passed the S.S.L.C. </li>
                        <br>
                        <li>Public Examination or its equivalent and be eligible for admission to Higher Secondary Courses of Study </li>
                        <br>
                        <li>Make sure to have all the relevant documents mentioned for the TNPSC Eligibility Criteria 2024.</li>
                        <br>
                        <li>Ration Cards and Learner's Driving License is not accepted as identity proof</li>
                        <br>
                        <li>TNPSC Employees/Government Servants claiming age relaxation shall have to produce a certificate in the format prescribed by the TNPSC.</li>
                        <br>
                        <li>The signature on all the documents must be identical.</li>
                    </ul>
                </q-card-section>
            </q-card>
        </div>
    </div>

    <!-- Course -->
    <div>

        <h4 class="text-center about">Video</h4>
        <div class="q-pa-md text-center row justify-center" style="filter: drop-shadow(0 0 0.75rem black);">
            <iframe class="q-pl-md col-12 col-md-6" height="450" src="https://www.youtube.com/embed/ic_g8EWF_l0?si=EFtxROIZdXvdt2jE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
    </div>

    <!-- Banking -->
    <div class="q-pa-lg">
        <h4 class="text-center about ">Course</h4>
        <div class="row text-center" style="display: flex; justify-content: space-evenly; font-size: 25px; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; font-style: oblique;">
            <div class="q-pa-md col-12 col-md-6">
                <q-card class="my-card">
                    <q-parallax src="https://assets.thehansindia.com/h-upload/2019/10/28/230255-1.webp" :height="250" />

                    <q-card-section>
                        <div class="text-h6">50% off on TNPSC</div>
                        <div class="text-subtitle2"><strike>60,000</strike>30,000/-</div>
                    </q-card-section>
                </q-card>
            </div>
            <div class="col-12 col-md-6 form" style="border: 1px solid grey; border-radius: 60px 100px 100px 40px; height: 370px; background: lightcoral">

                <form class="q-pl-lg  text-center">
                    <div style="">
                        <h5 class="">For Any Queries Please Fill Out The Form</h5>
                        <div class="row" style="display:flex; justify-content: space-evenly; gap: 2px; row-gap: 5px; height: 100%; ">
                            <div class="q-p-md" style="max-width: 400px">

                                <q-form @submit="onSubmit" @reset="onReset" class="q-gutter-md">
                                    <q-input filled v-model="name" label="Your name *" hint="Name and surname" lazy-rules :rules="[ val => val && val.length > 0 || 'Please type something']" />

                                    <q-input filled type="number" v-model="age" label="Your mobile number *" lazy-rules :rules="[
      val => val !== null && val !== '' || 'Enter mobile number',
      val => val > 0 && val < 100 || 'Please type 10 digits number'
    ]" />

                                    <div class="q-mt-sm">
                                        <q-btn class="q-ml-sm" label="Submit" type="submit" rounded style="background-color: purple 25%; color: whitesmoke;" />
                                        <q-btn label="Reset" type="reset" style="color= purple;" flat class="q-ml-sm" />
                                    </div>
                                </q-form>

                            </div>

                        </div>

                    </div>
                </form>
            </div>
        </div>

        <!-- card -->
        <div>
            <h4 class="text-center about">Online, Offline Interactions Class Highlights</h4>
            <div class="row" style="display: flex; justify-content: center;">
                <q-card class="my-card col-12 col-md-6 cd" style="width: 400px;">
                    <q-img src="https://www.sacap.edu.za/wp-content/uploads/2017/10/difference-between-coaching-and-mentoring-768x512.jpg">
                        <div class="absolute-bottom text-subtitle2 text-center" style="height:100%">
                            <h6>Face to Face Engagement and Individual Mentor Support</h6>
                            <p>Interact with our Staff & Mentors.</p>
                        </div>
                    </q-img>
                </q-card>
            </div>
            <div class="row" style="display: flex; justify-content: space-between;">
                <q-card class="my-card col-12 col-md-3 cd" style="width: 400px;">
                    <q-img src="https://prod-aaudxp-cms-001-app.azurewebsites.net/media/s5qbptfi/study-environment.jpg?width=960">
                        <div class="absolute-bottom text-subtitle2 text-center" style="height:100%">
                            <h6>Good Study Environment</h6>
                            <p>A good study environment can help you study more efficiently and effectively.</p>
                        </div>
                    </q-img>
                </q-card>
                <q-img class="col-12 col-md-3 q-pt-lg join" style="width: 200px; height: 230px; filter: drop-shadow(0 0 0.75rem black);" src="../assets/join now.png"></q-img>
                <q-card class="my-card col-12 col-md-3 cd" style="width: 400px;">
                    <q-img height="100%" src="https://cdn.dnaindia.com/sites/default/files/styles/full/public/2021/07/15/985341-neet-2021-study-material.jpg">
                        <div class="absolute-bottom text-subtitle2 text-center" style="height:100%">
                            <h6>Latest updated Course Content and Materials</h6>
                            <p>Get Book Materials & Handouts prepared by Research Team.</p>
                        </div>
                    </q-img>
                </q-card>
            </div>
            <div class="row" style="display: flex; justify-content: center;">
                <q-card class="my-card col-12 col-md-6 cd" style="width: 400px;">
                    <q-img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQa93IJSB007iSDAJZy0_Rj1HNhHrE2xPVSBw&usqp=CAU">
                        <div class="absolute-bottom text-subtitle2 text-center" style="height:100%">
                            <h6>100% Result focussed Coaching & Training Policy</h6>
                            <p>Result oriented coaching and practice strategy will get you sure success.</p>
                        </div>
                    </q-img>
                </q-card>
            </div>
        </div>

        <br><br>

    </div>

    <!-- Footer        -->
    <div class="text-center q-pt-lg" style="background-color: #05386B; color:aliceblue;">
        <div class="q-pb-lg" style="">
            Chennai:+91-8099765311 | Madurai:+91-73382675110 | Coimbatore:+91-9841422357 | Trichy:+91-6345567901 | Salem:+91-8277701223
        </div>
        <div>
            <a>Terms & Conditions | </a>
            <a>Privacy Policy | </a>
            <a>Refund/Cancellation Policy</a>
            <a>Terms of Use</a>
        </div>
        <br>
    </div>

</q-page>
</template>

<script>
export default {
    name: 'WorkPage',

    data: function () {
        return {

        }
    }
}
</script>

<style lang="scss">
.about {
    font-family: fantasy;
    // background-image: url("");
}

.card {
    border-radius: 10%;
    filter: drop-shadow(0 0 0.49rem grey);
    background-color: #d4c0d9;

}

.cname {
    font-family: 'Times New Roman', Times, serif;
    // text-wrap: nowrap;
    margin-left: 10px;
}

.trial {
    padding: 17px 40px;
    margin-left: 80px;
    border-radius: 50px;
    cursor: pointer;
    border: 0px;
    background-color: #d4c0d9;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    font-size: 15px;
}

.trial:hover {
    letter-spacing: 3px;
    background-color: #05386B;
    color: aliceblue;
    box-shadow: blue 0px 7px 29px 0px;

}

td {
    width: 300px;
    height: 70px;

}

.form:hover {
    padding-right: 5px;
    filter: brightness(110%);
    color: white;
}

.cd:hover {
    filter: drop-shadow(0 0 0.99rem rgb(143, 143, 228));

}

@media screen and (max-width:1000px) {
    .trial {
        margin-left: 10px;
        size: 30px;
    }

    .image1 {
        width: 300px;
    }

    .cname {
        font-weight: 500;
    }

    .join {
        margin-left: 66px;
    }
}
</style>
