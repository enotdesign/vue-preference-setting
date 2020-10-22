<template>
    <article>
        <h2>ww</h2>
        <form action="">
            <input type="text" placeholder="correo electronico">
            <input type="submit" value="enviar">
        </form>
    </article>
</template>

<script>
    export default {
        name:"LocalForm",
        props:{

        }
    }
</script>

<style lang="scss" scoped>
article *{
    box-sizing: border-box;
}

h2{
    margin-bottom: 0;
}

form{
    padding: 20px;
    
}
input{
    width:100%;
    margin: 10px 0;
    padding: 10px;
}

</style>