<template>
  <div>
    <b-container>
      <b-breadcrumb :items="items"></b-breadcrumb>
    </b-container>
    <h1>Inicio Bienvenido </h1>
    <div>
      <img src="https://best-fit.transforms.svdcdn.com/production/albums/Thirty-Seconds-To-Mars-Its-The-End-Of-The-World-cover.png?w=768&q=95&auto=format&fit=crop&dm=1694693870&s=3e6cdde868cc0ae7c23a912585853117">
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          text: "",
          active: true,
        },
      ],
    };
  },
};
</script>
<style>
.btn-inicio {
  padding: 20px;
  margin: 10px;
}

.btn-inicio a {
  text-decoration: none;
  color: white;
}
</style>
