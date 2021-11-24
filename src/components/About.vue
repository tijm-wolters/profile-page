<template>
  <div class="about">
    <p>
      I'm a {{ getAge }}-year-old Software Engineer, I'm a high school dropout
      because of my autism. I've since then started to teach myself how to code.
      I pick skills up quickly and am able to take a lot of knowledge in, giving
      me the ability to work on many different kinds of projects. I'm currently
      working at IXON Cloud as a Front-End Developer.

      <br /><br />
      <b>Working on</b>
      <br />

      Multiple personal and work projects, using many tools and languages. My
      skills range from Web Development with Angular, Typescript and the
      firebase suite, Mobile iOS and Android deployment with Fastlane, to
      improving automation with Python, Docker and Node.js

      <br /><br />
      <b>Wanting to learn</b>
      <br />

      Some of the things I'd like to learn include a low level programming
      language, a non object oriented language, and some more Web development
      frameworks, like Vue, Svelte or React.
    </p>
  </div>
</template>

<script>
export default {
  name: 'About',
  computed: {
    getAge() {
      // Calculates my current age
      return Math.floor((Date.now() - new Date('12-04-2005')) / 31556926000);
    },
  },
};
</script>

<style lang="scss" scoped>
.about {
  margin: 32px 128px;
}
p {
  margin: 0;
}
</style>
