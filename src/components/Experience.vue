<template>
    <section class="experience" id="experience">
        <h1 class="title">Experience</h1>
        <main class="content">
            <div class="experience company" v-for="i in 3" :key="i">
                <h3><span>{{'0'+i}}</span>Tesla Corp. Pvt. Ltd.</h3>
                <p>2018-NOW</p>
                <p>Software Engineer - 1</p>
                <ul>
                    <li> Translating UI/UX designs into pipel-perfect campaigns.</li>
                    <li> Implementing interactive elements and animations for a smooth user experience.</li>
                    <li> Ensuring responsiveness across different devices and screen sizes.</li>
                    <li>Collaborating with back-end developers to integrate APIs and data sources.</li>
                    <li>Implementing performance optimization techniques for fast loading times.</li>
                </ul>
            </div>
        </main>
    </section>
</template>

<style lang="scss" scoped>
    section{
        margin-top: 10%;
        h1.title{
            font-size: 3rem;
            &::after{
                content: '';
                display: block;
                width: 100%;
                height: 10px;
                background-color: rgba(211, 214, 216, .2);
                transform: skewX(-50deg);
                // margin-top: -20px;
            }
        }

        .experience{
            h3{
                font-size: 1.8rem;
                color: rgba(211, 214, 216, .6);
                margin-bottom: 0;
                position: relative;

                span{
                    font-size: 4rem;
                    // position: absolute;
                    left: -10px;
                    bottom: -25%;
                    color: rgba(211, 214, 216, .08);
                }
            }
            p{
                margin: 0;
              &:nth-child(1){
              }  
            }
        }
    }
</style>