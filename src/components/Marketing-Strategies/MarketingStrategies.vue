<template >
    <!--Marketing Strategies-->
    <div class="marketing-strategies_section">
        <div class="container">

            <div class="marketing-strategies_h">
                <h1 class="marketing-strategies_theme">
                    Marketing Strategies
                </h1>
                <p class="marketing-strategies_p">Join 40,000+ other marketers and get proven strategies on email
                    marketing
                </p>
            </div>
            <div class="marketing-strategies_cards">
                <div class="marketing-strategies_card">
                    <img src="src/v_jpg/Bitmap.png" alt="">
                    <h5 class="card-h">By Abdullah | 03 March 2019</h5>
                    <h2 class="card-h2">Increasing Prosperity With Positive Thinking</h2>
                </div>
                <div class="marketing-strategies_card">
                    <img src="src/v_jpg/Bitmap (1).png" alt="">
                    <h5 class="card-h">By Abdullah | 03 March 2019</h5>
                    <h2 class="card-h2">Motivation Is The First Step To Success</h2>
                </div>
                <div class="marketing-strategies_card">
                    <img src="src/v_jpg/Bitmap (2).png" alt="">
                    <h5 class="card-h">By Abdullah | 03 March 2019</h5>
                    <h2 class="card-h2">Success Steps For Your Personal Or Business Life</h2>
                </div>
            </div>
        </div>
    </div>
    <!--line-->
    <div class="line">
        <button class="line-button"></button>
    </div>
    <!--/line-->
</template>
<script>
export default {

}
</script>
<style  scoped>
/*marketing strtegies*/
.marketing-strategies_theme {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 34px;
    line-height: 51px;
    color: #2F281E;

}

.marketing-strategies_p {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 26px;
    color: #544837;
}

.marketing-strategies_h {
    height: 150px;
}

.marketing-strategies_cards {
    display: flex;
    justify-content: space-between;

}

.marketing-strategies_cards img {
    border-radius: 8px 8px 0px 0px;
}

.card-h {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 28px;
    color: #544837;

}

.card-h2 {
    width: 280px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 34px;
    color: #2F281E;
    transition: 0.6s;
}

.card-h2:hover {
    color: #FF9900;
}

/*line*/
.line {
    text-align: center;
    width: 100%;
    padding-bottom: 60px;
}

.line-button {
    width: 1205px;
    height: 1px;
    border: 0;
    background: rgba(188, 208, 229, 0.496913)
}
</style>