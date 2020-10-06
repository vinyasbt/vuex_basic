<template>
    <div>
        {{count}}
        <button @click="increment()">+</button>
        <button @click="decrement()">-</button>
    </div>
</template>
<script>
export default {
    name:"counte",
   
    methods:{
        increment(){
            this.$store.commit("increment")
        },
         decrement(){
            this.$store.commit("decrement")
        }
    },
    computed:{
        count(){
            return this.$store.state.count
        }
    }
}
</script>