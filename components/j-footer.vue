<template>
    <div class="blue w-100 flex pa3 footer">
        <div class="">
            <p>Jordan Furr</p>
            <span @click="copyEmail" style="cursor: pointer;">jordan@jordanfurr.com</span>
            <span v-if="copied" class="copied">Copied!</span>
            <div class="spacer"></div>
        </div>
    </div>
</template>

<script>
export default {
  data() {
    return {
      copied: false
    };
  },
  methods: {
    copyEmail() {
      const email = 'jordan@jordanfurr.com';
      navigator.clipboard.writeText(email)
        .then(() => {
          this.copied = true;
          setTimeout(() => {
            this.copied = false;
          }, 1500);
        })
        .catch(error => {
          console.error('Failed to copy:', error);
        });
    }
  }
};
</script>