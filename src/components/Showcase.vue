<template>
    <div class="w-full h-screen bg-slate-700 grid grid-cols-2 grid-rows-2   ">
        <div class="space-y-4 h-1/2 p-12">
            <div class="w-96 bg-white shadow rounded">
                w-96
            </div>
            <div class="w-80 bg-white shadow rounded">
                w-80
            </div>
            <div class="w-72 bg-white shadow rounded">
                w-72
            </div>
            <div class="w-64 bg-white shadow rounded">
                w-64
            </div>
            <div class="w-60 bg-white shadow rounded">
                w-60
            </div>
            <div class="w-56 bg-white shadow rounded">
                w-56
            </div>
            <div class="w-52 bg-white shadow rounded">
                w-52
            </div>
            <div class="w-48 bg-white shadow rounded">
                w-48
            </div>
        </div>
        <div class="grid grid-rows-4 h-min gap-4 p-12">
            <div class="grid grid-cols-10 gap-2">
                <div class="bg-sky-50 aspect-square"></div>
                <div class="bg-sky-100 aspect-square"></div>
                <div class="bg-sky-200 aspect-square"></div>
                <div class="bg-sky-300 aspect-square"></div>
                <div class="bg-sky-400 aspect-square"></div>
                <div class="bg-sky-500 aspect-square"></div>
                <div class="bg-sky-600 aspect-square"></div>
                <div class="bg-sky-700 aspect-square"></div>
                <div class="bg-sky-800 aspect-square"></div>
                <div class="bg-sky-900 aspect-square"></div>
            </div>
            <div class="grid grid-cols-10 gap-2">
                <div class="bg-blue-50 aspect-square"></div>
                <div class="bg-blue-100 aspect-square"></div>
                <div class="bg-blue-200 aspect-square"></div>
                <div class="bg-blue-300 aspect-square"></div>
                <div class="bg-blue-400 aspect-square"></div>
                <div class="bg-blue-500 aspect-square"></div>
                <div class="bg-blue-600 aspect-square"></div>
                <div class="bg-blue-700 aspect-square"></div>
                <div class="bg-blue-800 aspect-square"></div>
                <div class="bg-blue-900 aspect-square"></div>
            </div>
            <div class="grid grid-cols-10 gap-2">
                <div class="bg-indigo-50 aspect-square"></div>
                <div class="bg-indigo-100 aspect-square"></div>
                <div class="bg-indigo-200 aspect-square"></div>
                <div class="bg-indigo-300 aspect-square"></div>
                <div class="bg-indigo-400 aspect-square"></div>
                <div class="bg-indigo-500 aspect-square"></div>
                <div class="bg-indigo-600 aspect-square"></div>
                <div class="bg-indigo-700 aspect-square"></div>
                <div class="bg-indigo-800 aspect-square"></div>
                <div class="bg-indigo-900 aspect-square"></div>
            </div>
            <div class="grid grid-cols-10 gap-2">
                <div class="bg-violet-50 aspect-square"></div>
                <div class="bg-violet-100 aspect-square"></div>
                <div class="bg-violet-200 aspect-square"></div>
                <div class="bg-violet-300 aspect-square"></div>
                <div class="bg-violet-400 aspect-square"></div>
                <div class="bg-violet-500 aspect-square"></div>
                <div class="bg-violet-600 aspect-square"></div>
                <div class="bg-violet-700 aspect-square"></div>
                <div class="bg-violet-800 aspect-square"></div>
                <div class="bg-violet-900 aspect-square"></div>
            </div>
        </div>
        <div class=" flex items-center justify-center gap-14    ">
            <button class="bg-green-500">Colors</button>
            <button class="bg-cyan-500 shadow-lg shadow-cyan-500/50">Shadows</button>
            <button class="bg-red-500 shadow-lg shadow-red-500/50 w-24">Sizes</button>
            <button class="bg-indigo-500 shadow-lg shadow-indigo-500/50 w-24 rounded-xl">Rounded</button>
            <button
                class="bg-purple-500 shadow-lg shadow-purple-500/50 w-24 rounded-xl hover:bg-pink-500 hover:shadow-lg hover:shadow-pink-500/50">All
                of it</button>
        </div>
        <div class="p-10">
            <div
                class="bg-white border-slate-100 dark:bg-slate-800 dark:border-slate-500 border-b rounded-t-xl p-4 pb-6 sm:p-10 sm:pb-8 lg:p-4 xl:p-4 xl:pb-8 space-y-6 sm:space-y-8 lg:space-y-6 xl:space-y-8">
                <div class="flex items-center space-x-4">
                    <img src="../assets/pegasus-logo.svg" alt="" width="88" height="88"
                        class="flex-none rounded-lg bg-slate-100" loading="lazy" />
                    <div class="min-w-0 flex-auto space-y-1 font-semibold">
                        <p class="text-cyan-500 dark:text-cyan-400 text-sm leading-6">
                            <abbr title="Fancy">Fancy</abbr> 256
                        </p>
                        <h2 class="text-slate-500 dark:text-slate-400 text-sm leading-6 truncate">
                            This is the superior feature
                        </h2>
                        <p class="text-slate-900 dark:text-slate-50 text-lg">
                            Dark Mode!
                        </p>
                    </div>
                </div>
                <div class="space-y-2">
                    <div class="relative">
                        <div class="bg-slate-100 dark:bg-slate-700 rounded-full overflow-hidden">
                            <div class="bg-cyan-500 dark:bg-cyan-400 w-1/2 h-2" role="progressbar"
                                aria-label="music progress" aria-valuenow="1456" aria-valuemin="0" aria-valuemax="4550">
                            </div>
                        </div>
                        <div
                            class="ring-cyan-500 dark:ring-cyan-400 ring-2 absolute left-1/2 top-1/2 w-4 h-4 -mt-2 -ml-2 flex items-center justify-center bg-white rounded-full shadow">
                            <div
                                class="w-1.5 h-1.5 bg-cyan-500 dark:bg-cyan-400 rounded-full ring-1 ring-inset ring-slate-900/5">
                            </div>
                        </div>
                    </div>
                    <div class="flex justify-between text-sm leading-6 font-medium tabular-nums">
                        <div class="text-cyan-500 dark:text-slate-100">24:16</div>
                        <div class="text-slate-500 dark:text-slate-400">75:50</div>
                    </div>
                </div>
            </div>
            <div class="bg-slate-50 text-slate-500 dark:bg-slate-600 dark:text-slate-200 rounded-b-xl flex items-center">
                <div class="flex-auto flex items-center justify-evenly">
                    <button type="button" aria-label="Add to favorites">
                        <svg width="24" height="24">
                            <path d="M7 6.931C7 5.865 7.853 5 8.905 5h6.19C16.147 5 17 5.865 17 6.931V19l-5-4-5 4V6.931Z"
                                fill="currentColor" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" />
                        </svg>
                    </button>
                    <button type="button" class="hidden sm:block lg:hidden xl:block" aria-label="Previous">
                        <svg width="24" height="24" fill="none">
                            <path d="m10 12 8-6v12l-8-6Z" fill="currentColor" stroke="currentColor" stroke-width="2"
                                stroke-linecap="round" stroke-linejoin="round" />
                            <path d="M6 6v12" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" />
                        </svg>
                    </button>
                    <button type="button" aria-label="Rewind 10 seconds">
                        <svg width="24" height="24" fill="none">
                            <path
                                d="M6.492 16.95c2.861 2.733 7.5 2.733 10.362 0 2.861-2.734 2.861-7.166 0-9.9-2.862-2.733-7.501-2.733-10.362 0A7.096 7.096 0 0 0 5.5 8.226"
                                stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                            <path d="M5 5v3.111c0 .491.398.889.889.889H9" stroke="currentColor" stroke-width="2"
                                stroke-linecap="round" stroke-linejoin="round" />
                        </svg>
                    </button>
                </div>
                <button type="button"
                    class="bg-white text-slate-900 dark:bg-slate-100 dark:text-slate-700 flex-none -my-2 mx-auto w-20 h-20 rounded-full ring-1 ring-slate-900/5 shadow-md flex items-center justify-center"
                    aria-label="Pause">
                    <svg width="30" height="32" fill="currentColor">
                        <rect x="6" y="4" width="4" height="24" rx="2" />
                        <rect x="20" y="4" width="4" height="24" rx="2" />
                    </svg>
                </button>
                <div class="flex-auto flex items-center justify-evenly">
                    <button type="button" aria-label="Skip 10 seconds">
                        <svg width="24" height="24" fill="none">
                            <path
                                d="M17.509 16.95c-2.862 2.733-7.501 2.733-10.363 0-2.861-2.734-2.861-7.166 0-9.9 2.862-2.733 7.501-2.733 10.363 0 .38.365.711.759.991 1.176"
                                stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                            <path d="M19 5v3.111c0 .491-.398.889-.889.889H15" stroke="currentColor" stroke-width="2"
                                stroke-linecap="round" stroke-linejoin="round" />
                        </svg>
                    </button>
                    <button type="button" class="hidden sm:block lg:hidden xl:block" aria-label="Next">
                        <svg width="24" height="24" fill="none">
                            <path d="M14 12 6 6v12l8-6Z" fill="currentColor" stroke="currentColor" stroke-width="2"
                                stroke-linecap="round" stroke-linejoin="round" />
                            <path d="M18 6v12" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round" />
                        </svg>
                    </button>
                    <button type="button"
                        class="rounded-lg text-xs leading-6 font-semibold px-2 ring-2 ring-inset ring-slate-500 text-slate-500 dark:text-slate-100 dark:ring-0 dark:bg-slate-500">
                        1x
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>