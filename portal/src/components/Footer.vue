<template>
    <div>
        <div class = "logo">
            <img :src="logoubt"/>

        </div>
        <div class="menu">
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Lajmet</li>
                <li>Contact</li>
            </ul>
        </div>
        
    <h2>Footer</h2>
    </div>
</template>
<script>
export default {
    name: 'Footer',
    data:function(){
        return{
            logoubt:"https://www.ubt-uni.net/wp-content/themes/university-of-business-and-technology/repository/logo.png"
        }
    }
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
