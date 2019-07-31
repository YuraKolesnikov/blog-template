<template>
  <div class="post-card">
    <div class="post-card__overlay">
      <div class="post-card__text">
        <p class="text__underline">{{post.author}}</p>
        <h6 class="post-card__title">{{post.title}}</h6>
        <p class="text__underline post-card__date">{{post.date}}</p>
      </div>
    </div>
    <div class="post-card__img">
      <img :src="post.img">
    </div>
    <div class="post-card__icon">
      <ProfileImage :img="post.profileImage" />
    </div>
    <div class="post-card__text">
      <p class="text__underline">{{post.author}}</p>
      <h6 class="post-card__title">{{post.title}}</h6>
      <p class="text__underline post-card__date">{{post.date}}</p>
    </div>
  </div>
</template>
<script>
import ProfileImage from '@/components/ProfileImage'
export default {
  props: [],
  components: { ProfileImage }
}
</script>
