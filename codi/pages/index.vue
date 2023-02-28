<template>
  <div class="codFun-galery">
    <div
      style="
        background-image: url('https://images.unsplash.com/photo-1497032628192-86f99bcd76bc?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80');
      "
    ></div>
    <div
      style="
        background-image: url('https://images.unsplash.com/photo-1619183744799-68f1fd8f1edb?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80');
      "
    ></div>
    <div
      style="
        background-image: url('https://images.unsplash.com/photo-1614624532983-4ce03382d63d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1031&q=80');
      "
    ></div>
    <div
      style="
        background-image: url('https://images.unsplash.com/photo-1581646064576-6bc5a216f02c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80');
      "
    ></div>
    <div
      style="
        background-image: url('https://images.unsplash.com/photo-1507919909716-c8262e491cde?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1032&q=80');
      "
    ></div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
<style>
.codFun-galery {
  display: flex;
  height: 20rem;
  gap: 1rem;
}
.codFun-galery > div {
  flex: 1;
  border-radius: 1rem;
  background-position: center;
  background-repeat: no-repeat;
  background-size: auto 100%;
  transition: all 0.8s cubic-bezier(0.25, 0.4, 0.45, 1.4);
}
.codFun-galery > div:hover {
  flex: 5;
}
</style>
