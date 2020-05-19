<template>
  <div class='details-container'>
  <h4 class='title-header'>Experience</h4>
  <hr />
  <div class='exp-details'>
    <div><b>2005-12 - present</b></div>
    <div class='exp-title'><b>Senior Project Manager</b></div>
  </div>
  <div class='exp-place'>Seton Hospital, ME</div>
  <div class='exp-description'>
    <ul>
        <li>Oversaw all major hospital IT projects for 10+ years, focus on cost reduction.</li>
        <li>Responsible for crewing, improving, and developing IT project strategies.</li>
        <li>Implemented the highly successful Lean Training and Six Sigma projects for all employees.</li>
        <li>Reduced the costs of IT infrastructure maintenance by 5% in 2015 by successfully rebuilding the infrastructure.</li>
    </ul>  
  </div>
  <div class='exp-details'>
    <div><b>2004-09 - 2006-12</b></div>
    <div class='exp-title'><b>Junior Project Manager</b></div>
  </div>
  <div class='exp-place'>Seton Hospital, ME</div>
  <div class='exp-description'>
    <ul>
    <li>Streamlined IT logistics and administration operation cutting costs by 25%.</li>
    <li>Diagnosed problems with hardware and operating systems and implemented solutions to increase efficiency.</li>
    <li>Maintained the user database of over 30000 patients, implemented new solutions inside the dashboard.</li>
    <li>Managed project for lean training for all IT Support Officers.</li>
    </ul>  
  </div>
</div>
</template>

<script>
export default {
  name: 'Experience',
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

.exp-details {
    display: flex;
}

.exp-place {
    margin-top: 4px;
    margin-left: 196px;
}

.exp-description {
    font-size: small;
    margin-left: 172px;
    text-align: justify;
}

.exp-title {
    margin-left: 64px;
}

</style>
