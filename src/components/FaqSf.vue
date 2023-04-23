<template>
    <div id="faq__wrapper">
        <div class="container">
            <div id="faq__title">
                FAQ
            </div>
            <div id="faq__items">
                <div id="faq__item-wrap">
                    <button @click="this.isHiddenAns1 = !this.isHiddenAns1" id="faq__item">
                        <li id="faqa__title">
                            What is Shopify and how does it work?
                        </li>
                        <div class="faq__showanswer">
                            <svg v-if="isHiddenAns1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="rounded-full p-1.5 w-[44px] h-[44px] bg-white text-black group-hover:bg-shade-30 group-active:bg-shade-50 group-focus-visible:outline group-focus-visible:outline-2 group-focus-visible:outline-state-focus"><path d="M10 4a1 1 0 0 0-1 1v4H5a1 1 0 1 0 0 2h4v4a1 1 0 1 0 2 0v-4h4a1 1 0 1 0 0-2h-4V5a1 1 0 0 0-1-1Z" fill="currentColor"></path></svg>
                            <svg v-else viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" class="rounded-full p-1.5 w-[44px] h-[44px] bg-black text-white border-2 border-white group-hover:border-shade-30 group-active:border-shade-50 group-focus-visible:outline group-focus-visible:outline-2 group-focus-visible:outline-state-focus"><path d="M14.1667 9H5.83333C5.3725 9 5 9.448 5 10C5 10.552 5.3725 11 5.83333 11H14.1667C14.6275 11 15 10.552 15 10C15 9.448 14.6275 9 14.1667 9" fill="currentColor"></path></svg>
                        </div>
                    </button>
                    <ul v-if="!isHiddenAns1" id="answer__wrap">
                        <li id="answer__text-up">
                            Shopify is a complete commerce platform that lets you start, grow, and manage a business
                        </li>
                        <li id="answer__text-up">
                            With Shopify, you can:
                        </li>
                        <li id="answer__marked">
                            Create and customize an online store
                        </li>
                        <li id="answer__marked">
                            Sell in multiple places, including web, mobile, social media, online marketplaces, brick-and-mortar locations, and pop-up shops
                        </li>
                        <li id="answer__marked">
                            Manage products, inventory, payments, and shipping
                        </li>
                        <li id="answer__text">
                            Shopify is completely cloud-based and hosted, which means you don't have to worry about upgrading or maintaining software or web servers. 
                            This gives you the flexibility to access and run your business from almost anywhere, including your mobile device.
                        </li>
                    </ul>
                </div>
                <div id="faq__item-wrap">
                    <button @click="isHiddenAns2 = !isHiddenAns2" id="faq__item">
                        <li id="faqa__title">
                            How much does Shopify cost?
                        </li>
                        <div class="faq__showanswer">
                            <svg v-if="isHiddenAns2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="rounded-full p-1.5 w-[44px] h-[44px] bg-white text-black group-hover:bg-shade-30 group-active:bg-shade-50 group-focus-visible:outline group-focus-visible:outline-2 group-focus-visible:outline-state-focus"><path d="M10 4a1 1 0 0 0-1 1v4H5a1 1 0 1 0 0 2h4v4a1 1 0 1 0 2 0v-4h4a1 1 0 1 0 0-2h-4V5a1 1 0 0 0-1-1Z" fill="currentColor"></path></svg>
                            <svg v-else viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" class="rounded-full p-1.5 w-[44px] h-[44px] bg-black text-white border-2 border-white group-hover:border-shade-30 group-active:border-shade-50 group-focus-visible:outline group-focus-visible:outline-2 group-focus-visible:outline-state-focus"><path d="M14.1667 9H5.83333C5.3725 9 5 9.448 5 10C5 10.552 5.3725 11 5.83333 11H14.1667C14.6275 11 15 10.552 15 10C15 9.448 14.6275 9 14.1667 9" fill="currentColor"></path></svg>
                        </div>
                    </button>
                    <ul v-if="!isHiddenAns2" id="answer__wrap">
                        <li id="answer__text-up">
                            Try Shopify free for 3 days, no credit card required.
                        </li>
                        <li id="answer__text-up">
                            After your trial expires, choose a pricing plan that suits the size and stage of your business.
                        </li>
                    </ul>
                </div>
                <div id="faq__item-wrap">
                    <button @click="isHiddenAns3 = !isHiddenAns3" id="faq__item">
                        <li id="faqa__title">
                            Can I use my own domain name with Shopify?
                        </li>
                        <div class="faq__showanswer">
                            <svg v-if="isHiddenAns3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="rounded-full p-1.5 w-[44px] h-[44px] bg-white text-black group-hover:bg-shade-30 group-active:bg-shade-50 group-focus-visible:outline group-focus-visible:outline-2 group-focus-visible:outline-state-focus"><path d="M10 4a1 1 0 0 0-1 1v4H5a1 1 0 1 0 0 2h4v4a1 1 0 1 0 2 0v-4h4a1 1 0 1 0 0-2h-4V5a1 1 0 0 0-1-1Z" fill="currentColor"></path></svg>
                            <svg v-else viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" class="rounded-full p-1.5 w-[44px] h-[44px] bg-black text-white border-2 border-white group-hover:border-shade-30 group-active:border-shade-50 group-focus-visible:outline group-focus-visible:outline-2 group-focus-visible:outline-state-focus"><path d="M14.1667 9H5.83333C5.3725 9 5 9.448 5 10C5 10.552 5.3725 11 5.83333 11H14.1667C14.6275 11 15 10.552 15 10C15 9.448 14.6275 9 14.1667 9" fill="currentColor"></path></svg>
                        </div>
                    </button>
                    <ul v-if="!isHiddenAns3" id="answer__wrap">
                        <li id="answer__text-up">
                            Yes, you can use your own domain name with Shopify.
                        </li>
                        <li id="answer__text-up">
                            If you have an existing domain name, you can connect it to Shopify from your store's admin.
                        </li>
                        <li id="answer__marked">
                            If you don't have a domain name yet, you can either buy one through Shopify or a third-party provider.
                        </li>
                    </ul>
                </div>
                <div id="faq__item-wrap-l">
                    <button @click="isHiddenAns4 = !isHiddenAns4" id="faq__item">
                        <li id="faqa__title">
                            Do I need to be a designer or developer to use Shopify?
                        </li>
                        <div class="faq__showanswer">
                            <svg v-if="isHiddenAns4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" class="rounded-full p-1.5 w-[44px] h-[44px] bg-white text-black group-hover:bg-shade-30 group-active:bg-shade-50 group-focus-visible:outline group-focus-visible:outline-2 group-focus-visible:outline-state-focus"><path d="M10 4a1 1 0 0 0-1 1v4H5a1 1 0 1 0 0 2h4v4a1 1 0 1 0 2 0v-4h4a1 1 0 1 0 0-2h-4V5a1 1 0 0 0-1-1Z" fill="currentColor"></path></svg>
                            <svg v-else viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg" class="rounded-full p-1.5 w-[44px] h-[44px] bg-black text-white border-2 border-white group-hover:border-shade-30 group-active:border-shade-50 group-focus-visible:outline group-focus-visible:outline-2 group-focus-visible:outline-state-focus"><path d="M14.1667 9H5.83333C5.3725 9 5 9.448 5 10C5 10.552 5.3725 11 5.83333 11H14.1667C14.6275 11 15 10.552 15 10C15 9.448 14.6275 9 14.1667 9" fill="currentColor"></path></svg>
                        </div>
                    </button>
                    <ul v-if="!isHiddenAns4" id="answer__wrap">
                        <li id="answer__text-up">
                            No, you don't need to be a designer or developer to use Shopify.
                        </li>
                        <li id="answer__text-up">
                            Signing up for Shopify allows you to:
                        </li>
                        <li id="answer__marked">
                            Customize the look and feel of your store with the online store builder and themes.
                        </li>
                        <li id="answer__marked">
                            Add features and functionality to your store with apps.
                        </li>
                        <li id="answer__text">
                            If you need extra help, you can contact our support team, 
                            or visit the Shopify Expert Marketplace to search for and hire a certified Shopify expert.
                        </li>
                    </ul>
                </div>
            </div>
            <ul id="footer">
                <li id="footer__item">
                    Terms of Service
                </li>
                
                <li id="footer__item">
                    Privacy Policy
                </li>
                
                <li id="footer__item">
                    Sitemap
                </li>
            </ul>
        </div>
    </div>
</template>
<script>
export default{
    data(){
        return{
            isHiddenAns1 : true,
            isHiddenAns2 : true,
            isHiddenAns3 : true,
            isHiddenAns4 : true,
        }
    },
    methods : {
        
    }
}


</script>
<style>
#faq__wrapper
{ 
    height: 885px; 
    padding: 0px 20px; 
    padding-top: 82px;  
}
#faq__items
{
    display: flex;
    flex-direction: column;
    gap: 42px;
    margin-top: 47px;
}
#faq__item
{
    display: flex;
    justify-content: space-between;
    width: 100%;
    color: #000;
}
#faq__item:hover
{ opacity: .7; }
#faq__item-wrap,#faq__item-wrap-l
{
    margin-left: 16.95%;
    max-width: 979px;
    padding: 0px 40px 24px;
    border-bottom: 2px solid rgb(210 213 217) ;
}
#faq__item-wrap-l
{ border: 0; }

#faq__title
{
    font-size: 60px;
    font-weight: 700;
    letter-spacing: -.02em;
    line-height: 4.125rem;
}
#faqa__title
{
    font-size: 32px;
    font-weight: 600;
    letter-spacing: -.02em;
    line-height: 4.125rem;
}
.faq__showanswer
{
    width: 32px;
    height: 32px;
    background-color: #fff;
    border-radius: 9999px;
    padding: 6px;
    margin-top: 14px;
}

#answer__wrap
{ margin-top: 5px; max-width: 758px; }
#answer__marked,#answer__text,#answer__text-up
{ font-size: 18px; }
#answer__text-up
{ margin-bottom: 35px; }
#answer__marked
{
    margin-top: 5px;
    margin-left: 25px;
    display: list-item  ;
    list-style-type: disc;
    margin-bottom: 22px;
}

#footer
{
    display: flex;
    justify-content: space-between;
    max-width:545px;
    margin-left: auto;
    margin-top: 96px;
}
#footer__item
{
    text-decoration: underline;
    font-size: 18px;
    font-weight: 700;
}

</style>