<template>
  <div>
    <nav class="navbar nav-blue">
      <div class="container">
        <img alt="Vue logo" src="../assets/BlueCross.png" />
      </div>
    </nav>
    <div class="container">
      <h2>{{ msg }}</h2>
    </div>
    <hr />
    <SourceTargetSelect />
    <hr />
    <!-- -------- -->
    <SetCriteria />
    <hr />
    <LoadDuplicate />
    <hr />
    <DetailsTable />
  </div>
</template>

<script>
import SourceTargetSelect from "@/components/SourceTargetSelect.vue";
import SetCriteria from "@/components/SetCriteria.vue";
import LoadDuplicate from "@/components/LoadDuplicate.vue";
import DetailsTable from "@/components/DetailsTable.vue";

export default {
  name: "HomeComponent",

  props: {
    msg: String,
  },
  components: {
    SourceTargetSelect,
    SetCriteria,
    LoadDuplicate,
    DetailsTable,
  },
};
</script>

<style lang="scss" scoped>
</style>