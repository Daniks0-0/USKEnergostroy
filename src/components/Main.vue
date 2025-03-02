<script setup>
const ArrayAbout = ["ЮСК ЭнергоСтрой осуществляет комплексную реализацию проектов в области энергетики, вентиляции, а также наружных и внутренних инженерных сетей под ключ. Мы предлагаем решения, которые сочетают в себе надежность, инновации и индивидуальный подход к каждому клиенту. "];



</script>

<template>
    <div class="back">
        <div class="card">
<!-- черная основа для картинки и текста -->
            <div class="card__base">
                <div class="text">
                    <h1>ЮСК ЭнергоCтрой</h1>
                    <p>Комплексные решения для строительства энергетической инфраструктуры и систем вентиляции</p>
                    <a href="">Подробнее </a>

                </div>
                <div class ="img-fon">
                    <img src="@/assets/images/mainImg.png" alt="">

                </div>


            </div>

        </div>
        <div class="about">
            <h1>
                ЮСК ЭнергоCтрой
            </h1>
            <p v-for=" (text, index) in ArrayAbout" :key="index" class="about__text">{{ text }}</p>

        </div>

    </div>


</template>

<style scoped lang="scss">
.back{
    background: #065B4C;
    display: flex;
    flex-direction: column;

    .card{

    }

    .about{

    }
}

</style>