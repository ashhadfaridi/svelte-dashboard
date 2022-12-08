<script>
  import MDBCard from 'mdbsvelte/src/MDBCard.svelte';
  import MDBCardBody from 'mdbsvelte/src/MDBCardBody.svelte';
  import MDBRow from 'mdbsvelte/src/MDBRow.svelte'
  import MDBCol from 'mdbsvelte/src/MDBCol.svelte'
  import MDBTable from 'mdbsvelte/src/MDBTable.svelte'
  import MDBTableHead from 'mdbsvelte/src/MDBTableHead.svelte'
  import MDBTableBody from 'mdbsvelte/src/MDBTableBody.svelte'
  import MDBView from 'mdbsvelte/src/MDBView.svelte'

</script>
<MDBRow>
  <MDBCol md="12">
    <MDBCard class="mt-5">
      <MDBView class="gradient-card-header blue darken-2">
        <h4 class="h4-responsive text-white">Basic</h4>
      </MDBView>
      <MDBCardBody>
        <h3 class="mt-5 text-left"><strong>Basic examples</strong></h3>
        <p>Using the most basic table markup, here’s how .table-based tables look in Bootstrap. All table styles are inherited in Bootstrap 4, meaning any nested tables will be styled in the same manner as the parent.</p>
      </MDBCardBody>
    </MDBCard>
  </MDBCol>
</MDBRow>
