<template>
    <header aria-label="header of the portfolio">
        <span>{{ title }}</span>

        <ul>
            <li>
                <a href="#">Home</a>
            </li>
            <li><a href="#experience">Experience</a>
            </li>
            <li><a href="#skills">Skill</a></li>
            <li><a href="#about">About</a></li>
        </ul>
    </header>
</template>

<style scoped>
header{
    display: flex;
    flex-direction: row;
    justify-content: space-between;

    /* position: sticky;
    top: 0; */
    /* padding: 1rem 0; */

    background-color: #242424;
    padding: 1rem 0;
    

    ul{
        display: flex;
        margin: 0;


        li{
            list-style: none;
            &:not(:last-child){
                margin-right: 1rem;
            }

           

            a{
                color: rgba(255, 255, 255, 0.87);
                text-decoration: underline;
            }
        }
    }
}
</style>

<script>

export default{
    name: 'Header',
    data(){
        return {
            title: "{{ Shivam's Portfolio }}"
        }
    }
    
}
</script>

