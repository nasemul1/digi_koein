<script setup>

</script>

<template>
    <nav>
        <div>
            <div class="logo">
                <img src="../assets/logo.png" alt="logo">
                <p>DIGI KOEIN</p>
            </div>
        </div>
        <div></div>
    </nav>
</template>

<style scoped>
    .logo{
        display: flex;
        align-items: center;
    }
    .logo>img{
        width: 57px;
        margin-right: 8px;
    }
    .logo>p{
        font-size: 25px;
        font-weight: 700;
    }

    @media only screen and (max-width: 1024px){
        .logo>img{
            width: 44px;
            margin-right: 8px;
        }
        .logo>p{
            font-size: 16px;
            font-weight: 700;
        }
    }

    @media only screen and (max-width: 640px){
        .logo>img{
            width: 40px;
            margin-right: 8px;
        }
        .logo>p{
            font-size: 12px;
            font-weight: 700;
        }
    }
</style>