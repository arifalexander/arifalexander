<template>
    <div class="experience mt-4 py-5">
        <div class="container">
            <div class="row">
                <div class="col-md-6 offset-md-3">
                    <h4>Latest News</h4>
                    <ul class="timeline">
                        <li>
                            <a href="http://kafeinarts.vercel.app/">KafeinArts</a> - 2023 
                            <p> Currently I am a mentor and founder of Code With Arif, CWA is an online learning platform that provides various courses and training in the fields of computer science and information technology. This platform is usually available in PowerPoint or video conference which allows users to carry out teaching and learning activities in real-time and also get material in PowerPoint or portable document format.</p>
                        </li>
                        <li>
                            <a href="http://arca-olive.vercel.app/">Arca Interactive</a> - 2022
                            <p>As a talented website designer, you have had valuable experience in creating an attractive appearance and user experience at startup Arca Interactive. With expertise in designing layouts, graphics and visual elements, you have succeeded in creating an aesthetic and functional website. At Arca Interactive, you play a role in designing innovative website interfaces, ensuring that every web page you design meets high design standards and creates a compelling experience for users. With your dedication to website design, you have made a significant contribution to strengthening the brand identity and user experience at startup Arca Interactive.</p>
                        </li>
                        <li>
                            <a href="https://www.guepedia.com/">Guepedia</a> - 2021
                            <p>As a frontend developer, I have extensive experience in designing and developing attractive and responsive user interfaces. With expertise in HTML, CSS, and JavaScript with some framework like vue js for the javascript and bootstrap for the css framework, I have succeeded in creating engaging user experiences through engaging visual design and intuitive functionality. In every project, I always focus on creating an aesthetic appearance and optimal user experience.
                            </p>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
ul.timeline {
    list-style-type: none;
    position: relative;
}

ul.timeline:before {
    content: ' ';
    background: #d4d9df;
    display: inline-block;
    position: absolute;
    left: 29px;
    width: 2px;
    height: 100%;
    z-index: 400;
}

ul.timeline>li {
    margin: 20px 0;
    padding-left: 20px;
}

ul.timeline>li:before {
    content: ' ';
    background: white;
    display: inline-block;
    position: absolute;
    border-radius: 50%;
    border: 3px solid #22c0e8;
    left: 20px;
    width: 20px;
    height: 20px;
    z-index: 400;
}
</style>