<template>
  <div id="app">
    <div>
      <aside>
        <!--Sidebar User Profile Start-->
        <div>
          <img src="http://tristanelliott.co.za/development/users/User1.jpg" alt="Users Profile Picture">
          <h2>Tristan Elliott</h2>
          <p>Developer</p>
        </div>
        <!--Sidebar User Profile End-->
        <!--Menu Links Start-->
        <h4>General</h4>
        <div>
          <a href="#">Home</a>
          <a href="#">Friends</a>
          <a href="#">Messages</a>
          <a href="#">Notifications</a>
          <a href="#">Project Invites</a>
        </div>
        <h4>Settings</h4>
        <div>
          <a href="#">General Settings</a>
          <a href="#">Profile Settings</a>
          <a href="#">Privacy Settings</a>
          <a href="#">Social Settings</a>
        </div>
        <!--Menu Links End-->
      </aside>
      <div>
        <header>
          <!--Main Top Navigation Start-->
            <nav>
              <!--Search Input Start-->
              <div>
                <form>
                  <div>
                    <label for="search">Search Here</label>
                    <input type="text" name="search" id="search" placeholder="Search ...">
                  </div>
                </form>
              </div>
              <!--Search Input End-->
              <!--Account Information Start-->
              <div class="nav-dropdown">
                <span class="dropdown-button">Username</span>
                <ul>
                  <li><a href="#">Profile</a></li>
                  <li><a href="#">Friends</a></li>
                  <li><a href="#">Messages</a></li>
                  <li><a href="#">Logout</a></li>
                </ul>
              </div>
              <!--Account Information End-->
            </nav>
          <!--Main Top Navigation End-->
        </header>
        <main>
        <!--Main Content Start-->
          <h1>Main Content</h1>
        <!--Main Content End-->
        </main>
        <footer>
        <!--Main Footer Start-->
          <p>All rights reserved <a href="http://tristanelliott.co.za">Tristan Elliott</a></p>
        <!--Main Footer End-->
        </footer>
      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {
    // Component Import
  }
}
</script>

<style>

</style>
