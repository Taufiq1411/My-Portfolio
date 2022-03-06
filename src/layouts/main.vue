<template>
    <header class="sticky top-0 z-50">
        <the-nav />
    </header>
    <body class=relative>
        <slot />
    </body>
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
