<template>
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
</template>

<script>
export default {
  layout: 'master',
  data() {
    return {

    }
  },
}
</script>

<style scoped>

</style>
