<template>
    <nav>
        <ul class="links">
            <li>
                ABOUT
            </li>
            <li>
                PORTFOLIO
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
        background-color: #191919;
        width: 100%;
        padding: 1em;
        margin: 0 auto;
        top: 0;
        left: 0;
        box-shadow: 2px 2px 25px #000;
    }

    ul {
        width: 100%;
        margin: 0 auto;
        color: #EEE5E5;
        list-style: none;
    }

    li {
        display: inline-block;
        margin-right: 10vw;
    }
</style>
