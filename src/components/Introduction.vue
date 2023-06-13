<script></script>

<template>
    <div class="h-screen w-full bg-slate-800 flex justify-center p-20 overflow-hidden">
        <div class="w-full">
            <div
                class="w-full h-52 bg-slate-600 rounded-3xl hover:bg-gradient-to-r hover:to-slate-700 hover:from-gray-700 hover:scale-105 flex items-center hover:text-red-600 text-slate-200">
                <img src="../assets/css3.png" class="h-full">
                <p class="text-3xl">CSS sucks. Css is unintuitive. Css Naming is hard. Css types are weird. Css
                    is no fun.</p>
            </div>
            <div class="grid grid-cols-3 items-center p-12">
                <div class="block p-6 bg-slate-700 border rounded-lg shadow-white m-8 h-full">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">CSS types are weird?
                    </h5>
                    <p class="font-normal text-gray-300 text-lg"> display: inline-block;
                        padding: 0.9rem 1.8rem;
                        font-size: 16px;
                        font-weight: 700;
                        color: white;
                        border: 3px solid rgb(252, 70, 100);
                        cursor: pointer;
                        position: relative;
                        background-color: transparent;
                        text-decoration: none;
                        overflow: hidden;
                        z-index: 1;
                        font-family: inherit;
                    </p>
                </div>
                <div class="block p-6 bg-slate-700 border rounded-lg shadow-white m-8 h-full">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Naming of CSS Classes
                        is weird</h5>
                    <p
                        class="font-normal text-lg bg-clip-text bg-gradient-to-r text-transparent from-green-600 to-lime-100">
                        navbar_button_icon1 <br>
                        navbar_content_center_new <br> navbar_icon_center <br> navbar_icon_button <br> navbar_home_button1
                        <br> navbar_button_home2
                    </p>
                </div>
                <div class="block p-6 bg-slate-700 border rounded-lg shadow-white m-8 h-full">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">CSS is painful</h5>
                    <p
                        class="font-normal text-lg bg-clip-text bg-gradient-to-r text-transparent to-red-600 from-orange-200">
                        Idea <br>
                        Write CSS <br> fail <br> retry <br> Google
                        <br> retry <br> fail <br> Copy-Paste Components
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>