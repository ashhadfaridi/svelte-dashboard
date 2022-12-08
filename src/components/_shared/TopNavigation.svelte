<script>
  import MDBNavbar from "mdbsvelte/src/MDBNavbar.svelte";
  import MDBNavbarBrand from "mdbsvelte/src/MDBNavbarBrand.svelte";
  import MDBNavbarNav from "mdbsvelte/src/MDBNavbarNav.svelte";
  import MDBNavbarToggler from "mdbsvelte/src/MDBNavbarToggler.svelte";
  import MDBCollapse from "mdbsvelte/src/MDBCollapse.svelte";
  import MDBNavItem from "mdbsvelte/src/MDBNavItem.svelte";
  import MDBNavLink from "mdbsvelte/src/MDBNavLink.svelte";
  import MDBIcon from "mdbsvelte/src/MDBIcon.svelte";

  let collapse = false;
  function toggle() {
    collapse = !collapse
  }

  function handleUpdate(event) {
    collapse = event.detail.isOpen;
  }

</script>

<MDBNavbar class="flexible-navbar" light expand="md">
  <MDBNavbarBrand href="/">
    <strong></strong>
  </MDBNavbarBrand>
  <MDBNavbarToggler on:click = { toggle } />
  <MDBCollapse isOpen = { collapse } navbar expand="md" on:update={handleUpdate}>
    <MDBNavbarNav left>
      <MDBNavItem >
        <MDBNavLink to="#"><strong>Home</strong></MDBNavLink>
      </MDBNavItem>
    </MDBNavbarNav>
    <MDBNavbarNav right>
    
    </MDBNavbarNav>
  </MDBCollapse>
</MDBNavbar>
