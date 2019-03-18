<template>
  <div>
    <img :src="avatar">
    <h1>{{title}}</h1>
    <p>{{job}}</p>
    <CVArea title="Erfaring"/>
    <CVArea title="Verv"/>
    <CVArea title="Utdanning"/>
  </div>
</template>

<script>
import Avatar from "@/assets/ola.jpeg";
import CVArea from "./CVArea.vue";

export default {
  data() {
    return {
      title: "Ola Nordmann",
      job: "IT Konsulent",
      avatar: Avatar
    };
  },
  components: {
    CVArea
  }
};
</script>

<style>
img {
  border: solid 1px grey;
  border-radius: 50%;
}
</style>
