<template>
  <div id="sticky">
    <div class="sticky-icons-container">
      <button class="scroll-top-btn">
        <img src="https://i.ibb.co/94yx1s3/scroll-top.png" alt="scroll-top" />
      </button>
      <button class="chatbot-btn">
        <img
          src="https://cdn.channel.io/plugin/images/ch-new-symbol-powered.png"
          alt="chat-bot"
        />
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "sticky-icons",
};
</script>

<style lang="scss">
@import "../styles/common.scss";

#sticky {
  position: fixed;
  z-index: 9999;

  .sticky-icons-container {
    display: flex;
    flex-direction: column;

    .scroll-top-btn {
      width: 50px;
      height: 50px;
      img {
        width: 100%;
        height: 100%;
      }
    }
    .chatbot-btn {
      width: 62px;
      height: 62px;
      img {
        width: 100%;
        height: 100%;
      }
    }
  }
}
</style>
