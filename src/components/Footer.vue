<template>
    <!-- FOOTER -->
    <footer class="container">
        <p class="float-end"><a href="#">Back to top</a></p>
        <p>&copy; Susana Piñero - {{ year }} &middot; <a href="#">Privacy</a> &middot; <a href="#">Terms</a></p>
    </footer>
</template>

<script>
export default {
    computed: {
        year() {
            return new Date().getFullYear();
        }
    }
}
</script>