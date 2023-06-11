
<template>
    <div>
      <div class="icecream" id="icecream">
        <p class="cone"></p>
        <div
          class="scoop"
          v-for="cartItem in cart"
          :class="cartItem.name.toLowerCase()"
        ></div>
        <div class="cherry" v-if="cart.length > 0"></div>
        <div class="question" v-else></div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      cart: {
        type: Array,
        required: true,
      },
    },
  };
  </script>
  
  <style scoped>
  .icecream {
    /* Add your styles for the ice cream container */
  }
  
  .cone {
    /* Add your styles for the ice cream cone */
  }
  
  .scoop {
    /* Add your styles for the ice cream scoops */
  }
  
  .cherry {
    /* Add your styles for the cherry */
  }
  
  .question {
    /* Add your styles for the question mark (when cart is empty) */
  }
  </style>
  
  
  
  