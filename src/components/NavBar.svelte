<script>
</script>

<header class="fixed w-full">
  <nav class="bg-white shadow-lg">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex justify-between">
        <div class="flex space-x-7">
          <!-- Logo -->
          <div class="logo">
            <a href="/" class="flex items-center py-4 px-2">
              <span
                class="font-bold bg-gradient-55 bg-clip-text text-transparent text-2xl"
              >
                Carrels
              </span>
            </a>
          </div>
          <!-- Navbar Menu -->
          <div class="hidden md:flex items-center space-x-1">
            <a href="/" class="navbar-menu hover:text-green-500 active">Home</a>
            <a href="/" class="navbar-menu hover:text-green-500">About</a>
            <a href="/" class="navbar-menu hover:text-green-500">Contact</a>
          </div>
        </div>
        <!-- Secondary Navbar items -->
        <div class="hidden md:flex items-center space-x-3">
          <a href="/" class="login bg-gradient-55 text-white">Login</a>
          <a
            href="/"
            class="signup text-gray-500 border-1 hover:bg-gradient-49 hover:text-white"
            >Sign Up</a
          >
        </div>
        <!-- Mobile menu -->
        <div class="md:hidden flex items-center">
          <button class="outline-none mobile-menu-button">
            <svg
              class=" w-6 h-6 text-gray-500 hover:text-green-500 "
              x-show="!showMenu"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path d="M4 6h16M4 12h16M4 18h16" />
            </svg>
          </button>
        </div>
      </div>
    </div>
  </nav>
</header>

<style>
  .navbar-menu {
    @apply py-4 px-2 text-gray-500 font-semibold transition duration-300;
  }
  .active {
    @apply text-green-500;
  }
  .login,
  .signup {
    @apply py-2 px-2 w-20 text-center font-medium text-gray-500 rounded transition duration-300;
  }
</style>
