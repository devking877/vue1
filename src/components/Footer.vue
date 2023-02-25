<script>
  import { MDBFooter, MDBContainer, MDBRow, MDBCol, MDBIcon, MDBBtn } from 'mdb-vue-ui-kit';

  export default {
    components: {
      MDBFooter,
      MDBContainer,
      MDBRow,
      MDBCol,
      MDBIcon,
      MDBBtn
    },
  };
</script>
<template>
    <!-- Footer -->
    <MDBFooter bg="light" :text="['center', 'purple']">
      <!-- Grid container -->
      <MDBContainer class="p-4">
        <div style="display: flex; color:purple">
        <!-- Section: Form -->
        <section class="">
          <form action="">
            <!--Grid row-->
            <MDBRow center class="d-flex">
              <!--Grid column-->
              <div style="margin-right: 70%;">Get HUMAN news and updates</div>
              <div style="display: flex; align-items: flex-start;">
                <input placeholder="your@email.com" style="border-radius: 4px; border-color: purple;">
                <button style="background-color: purple; border-radius: 4px; " class="mb-4"> Subscribe </button>
              </div>
              <strong style="margin-right: 70%">By subscribing you agree to our Privacy Policy</strong>
              <!--Grid column-->
            </MDBRow>
            <!--Grid row-->
          </form>
        </section>
        <!-- Section: Form -->
        <!-- Section: Social media -->
        <section class="mb-4">
          <!-- Facebook -->
          <a
            class="btn btn-outline-dark btn-floating m-1"
            href="#!"
            role="button"
            ><MDBIcon iconStyle="fab" icon="facebook-f"
          /></a>
          <!-- Twitter -->
          <a
            class="btn btn-outline-dark btn-floating m-1"
            href="#!"
            role="button"
            ><MDBIcon iconStyle="fab" icon="twitter"
          /></a>
          <!-- Google -->
          <a
            class="btn btn-outline-dark btn-floating m-1"
            href="#!"
            role="button"
            ><MDBIcon iconStyle="fab" icon="google"
          /></a>
          <!-- Instagram -->
          <a
            class="btn btn-outline-dark btn-floating m-1"
            href="#!"
            role="button"
            ><MDBIcon iconStyle="fab" icon="instagram"
          /></a>
          <!-- Linkedin -->
          <a
            class="btn btn-outline-dark btn-floating m-1"
            href="#!"
            role="button"
            ><MDBIcon iconStyle="fab" icon="linkedin-in"
          /></a>
          <!-- Github -->
          <a
            class="btn btn-outline-dark btn-floating m-1"
            href="#!"
            role="button"
            ><MDBIcon iconStyle="fab" icon="github"></MDBIcon
          ></a>
        </section>
        <!-- Section: Social media -->
        </div>
        <!-- Section: Links -->
        <section class="">
          <!--Grid row-->
          <MDBRow style="color: purple">
            <!--Grid column-->
            <MDBCol lg="2" md="6" class="mb-4 mb-md-0">
              <h5 class="text">Products</h5>
              <ul class="list-unstyled mb-0">
                <li>
                  <a href="#!" class="text-black">HUMAN App</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Proof of HUMANity</a>
                </li>
                <li>
                  <a href="#!" class="text-black">IMOO</a>
                </li>
              </ul>
            </MDBCol>
            <!--Grid column-->
            <!--Grid column-->
            <MDBCol lg="2" md="6" class="mb-4 mb-md-0">
              <h5 class="text">Discover</h5>
              <ul class="list-unstyled mb-0">
                <li>
                  <a href="#!" class="text-black">Token</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Routing Layer</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Team</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Career</a>
                </li>
              </ul>
            </MDBCol>
            <!--Grid column-->
            <!--Grid column-->
            <MDBCol lg="2" md="6" class="mb-4 mb-md-0">
              <h5 class="text">Build</h5>
              <ul class="list-unstyled mb-0">
                <li>
                  <a href="#!" class="text-black">Developers</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Technology</a>
                </li>
                <li>
                  <a href="#!" class="text-black">DevBounty Program</a>
                </li>
                <li>
                  <a href="#!" class="text-black">BugBounty Program</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Github</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Grants Program</a>
                </li>
              </ul>
            </MDBCol>
            <!--Grid column-->
            <!--Grid column-->
            <MDBCol lg="2" md="6" class="mb-4 mb-md-0">
              <h5 class="text">Community</h5>
              <ul class="list-unstyled mb-0">
                <li>
                  <a href="#!" class="text-black">Grants Program</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Elite Ops Program</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Events</a>
                </li>
              </ul>
            </MDBCol>
            <!--Grid column-->
            <!--Grid column-->
            <MDBCol lg="2" md="6" class="mb-4 mb-md-0">
              <h5 class="text">Resources</h5>
              <ul class="list-unstyled mb-0">
                <li>
                  <a href="#!" class="text-black">Documents Hub</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Litepaper</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Technical Whitepaper</a>
                </li>
                <li>
                  <a href="#!" class="text-black">AI Whitepaper</a>
                </li>
                <li>
                  <a href="#!" class="text-black">System Status</a>
                </li>
                <li>
                  <a href="#!" class="text-black">In the News</a>
                </li>
                <li>
                  <a href="#!" class="text-black">One Pagers Archive</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Brand Assets</a>
                </li>
              </ul>
            </MDBCol>
            <!--Grid column-->
            <!--Grid column-->
            <MDBCol lg="2" md="6" class="mb-4 mb-md-0">
              <h5 class="text">Impact Projects</h5>
              <ul class="list-unstyled mb-0">
                <li>
                  <a href="#!" class="text-black">Blog</a>
                </li>
                <li>
                  <a href="#!" class="text-black">Explorer</a>
                </li>
              </ul>
            </MDBCol>
            <!--Grid column-->
          </MDBRow>
          <!--Grid row-->
        </section>
        <!-- Section: Links -->
      </MDBContainer>
      <!-- Grid container -->
      <!-- Copyright -->
      <div
        class="text-center p-3"
        style="background-color: rgba(0, 0, 0, 0.2)"
      >
        © 2021 HPF. HUMAN Protocol® is a registered trademark
      </div>
      <!-- Copyright -->
    </MDBFooter>
    <!-- Footer -->
  </template>