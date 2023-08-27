---
layout: default
---


## Welcome!

Most of the electronic projects I work on are always thinking about turning them into a product one day. **Embedded Rocks** is an umbrella of these projects with links to stores if you want to buy them as well as links to the repositories if you want to build one at home, since all projects are open-source.

If you have any questions or simply get in touch, sign my guestbook below :)

Jonathas.

---

[Visit the store](https://store.embedded.rocks/){:target="_blank"}


---





<div class="container">
    <h3>Guestbook</h3>
    <form action="https://usebasin.com/f/be3b2e6ed179" method="POST" enctype="multipart/form-data" id="guestbook">
        <textarea name="message" row="3" required placeholder="Message"></textarea>
        <input type="text" name="name" placeholder="Name or Email" required/>
        <input  id="dateTime" type="hidden" name="dateTime"/>
        <input type="submit"/>
    </form>
</div>
<script>
    document.getElementById('dateTime').value = new Date().toUTCString();
</script>
