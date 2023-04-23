<template>
    <div class="container">
        <div id="portfolio__wrap">
            <div id="portfolio__items">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/allbirds-en-32a9094fcaa4ba7a127ff52a9a8a051a501bee2dbc853e77b58347239eba2e31.svg" id="portfolio__item">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/gymshark-6dee5a0bce30830832bb264c6abe948259f5fbc3fae496363d65b93285c0def0.svg" id="portfolio__item">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/brooklinen-en-97e99d6b63701f9e8e01fa31088abea5471e0bffbc5399249d88efab78f09ad7.svg" id="portfolio__item">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/leesa-en-2b8ff54cd3589e8f971a15bec9d18d284f341e021f6d3b5342e5df0b99f90aa6.svg" id="portfolio__item">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/kylie-cosmetics-260bf2e2e655124c9331d97c26967ee10d71bd7384265e76013422c1d1386f84.svg" id="portfolio__item">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/telfar-5ad6221e7d86aeb6db1f6ece956ba85dd7f46ca1b54cef63dbec91d8cee62fbf.svg" id="portfolio__item">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/untuckit-en-ec6d2da1666f7817bd38320be4500cee061c9f2b1868f0bcf141e2cecbf4f876.svg" id="portfolio__item">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/death-wish-coffee-9512e9d17fdeedebb9abfce9ce082598ee47d470fd0f0272ccac128044b7fc70.svg" id="portfolio__item">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/jungalow-en-db026f34f2a0e403d05c12364aa7e8525c04a1bee09adfc20b794c1badec72d7.svg" id="portfolio__item">
                <img src="https://cdn.shopify.com/shopifycloud/brochure/assets/cms/logo-soup/en/rebecca-minkoff-3d13302faef2bb4815be8aa24b005dc5969f51f8b46eabf5cc397b526f2b5e8e.svg" id="portfolio__item">
            </div>
        </div>
        <ul id="quote">
            <li id="quote__title">
                "Shopify is better than any other platform we've played with, and we've played with them all."
            </li>
            <li id="quote__name">
                Jonathon Bayme, CEO of Theory11
            </li>
        </ul>
    </div>
</template>
<style>
#portfolio__wrap
{
    margin-top: 111px;
    border-top:2px solid #e5e7eb;
    border-bottom:2px solid #e5e7eb;
}
#portfolio__items
{
    padding: 40px 0px;
    display: grid;
    grid-template-columns: repeat(5,auto);
    column-gap: 1.5rem;
    row-gap: 2.5rem;
    max-width: 1145px;
    margin: 0 auto;
}
#portfolio__item
{ width: 100% }

#quote
{
    margin-top: 128px;
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: 40px;
}
#quote__title
{
    font-weight: 700;
    font-size: 60px;
    letter-spacing: -.02em;
    line-height: 4.125rem;
}
#quote__name
{
    font-size: 22px;
    letter-spacing: -.02em;
    line-height: 2rem;
}

</style>