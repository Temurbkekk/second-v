<template >
    <!--footer sektion-->
    <div class="container">
        <footer class="footer">
            <div class="footer-logo">
                <a href="#">
                    <img src="src/v_jpg/Logo.png" alt="logo">
                </a>
            </div>
            <div class=" quick-links">
                <ul clas="footer_items">
                    <li class="footer_item">
                        <a href="#">About Us</a>
                    </li>
                    <li class="footer_item">
                        <a href="#">Blog</a>
                    </li>
                    <li class="footer_item">
                        <a href="#">Concat</a>
                    </li>
                    <li class="footer_item">
                        <a href="#">FAQ</a>
                    </li>
                </ul>
            </div>
            <div class="legal-stuff">
                <ul class="footer_items">
                    <li class="footer_item">
                        <a href="#">Disclaimer</a>
                    </li>
                    <li class="footer_item">
                        <a href="#">Financing</a>
                    </li>
                    <li class="footer_item">
                        <a href="#">Privacy Policy</a>
                    </li>
                    <li class="footer_item">
                        <a href=" #"> Terms of Service</a>
                    </li>
                </ul>
            </div>
            <div style="width: 390px;">
                <form action="number" class="footer-form">
                    <input class="footer_form-i" type="tel" placeholder="Enter your phone Number">
                </form>
                <button class="footer_button">Sign up Now</button>
            </div>
        </footer>
    </div>
    <!--/footer-->
</template>
<script>
export default {

}
</script>
<style scoped>
/*footer*/
.footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 1225px;
}

.footer-logo {
    width: 187px;
    height: 260px;
}

.footer_item {
    display: flex;

}

.footer_item a {
    text-decoration: none;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 35px;
    color: #544837;
    transition: 0.3s;
}

.footer_item a:hover {
    color: #FF9900;
}

.footer_button {
    background: #FF9900;
    border-radius: 4px;
    border: 0;
    height: 39px;
    width: 132.6537322998047px;
    font-family: 'poppins';
    color: #FFFFFF;
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    text-align: center;
    cursor: pointer;
    transition: 0.7s;
    margin-top: 20px;
}

.footer_button:hover {
    background: #FFFFFF;
    color: #FF9900;
    font-family: 'poppins';
    border: 1px solid #FF9900;
    font-size: 16px;
}

.footer-form {
    background: #ffff;
    border: 1px solid #BCD0E5;
    font-size: 24px;
    padding: 0px 15px;
    display: flex;
    align-items: center;
    height: 48px;
    width: 329.102783203125px;
    border-radius: 4px;
}

.footer_form-i {
    border: none;
    box-sizing: border-box;
    outline: none;
    height: 48px;
    width: 329.102783203125px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    color: #BCD0E5;
}
</style>