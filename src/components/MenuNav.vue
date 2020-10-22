<template>
<div>
    <logo></logo>
    <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    </div>
</div>

</template>

<script>

import Logo from './Logo'
export default {
    
    props:{

    },
    components:{
        Logo
    }
}
</script>

