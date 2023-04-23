<template>
    <div id="build__wrapper">
        <img src="https://cdn.shopify.com/b/shopify-brochure2-assets/0d56efcd813bc72d0427f8863976c3a1.svgz" id="mark-1">
        <ul id="build__title">
            <li id="build__title-main">
                Build your dream business for $1/month
            </li>
            <li id="build__title-sup">
                Start your free trial and enjoy 2 months of Shopify for $1/month on select plans.
            </li>
        </ul>
        <form id="build__inputzone">
            <input type="text" v-model="inputEmailBuild" placeholder="Enter your email address" id="input__email-build">
            <button type="button" @click="sendEmailBuild" id="send__email-build">Start free trial</button>
        </form>
        <div id="build__ps">
            Try Shopify free for 3 days, no credit card required. By entering your email, you agree to receive marketing emails from Shopify.
        </div>
        <img src="https://cdn.shopify.com/b/shopify-brochure2-assets/1d5f94e0fb634025423acb965ece0b18.svgz" id="mark-2">
    </div>
</template>
<script>
export default{
    data(){
        return{
            inputEmailBuild : ''
        }
    },
    methods : {
        sendEmailBuild(){
            console.log(this.inputEmailBuild)
        }
    }
}


</script>
<style scoped>

#build__wrapper
{
    margin-top: 86px;
    padding-top: 128px;
    background: #054a49 radial-gradient(circle at -48% 130%,#d0f224aa 24%,#054a49 45%);
    height: 406px;
}

#mark-1,#mark-2
{
    position: absolute;
    z-index: 99;
    right:-4px;
    margin-top: -198px;
}
#mark-2{ left:35px; margin-top: 36px; }

#build__title
{
    max-width: 1220px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 40px;
}
#build__title-main
{
    color: #fff;
    text-align: center;
    font-weight: 700;
    font-size: 60px;
    letter-spacing: -.02em;
    line-height: 4.125rem;
}
#build__title-sup
{
    color: #fff;
    text-align: center;
    font-size: 22px;
    letter-spacing: -.02em;
    line-height: 2rem;
}

#build__inputzone
{
    max-width: 494px;
    max-height: 64px;
    margin: 0 auto;
    margin-top:  40px;
    border-radius: 9999px;
    display: flex;
    background-color: #fff;
    justify-content: space-between;
    border: 1px solid #fff;
    padding: 3.5px 0px;
}
::placeholder
{
    font-size: 16px;
    color: rgb(204, 204, 204);
}
#input__email-build
{
    padding-left: 3px;
    padding-top: 2.5px;
    margin-left: 20px;
}
#send__email-build
{
    background-color: #fff;
    border-radius: 9999px;
    color: #000;
    font-size: 16px;
    font-weight: 700;
    height: 53px;
    width: 160px;
    margin-right: 4px;
}
#send__email-build:hover
{
    background-color: rgb(211, 211, 211);
    opacity: 1;
}
#build__ps
{
    font-size: 14px;
    line-height: 1.25rem;
    letter-spacing: .02em;
    max-width: 856px;
    margin: 0 auto;
    padding-top: 16px;
    text-align: center;
    color: #fff;
}


</style>