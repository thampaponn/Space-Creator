<script>
import Navbar from '../components/Navbar.vue'
import CardItem from '../components/CardItem.vue'
export default {
    components: {
        Navbar,
        CardItem
    }
};
</script>

<template>
    <!-- navbar -->
    <Navbar></Navbar>

    <!-- 1st floor -->
    <div class="relative text-left justify-text-center font-bold text-3xl pt-8">
        <a class="thai first hover:text-primary-600 " style="color: rgb(35, 87, 165);" href="/mainpage">รายละเอียด</a>
        <a class="thai ml-8 hover:text-primary-600" style="color: rgb(35, 87, 165);" href="">รายการจอง</a>

        <div class="cardbg mt-4 shadow-5">

            <!-- card loop -->
            <div class="justify-content-center">
                <div class="cardone bg-primary w-5 h-30rem border-round-2xl z-1 shadow-6">
                    <div class="absolute border-round-3xl" style="margin-left: 14.5%; margin-top: 10%;"></div>
                </div>

            </div>
            <div class="absolute text-6xl font-bold" style="right: 35%; top: 28%;">
                Auditorium
            </div>
            <div class="bar"></div>
            <div class="thai text-black absolute" style="right: 41%; top: 40%;">รายละเอียด</div>

        </div>

    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Mitr&display=swap');


* {
    font-family: 'Inter', sans-serif;
    margin: 0;
}

.thai {
    font-family: 'Mitr', sans-serif;
}

.cardbg {
    background-color: rgb(233, 238, 246);
    margin-left: 10%;
    margin-right: 10%;
    margin-bottom: 5%;
    border-radius: 10px;
    padding-top: 4%;
    padding-bottom: 4%;
}

.cardone {
    margin-left: 2%;
    margin-bottom: 1%;
}

.bar {
    height: 0.5vh;
    width: 34vw;
    /* Position the rectangle in the center */
    position: absolute;
    top: 37%;
    left: 69%;
    background-color: #000;
    transform: translate(-50%, -50%);
}

.first {
    margin-left: 13%;
}

a:link {
    text-decoration: none;
}

a:visited {
    text-decoration: none;
}

a:hover {
    text-decoration: none;
}

a:active {
    text-decoration: none;
}
</style>
