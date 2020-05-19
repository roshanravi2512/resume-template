<template>
  <div class="details-container">
  <h4 class='title-header'>Skills</h4>
  <hr />
  <div class='skill-details'>
  <div><b>Business Process Improvement - </b>history of successful innovations leading to cost savings</div>
  <div><b>Vendor Management - </b>proven track record of managing vendors in projects with budgets of over S1'000'000</div>
  <div><b>Project Scheduling - </b>over 90% of projects led were finished in due time</div>
  <div><b>Sales Analysis - </b>background in IT Sales with deep understanding of negotiating contracts</div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'Skills',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.details-container {
    width: 640px;
    margin: auto;
}

.title-header {
    margin-bottom:0;
}

.skill-details {
    font-size: small;
    margin-left: 196px;
    text-align: justify;
}

.skill-place {
    margin-top: 4px;
    margin-left: 196px;
}

.skill-description {
    font-size: small;
    margin-left: 172px;
    text-align: justify;
}

.skill-title {
    margin-left: 64px;
}

</style>