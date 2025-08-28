<script setup>
import { BloggerIcon, GitHubIcon, GmailIcon, MastodonIcon, TelegramIcon, XIcon } from 'vue3-simple-icons'
const { title } = useAppConfig()
</script>

<template>
  <section>
    <div>
      <a href="https://sink.cool">{{ title }}</a>
    </div>
  </section>
</template>
