<template>
  <div>
    <div class="tw-flex tw-items-start">
      <div class="tw-hidden  lg:tw-block tw-fixed top-20 tw-h-screen tw-w-64"
           style="background-image: url(https://images.unsplash.com/photo-1531651008558-ed1740375b39?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80)">
        <div
          class="tw-bg-[#322328] tw-text-white tw-bg-opacity-90 md:tw-absolute md:tw-inset-0 md:tw-overflow-y-auto md:tw-flex md:tw-flex-nowrap md:tw-overflow-hidden tw-shadow-xl tw-relative tw-z-10 tw-p-3"
        >
          <div
            class="md:tw-flex-col md:tw-items-stretch md:tw-min-h-full md:tw-flex-nowrap tw-px-0 tw-flex tw-flex-wrap tw-items-center tw-justify-between tw-w-full tw-mx-auto"
          >
            <!-- Logo -->
            <img class="tw-w-full tw-h-28 tw-hidden" src="@/assets/img/sheesh-logo.png" alt="...">

            <!-- Collapse -->
            <div
              class="md:tw-flex md:tw-flex-col md:tw-items-stretch md:tw-opacity-100 md:tw-relative md:tw-mt-4 md:tw-shadow-none tw-shadow tw-absolute tw-top-0 tw-left-0 tw-right-0 tw-z-40 tw-overflow-y-auto tw-overflow-x-hidden tw-h-auto tw-items-center tw-flex-1 tw-rounded {collapseShow}"
            >
              <!-- Collapse header -->
              <div
                class="md:tw-min-w-full md:tw-hidden tw-block tw-pb-4 tw-mb-4 tw-border-b tw-border-solid tw-border-blueGray-200"
              >
                <div class="tw-flex tw-flex-wrap">
                  <div class="tw-w-6/12">
                    <a
                      class="md:tw-block tw-text-left md:tw-pb-2 text-blueGray-600 tw-mr-0 tw-inline-block tw-whitespace-nowrap tw-text-sm tw-uppercase tw-font-bold tw-p-4 tw-px-0"
                      href="/"
                    >
                      Notus Svelte
                    </a>
                  </div>
                  <div class="tw-w-6/12 tw-flex tw-justify-end">
                    <button
                      type="button"
                      class="tw-cursor-pointer tw-text-black tw-opacity-50 md:tw-hidden tw-px-3 tw-py-1 tw-text-xl tw-leading-none tw-bg-transparent tw-rounded tw-border tw-border-solid tw-border-transparent"
                    >
                      <i class="fas fa-times"></i>
                    </button>
                  </div>
                </div>
              </div>
              <!-- Form -->
              <form class="tw-mt-6">
                <div class="tw-relative tw-mb-6 tw-px-1">
                  <div
                    class="tw-absolute tw-inset-y-0 tw-left-0 tw-flex tw-items-center tw-pl-3 tw-pointer-events-none">
                    <v-icon color="white" class="tw-text-white" height="3" width="3">mdi-magnify</v-icon>
                  </div>
                  <input type="text" id="input-group-1"
                         class="tw-text-white tw-bg-[#4a3e40] tw-border tw-text-gray-500 tw-text-md tw-rounded-lg focus:tw-ring-red-200 tw-block tw-w-full tw-pl-10 tw-p-2.5"
                         placeholder="Rechercher">
                </div>
              </form>

              <h6
                class="md:tw-min-w-full tw-text-gray-400 tw-text-xs tw-uppercase tw-font-bold tw-block tw-pt-1 tw-pb-4 tw-no-underline"
              >
                Apple muzic
              </h6>
              <!-- Navigation -->

              <ul class="md:tw-flex-col md:tw-min-w-full tw-flex tw-flex-col tw-list-none">
                <li class="tw-items-center tw-pl-1 hover:tw-bg-[#4a3e40] hover:tw-bg-opacity-60 hover:tw-rounded">
                  <NuxtLink
                    to="/"
                    class="tw-inline-flex tw-items-center tw-text-xs tw-capitalize tw-py-2 tw-font-bold tw-block"
                  >
                    <div
                      class="tw-mr-2 tw-text-sm"
                    >
                      <v-icon size="22" color="red darken-1" style="color: red">mdi-play-circle-outline</v-icon>
                    </div>
                    écouter
                  </NuxtLink>
                </li>

                <li class="tw-items-center tw-pl-1 hover:tw-bg-[#4a3e40] hover:tw-bg-opacity-60 hover:tw-rounded">
                  <NuxtLink
                    to="/"
                    class="tw-inline-flex tw-items-center tw-text-xs tw-capitalize tw-py-2 tw-font-bold tw-block"
                  >
                    <div
                      class="tw-mr-2 tw-text-sm"
                    >
                      <v-icon size="22" color="red darken-1" style="color: red">mdi-radio-tower</v-icon>
                    </div>
                    écouter
                  </NuxtLink>
                </li>
              </ul>

              <h6
                class="tw-mt-4 md:tw-min-w-full tw-text-gray-400 tw-text-xs tw-uppercase tw-font-bold tw-block tw-pt-1 tw-pb-4 tw-no-underline"
              >
                Bibliothèque
              </h6>
              <ul class="md:tw-flex-col md:tw-min-w-full tw-flex tw-flex-col tw-list-none">
                <li class="tw-items-center tw-pl-1 hover:tw-bg-[#4a3e40] hover:tw-bg-opacity-60 hover:tw-rounded">
                  <NuxtLink
                    to="/"
                    class="tw-inline-flex tw-items-center tw-text-xs tw-capitalize tw-py-2 tw-font-bold tw-block"
                  >
                    <div
                      class="tw-mr-2 tw-text-sm"
                    >
                      <v-icon size="22" color="red darken-1" style="color: red">mdi-clock-time-nine-outline</v-icon>
                    </div>
                    Ajouts récents
                  </NuxtLink>
                </li>

                <li class="tw-items-center tw-pl-1 hover:tw-bg-[#4a3e40] hover:tw-bg-opacity-60 hover:tw-rounded">
                  <NuxtLink
                    to="/"
                    class="tw-inline-flex tw-items-center tw-text-xs tw-capitalize tw-py-2 tw-font-bold tw-block"
                  >
                    <div
                      class="tw-mr-2 tw-text-sm"
                    >
                      <v-icon size="22" color="red darken-1" style="color: red">mdi-microphone-variant</v-icon>
                    </div>
                    Artistes
                  </NuxtLink>
                </li>
                <li class="tw-items-center tw-pl-1 hover:tw-bg-[#4a3e40] hover:tw-bg-opacity-60 hover:tw-rounded">
                  <NuxtLink
                    to="/"
                    class="tw-inline-flex tw-items-center tw-text-xs tw-capitalize tw-py-2 tw-font-bold tw-block"
                  >
                    <div
                      class="tw-mr-2 tw-text-sm"
                    >
                      <v-icon size="22" color="red darken-1" style="color: red">mdi-album</v-icon>
                    </div>
                    Albums
                  </NuxtLink>
                </li>

              </ul>

              <h6
                class="tw-mt-4 md:tw-min-w-full tw-text-gray-400 tw-text-xs tw-uppercase tw-font-bold tw-block tw-pt-1 tw-pb-4 tw-no-underline"
              >
                Mon compte
              </h6>
              <ul class="md:tw-flex-col md:tw-min-w-full tw-flex tw-flex-col tw-list-none">
                <li class="tw-items-center tw-pl-1 hover:tw-bg-[#4a3e40] hover:tw-bg-opacity-60 hover:tw-rounded">
                  <NuxtLink
                    to="/"
                    class="tw-inline-flex tw-items-center tw-text-xs tw-capitalize tw-py-2 tw-font-bold tw-block"
                  >
                    <div
                      class="tw-mr-2 tw-text-sm"
                    >
                      <v-icon size="22" color="red darken-1" style="color: red">mdi-account</v-icon>
                    </div>
                    Profile
                  </NuxtLink>
                </li>

                <li class="tw-items-center tw-pl-1 hover:tw-bg-[#4a3e40] hover:tw-bg-opacity-60 hover:tw-rounded">
                  <NuxtLink
                    to="/"
                    class="tw-inline-flex tw-items-center tw-text-xs tw-capitalize tw-py-2 tw-font-bold tw-block"
                  >
                    <div
                      class="tw-mr-2 tw-text-sm"
                    >
                      <v-icon size="22" color="red darken-1" style="color: red">mdi-logout</v-icon>
                    </div>
                    Déconnexion
                  </NuxtLink>
                </li>
              </ul>

            </div>
          </div>
        </div>
      </div>

      <div class="tw-relative tw-ml-0 lg:tw-ml-64 tw-flex tw-flex-col tw-w-full tw-h-full">
        <div style="z-index: 999" class="tw-fixed tw-top-0 tw-left-0 lg:tw-left-64 tw-right-0 tw-bg-gray-900 tw-shadow-lg">
          <div class="tw-flex tw-items-center tw-px-4 tw-py-1">
            <div class="tw-w-1/3 lg:tw-w-3/12 tw-py-2 tw-bg-transparent tw-flex tw-items-center tw-justify-center">
              <div class="tw-inline-flex tw-gap-2 tw-items-center">
                <button class="tw-mr-4">
                  <v-icon color="white" class="tw-text-white">mdi-playlist-music-outline</v-icon>
                </button>
                <button>
                  <v-icon color="white" class="tw-text-white">mdi-skip-previous</v-icon>
                </button>
                <button>
                  <v-icon color="white" class="tw-text-white">mdi-play</v-icon>
                </button>
                <button>
                  <v-icon color="white" class="tw-text-white">mdi-skip-next</v-icon>
                </button>
                <button class="tw-ml-4">
                  <v-icon color="white" class="tw-text-white">mdi-repeat-variant</v-icon>
                </button>
              </div>
            </div>

            <div
              class="tw-w-1/3 lg:tw-w-6/12 tw-pl-1 tw-bg-gray-800 tw-h-full tw-flex tw-items-center tw-justify-between ">
              <img class="tw-h-11 tw-w-11 tw-my-1"
                   src="https://images.unsplash.com/photo-1560800452-f2d475982b96?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"
                   alt="music-image">
              <div class="tw-flex tw-justify-center tw-text-center tw-w-full">
                <div class="tw-flex tw-flex-col">
                  <h1 class="tw-uppercase tw-text-sm tw-font-medium tw-text-white">Kora inspiration</h1>
                  <h2 class="tw-text-xs tw-uppercase tw-text-gray-300">African music for méditation</h2>
                </div>
              </div>
            </div>

            <div class="tw-w-1/3 lg:tw-w-3/12 tw-bg-transparent tw-flex tw-items-center tw-justify-end">
              <div class="tw-w-2/3 tw-flex tw-items-center tw-justify-between">
                <button>
                  <v-icon color="white" class="tw-text-white">mdi-volume-high</v-icon>
                </button>

                <div class="tw-inline-flex tw-gap-4">
                  <button>
                    <v-icon color="white" class="tw-text-white">mdi-comment-quote-outline</v-icon>
                  </button>
                  <button :class="showHistoriqueAside ? 'tw-bg-gray-800 tw-rounded-lg' : ''"
                          @click="showHistoriqueAside =! showHistoriqueAside">
                    <v-icon color="white" class="tw-text-white tw-m-1.5">mdi-format-list-bulleted</v-icon>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="tw-mt-14 tw-w-full">
          <div class="tw-flex tw-items-start tw-w-full tw-h-full">
            <div class="tw-w-full tw-p-6 tw-bg-gray-900 tw-flex tw-flex-col tw-gap-4">
              <h1 class="tw-text-white tw-text-xl tw-font-semibold">Parcourir les catégories</h1>
              <div class="tw-grid md:tw-grid-cols-2 lg:tw-grid-cols-3 tw-gap-6">
                <a v-for="i in 27"
                   href="#"
                   style="background-image: url(https://images.unsplash.com/photo-1505740420928-5e560c06d30e?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80)"
                   class="tw-relative tw-block tw-overflow-hidden tw-rounded-xl tw-bg-cover tw-bg-center tw-bg-no-repeat"
                >
                  <span
                    class="tw-absolute tw-right-4 tw-top-4 tw-inline-flex tw-items-center tw-rounded-full tw-bg-black tw-px-3 tw-py-1 tw-text-xs tw-font-semibold tw-text-white">
                    4.5
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="tw-ml-1.5 tw-h-4 tw-w-4 tw-text-yellow-300"
                      viewBox="0 0 20 20"
                      fill="currentColor"
                    >
                      <path
                        d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/>
                    </svg>
                  </span>

                  <div class="tw-relative tw-bg-[#322328] tw-bg-opacity-40 tw-px-6 tw-pb-4 tw-pt-40 tw-text-white">
                    <h3 class="tw-text-xl tw-font-bold">DJ Mixes</h3>

                    <p class="tw-text-sm">Afrikaans</p>
                  </div>
                </a>
              </div>
            </div>
          </div>


          <div :class="showHistoriqueAside ? 'tw-fixed':'tw-hidden'"
               class=" tw-right-0 tw-top-14 tw-w-64 lg:tw-w-[20%] tw-px-4 tw-h-screen tw-shadow-b-xl tw-bg-gray-900">
            <div class="tw-flex tw-flex-col tw-gap-4">
              <div
                class="tw-bg-gray-800 tw-rounded tw-font-medium tw-shadow tw-mt-4 tw-flex tw-justify-between tw-relative tw-items-center">
                <button @click="showQueue = true, showHistorique = false" :class="showQueue ? 'tw-bg-gray-500 tw-rounded' : ''" class="tw-duration-150 tw-text-white tw-w-1/2 tw-py-1">Suivant</button>
                <button @click="showHistorique = true, showQueue = false" :class="showHistorique ? 'tw-bg-gray-500 tw-rounded' : ''" class="tw-duration-150 tw-text-white tw-w-1/2 tw-py-1">Historique</button>
              </div>

              <hr>
              <div v-if="showQueue" class="tw-flex tw-flex-col">
                <div class="tw-flex tw-items-center tw-justify-between tw-py-2">
                  <h1 class="tw-text-white">File d'attente</h1>
                  <div class="tw-inline-flex tw-gap-2 tw-text-gray-300">
                    <button>Effacer</button>
                    <v-icon class="tw-text-white">mdi-update</v-icon>
                  </div>
                </div>
                <div class="tw-flex tw-flex-col">
                  <div class="tw-flex tw-items-center tw-gap-2 tw-py-2 tw-border-b tw-border-gray-400" v-for="i in 12">
                    <img class="tw-h-12 tw-w-12 tw-rounded tw-bg-cover" src="https://images.unsplash.com/photo-1495305379050-64540d6ee95d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
                         alt="song-caption">
                    <div class="tw-flex tw-flex-col tw-gap-1">
                      <h1 class="tw-text-white tw-font-medium tw-text-sm">Peureux</h1>
                      <h1 class="tw-text-gray-400 tw-text-xs tw-font- text-truncate">AI Asplash & Bilal Danjum lash &
                        Bilal Danjum</h1>
                    </div>
                    <h2 class="tw-text-gray-400 tw-font-medium text-truncate">3:22</h2>
                  </div>
                </div>
              </div>

              <div v-if="showHistorique" class="tw-flex tw-flex-col">
                <div class="tw-flex tw-items-center tw-justify-between tw-py-2">
                  <h1 class="tw-text-white">Historique</h1>
                  <div class="tw-inline-flex tw-gap-2 tw-text-gray-300">
                    <button>Effacer</button>
                    <v-icon class="tw-text-white">mdi-update</v-icon>
                  </div>
                </div>
                <div class="tw-flex tw-flex-col">
                  <div class="tw-flex tw-items-center tw-gap-2 tw-py-2 tw-border-b tw-border-gray-400" v-for="i in 7">
                    <img class="tw-h-12 tw-w-12 tw-rounded tw-bg-cover" src="https://images.unsplash.com/photo-1587714656374-fb3c9c3a4977?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
                         alt="song-caption">
                    <div class="tw-flex tw-flex-col tw-gap-1">
                      <h1 class="tw-text-white tw-font-medium tw-text-sm">Rita Ora</h1>
                      <h1 class="tw-text-gray-400 tw-text-xs tw-font- text-truncate">Body On Me ft Chris Brown</h1>
                    </div>
                    <h2 class="tw-text-gray-400 tw-font-medium text-truncate">3:22</h2>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // layout: 'master',
  data() {
    return {
      showHistoriqueAside: false,
      showHistorique: false,
      showQueue: true,
    }
  },


}
</script>

<style scoped>

</style>
