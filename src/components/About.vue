<template>
    <section class="experience" id="about">
        <h1 class="title">About</h1>
        <main class="content">
            <div class="wrapper-1">
                <div>

                    <h4>Let's Connect.</h4>
                    <p>Email: shivamg8797@gmail.com</p>
                </div>
                    <div class="social-media">
                        
                        <ul>
                            <li><a href="#">LinkedIn</a></li>
                            <li><a href="#">Instagram</a></li>
                            
                        </ul>

               </div>
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

        .wrapper{
            display: flex;
            // justify-content: center;
            flex-wrap: wrap;
            gap: 40px 10px;
            .skill{
                flex:  0 1 calc(25% - (2 * 10px));
                // border: solid;
                display: flex;
                justify-content: center;
                img{
                    max-width: 100%;
                    object-fit: contain;
                    max-height: 100px;
                    aspect-ratio: 1;
                    transition: all .2s ease-in;

                    @at-root:nth-child(6) img{
                        mix-blend-mode: difference;
                    }
                   

                    &:hover{
                        mix-blend-mode: multiply;
                    }
                }

                
            }
        }
    }
</style>

<script>
export default{
    name: 'Skill',
    
}
</script>