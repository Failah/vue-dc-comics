<template>
  <div class="container">
    <header>
        <div id="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>

        <nav>
            <ul>
                <li v-for="link in navLinks" :key="link.title">
                    <a :href="link.link" :class="{ active: link.active }">{{ link.title }}</a>
                </li>
            </ul>
        </nav>

    </header>
  </div>
</template>

<script>
export default {
name: 'HeaderComponent',

data(){
    return {
        navLinks: [
            {
                title: 'Characters',
                link: '#',
                active: false,
            },
            {
                title: 'Comics',
                link: '#',
                active: true,
            },
            {
                title: 'Movies',
                link: '#',
                active: false,
            },
            {
                title: 'TV',
                link: '#',
                active: false,
            },
            {
                title: 'Games',
                link: '#',
                active: false,
            },
            {
                title: 'Collectibles',
                link: '#',
                active: false,
            },
            {
                title: 'Videos',
                link: '#',
                active: false,
            },
            {
                title: 'Fan',
                link: '#',
                active: false,
            },
            {
                title: 'News',
                link: '#',
                active: false,
            },
            {
                title: 'Shop',
                link: '#',
                active: false,
            },
        ]
    }
}
}
</script>

<style lang="scss" scoped>

@import '../styles/variables.scss';

header {
    display: flex;
    justify-content: space-between;
}

#logo {
    width: 80px;
    margin: 20px 0px;

    img {
        vertical-align: middle;
    height: 100%;
    }
}

ul {
    list-style-type: none;
    height: 100%;
    display: flex;

    li {
    height: 100%;
    padding: 0px 10px;
    font-weight: bold;

        a {
    text-decoration: none;
    text-transform: uppercase;
    color: #443c32;
    display: flex;
    align-items: center;
    height: 100%;
    &.active {
        border-bottom: 2px solid $dc-brand-color;
        color: #309efb;
    }
}
}
}

</style>