<template>
    <div class="card">
      <div class="card-image">
        <figure class="image has-text-centered mt-4">
          <FigureCard class="Figure" />
        </figure>
      </div>
      <div class="card-content">
        <div class="content has-text-centered">
          <p class="title is-4">{{$props.Add}}</p>
          <p class="subtitle is-6">{{$props.Bill}}</p>
        </div>
      </div>
    </div>
</template>
<script>
export default {
    props:[
        "Add",
        "Bill"
    ]
}
</script>
