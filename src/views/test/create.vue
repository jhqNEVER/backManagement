<template>
  <div>
   <article-detail :is-edit="false" /> 

  </div>
  
</template>

<script>
import ArticleDetail from './components/ArticleDetail'

export default {
  name: 'CreateArticle',
  components: { ArticleDetail }
}
</script>

