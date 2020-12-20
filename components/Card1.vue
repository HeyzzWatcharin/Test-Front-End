<template>
  <div class="card">
    <div class="card-image">
      <figure class="image has-text-centered mt-4">
        <FigureCard class="Figure" />
      </figure>
    </div>
    <div class="card-content">
      <div class="content has-text-centered">
        <p class="is-size-4 title" style="  font-family:  p-bold;">
          {{ $props.Add }}
        </p>
        <p class="subtitle" style="  font-family: dx-text;">{{ $props.Bill }}</p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: ["Add", "Bill"]
};
</script>
