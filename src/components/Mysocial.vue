<template>
  <section>
    <div class="container">
      <button>SIGN-UP NOW!</button>

      <div>
      <div>FOLLOW US</div>
        <ul>
          <li><img src="../assets/img/footer-facebook.png" alt="facebook"></li>
          <li><img src="../assets/img/footer-twitter.png" alt="twitter"></li>
          <li><img src="../assets/img/footer-youtube.png" alt="youtube"></li>
          <li><img src="../assets/img/footer-pinterest.png" alt="pinterest"></li>
          <li><img src="../assets/img/footer-periscope.png" alt="periscope"></li>
        </ul>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: 'Mysocial',
  
}
</script>

<style scoped lang="scss">
    section {
        height: 100px;
        background-color: #202020;
        .container {
          height: 100px;
          display: flex;
          justify-content: space-between;
          width: 80%;
          margin: auto;
        }
        button {
            font-size: 14px;
            border: 2px solid #1594fc;
            background-color: transparent;
            color: white;
            padding: 10px;
        }
        div {
            display: flex;
            align-items: center;
            margin-right: 20px;
            color: #1594fc;
            text-transform: uppercase;
            font-weight: bold;
        }
        ul {
            display: flex;
            align-items: center;
            li {
                display: inline-block;
                margin-right: 20px;   
            }
        }
    }
</style>