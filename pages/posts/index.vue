<template>
  <div>
    <h2>Posts Page</h2>
    <Header />
    <PostContent />
  </div>
</template>
<script>
import Header from "@/components/posts/Header";
import PostContent from "@/components/posts/PostContent";
export default {
  layout: "corelayout",
  components: {
    Header,
  },
};
</script>