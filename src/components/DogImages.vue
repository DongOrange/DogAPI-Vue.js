<script setup>
import { ref } from 'vue'
</script>

<template>
  <main>
    <section>
        <h1>狗狗生產器</h1>
        <div class="imgBox">
            <img class="img" src="">
        </div>
        <button class="btn">開始生產！</button>
    </section>
  </main>
</template>

<style scoped>
main{
    width: 100%;
    height: 100dvh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #eee;
    padding: 20px;
}
section{
    background-color: #fff;
    border-radius: 15px;
    box-shadow: 5px 5px 8px rgba(0,0,0,0.1);
    padding: 30px 40px;
    max-width: 400px;
    width: 100%;
}
h1{
    text-align: center;
    font-size: 30px;
    font-weight: bold;
    margin-bottom: 20px;
}
.imgBox{
    position: relative;
    border-radius: 10px;
    background-color: #eee;
    aspect-ratio: 1 / 1;
    margin-bottom: 30px;
}
.imgBox .img{
    position: absolute;
    inset:0;
    margin: auto;
    max-width: 100%;
    max-height: 100%;
    width: 100%;
}
.btn{
    background: #ff9500;
    border: none;
    border-radius: 10px;
    color: #fff;
    line-height: 42px;
    width: 140px;
    margin: auto;
    display: block;
    font-size: 16px;
}
</style>