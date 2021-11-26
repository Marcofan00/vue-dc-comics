<template>
  <div class="footer">
      <div class="navbars">
          <section class="navbar">
              <nav>
                  <h4>DC COMICS</h4>
                  <ul>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Comics</a>
                      </li>
                      <li>
                          <a href="#">Movies</a>
                      </li>
                      <li>
                          <a href="#">TV</a>
                      </li>
                      <li>
                          <a href="#">Games</a>
                      </li>
                      <li>
                          <a href="#">Videos</a>
                      </li>
                      <li>
                          <a href="#">News</a>
                      </li>
                  </ul>
              </nav>
              <nav>
                  <h4>SHOP</h4>
                  <ul>
                      <li>
                          <a href="#">Shop Dc</a>
                      </li>
                      <li>
                          <a href="#">Shop Dc Collectibles</a>
                      </li>
                  </ul>
              </nav>
          </section>
          <section class="navbar">
              <nav>
                  <h4>DC</h4>
                  <ul>
                      <li>
                          <a href="#">Terms Of Use</a>
                      </li>
                      <li>
                          <a href="#">Privacy policy (New)</a>
                      </li>
                      <li>
                          <a href="#">Ad Choices</a>
                      </li>
                      <li>
                          <a href="#">Advertising</a>
                      </li>
                      <li>
                          <a href="#">Jobs</a>
                      </li>
                      <li>
                          <a href="#">Subscriptions</a>
                      </li>
                      <li>
                          <a href="#">Talent Workshops</a>
                      </li>
                      <li>
                          <a href="#">CPSC Certificates</a>
                      </li>
                      <li>
                          <a href="#">Rating</a>
                      </li>
                      <li>
                          <a href="#">Shop help</a>
                      </li>
                      <li>
                          <a href="#">Contact Us</a>
                      </li>
                  </ul>
              </nav>
          </section>
          <section class="navbar">
              <nav>
                  <h4>SITES</h4>
                  <ul>
                      <li>
                          <a href="#">DC</a>
                      </li>
                      <li>
                          <a href="#">MAD Magazine</a>
                      </li>
                      <li>
                          <a href="#">DC Kids</a>
                      </li>
                      <li>
                          <a href="#">DC Universe</a>
                      </li>
                      <li>
                          <a href="#">DC Power Visa</a>
                      </li>
                  </ul>
              </nav>
          </section>
      </div>
      <div class="logo_dc">
          <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
  </div>
</template>
<script>
export default {
  name: 'Myfooter'
}
</script>
<style scoped lang="scss">
    .footer {
        font-size: .8em;
        display: flex;
        justify-content: space-around;
        align-items: center;
        width: 100%;
        height: 400px;
        background-color: grey;
        background-image: url("../assets/img/footer-bg.jpg");
        .navbars {
            display: flex;
            nav {
                margin: 0 20px;
                h4 {
                    color: white;
                    margin-left: 40px;
                }
                ul> li  {
                    list-style: none;
                    margin-bottom: 5px;
                    a {
                        text-decoration: none;
                        color: grey;
                        &:hover {
                            color: white;
                        }
                    }
                }
            }
        }
        .logo_dc {
            height: 100%;
            img {
                width: 70%;
            }
        }
    }
</style>