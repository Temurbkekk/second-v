<template>
    <header class="header_section">
        <div class="container">
            <!--navbar-->
            <nav class="navbar">
                <div class="logo">
                    <a href="#">
                        <img src="/src/v_jpg/Logo.png" alt="logo">
                    </a>
                </div>
                <ul class="nav navbar_items">
                    <li class="navbar_item">
                        <a href="verstka.html"> Home</a>
                    </li>
                    <li class="navbar_item">
                        <a href="#"> Product</a>
                    </li>
                    <li class="navbar_item">
                        <a href="#">Customers</a>
                    </li>
                    <li class="navbar_item">
                        <a href="#">Pricng</a>
                    </li>
                    <li class="navbar_item">
                        <a href="#"> Resources</a>
                    </li>
                </ul>
                <div class="navbar_button">
                    <button class="button_1">Sign In</button>
                    <button class="button_2">Sign Up</button>
                </div>
            </nav>
            <!--/navbar-->
        </div>
    </header>
</template>
<script>
</script>
<style scoped>
/*navbar*/
.logo {
    width: 260px;
}

.logo img {
    width: 187px;
    height: 32px;
}

.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.navbar_items a {
    text-decoration: none;
    color: #2F281E;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 28px;
    transition: 0.3s;
    position: relative;
    text-transform: capitalize;
}

.nav a::before {
    content: '';
    position: absolute;
    bottom: -10px;
    left: 0;
    width: 0;
    height: 3px;
    background-color: #ff9900;
    transition: 0.5s;
}

.nav a:hover::before {
    width: 100%;
}

.navbar_items a:hover {
    color: #FF9900;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 28px;
}


.navbar_item {
    display: inline-block;
    padding: 15px;
}

.button_1 {
    box-sizing: border-box;
    Width: 102px;
    Height: 46px;
    border: 1px solid #BCD0E5;
    border-radius: 4px;
    font-size: 16px;
    font-family: 'Poppins';
    font-weight: 600;
    cursor: pointer;
    transition: 0.7s;
    color: #173A56;
}

.button_1:hover {
    border: 1px solid #BCD0E5;
    color: #FFFFFF;
    background: #173A56;
}

.button_2 {
    box-sizing: border-box;
    Width: 102px;
    Height: 46px;
    font-size: 16px;
    border-radius: 4px;
    border: none;
    background-color: #FF9900;
    font-family: 'Poppins';
    font-weight: 600;
    color: #FFFFFF;
    cursor: pointer;
    transition: 0.7s;
}

.button_2:hover {
    background: #FFFFFF;
    color: #FF9900;
    font-family: 'poppins';
    border: 1px solid #FF9900;
    font-size: 16px;
    font-weight: 700;
}

.navbar_button {
    display: flex;
    align-items: center;
    width: 220px;
    justify-content: space-between;
}

.h5_1 {
    height: 24px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    color: #544837;
}

.h5_2 {
    height: 26px;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 26px;
    color: #2F281E;
}
</style>