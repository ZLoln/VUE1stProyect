<script>
import { isIntegerKey } from '@vue/shared';

    export default {
        props: {
            movieTitle: String,
        },
        data(){
            return{
                brandChild: 'DC Comics',
            }
        },
        methods: {
            sendBrand(){
                this.$emit('brand', this.brandChild)
            }
        }
    }
</script>

<template>
    <h2>Hijita {{ movieTitle }}ita</h2>
    <button @click="sendBrand">Send Brand</button>
</template>

<style></style>