<template>
<div>
<h4>Messages</h4>
<ul v-for="(message,index) in messages" v-bind:key="index">
    <li>{{message}}</li>
    </ul>
</div> 
</template>
<script>
export default {
    data() {
      return {
        messages: ["hello", "hi", "its working"]
      }
}
}
</script>

