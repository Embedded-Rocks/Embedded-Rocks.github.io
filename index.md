---
layout: default
---


## Welcome!

Most of the electronic projects I work on are always thinking about turning them into a product one day. **Embedded Rocks** is an umbrella of these projects with links to stores if you want to buy them as well as links to the repositories if you want to build one at home, since all projects are open-source.

If you have any questions or simply get in touch, sign my guestbook below :)

Jonathas.

---

## Shopping


![90s GIF On Sale](assets/img/SALE.gif) Visit the [oficial store](https://store.embedded.rocks/){:target="_blank"}


|---|---|
|![Clockwise logo](assets/img/clockwise-logo.png)| Get the Clockwise DIY Kit with **5% OFF** clicking [here](https://0f44a3.myshopify.com/cart/46296134254874:1?storefront=true&note=origin-embeddedrocks-homepage&discount=CLOCKWISEOFF5){:target="_blank"}|







---

## Guestbook
<!--![Shopify button](assets/img/shopify.png) -->
<div class="container">
    <form action="https://usebasin.com/f/be3b2e6ed179" method="POST" enctype="multipart/form-data" id="guestbook">
        <textarea name="message" row="3" placeholder="Message" required></textarea>
        <input type="text" name="name" placeholder="Name or Email" required/>
        <input  id="dateTime" type="hidden" name="dateTime"/>
        <input type="submit"/>
    </form>
</div>
<script>
    document.getElementById('dateTime').value = new Date().toUTCString();
</script>
