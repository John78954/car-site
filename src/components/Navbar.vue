<template>
    <div>
        <mdb-navbar expand="large" dark color="blue">
          <router-link to="/">
            <mdb-navbar-brand>
            Car Site
            </mdb-navbar-brand>
          </router-link>
            <mdb-navbar-toggler>
            <mdb-navbar-nav right>
                <router-link to="/"><mdb-nav-item active>Home</mdb-nav-item></router-link>
                <router-link to="/about"><mdb-nav-item active>About</mdb-nav-item></router-link>
                <router-link to="/used-cars"><mdb-nav-item active>Used Cars</mdb-nav-item></router-link>
                <router-link to="/contact"><mdb-nav-item active>Contact</mdb-nav-item></router-link>
                <mdb-dropdown tag="li" class="nav-item">
                <mdb-dropdown-toggle tag="a" navLink slot="toggle" waves-fixed>Car Brands</mdb-dropdown-toggle>
                <mdb-dropdown-menu>
                    <mdb-dropdown-item>Toyota</mdb-dropdown-item>
                    <mdb-dropdown-item>Honda</mdb-dropdown-item>
                    <mdb-dropdown-item>Ram</mdb-dropdown-item>
                    <mdb-dropdown-item>Chevy</mdb-dropdown-item>
                    <mdb-dropdown-item>Other</mdb-dropdown-item>
                </mdb-dropdown-menu>
                </mdb-dropdown>
            </mdb-navbar-nav>
            </mdb-navbar-toggler>
        </mdb-navbar>
    </div>
</template>

<script>
  import { mdbDropdown, mdbDropdownToggle, mdbDropdownMenu, mdbDropdownItem, mdbNavbar, mdbNavbarBrand, mdbNavbarToggler, mdbNavbarNav, mdbNavItem } from 'mdbvue';
  export default {
    name: 'Navbar',
    components: {
      mdbNavbar,
      mdbNavbarBrand,
      mdbNavbarToggler,
      mdbNavbarNav,
      mdbNavItem,
      mdbDropdown,
      mdbDropdownToggle,
      mdbDropdownMenu,
      mdbDropdownItem
    }
  }
</script>

<style scoped>

</style>