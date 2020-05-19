<template>
  <div class='details-container'>
  <h4 class='title-header'>Education</h4>
  <hr />
  <div class='edu-details'>
    <div><b>1996-09 - 2001-05</b></div>
    <div class='edu-place'><b>Master of Computer Science, University of Maryland</b></div>
  </div>
  <div class='edu-description'>
    <ul>
        <li>Graduated Summa Cum Laude.</li>
        <li>Andersen Postgraduate Fellowship to study advanced nursing techniques.</li>
        <li>Managed a student project to develop a weekly nursing podcast.</li>
    </ul>
  </div>
  </div>
</template>

<script>
export default {
  name: 'Education',
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

.edu-details {
    display: flex;
}

.edu-place {
    margin-left: 60px;
}

.edu-description {
    font-size: small;
    margin-left: 172px;
    text-align: justify;
}

.edu-title {
    margin-left: 64px;
}

</style>
