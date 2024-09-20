<template>
    <!-- BEGIN CONTACT -->
    <div class="row blue">
      <div class="side-content"></div>
      <div class="main-content">
        <div class="content-header">
          <a class="anchor" name="contact"></a>
          <h2 class="white-text">Contact Me</h2>
        </div>
        <div class="contact content-body">
          <form method="POST" action="https://formspree.io/email@email.com">
            <input type="hidden" name="_subject" value="Contact request from personal website" />
            <input type="email" name="_replyto" placeholder="Your email" required>
            <textarea name="message" placeholder="Your message" required></textarea>
            <button type="submit">Send</button>
          </form>
        </div>
      </div>
      <div class="side-content"></div>
    </div>
    <!-- END CONTACT -->
</template>

<script>
</script>

<style lang="scss" scoped>

</style>
