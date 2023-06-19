<template>
    <div class="main_section">
        <div class="container">
            <section id="Main section" class="main-section">

                <div class="main-section_theme">
                    <h1 class="theme">The Design Thinking <br>superpowers</h1>
                    <p class="paragrf">Tools, tutorials, design and innovation experts, all in one place! The most
                        intuitive way to imagine your next user experience.</p>
                    <div class="main-section_button">
                        <button class="button_3">Get started</button>
                        <a href="#"><img src="/src/v_jpg/button.png" alt="img"></a>

                    </div>
                </div>

                <div class="main-section-image">
                    <img src="/src/v_jpg/Image (3).png" alt=" image">
                </div>

            </section>
        </div>
    </div>
</template>
<script></script>
<style>
/*main section*/
.main-section_theme {
    width: 445px;
    line-height: 90px;
}

.main-section {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 494px;
    padding-bottom: 40px;
}

.main-section-image img {
    width: 602.36px;
    height: 494.83px;
    left: 666px;
    top: 128px;

}

.theme {
    width: 100%;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 44px;
    line-height: 54px;
    /* or 123% */


    color: #2F281E;

}

.button_3 {
    width: 175px;
    height: 53px;
    left: 145px;
    top: 489px;
    border: none;
    background: #FF9900;
    border-radius: 4px;
    font-family: 'poppins';
    font-size: 16px;
    color: #FFFFFF;
    cursor: pointer;
    font-weight: 700;
    transition: 0.8s;
}

.button_3:hover {
    background: #FFFFFF;
    color: #FF9900;
    font-family: 'poppins';
    border: 1px solid #FF9900;
    font-size: 16px;
    font-weight: 700;
}

.main-section_button {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 370px;

}

.main-section_button a {
    height: 78px;
}

.paragrf {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 28px;
    /* or 156% */


    color: #544837;
}

.blog-item__title {
    height: 33px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 22px;
    line-height: 33px;
    color: #2F281E;
}
</style>