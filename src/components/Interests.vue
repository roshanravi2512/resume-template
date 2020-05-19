<template>
  <div class="details-container">
    <h4 class='title-header'>Interests</h4>
    <hr />
    <div class="interests-details">
        <div>Avid cross country skier and cyclist.</div>
        <div>Member of the Parent Teacher Association.</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Interests',
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

.interests-details {
    font-size: small;
    margin-left: 196px;
}

.interests-place {
    margin-top: 4px;
    margin-left: 196px;
}

.interests-description {
    font-size: small;
    margin-left: 172px;
    text-align: justify;
}

.interests-title {
    margin-left: 64px;
}
</style>