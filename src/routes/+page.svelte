<script>
  import Header from "../components/Header/Header.svelte";
  import SectionDifferent from "../components/Section/SectionDifferent.svelte";
  import SectionDiscover from "../components/Section/SectionDiscover.svelte";
  import SectionEnjoy from "../components/Section/SectionEnjoy.svelte";
</script>

<style>
  @import '../style/global.css';
  @import url('https://fonts.googleapis.com/css2?family=Clicker+Script&family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&display=swap');
</style>

<div>
  <Header/>
  <SectionDiscover/>
  <SectionEnjoy/>
  <SectionDifferent/>
</div>
