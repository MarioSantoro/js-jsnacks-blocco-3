<template>
    <ul>
        <li v-for="list in List">{{ list.text }}
        </li>
    </ul>
</template>


<script>
export default {
    data() {
        return {
            List: [
                {
                    text: "Home"
                },
                {
                    text: "Chi siamo"
                },
                {
                    text: "Prodotti"
                },
                {
                    text: "Suona"
                },
                {
                    text: "Forza"
                },
                {
                    text: "Liguria"
                }
            ]
        }
    }
}
</script>
<style lang="scss">
@import "../styles/partials/mixins";
@import "../styles/partials/variables";
</style>