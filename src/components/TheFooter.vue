<template>
  <div class="the-footer">
    <single-line class="single-line"/>
    <div class="icons">
      <social-icon url="http://www.flickr.com/photos/111512626@N08/sets/" image="flickr"/>
      <social-icon url="http://github.com/thomastodon" image="git"/>
      <social-icon url="http://instagram.com/thomasshouler" image="insta"/>
      <social-icon url="http://www.linkedin.com/in/thomasshouler" image="linkd"/>
      <social-icon url="http://stackoverflow.com/users/3746982/thomasshouler" image="stack"/>
      <social-icon url="http://www.strava.com/athletes/thomasshouler" image="strava"/>
      <social-icon url="http://thomasshouler.tumblr.com" image="bulb"/>
      <social-icon url="http://vimeo.com/user22045579" image="vimeo"/>
    </div>
  </div>
</template>

<script>
  import SingleLine from './SingleLine';
  import SocialIcon from './SocialIcon';

  export default {
    name: 'the-footer',
    components: {SocialIcon, SingleLine},
  }
</script>

<style scoped lang="scss">

  div.the-footer {
    height: auto;
  }

  div.icons {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
  }
</style>