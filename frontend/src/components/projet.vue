<template>
   <section>
     <h1 class="text-blue-400 text-3xl font-bold">Mes projets</h1>
     <p>Projet demontrant mon expertise et mes qualites</p>

     <div class=" sm:grid sm:grid-cols-2 lg:grid-cols-3 gap-8 mt-15 mb-15 md:pl-20 md:pr-20 text-center">
        <div class="project-card shadow-lg rounded-2xl p-10 " >
            <div class="content">
                <h2 class="font-bold">CALCULATRICE</h2>
                <p>calculatrice standart effectuent des operations d'addition, de soustraction , de multiplication et de division.</p>
                <div class="flex m-4  gap-2 animate-bounce">
                    <span class="bg-orange-500 text-white p-2.5 rounded-full w-20">html</span>
                    <span class="bg-blue-500 text-white p-2.5 rounded-full w-20">css</span>
                    <span class="bg-yellow-300 text-white p-2.5 rounded-full w-25">Javascript</span>
                </div>
            <div>
                <a href="">code source</a>
            </div>
            </div>
        </div>
        <div class="project-card shadow-lg rounded-2xl p-10">
            <div class="content">
                <h2 class="font-bold">JEU DE REFLEX</h2>
                <p>Petit jeux ou le but est de reussir a trouver un objet present dans un espace ayant presque que la meme couleur que l'objet . Ici il est question de tester ses capacite visuel et reactif</p>
                <div class="flex m-4  gap-2 animate-bounce">
                    <span class="bg-orange-500 text-white p-2.5 rounded-full w-20">html</span>
                    <span class="bg-blue-500 text-white p-2.5 rounded-full w-20">css</span>
                    <span class="bg-yellow-300 text-white p-2.5 rounded-full w-25">Javascript</span>
                </div>
                <div>
                    <a href="">code source</a>
                </div>
            </div>
        </div>
        <div class="project-card shadow-lg rounded-2xl p-10 ">
            <div class="content">
                <h2 class="font-bold">JEU DE REFLEX</h2>
                <p>Petit jeux ou le but est de reussir a trouver un objet present dans un espace ayant presque que la meme couleur que l'objet . Ici il est question de tester ses capacite visuel et reactif</p>
                <div class="flex m-4  gap-2 animate-bounce">
                    <span class="bg-orange-500 text-white p-2.5 rounded-full w-20">html</span>
                    <span class="bg-blue-500 text-white p-2.5 rounded-full w-20">css</span>
                    <span class="bg-yellow-300 text-white p-2.5 rounded-full w-25">Javascript</span>
                </div>
                <div>
                    <a href="">code source</a>
                </div>
            </div>
        </div>
     </div>
     <p>vous en verrez plus sur <a href="" class="text-blue-500 ">mon Github</a></p>
   </section>
</template>

<style>
    /* animation du haut vert le bas de la section  */
    .project-card{
        animation: slideDown 7s ease-in-out;
    }
    @keyframes slideDown {
        0% {
            transform: translateX(-60px);
            opacity: 0;
        }
        100% {
            transform: translateX(0);
            opacity: 1;
        }
    }

    /* animation du contenue : apparition des element en slide down */
    .content{
        animation: slideUp 6s ease-in-out;
    }

    @keyframes slideUp {
        0% {
            transform: translateY(60px);
            opacity: 0;
        }
        100% {
            transform: translateY(0);
            opacity: 1;
        }
    }
</style>