<template>
    <section class="slider text-center position-relative">
        <div class="caption position-absolute top-50 start-50 translate-middle">
        <h3>design / development / photography</h3>
        <h1>creativity has new level</h1>
        <a class="btn career">preview</a>
        <a class="btn career">Get theme</a>
        </div>
    </section>
</template>

<style scoped>
    .slider{
        background-image: url('../assets/img/header.jpg');
        background-size: cover;
        height: 85vh;
        background-color: var(--second-color);
        background-blend-mode:multiply; 
        color: var(--white);
    }
    .slider .caption .career{
        color: var(--white);
        padding: 10px 20px;
        border: 3px solid var(--main-color);
        margin-left: 10px;
    } 
    .slider .caption .career:hover{
        background-color: var(--main-color);
        border-color:var(--second-color);
        transition: 1s all ease-in-out;
    }
</style>

<script>
export default{
    name:'homeComp'
}
</script>
