<template>
  <div id="app">
    <footer>
        <div class="top_footer">
            <div class="container">
                <div class="footer_left">
                            <div class="first_column_footer">
                                <h3>dc comics</h3>
                                <ul>
                                    <li>Characters</li>
                                    <li>Comics</li>
                                    <li>Movies</li>
                                    <li>TV</li>
                                    <li>Games</li>
                                    <li>Videos</li>
                                    <li>News</li>
                                </ul>
                                <h3>shop</h3>
                                <ul>
                                    <li>Shop DC</li>
                                    <li>Shop DC Collectables</li>
                                </ul>
                            </div>
                            <div class="second_column_footer">
                                <h3>dc</h3>
                                <ul>
                                    <li>Terms Of Use</li>
                                    <li>Privacy Policy</li>
                                    <li>Ad Choices</li>
                                    <li>Advertising</li>
                                    <li>Jobs</li>
                                    <li>Subscription</li>
                                    <li>Talent Workshop</li>
                                    <li>CPSC Certificates</li>
                                    <li>Ratings</li>
                                    <li>Shop Help</li>
                                    <li>Contact Us</li>
                                </ul>
                            </div>
                            <div class="third_column_footer">
                                <h3>sites</h3>
                                <ul>
                                    <li>DC</li>
                                    <li>MAD Magazine</li>
                                    <li>DC Kids</li>
                                    <li>DC Universe</li>
                                    <li>DC Power Visa</li>
                                </ul>
                            </div>
                </div>

                <img src="../assets/img/dc-logo-bg.png" class="big_logo" alt="logo big">
            </div>
        </div>

        <div class="footer_banner">
            <div class="container">
                <a href="#">sign-up now!</a>
                <div>
                    <h3>follow us</h3>
                    <div>
                        <img src="../assets/img/footer-facebook.png" alt="fb">
                        <img src="../assets/img/footer-twitter.png" alt="twitter">
                        <img src="../assets/img/footer-youtube.png" alt="yt">
                        <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                        <img src="../assets/img/footer-periscope.png" alt="periscope">
                    </div>
                </div>
            </div>
        </div>
        
    </footer>
  </div>
</template>

<script>

export default {
  name: 'Footer',
}
</script>

<style lang="scss" scoped>
    .container {
        position: relative;
        width: 70%;
        height: 100%;
        margin: auto;

        li {
            list-style: none; 
            font-size: 13px;
        }
        h3 {
            text-transform: uppercase;
            margin: 10px 0 10px 0;
        }

        .big_logo {
            height: 500px;
            position: absolute;
            right: 0px;
            top: -80px;
            z-index: 0;
        }

    }

    .top_footer {
            display: flex;
            justify-content: space-between;
            color: white;
            
            background-image: url('../assets/img/footer-bg.jpg');
        }

    .footer_left {
        display: flex;

        div {
            margin: 25px;
        }
    }

    footer  {
        height: 400px;
    }

    .footer_banner {
        height: 130px;
        width: 100%;
        z-index: 2;
        position: relative;
        background-color: #1c1c1c;
        
        .container {
            display: flex;
            justify-content: space-between;
            align-items: center;

            div {
                display: flex;
                align-items: center;

                h3 {
                    margin-right: 15px;
                }
            }
        }
        
        a {
            padding: 10px;
            text-transform: uppercase;
            text-decoration: none;
            border: 2px solid #0282f9;
            color: white;
        }

        h3 {
            color: #0282f9;
        }

        img {
            margin: 10px;
            height: 40px;
            cursor: pointer; 
        }
    
    }

</style>