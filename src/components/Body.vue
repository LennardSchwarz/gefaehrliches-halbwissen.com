<template>
  <div>
    <h1>gefährliches halbwissen.</h1>
    
    <!-- Button -->
    <form>
      <button class="button-18" v-on:click="rickroll()">Bilde dich</button>
    </form>


  </div>
</template>

<script>

export default {
  name: "Body",

  methods: {
  // opens a rickroll youtube video
  rickroll () {
    window.open(
      "https://www.youtube.com/watch?v=dQw4w9WgXcQ", "_blank"
      );
    }
  },
  mounted() {
    // methods can be called in lifecycle hooks, or other methods!
    this.rickroll()
  }
};



// TODO: fix button
// function rickroll() {
//         document.getElementById("youtube_video").innerHTML = '<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ?controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>';


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 40px 0 0;
  color: #854442;
;
}

h3 {
  margin: 10px 0 0;
  color: #854442;
}

/* CSS */
.button-18 {
  align-items: center;
  background-color: #854442;
  border: 0;
  border-radius: 100px;
  box-sizing: border-box;
  color: #ffffff;
  cursor: pointer;
  display: inline-flex;
  font-family: -apple-system, system-ui, system-ui, "Segoe UI", Roboto, "Helvetica Neue", "Fira Sans", Ubuntu, Oxygen, "Oxygen Sans", Cantarell, "Droid Sans", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Lucida Grande", Helvetica, Arial, sans-serif;
  font-size: 16px;
  font-weight: 600;
  justify-content: center;
  line-height: 20px;
  max-width: 480px;
  min-height: 40px;
  min-width: 0px;
  overflow: hidden;
  padding: 0px;
  padding-left: 20px;
  padding-right: 20px;
  text-align: center;
  touch-action: manipulation;
  transition: background-color 0.167s cubic-bezier(0.4, 0, 0.2, 1) 0s, box-shadow 0.167s cubic-bezier(0.4, 0, 0.2, 1) 0s, color 0.167s cubic-bezier(0.4, 0, 0.2, 1) 0s;
  user-select: none;
  -webkit-user-select: none;
  vertical-align: middle;
  margin: 15px 0 0;
}

.button-18:hover,
.button-18:focus { 
  background-color: #854442;
  color: #ffffff;
}

.button-18:active {
  background: #854442;
  color: rgb(255, 255, 255, .7);
}

.button-18:disabled { 
  cursor: not-allowed;
  background: rgba(0, 0, 0, .08);
  color: rgba(0, 0, 0, .3);
}

.body {
  margin: 200px auto;
  text-align: center;
  padding: 20px 20px;
  border-radius: 8px;
  max-width: 600px;
}
</style>
