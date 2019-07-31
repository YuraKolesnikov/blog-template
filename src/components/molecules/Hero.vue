<template>
  <FullWidthBox :bgPath="bgPath">
    <Badge />
    <h1 class="hero__title">Creating Remarkable Poster Prints Through 4 Color Poster Printing</h1>
    <ProfileImage />
    <p>Caleb Atkins</p>
  </FullWidthBox>
</template>
<script>
import FullWidthBox from '@/components/FullWidthBox'
import Badge from '@/components/Badge'
import ProfileImage from '@/components/ProfileImage'
export default {
  components: { FullWidthBox, Badge, ProfileImage },
  data() {
    return {
      bgPath: ''
    }
  }
}
</script>
