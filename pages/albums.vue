<template>
  <div class="tw-flex tw-items-start tw-w-full tw-h-full">
    <div class="tw-w-full tw-p-6 tw-bg-gray-900 tw-flex tw-flex-col tw-gap-4">
      <h1 class="tw-text-white tw-text-xl tw-font-semibold">Liste des albums</h1>
      <div class="tw-grid md:tw-grid-cols-2 lg:tw-grid-cols-4 tw-gap-6">
        <a v-for="i in 18" href="#" class="tw-block tw-rounded-lg tw-shadow-sm shadow-indigo-100">
          <img
            alt="Home"
            src="https://hiphopcorner.fr/wp-content/uploads/2015/12/image-lacrim-et-maitre-gims-du-son-petit-jaloux-1200x718.png"
            class="tw-h-44 tw-w-full tw-rounded-md tw-object-cover"
          />

          <div class="tw-mt-2">
            <dl>
              <div>
                <dt class="tw-sr-only">Price</dt>

                <dd class="tw-text-sm tw-text-white tw-font-semibold">Album inconnu</dd>
              </div>

              <div>
                <dt class="tw-sr-only">Title</dt>

                <dd class="tw-font-medium tw-capitalize tw-text-gray-400">[FREE] Central Cee X Melodie Drill Type Beat</dd>
              </div>
            </dl>
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
