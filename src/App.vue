<script setup>
  import { onMounted } from 'vue';
  onMounted(() => document.getElementById("app").innerHTML = `<iframe id="iframe" src="http://8.137.114.177:5173/" frameborder="0"></iframe>`);
</script>