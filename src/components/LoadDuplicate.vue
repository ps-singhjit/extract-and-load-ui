<template>
  <div class="container mt-5">
    <div class="row">
      <div class="col-12 text-center">
        <button type="submit" class="btn btn-primary loat-right">Load</button>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row">
      <!-- <div class="col-8 text-center"> -->
      <div class="col">
        <div class="row mt-5">
          <div class="col-md-4">
              <!-- <label for="copy">Copy</label> -->
            <div class="col-md-4">
              <input
                type="text"
                name="copy"
                id="id-copy"
                class="form-control"
                placeholder="# of copies"
              />
            </div>
          </div>
          <div class="col-md-4 text-center">
            <input
              type="submit"
              class="btn btn-outline-primary"
              value="Duplicate"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LoadDuplicate",
};
</script>

<style lang="scss" scoped>
</style>