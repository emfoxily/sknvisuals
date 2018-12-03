<template>
    <nav>
        <img src="../assets/sknvisuals.png" alt="sknvisuals" />
        <ul class="links">
            <li>
                ABOUT
            </li>
            <li>
                CALENDAR
            </li>
            <li>
                BOOK ME
            </li>
            <li>
                CONTACT
            </li>
        </ul>
    </nav>
</template>

<script>
export default {
    name: 'Navigation',
}
</script>

<style scope>
    nav {
        position: fixed;
        background-color: #28AFB0;
        width: 100%;
        top: 0;
        left: 0;
    }
    nav img {
        width: 15%;
    }

    ul {
        display: flex;
        width: 100%;
        margin: 0 auto;
        background-color: #191919;
        color: #EEE5E5;
        list-style: none;
    }

    li {
        margin-right: 10vw;
    }
</style>
