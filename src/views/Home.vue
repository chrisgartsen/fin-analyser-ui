<template>
  <div class="home">
    Home

        <div class="field">
            <b-checkbox v-model="checkboxCustom"
                true-value="Yes"
                false-value="No">
                Blah
            </b-checkbox>
        </div>

  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>
