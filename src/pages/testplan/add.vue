<template>
  <div class="app-container">
    <save-test-plan :is-add="true" />
  </div>
</template>

<script>
import SaveTestPlan from './components/SaveTestPlan'
export default {
  name: 'AddTestPlan',
  components: {
    SaveTestPlan
  }
}
</script>
