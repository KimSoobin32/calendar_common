<template>
  <div class="parent_container">
    <div>
      <h1 class="project-name">
        calendar_common
      </h1>
      <div class="links">
        <div>
          <nuxt-link :to="`/milly`">milly의 calendar</nuxt-link>
        </div>
        <div>
          <nuxt-link :to="`/kate`">kate 의 calendar</nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.parent_container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.project-name {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.links {
  > div{
    margin: 50px;
  }
}
</style>
