<script>
import SignupButton from './SignupButton.vue';
export default {
    components: {
        SignupButton
    }
}
</script>


<template>
    <!-- navbar -->
    <div>
        <header>
            <div class="card">
                <div class="flex flex-wrap card-container">
                    <div>
                        <img class="absolute z-0 w-full" src="src/assets/img/navbar.png" alt="">
                    </div>
                    <!-- home -->
                    <div class="z-1">
                        <a class="text-white font-bold flex align-items-center justify-content-left ml-4"
                            style="min-width: 200px; min-height: 100px" href="./mainpage"><img
                                src="../assets/img/logonavbar.png" class="h-4rem" alt=""></a>
                    </div>

                    <!-- space -->
                    <div class="text-white font-bold flex align-items-center justify-content-center"
                        style="min-width: 200px; min-height: 100px"></div>
                    <div class="text-white font-bold flex align-items-center justify-content-center"
                        style="min-width: 200px; min-height: 100px"></div>
                    <div class="text-white font-bold flex align-items-center justify-content-center"
                        style="min-width: 200px; min-height: 100px"></div>
                    <div class="text-white font-bold flex align-items-center justify-content-center"
                        style="min-width: 200px; min-height: 100px"></div>
                    <div class="text-white font-bold flex align-items-center justify-content-center"
                        style="min-width: 200px; min-height: 100px"></div>
                    <div class="text-white font-bold flex align-items-center justify-content-center"
                        style="min-width: 200px; min-height: 100px"></div>

                    <!-- history -->
                    <a class="z-1 bg-transparent text-white border-round-3xl ml-6 my-4 text-2xl font-bold flex align-items-center justify-content-center"
                    style="min-width: 125px; min-height: 25px" href="/history"> <i class="pi pi-history mr-2"></i>
                    History</a>

                    <!-- username -->
                    <a class="z-1 bg-transparent text-white border-round-3xl ml-6 my-4 text-2xl font-bold flex align-items-center justify-content-center"
                    style="min-width: 125px; min-height: 25px" href="/history"> <i class="pi pi-user mr-2"></i>
                    USERNAME</a>

                    <!-- login button -->
                    <!-- <a class="z-1 bg-white text-primary-800 border-round-3xl ml-6 my-4 text-xl font-bold flex align-items-center justify-content-center shadow-5 hover:bg-bluegray-100"
                                            style="min-width: 125px; min-height: 25px" href="./">Log
                                            in</a> -->

                    <!-- sign up button -->
                    <!-- <a class="z-1 bg-primary-600 text-white border-round-3xl ml-4 my-4 text-xl font-bold flex align-items-center justify-content-center shadow-5 hover:bg-primary-700"
                                        style="min-width: 125px; min-height: 25px" href="./signup">Sign
                                        up</a> -->

                </div>
            </div>


        </header>
    </div>
</template>
