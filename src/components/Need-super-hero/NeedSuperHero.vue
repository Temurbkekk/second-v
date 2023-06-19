<template>
    <!--Need a super hero-->

    <div class="need_section">

        <div class="need_head">
            <h1 class="need_themes">Need a super hero?</h1>
            <p class="need_p">Do you require some help for your project: Conception workshop,
                prototyping, marketing strategy, landing page, Ux/UI?</p>
            <button class="need_button">Contact our expert</button>
        </div>
        <div class="need-i1">
            <img src="src/v_jpg/5.png" alt="">
        </div>
        <div class="need-i2">
            <img src="src/v_jpg/3.png" alt="">
        </div>


        <div class="need-i3">
            <img src="src/v_jpg/1.png" alt="">
        </div>
        <div class="need-i4">
            <img src="src/v_jpg/2.png" alt="">
        </div>

        <div class="need-i5">
            <img src="src/v_jpg/4.png" alt="">
        </div>

    </div>
    <!--/Need a super hero-->
</template>
<script>
export default {

}
</script>
<style scoped>
/*need a super hero*/
.need_section {
    background-image: url(src/v_jpg/Oval.png);
    position: relative;
    height: 835px;
}

.need_themes {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 36px;
    line-height: 54px;
    text-align: center;
    color: #2F281E;

}

.need_head {
    display: flex;
    flex-direction: column;
    align-items: center;
    position: absolute;
    padding-top: 240px;
    padding-left: 380px;

}

.need_p {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 26px;
    text-align: center;
    color: #567592;
    width: 600px;
}

.need_button {
    background: #FF9900;
    border-radius: 4px;
    border: 0;
    height: 53px;
    width: 216px;
    color: #FFFFFF;
    font-family: 'poppins';
    font-size: 16px;
    font-weight: 700;
    line-height: 24px;
    letter-spacing: 0px;
    text-align: center;
    cursor: pointer;
    transition: 0.7s;
}

.need_button:hover {
    background: #FFFFFF;
    color: #FF9900;
    font-family: 'poppins';
    border: 1px solid #FF9900;
    font-size: 16px;
}

.need-i1 {
    position: absolute;
    padding-top: 220px;
    padding-left: 135px;
}

.need-i2 {
    padding-top: 131px;
    position: absolute;
    padding-left: 824px;
}

.need-i3 {
    position: absolute;
    padding-top: 500px;
    padding-left: 110px;
}

.need-i4 {
    margin-top: 600px;
    padding-left: 540px;
    position: absolute;
}

.need-i5 {
    position: absolute;
    margin-top: 500px;
    padding-left: 970px;
}
</style>