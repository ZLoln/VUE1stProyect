<script>
    export default {
        data () {
            return {
                listCountry: ['spain', 'france', 'italy'],
            }
        },
    };
</script>

<template>
    <div>
        <h3>v-for directive -----------------</h3>
        <ul>
            <template v-for="(country, key) in listCountry" :key="key">
                <li :id="[key + 1]">{{ key + 1 }}: {{ country }}</li>
            </template>
        </ul>
    </div>
</template>

<style></style>