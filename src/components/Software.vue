<template>
  <div class="details-container">
    <h4 class='title-header'>Software</h4>
    <hr/>
    <div class="software-details">
        <div class='software-skill'>
            <div>Microsoft Project</div>
            <div class='skill-stars'>
                <div class='skill-star'></div>
                <div class='skill-star'></div>
                <div class='skill-star'></div>
                <div class='skill-star'></div>
                <div class='skill-star'></div>
            </div>
        </div>
        <div class='software-skill'>
            <div></div>
            <div>Excellent</div>
        </div>
        <div class='software-skill'>
            <div>Microsoft Excel</div>
            <div class='skill-stars'>
                <div class='skill-star'></div>
                <div class='skill-star'></div>
                <div class='skill-star'></div>
                <div class='skill-star-blur'></div>
                <div class='skill-star-blur'></div>
            </div>
        </div>
        <div class='software-skill'>
            <div></div>
            <div>Good</div>
        </div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Software',
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

.software-details {
    margin-left: 196px;
}

.skill-stars {
    display: flex;
}

.skill-star {
    width: 14px;
    height: 14px;
    background: black;
    margin: 0 1px;
}

.skill-star-blur {
    width: 14px;
    height: 14px;
    background: darkgrey;
    margin: 0 1px;
}

.software-skill {
    margin: 4px 0;
    display: flex;
    justify-content: space-between;
    font-size: small;
}
</style>
