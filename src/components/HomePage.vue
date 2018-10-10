<template>
  <div>
    <base-header />
    <base-button title="Click" />
  </div>
</template>

<script>
import BaseHeader from '@/common/BaseHeader'
import BaseButton from '@/common/BaseButton'

export default {
  name: 'HomePage',
  components: { BaseHeader, BaseButton },
}
</script>
