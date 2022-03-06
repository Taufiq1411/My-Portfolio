<template>
  <div>
    <header>
        <the-nav />
    </header>
    <body>
        <slot />
    </body>
  </div>
</template>

<script>
import TheNav from '@/components/Nav.vue';

export default {
  name: 'the-main',
  components: {
    TheNav,
  },
};
</script>
