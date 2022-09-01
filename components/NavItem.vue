<template>
    <div id="BOVAEA part 1">
        <div class="flex flex-row">
            <h3><NuxtLink to="">{{ title }}</NuxtLInk></h3>
            <button @click="toggleIsHidden">
                <svg
                    class="-mr-1 ml-2 h-5 w-5"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                    aria-hidden="true">
                    <path
                        fill-rule="evenodd"
                        d="M5.23 7.21a.75.75 0 011.06.02L10 11.168l3.71-3.938a.75.75 0 111.08 1.04l-4.25 4.5a.75.75 0 01-1.08 0l-4.25-4.5a.75.75 0 01.02-1.06z"
                        clip-rule="evenodd"
                    />
                    </svg>
            </button>
        </div>
        <div v-show="isHidden" id="dropdown" class="flex flex-col">
            <ul
                <li v-for="(name, link) in "
                    :key={{ name }}
                    :value={{ link }}
                >
                </li>
            </ul>
        </div>
    </div>
</template>
