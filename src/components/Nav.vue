<template>
    <div class="navbar">
        <div class="navbar-start">
            <div class="navbar-brand">
                <a class="navbar-item" href="/">
                    <img src="../assets/img/GM.svg" alt="" width="115">
                </a>
            </div>
        </div>

        <div class="navbar-end navbar-menu">
            <a class="navbar-item is-size-7 has-text-weight-bold has-text-dark">
                | hello@greatest.media |
            </a>
        </div>
    </div>
</template>


<script>
    export default {
        name: 'Nav',
        data: function () {
            return {
                showNav: false
            }
        }

    }
</script>