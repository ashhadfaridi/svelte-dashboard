<script>
  import AdminCardSection1 from './sections/AdminCardSection1.svelte'
  import AdminCardSection2 from './sections/AdminCardSection2.svelte'
  import BreadcrumbSection from './sections/BreadcrumbSection.svelte'
  import ChartSection1 from './sections/ChartSection1.svelte'
  import ChartSection2 from './sections/ChartSection2.svelte'
  import TableSection from './sections/TableSection.svelte'
  import ModalSection from './sections/ModalSection.svelte'
  import MDBContainer from 'mdbsvelte/src/MDBContainer.svelte'
</script>
<MDBContainer fluid>
  <iframe src="https://reactor.ctre.iastate.edu/interstate-delay-cost-summary/" height="700" width="1300" title="Iframe Example"></iframe>
  <!-- <BreadcrumbSection />
  <AdminCardSection1 />
  <ChartSection1 />
  <TableSection />
  <ChartSection2 />
  <ModalSection />
  <AdminCardSection2 /> -->
</MDBContainer>
