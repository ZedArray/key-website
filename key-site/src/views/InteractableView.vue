<template>
    <div class="flex flex-col justify-center items-center gap-10 m-10">
        <div class="text-center flex flex-col gap-2">
            <p class="text-3xl font-bold">Year 9 HASS Interactive Activities</p>
            <p class="text-sm text-gray-400">Interactive Games and Activities</p>
        </div>
        <div class="flex flex-col w-full gap-8 lg:flex-row">
            <div class="border rounded-2xl border-gray-700 p-5 grow lg:max-w-1/3">
                <div class="card bg-base-100 shadow-sm">
                    <figure>
                        <img src="../assets/biomegame.png"
                            alt="Biomes Quiz Game" />
                    </figure>
                    <div class="card-body">
                        <h2 class="card-title">Biomes Quiz Game
                        </h2>
                        <!-- <p>A card component has a figure, a body part, and inside body there are title and actions parts
                        </p> -->
                        <div class="card-actions justify-end">
                            <a class="btn btn-primary" target="_blank"
                                href="https://world-geography-games.com/en/world_biomes.html">Play</a>
                        </div>
                    </div>
                </div>
            </div>

            <div class="border rounded-2xl border-gray-700 p-5 w-full flex flex-col items-center justify-center">
                <iframe src="https://scratch.mit.edu/projects/468633612/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
                <p class="mt-5 ml-5 font-bold text-lg">Scratch Biome Platformer Game</p>
            </div>

            <div class="border rounded-2xl border-gray-700 p-5 grow lg:max-w-1/3">
                <div class="card bg-base-100 shadow-sm">
                    <figure>
                        <img src="../assets/bamboozle.png"
                            alt="Baamboozle Biome Quiz" />
                    </figure>
                    <div class="card-body">
                        <h2 class="card-title">Baamboozle Biome Quiz
                        </h2>
                        <!-- <p>A card component has a figure, a body part, and inside body there are title and actions parts
                        </p> -->
                        <div class="card-actions justify-end">
                            <a class="btn btn-primary" target="_blank"
                                href="https://www.baamboozle.com/game/798113?page=2">Play</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>