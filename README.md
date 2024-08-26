# Tennis market

<style>
h1 {
    text-align: center;
}

#txt_welcome {
    text-align: center; 
    margin-bottom: 50px;
}

.card {
    text-align: center;
}

.card_title {
    font-size: 20px;
}

.card_button {
    font-size: 25px;
    width: 150px;
    height: 30px;
}

.card_img {
    width: 300px;
    height: 300px;
}
</style>

<div id="txt_welcome">
Welcome to Tennis market! <br>
Enjoy your shopping.
<br>
<br>
<a href="./orderlist"> order list </a>
</div>

<div style="display:grid; grid-template-columns: 1fr 1fr 1fr;">
<div class="card">

![Red Racket](/public/img/redRacket.png){: .card_img}

**Red Racket**{: .card_title}

<input class="card_button" type="button" value="order" onclick="location.href='/order?productId=1'">

</div>
<div class="card">

![Blue Racket](/public/img/blueRacket.png){: .card_img}

**Blue Racket**{: .card_title}

<input class="card_button" type="button" value="order" onclick="alert(2);">

</div>
<div class="card">

![Black Racket](/public/img/blackRacket.png){: .card_img}

**Black Racket**{: .card_title}

<input class="card_button" type="button" value="order" onclick="alert(3);">

</div>
</div>