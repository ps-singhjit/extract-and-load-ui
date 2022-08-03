<template>
  <div class="container">
    <h3>Details Table</h3>
    <table
      class="table table-striped table-hover table-inverse table-responsive"
    >
      <thead class="thead-inverse">
        <tr class="table-secondary table-primary">
          <th>Cert #</th>
          <th>FirstName</th>
          <th>LastName</th>
          <th>Dob</th>
          <th>Policy #</th>
          <th>Carrier</th>
          <th>HC-BoB</th>
          <th>Generated</th>
          <th>Note</th>
        </tr>
      </thead>
      <tbody v-for="detail in tableDetails" :key="detail.cert">
        <tr>
          <td scope="row">{{ detail.cert }}</td>
          <td>{{ detail.first }}</td>
          <td>{{ detail.last }}</td>
          <td>{{ detail.dob }}</td>
          <td>{{ detail.policy }}</td>
          <td>{{ detail.carrier }}</td>
          <td>{{ detail.bob }}</td>
          <td>{{ detail.generated }}</td>
          <td>
            {{ detail.note }}
            <i class="fa fa-sticky-note-o" aria-hidden="true"></i>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: "DetailsTable",
  data() {
    return {
      tableDetails: [
        {
          cert: 12345,
          first: "tom",
          last: "jerry",
          dob: "1/11/2022",
          policy: 12345,
          carrier: "MBC",
          bob: "IND",
          generated: "yes",
          note: "note",
        },
        {
          cert: 23546,
          first: "tom",
          last: "jerry",
          dob: "1/11/2022",
          policy: 22222,
          carrier: "MBC",
          bob: "IND",
          generated: "yes",
          note: "note",
        },
        {
          cert: 33333,
          first: "tom",
          last: "jerry",
          dob: "1/11/2022",
          policy: 3333,
          carrier: "MBC",
          bob: "IND",
          generated: "yes",
          note: "note",
        },
        {
          cert: 44444,
          first: "tom",
          last: "jerry",
          dob: "1/11/2022",
          policy: 4444,
          carrier: "MBC",
          bob: "IND",
          generated: "yes",
          note: "note",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
</style>