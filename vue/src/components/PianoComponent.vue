<template>
    <ul class="set">
        <li class="white c"></li>
        <li class="black db"></li>
        <li class="white d"></li>
        <li class="black eb"></li>
        <li class="white e"></li>
        <li class="white f"></li>
        <li class="black gb"></li>
        <li class="white g"></li>
        <li class="black ab"></li>
        <li class="white a"></li>
        <li class="black bb"></li>
        <li class="white b"></li>
        <li class="white c"></li>
    </ul>
</template>

<script>

</script>

<style scoped>

* {
  box-sizing: border-box;
}

ul {
  list-style-type: none;
  background-color: transparent;
  margin: 0;
  padding: 0;
}

li {
  margin: 0;
  padding: 0;
  list-style: none;
  position: relative;
  float: left;
  box-shadow:0 0 50px rgba(0,0,0,0.5) inset,0 1px rgba(212,152,125,0.2) inset,0 5px 15px rgba(0,0,0,0.5);

}

.white {
  height: 24em;
  width: 6em;
  z-index: 1;
  border-left:1px solid #bbb;
  border-bottom:1px solid #bbb;
  border-radius:0 0 5px 5px;
  box-shadow:-1px 0 0 rgba(255,255,255,0.8) inset,0 0 5px #ccc inset,0 0 3px rgba(0,0,0,0.2);
  background:linear-gradient(to bottom,#eee 0%,#fff 100%)
}

.white:hover {
  border-top:1px solid #777;
  border-left:1px solid #999;
  border-bottom:1px solid #999;
  box-shadow:2px 0 3px rgba(0,0,0,0.1) inset,-5px 5px 20px rgba(0,0,0,0.2) inset,0 0 3px rgba(0,0,0,0.2);
  background:linear-gradient(to bottom,#fff 0%,#e9e9e9 100%)
}

.black {
  height: 16em;
  width: 4em;
  margin: 0 0 0 -2em;
  z-index:2;
  border:1px solid #000;
  border-radius:0 0 3px 3px;
  box-shadow:-1px -1px 2px rgba(255,255,255,0.2) inset,0 -5px 2px 3px rgba(0,0,0,0.6) inset,0 2px 4px rgba(0,0,0,0.5);
  background:linear-gradient(45deg,#222 0%,#555 100%)
}

.black:hover {
  box-shadow:-1px -1px 2px rgba(255,255,255,0.2) inset,0 -2px 2px 3px rgba(0,0,0,0.6) inset,0 1px 2px rgba(0,0,0,0.5);
  background:linear-gradient(to right,#444 0%,#222 100%)
}

.g,.a,.b,.d,.e {
  margin: 0 0 0 -2em
}

ul li:first-child {
  border-radius:5px 0 5px 5px
}

ul li:last-child {
  border-radius:0 5px 5px 5px
}

</style>
