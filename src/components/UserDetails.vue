<template>
  <div class="details-container">
    <h3>John Smith</h3>
    <div id='user-title'>IT Project Manager</div>
    <div class='user-details'>
      <div id='user-phone'><b>Phone</b> 774-987-4009</div>
      <div id='user-linkedin'><b>Linkedln</b> Iinkedin.comljohnutw</div>
    </div>
    <div id='user-email'><b>E-mail</b> j.smith@uptowork.com</div>

    
    <div><p class='description'>IT Professional with over 10 years of experience specializing in IT department 
      management for international logistics companies. I can implement effective IT strategies 
      at local and global levels. My greatest strength is business awareness, which enables me to 
      permanently streamline infrastructure and applications. Looking to leverage my IT Management 
      skills at SanCorp Inc.</p></div>

  </div>
</template>

<script>
export default {
  name: 'UserDetails',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.details-container {
  width: 640px;
  margin: auto;
}

.user-details {
  display: flex;
  margin: 8px 0;
  font-size: small;
}

#user-linkedin {
  margin-left: 96px;
}

.description {
  font-size: small;
  text-align: justify;
}

#user-email {
  font-size: small;
}

</style>
