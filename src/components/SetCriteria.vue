<template>
  <div class="container">
    <div class="row">
      <div class="col-md-2">
        <div class="form-group">
          <label for="entity">Entity</label>
          <select class="form-control" name="entity" id="id-entity">
            <option value="c0" selected>Certificate</option>
            <option value="c1">Agreement</option>
            <option value="c2">Agreement2</option>
            <option value="c3">Agreement3</option>
          </select>
        </div>
      </div>
      <div class="col-md-2">
        <label for="certificate">Certificate #</label>
        <input
          type="text"
          class="form-control"
          name="certificate"
          id="id-certificate"
          aria-describedby="helpId"
          placeholder="12345"
        />
      </div>
      <div class="col-md-2">
        <label for="policy">Policy #</label>
        <input
          type="text"
          class="form-control"
          name="policy"
          id="id-policy"
          aria-describedby="helpId"
          placeholder="12345"
        />
      </div>
      <div class="col-md-2">
        <label for="carrier">Carrier</label>
        <input
          type="text"
          class="form-control"
          name="carrier"
          id="id-carrier"
          aria-describedby="helpId"
          placeholder="MEDAVIE"
          value="MEDAVIE"
        />
      </div>
      <div class="col-md-2">
        <div class="form-group">
          <label for="hc-bob">HC-BoB</label>
          <select class="form-control" name="hc-bob" id="id-hc-bob">
            <option value="h0" selected>MBC-IND</option>
            <option value="h1">MBC-IND1</option>
            <option value="h2">MBC-IND2</option>
          </select>
        </div>
      </div>
      <div class="col">
        <div class="col">
          <label></label>
        </div>
        <button type="submit" class="btn btn-primary btn-round">
          <i class="fa fa-search" aria-hidden="true"></i>
        </button>
      </div>
      <div class="col">
        <div class="col">
          <label>Found</label>
        </div>
        <button type="submit" class="btn btn-success btn-round">
          <i class="fa fa-check" aria-hidden="true"></i>
        </button>
      </div>
      <div class="col">
        <div class="col">
          <label>Loaded</label>
        </div>
        <button type="submit" class="btn btn-danger btn-round">
          <i class="fa fa-check" aria-hidden="true"></i>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SetCriteria",
};
</script>

<style lang="scss" scoped>
</style>