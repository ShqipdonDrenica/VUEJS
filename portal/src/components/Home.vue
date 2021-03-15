<template>
    <div>
        <div class = "logo">


        </div>
        <div class="menu">
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Lajmet</li>
                <li>Contact</li>
            </ul>
        </div>
        <h2>Hello world - from  Home Component</h2>
    </div>
</template>
<script>
export default {
    name: 'Home'
}
</script>
<style scope>
    .logo{
        float:left;
    }
    .menu{
        float:right;
    }
   .menu ul {
       list-style-type: none;
    }
     .menu ul li {
         display: inline;
    }

</style>
