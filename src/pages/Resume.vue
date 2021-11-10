<template>
    <v-parallax src="https://cdn.vuetifyjs.com/images/parallax/material.jpg" height="100%" class="parallax-overlay">
        <v-layout row wrap style="margin-top: 6rem;">
            <v-flex xs12>
                <v-card style="padding: 3rem;" class="section-card">
                    <div class="headline">SKILLS SUMMARY</div>
                    <v-divider style="margin-bottom: 1rem;"></v-divider>
                    <div class="subheading"><b>Languages</b></div>
                    <ul class="subheading">
                        <li>JavaScript, TypeScript, PHP, HTML5, CSS3, Java, C++, Golang</li>
                    </ul>
                    <br>
                    <div class="subheading"><b>Frameworks/Libraries/Tools</b></div>
                    <ul class="subheading">
                        <li>React, Vue, Vuex, AngularJS, GraphQL, Datadog, Jest, Cypress, Webpack, Swagger, Git, JIRA</li>
                    </ul>
                    <br>
                    <div class="subheading"><b>Databases</b></div>
                    <ul class="subheading">
                        <li>PostgreSQL, MySQL, SQLite, Microsoft SQL server</li>
                    </ul>
                </v-card>
            </v-flex>

            <v-flex xs12 style="margin: 2rem 0 2rem 0">
                <v-card style="padding: 3rem;" class="section-card">
                    <div class="headline">Work Experience</div>
                    <v-divider style="margin-bottom: 1rem;"></v-divider>

                    <div class="subheading"><b>Enzuzo Inc. – Full Stack Developer | July 2020 – August 2021</b></div>
                    <ul class="subheading">
                        <li>Created a React app that allows Shopify users to obtain an automated Terms of Service and Privacy
                            Policy page as one of the primary features to attract users to use the company’s services</li>
                        <li>Developed data-driven questionnaire by parsing fields such as question type and title in a JSON file
                            which produces a customized Terms of Service and Privacy Policy automatically based on the user’s
                            answers, increasing user participation with personalized results</li>
                        <li>Configured tools such as Webpack, Babel and ESLint to help unify 3 separate web apps, ensure quality
                            code and compatibility for older browsers</li>
                        <li>Implemented several database features by creating Swagger definitions and using Golang to easily
                            query data for a user’s Privacy Policy and Terms of Service page while keeping the flexibility to easily
                            add more custom fields</li>
                        <li>Mentored co-ops by initiating pair-programming and having an open-door policy to speed up learning
                            process</li>
                        <li>Integrated Datadog for front-end monitoring to analyze recent uninstall data from users to identify any
                            common causes, using this data to direct future projects to improve app retention</li>
                    </ul>

                    <br>

                    <div class="subheading"><b>SSIMWAVE Inc. – Front-End Developer | May 2019 – August 2019</b></div>
                    <ul class="subheading">
                        <li>Collaborated with engineering and design team to overhaul front-end from AngularJS to Vue</li>
                        <li>Modernized the UI by transforming design mock-ups to actual code while also taking steps towards
                            unifying different apps to use the same architectural designs such as tech stack and file structure</li>
                        <li>Helped develop a new scheduling functionality by using design mock-ups to implement in Vue.js and
                            Express.js and prioritized ease of use by referencing various calendars in order to attract more users
                            with the app’s expansive set of features</li>
                        <li>Expanded automated testing by adding an end-to-end testing framework like Cypress to test more
                            involved workflows which allowed for larger test coverage on top of unit tests</li>
                    </ul>

                    <br>

                    <div class="subheading"><b>University of Waterloo – Full Stack Developer | September 2018 – December 2018</b></div>
                    <ul class="subheading">
                        <li>Assisted in developing a paging widget to replace the old co-op interview calling system, improving
                            efficiency by automating tasks and making intuitive design targeted for new users</li>
                        <li>Aided in modernizing the front-end design and implementation by incorporating student suggestions
                            and university branding to improve overall look and feel</li>
                        <li>Developed a working prototype of an instant messaging widget for Portal 1.0 as an 80/20 project,
                            learning how sockets and instant messaging work, with plans to integrate the improved model into
                            Portal 2.0</li>
                    </ul>
                    <br>
                </v-card>
            </v-flex>

            <v-flex xs12 style="margin: 2rem 0 2rem 0">
                <v-card style="padding: 3rem;" class="section-card">
                    <div class="headline">Projects</div>
                    <v-divider style="margin-bottom: 1rem;"></v-divider>

                    <div class="subheading"><b>Tunelight – HackConcordia2019</b></div>
                    <ul class="subheading">
                        <li>Generates the top 10 songs, genres or artists given a date range and location using TouchTunes’ API</li>
                        <li>Tasked with building the front-end</li>
                        <li>Spent 36 hours to learn React from scratch</li>
                    </ul>

                    <br>

                    <div class="subheading"><b>Listmaker</b></div>
                    <ul class="subheading">
                        <li>Motivated to learn how GraphQL and Auth0 works</li>
                        <li>Retrieves restaurants from Yelp and allows you to add restaurant to your list on your account</li>
                        <li>Uses your geolocation to provide you with restaurants nearby to provide a more personal experience</li>
                    </ul>
                </v-card>
            </v-flex>

            <v-flex xs12 style="margin: 2rem 0 2rem 0">
                <v-card style=" padding: 3rem;" class="section-card">
                    <div class="headline">Education</div>
                    <v-divider style="margin-bottom: 1rem;"></v-divider>
                    <div class="subheading">Bachelor of Computer Science, Computer Science, University of Waterloo,
                        Waterloo, Ontario, September 2014 – December 2019</div>
                </v-card>
            </v-flex>
        </v-layout>
    </v-parallax>
</template>

<script>
    export default {
        name: "Resume"
    }
</script>

<style scoped>
    .section-card {
        -webkit-border-radius: 10px;
        -moz-border-radius: 10px;
        border-radius: 10px;
    }

    .parallax-overlay:before {
        content: "";
        display: block;
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background-color: #6d6d6d;
        opacity: 0.5;
        transition: all .3s linear;
        z-index: 2;
    }
</style>