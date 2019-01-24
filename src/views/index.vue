<template>
  <div>
    <b-nav-bar></b-nav-bar>
    <div class="blog">
      <b-posts></b-posts>
    </div>
  </div>
</template>

<script>
import '../assets/scss/_index.scss'
import NavBar from '../components/navBar'
import Posts from '../components/posts'
export default {
  name: 'posts',
  data () {
    return {
      posts: 'posts'
    }
  },
  components: {
    'b-nav-bar': NavBar,
    'b-posts': Posts
  }
}
</script>
