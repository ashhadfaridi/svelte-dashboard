<script>
  export let segment;
  export let isOpen = true;

  import MDBListGroup from 'mdbsvelte/src/MDBListGroup.svelte';
  import MDBListGroupItem from 'mdbsvelte/src/MDBListGroupItem.svelte';
  import MDBIcon from 'mdbsvelte/src/MDBIcon.svelte';
  import MDBNavLink from 'mdbsvelte/src/MDBNavLink.svelte';
  import {Navigate} from 'svelte-router-spa';
</script>

{#if isOpen}
  <div class="sidebar-fixed position-fixed">
    <a href="#!" class="logo-wrapper waves-effect">
      <h3 style="text-align: center;
      margin-bottom: 30px;
      margin-top: 18px;
      margin-left: 25px;">
       <strong> Dashboard</strong>
      </h3>
      <!-- <img alt="MDB React Logo" class="img-fluid" src="mdbsvelte.png" /> -->
    </a>
    <MDBListGroup class="list-group-flush">
      <div class="dropdown">
        <button onclick="myFunction()" class="dropbtn"
          >Interstate Congestion Report</button
        >
        <div id="myDropdown" class="dropdown-content">
          <a href="#home">Item1</a>
          <a href="#about">Item2</a>
          <a href="#contact">Item3</a>
        </div>
      </div>

      <div class="dropdown1">
        <button onclick="myFunction1()" class="dropbtn1"
          >DropDown1</button
        >
        <div id="myDropdown1" class="dropdown-content1">
          <a href="#home">Item1</a>
          <a href="#about">Item2</a>
          <a href="#contact">Item3</a>
        </div>
      </div>

     
    </MDBListGroup>
  </div>
{/if}
