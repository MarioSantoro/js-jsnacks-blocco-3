<template>
    <header>
        <ul>
            <li v-for="list in List">{{ list.text }}
            </li>
        </ul>
    </header>
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
@use "../styles/partials/mixins" as *;
@use "../styles/partials/variables" as *;

header {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;

    ul {
        display: flex;
        list-style-type: none;
    }
}
</style>