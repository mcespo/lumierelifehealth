<template>
    <div class="layout">
        <HeaderComponent />
        <main class="container">
            <slot/>
        </main>
        <FooterComponent />
    </div>
</template>


<script>
import HeaderComponent from '~/components/HeaderComponent'
import FooterComponent from '~/components/FooterComponent'

export default {
  components: {
    HeaderComponent,
    FooterComponent
  }
}
</script>

<style lang="scss">
body {
    font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.5;
}
.layout {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    main {
        flex: 1;
    }
}
</style>
