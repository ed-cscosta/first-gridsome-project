<template>
  <div>
    <header>
      <nav>
        <a href="#">
          Design Monthly
          <span>FREE</span>
        </a>
        <a href="#">
          <g-image src="~/assets/images/nav_icon.png" alt="nav icon" />
        </a>
      </nav>
      <h1>Work faster with our free design resources and monthly packages.</h1>
      <a href="#" class="btnOutline">Sign Up</a>
    </header>

    <div class="team">
      <h1>
        Our resources are crafted in-house by our talented team of designers
        from various backgrounds.
      </h1>
      <div class="members">
        <div class="person">
          <g-image src="~/assets/images/david_coyle_img.png" alt="profile icon" />
          <h3>David Coyle</h3>
          <p>4 years of Visual Design</p>
        </div>
        <div class="person">
          <g-image src="~/assets/images/mary_hutton_img.png" alt="profile icon" />
          <h3>Marry Hutton</h3>
          <p>7 years of UI/UX</p>
        </div>
        <div class="person">
          <g-image src="~/assets/images/james_hillman_img.png" alt="profile icon" />
          <h3>James Hillman</h3>
          <p>5 years of User Interaction</p>
        </div>
      </div>
    </div>

    <div class="about">
      <h1>
        Each month we create hundreds of resources for you to use in commercial
        and non-commercial projects.
      </h1>
      <div class="icons">
        <g-image src="~/assets/images/xd_icon.png" alt="Adobe Xd Icon" />
        <g-image src="~/assets/images/sketch_icon.png" alt="SketchApp Icon" />
      </div>
    </div>

    <div class="callToAction">
      <h1>Sign Up Now</h1>
      <a href="#" class="btnFilled">Get Started</a>
    </div>

    <footer>
      <p>© 2020 Design Monthly</p>
      <div class="footerPages">
        <a href="#">Home</a>
        <a href="#">Resources</a>
        <a href="#">Monthly</a>
        <a href="#">Terms</a>
        <a href="#">Privacy</a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  metaInfo: {
    title: "Home"
  }
};
</script>