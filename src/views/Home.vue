<template lang="pug">
div
  h3 Hello early user,
  p
    | It's still early days for ActivityWatch. We've come a long way but we currently need users (like you!) to provide feedback and help us turn ActivityWatch into a successful project.
    | Your interest as an early user means extra much to us, and we hope you'll reach out to us with any ideas you have for improvements!
  p
    | If you are a developer we hope you take a peek at the documentation (found in the links below) as well as try to write a watcher, visualizer or some other tool to help build an ecosystem (it's easy!).
  p
    | Thank you for using ActivityWatch!

  hr

  div.row
    div.col-md-6
      h4 Spread the word
      p
        | Nothing is as motivating as getting ActivityWatch into the hands of users.
        | By sharing it you help us make ActivityWatch even better!
      ul
        li
          | Give us a like and a review on #[a(href="https://alternativeto.net/software/activitywatch/") AlternativeTo]
        li
          | Follow us and spread the word on #[a(href="https://twitter.com/ActivityWatchIt") Twitter] and #[a(href="https://www.facebook.com/ActivityWatch") Facebook]
        li
          | Star us on #[a(href="https://github.com/ActivityWatch/activitywatch") GitHub]

    div.col-md-6
      h4 Support us!
      p
        | Do you like what we do? Help us out by donating so we can keep doing it!
        | You can donate to us via:
      ul
        li #[a(href="https://www.patreon.com/erikbjare") Patreon]
        li #[a(href="https://opencollective.com/activitywatch") Open Collective]
        li #[a(href="https://www.bountysource.com/teams/activitywatch") Bountysource]
        li #[a(href="https://activitywatch.net/donate/") Other methods] (incl. cryptocurrency)
      p
        | For more info about the how and why of donating, please visit #[a(href="https://activitywatch.net/donate/") the donation page on our website].

  hr

  h4 Resources
  p
    ul
      li
        a(href="http://activitywatch.net/")
          | Website
      li
        a(href="https://forum.activitywatch.net/")
          | Forum
      li
        a(href="https://github.com/ActivityWatch/activitywatch")
          | GitHub
      li
        a(href="https://activitywatch.readthedocs.org/")
          | Documentation
      li
        a(href="/api/")
          | API Browser

</template>

<style scoped lang="scss">
</style>

<script>
export default {
  name: "Home"
}
</script>
