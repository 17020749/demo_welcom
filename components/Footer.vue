<template>
  <div>
    <footer>
      <div>
        <div class="sizeOfGetapp">Get The App</div>

        <img
          src="../static/img/chplay.png"
          alt="Error. Cannot show photos"
          class="imgChPlay"
        />

        <img
          src="../static/img/app-store.png"
          alt="Error. Cannot show photos"
          class="imgAppStore"
        />
      </div>
      <br />
      <hr />
      <br />
      <!-- 3 part  -->
      <div class="flexFooter">
        <div>
          <img
            src="../static/img/logoFooter.png"
            class="logoFooter"
            alt="Error. Cannot show logo"
          />
        </div>
        <div class="middleChildFlext">
          <h3 class="middleOfLogoFT">Contact</h3>
          <br />
          <span class="middleOfLogoFT">abcdef@onme.com.vn</span>
          <br />
          <span class="middleOfLogoFT">abcdef@onme.com.vn</span>
          <br />

          <span class="middleOfLogoFT">abcdef@onme.com.vn</span>
          <br />

          <span class="middleOfLogoFT">abcdef@onme.com.vn</span>
        </div>
        <div class="rightChildFlext">
          <h3 class="rigthOfLogoFT">Legal</h3>
          <br />

          <span class="rigthOfLogoFT">Teamn of Service</span>
          <br />
          <span class="rigthOfLogoFT">Privacy Policy</span>
          <br />
          <br />
          <br />
          <br />
        </div>
      </div>

      <div>
        <br />
        <br />
        <br />
        <div class="endFlext">
          <p class="endOfFooter">@2022 Onme</p>
        </div>
        <br />
        <br />
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style >
table {
  margin: auto;
}
hr {
  width: 1000%;
}
/* text: get the App*/
.sizeOfGetapp {
  font-size: 40px;
  color: black;
  font-weight: bold;
  text-align: center;
}

/* img: ChPlay*/
.imgChPlay {
  height: 60px;
  width: 200px;
  margin-left: 450px;
  margin-right: 10px;
}

/* img: AppStore*/
.imgAppStore {
  height: 60px;
  width: 200px;
  margin-right: 10px;
  margin-left: 10px;
}
/* logo - left - right*/
.logoFooter {
  height: 200px;
  width: 200px;
  /*margin-left: 320px;
  margin-right: 10px;*/
}
/* Flex */
.flexFooter {
  display: flex;

}
.flexFooter > div{
  position: relative;
  left: 325px;
  top: 15px;
}
.middleChildFlext{
  margin-left:80px;
}
.rightChildFlext{
margin-left:80px;
}
.endOfFooter
{
  text-align:right;
  margin-left:100px;
}
/* logo -mid - right*/

/* logo - FT - right*/

/* text

*/
</style>

