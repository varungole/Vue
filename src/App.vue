<template>

<p>Simple text</p>

</template>

<script>
export default {
    data() {
        return {
            activePage: 0,
            pages: [
                {
                    link: {text: 'Home', url: 'index.html'},
                    pageTitle: 'Home Page'
                },
                 {
                    link: {text: 'About', url: 'about.html'},
                    pageTitle: 'About Page'
                }

            ]
        }
    }
}
</script>