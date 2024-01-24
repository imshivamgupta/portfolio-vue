<template>
    <section>
        <main>
            <div class="main-content">
            <h1>Turnning Vision 
            Into Reality
        With Code And Design.</h1>

        <h5>As a skilled full-stack developer, I am dedicated to turning ideas into innovative web applications. Explore my latest projects and articles, showcasing my expertise in React.js and web development.</h5>
        </div>
        <div class="btn-group">
            <button class="btn-primary">Resume</button>
            <button class="btn-secondary">Contact</button>
        </div>
        </main>
        <div class="img-wrapper">

            <img src="@/assets/hero.png" class="hero-img"/>
        </div>
    </section>
</template>

<style scoped>
section{
    display: flex;
    align-items: center;
    main{
        max-width: 56%;
    }

    .img-wrapper:hover img{
        
            /* transform: scale(-1, 1) skew(-5deg); */
            -webkit-filter: drop-shadow(5px 5px 5px #fff);
        filter: drop-shadow(-5px 0px 1px pink);
        
    }
    .hero-img{
        /* max-width: 10vw; */
        box-sizing: border-box;
        max-height: 500px;
        margin: auto;
        transform: scale(-1, 1);
        transition: all .2s linear;
    }
}


.main-content{
    /* max-width: 56%; */
    h1{
        font-size: 5rem;
        line-height: 1;
        margin-bottom: 1rem;
    }

    h5{
        max-width: 80%;
        font-weight: 400;
    }

   
}

.btn-group{
        display: flex;

        button{
            border: none;
            padding: 1rem 4rem;
            border-radius: .25rem;
            font-weight: 600;
            cursor: pointer;
            transition: all .2s linear;
            &:last-child{
                margin-left: 1rem;
            }
        }
        .btn-primary{
            
            background-color: white;
            color: #242424;


            &:hover{
                filter: invert(90%);
            }
        }

        .btn-secondary{
            background-color: unset;
            border: 1px solid whitesmoke;

            &:hover{
                filter: invert(40%);
            }
        }
    }
</style>

<script>
export default{

}
</script>