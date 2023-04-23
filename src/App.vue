<template>
    <div v-if="isFixed" id="header__fixed">
        <div id="fixed__items">
            <li id="fixed__text">Start your free-trial today</li>
            <ul id="fixed__buttons">
                <button id="fixed__get-started">Get started</button>
                <button id="fixed__learn-more">Learn more</button>
            </ul>
        </div>
    </div>
    <BringIdeas/>
    <AdvantagesSf/>
    <PortfolioSf/>
    <BuildSf/>
    <FaqSf/>
</template>
<script>
import BringIdeas from '@/components/BringIdeas.vue';
import AdvantagesSf from '@/components/AdvantagesSf.vue';
import PortfolioSf from '@/components/PortfolioSf.vue';
import BuildSf from '@/components/BuildSf.vue';
import FaqSf from '@/components/FaqSf.vue';

export default{
    components : {
        BringIdeas,
        AdvantagesSf,
        PortfolioSf,
        BuildSf,
        FaqSf
    },
    data(){
        return{
            isFixed : false
        }
    },
    beforeMount(){
        window.addEventListener('scroll', () => {
            let position = window.pageYOffset
            if(position > 199){
                this.isFixed = true
                console.log(position)
            }
            else{
                console.log(position)
                this.isFixed = false
            }
        })
    }
}

</script>
<style>
*
{
    transition: all .3s;
    background-color: transparent;
    margin: 0;
    padding: 0;
    text-decoration: none;
    outline: none;
    color: #000;
    list-style-type: none;
}
body
{ 
    overflow-x: hidden;
    margin: 0; 
    font-family: ShopifySans,Helvetica,Arial,sans-serif; 
    background-color: #f1fff9;
}
a,button,input
{ 
    padding: 0;
    margin: 0;
    cursor: pointer;
    border: 0;
    background: none;
}
.container
{ max-width: 1420px; margin: 0 auto; }

#header__fixed
{
    border-bottom: 1px solid rgb(228, 228, 229);
    background-color: #fff;
    width: 100%;
    display: block;
    position: fixed;
    z-index: 99;
    height: 62px;
}
#fixed__items
{
    max-width: 495px;
    margin: 11.5px auto;
    display: flex;
    justify-content: space-between;
}
#fixed__text
{
    max-width: 222.5px;
    font-size: 16px;
    font-weight: 700;
    margin-top: 11px;
}
#fixed__buttons
{
    width: 243px;
    display: flex;
    justify-content: space-between;
}
#fixed__get-started,#fixed__learn-more
{
    font-size: 12px;
    border-radius: 999px;
    border: 2px solid #000;
    width: 110px;
    height: 40px;
    padding-top: 2px;
    margin-top: -1px;
}
#fixed__get-started
{
    width: 109.44px;
    background-color: #000;
    color: #fff;
}
#fixed__learn-more:hover
{ border: 3px solid #000; }
#fixed__get-started:hover
{ opacity: .8 ; }


@media (max-width: 1700px){
    #trial__msg-text
    { padding-left: 28%; }
}
@media (max-width: 1550px){
    #trial__msg-text
    { padding-left: 27.5%; }
}
@media (max-width: 1500px){
    #trial__msg-text
    { padding-left: 25%;}
}

@media (max-width: 1350px){
    #trial__msg-text
    { padding-left: 22.5%; }
}

@media (max-width: 1200px){
    #trial__msg-text
    { padding-left:20%; font-size: 16px; }
    #free__trial-msg
    { height: 24px; }
    #bring__title,#quote__title,#build__title-main
    { font-size: 58px; }
    #portfolio__items
    { 
        row-gap: 2.5rem;
        grid-template-columns: none;
        grid-template-areas: 
        'a b c'
        'd e f'
        'g h i'
        'j . .'
        ; 
    }
    #portfolio__wrap
    { margin: 0 20px; margin-top: 111px; }
}

@media (max-width: 1121px){
    #mark-2
    {  margin-top: 0px !important; }
}

@media (max-width: 900px){
    #trial__msg-text{ padding-left: 10%; font-size: 14px; }
    #free__trial-msg
    { height: 30px; padding: 11px 0px; }
    #advantages__items
    {
        display: flex;
        flex-direction: column;
        gap: 30px;
        margin: 0px 95px;
    }
}

@media (max-width: 841px){
    #mark-2
    {  margin-top: -20px !important; max-width: 109px; }
}

@media (max-width: 700px){
    #trial__msg-text
    {
        display: flex;
        flex-direction: column;
        text-align: center;
    }
    #free__trial-msg
    { height: 50px; padding: 11px 0px; }
    #bring__title,#quote__title,#build__title-main
    { font-size: 46px; }
}
</style>
