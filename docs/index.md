---
layout: page
head:
  - ['meta', {property: 'og:title', content: 'StackBlitz Docs'}]
  - ['meta', {property: 'og:image', content: 'https://developer.stackblitz.com/img/theme/docs-social.png'}]
---

<script setup lang="ts">
import Home from '@theme/components/Home.vue';

import { homeTopLinks, homeExternalLinks, footerSections } from './links';
</script>

<Home
  :topLinks="homeTopLinks"
  :externalLinks="homeExternalLinks"
  :footerSections="footerSections"
/>
