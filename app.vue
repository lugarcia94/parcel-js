new Vue({
  el: '#app',
  methods: {
    log: function (e) {
      console.log(e.currentTarget);
      console.log(e);
    } 
  }
});