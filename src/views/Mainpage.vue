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

    <!-- search bar -->
    <div class="py-6 text-center">
        <span>
            <InputText id="search" type="text" class="p-inputtext-lg shadow-2" style="width: 50%;" v-model="value" />
            <i class="pi pi-search px-3"></i>
        </span>
    </div>

    <!-- 1st floor -->
    <div class="relative text-left justify-text-center font-bold text-3xl pt-8">
        <a class="text-gray-900 first hover:text-primary-600" href="/mainpage">1ST FLOOR</a>
        <a class="text-gray-900 ml-8 hover:text-primary-600" href="">M FLOOR</a>
        <a class="text-gray-900 ml-8 hover:text-primary-600" href="">2ND FLOOR</a>
        <a class="text-gray-900 ml-8 hover:text-primary-600" href="">3RD FLOOR</a>

        <div class="cardbg mt-4 shadow-5">

            <!-- card loop -->
            <div class="grid justify-content-center">
                <div class="absolute w-10 h-11rem border-round-xl"
                    style="background-color: rgb(112, 130, 198); margin-top: 7%;"></div>
                <div class="cardone bg-primary w-20rem h-15rem border-round-2xl z-1 shadow-6">
                    <div class="absolute border-round-3xl" style="margin-left: 14.5%; margin-top: 10%;"><a href="/detail"><i
                                class="pi pi-search text-white"></i></a></div>
                </div>
                <div class="cardone bg-primary w-20rem h-15rem border-round-2xl z-1 shadow-6">
                    <div class="absolute border-round-3xl" style="margin-left: 14.5%; margin-top: 10%;"><a href="/detail"><i
                                class="pi pi-search text-white"></i></a></div>
                </div>
                <div class="cardone bg-primary w-20rem h-15rem border-round-2xl z-1 shadow-6">
                    <div class="absolute border-round-3xl" style="margin-left: 14.5%; margin-top: 10%;"><a href="/detail"><i
                                class="pi pi-search text-white"></i></a></div>
                </div>
                <div class="cardone bg-primary w-20rem h-15rem border-round-2xl z-1 shadow-6">
                    <div class="absolute border-round-3xl" style="margin-left: 14.5%; margin-top: 10%;"><a href="/detail"><i
                                class="pi pi-search text-white"></i></a></div>
                </div>
            </div>
            <div class="grid justify-content-center mt-8">
                <div class="absolute w-10 h-11rem border-round-xl"
                    style="background-color: rgb(112, 130, 198); margin-top: 7%;"></div>
                <div class="cardone bg-primary w-20rem h-15rem border-round-2xl z-1 shadow-6">
                    <div class="absolute border-round-3xl" style="margin-left: 14.5%; margin-top: 10%;"><a href=""><i
                                class="pi pi-search text-white"></i></a></div>
                </div>
                <div class="cardone bg-primary w-20rem h-15rem border-round-2xl z-1 shadow-6">
                    <div class="absolute border-round-3xl" style="margin-left: 14.5%; margin-top: 10%;"><a href=""><i
                                class="pi pi-search text-white"></i></a></div>
                </div>
                <div class="cardone bg-primary w-20rem h-15rem border-round-2xl z-1 shadow-6">
                    <div class="absolute border-round-3xl" style="margin-left: 14.5%; margin-top: 10%;"><a href=""><i
                                class="pi pi-search text-white"></i></a></div>
                </div>
                <div class="cardone bg-primary w-20rem h-15rem border-round-2xl z-1 shadow-6">
                    <div class="absolute border-round-3xl" style="margin-left: 14.5%; margin-top: 10%;"><a href=""><i
                                class="pi pi-search text-white"></i></a></div>
                </div>
            </div>

        </div>

    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter&display=swap');

* {
    font-family: 'Inter', sans-serif;
    margin: 0;
}

.cardbg {
    background-color: rgb(233, 238, 246);
    margin-left: 5%;
    margin-right: 5%;
    margin-bottom: 5%;
    border-radius: 15px;
    padding-top: 4%;
    padding-bottom: 4%;
}

.cardone {
    margin-left: 2%;
    margin-bottom: 5%;
}

.first {
    margin-left: 10%;
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

<script>
</script>