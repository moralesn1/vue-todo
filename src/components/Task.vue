<template>
  <h3>{{task.text}}</h3>
</template>

<script>
export default {
  name: 'Tasks',
  props: {
    task: {
      type: Object
    }
  }
}
</script>