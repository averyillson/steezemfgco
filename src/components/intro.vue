<template>
  <div class="container">
    <div class="row">
      <div  class="col-10">
        <div class="col-8">
          Steeze MFG Co.
        </div>
        <div class="row">
          <div class="col-6">
            <p>Steeze Mfg Co. is a small workshop that focused on helping independent fashion brands. We help by stepping in at the various levels where needed in the fashion pipeline.</p>
            <p>Do you have great ideas but lack execution? Hit us up. Do you have great products but can’t get the finer details or pieces produced? Hit us up. Do you have a garage full of stock but nobody to push it to? Hit us up.</p>
          </div>
          <div class="col-6">
            <p>We understand that sometimes you need to extend your team to achieve the goal. That’s where we step in. You know the target audience, the customers and the goals. We’re here to help you achieve those. Born out of the love for t-shirt illustrations we set out to help independent clothing brands either local or not.</p>
            <p>Let us use our technical and creative skills to empower you brand.</p>
          </div>
        </div>
      </div>
    </div>

    <div class="hero" style="background-image: url('https://picsum.photos/800/800?grayscale')">

    </div>
  </div>
</template>

<script>
export default {
  name: 'Intro',
  props: {
    msg: String
  }
}
</script>


<style scoped>
  .hero {
    width: 800px;
    height: 800px;
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
    //position: absolute;
    //z-index: -100;
  }

  p {
    text-align: left;
  }
</style>
