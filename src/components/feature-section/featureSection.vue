<template>
    <!--feature section-->
    <div class="feature-section">
        <div class="feature-section_theme">
            <h1 class="theme ">We design tools to unveil <br>your superpowers</h1>
        </div>
        <div class="blog-items_h">
            <div class="blog-items">
                <div class="blog-item">
                    <div class="blog-item__image">
                        <img src="src/v_jpg/icon.svg" alt="image">
                    </div>

                    <h5 class="blog-item__title">
                        First click tests
                    </h5>
                    <p class="paragrf blog-item_paragrf">
                        While most people enjoy casino gambling,
                    </p>

                </div>

                <div class="blog-item">
                    <div class="blog-item__image">
                        <img src="src/v_jpg/icon (1).svg" alt="image">
                    </div>

                    <h5 class="blog-item__title">
                        Design surveys
                    </h5>
                    <p class="paragrf blog-item_paragrf">
                        Sports betting, lottery and bingo playing for the fun
                    </p>

                </div>

                <div class="blog-item">
                    <div class="blog-item__image">
                        <img src="src/v_jpg/icon (2).svg" alt="image">
                    </div>

                    <h5 class="blog-item__title">
                        Preference tests
                    </h5>
                    <p class="paragrf blog-item_paragrf">
                        The Myspace page defines the individual.
                    </p>

                </div>

                <div class="blog-item">
                    <div class="blog-item__image">
                        <img src="src/v_jpg/icon (3).svg" alt="image">
                    </div>

                    <h5 class="blog-item__title">
                        Five second tests
                    </h5>
                    <p class="paragrf blog-item_paragrf">
                        Personal choices and the overall personality of the person.
                    </p>

                </div>
            </div>
            <div class="feature-button">
                <button class="feature-section_button">SIGN UP NOW</button>
            </div>
        </div>
    </div>
    <!--/feature section-->
</template>
<script></script>
<style>
/* feature section*/
.feature-section_theme {
    height: 180px;
    text-align: center;

}

.blog-items_h {
    background-image: url(src/v_jpg/Bg.png);
}

.blog-items {
    display: flex;
    justify-content: space-around;
    height: 300px;
}

.blog-item {
    width: 220px;
}

.feature-section_button {
    background: #FF9900;
    border-radius: 4px;
    height: 53px;
    width: 175px;
    border: 0;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 600;
    font-size: 16px;
    line-height: 24px;
    color: #FFFFFF;
    cursor: pointer;
    transition: 0.7s;
}

.feature-section_button:hover {
    background: #FFFFFF;
    color: #FF9900;
    font-family: 'poppins';
    border: 1px solid #FF9900;
    font-size: 16px;
    font-weight: 700;
}

.feature-button {
    width: 100%;
    height: 180px;
    text-align: center;

}
</style>