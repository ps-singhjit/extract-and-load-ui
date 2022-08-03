<template>
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <div class="form-group">
          <label for="source">Source: </label>
          <div class="col-md-4">
            <select class="form-control" name="source" id="id-sel-source">
              <option selected>MAAXS</option>
              <option value="m1">MAAXS1</option>
              <option value="m2">MAAXS2</option>
              <option value="m3">MAAXS3</option>
            </select>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="form-group">
          <label for="target">Target: </label>
          <div class="col-md-4">
            <select class="form-control" name="target" id="id-sel-target">
              <option selected>Target_Env</option>
              <option value="t1">Target_Env1</option>
              <option value="t2">Target_Env2</option>
              <option value="t3">Target_Env3</option>
            </select>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SourceTargetSelect",
};
</script>

<style lang="scss" scoped>
</style>