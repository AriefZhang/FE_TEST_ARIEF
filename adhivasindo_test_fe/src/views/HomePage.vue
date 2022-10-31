<template>
  <div>
    <page-one />
    <page-two />
  </div>
</template>

<script>
import PageOne from '@/components/InvitationPageOne.vue'
import PageTwo from '@/components/InvitationPageTwo.vue'

export default {
  components: {
    PageOne,
    PageTwo
  }
}
</script>
