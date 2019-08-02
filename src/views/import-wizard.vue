<template>

  <div class="container">

    <div class="columns mt-xl">
        <div class="column">
          <h2 class="is-size-3">Import data file</h2>
        </div>
    </div>

    <div class="columns mt-xl">
      <div class="column">
        <b-steps v-model="activeStep" :animated="true" :has-navigation="true">

          <b-step-item label="Select file" :clickable="true">
            
            <b-field class="file">
        <b-upload v-model="file">
            <a class="button is-primary">
                <b-icon icon="upload"></b-icon>
                <span>Select file</span>
            </a>
        </b-upload>
        <span class="file-name" v-if="file">
            {{ file.name }}
        </span>
    </b-field>


          </b-step-item>

          <b-step-item label="Profile" :clickable="true">
              Lorem ipsum dolor sit amet.
          </b-step-item>

          <b-step-item label="Finish" :clickable="true">
              Lorem ipsum dolor sit amet.
          </b-step-item>

        </b-steps>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: 'import-wizard',
  data() {
    return {
      activeStep: 0,
      file: null
    }
  }
}

</script>