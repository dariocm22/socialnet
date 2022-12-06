<template>
    <ul class="list-group">
  <li class="list-group-item text-muted">A 36 pesonas le gusta esto</li>
  <li class="list-group-item">
    <div class="row">
        <div class="col d-grid">
            <button class="btn d-flex justify-content-center align-items-center gap-2 px-0">
                <span class="material-icons-round">
                thumb_up
                </span>
                Me gusta</button>
        </div>
        <div class="col d-grid">
            <button class="btn d-flex justify-content-center align-items-center gap-2 px-0">
            <span class="material-icons-round">
            insert_comment
            </span>
            Comentar</button>
        </div>
    </div>
  </li>
</ul>
</template>

<script>
    export default {}
</script>

<style scoped>
    .btn:hover {
        color:rgb(0, 168, 168)
    }
</style>