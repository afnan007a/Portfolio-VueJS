<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>
      <strong>
        I am a Full-Stack Developer and I like having friends >w<
      </strong>
    </h2>
    <h2><strong>My Latest Works</strong></h2>
    <ul>
      <li>
        <a href="https://github.com/afnan007a" target="_blank" rel="noopener"
          >Github</a
        >
      </li>
      <li>
        <a href="https://gitlab.com/afnan007a" target="_blank" rel="noopener"
          >Gitlab</a
        >
      </li>
    </ul>
    <h2><strong>Essential Links</strong></h2>
    <ul>
      <li>
        <a
          href="https://www.youtube.com/watch?v=xvFZjo5PgG0"
          target="_blank"
          rel="noopener"
          >Latest Projects</a
        >
      </li>
      <li>
        <a
          href="https://www.youtube.com/watch?v=xvFZjo5PgG0"
          target="_blank"
          rel="noopener"
          >Status Page</a
        >
      </li>
    </ul>
    <br />
    <br />
    <br />
    <h3><strong>Vue Chan's Portfolio >w< </strong></h3>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
  margin: 25px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  font-size: 18px;
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #d05648;
}
</style>
