<script>
    import "../app.css";
    import Navbar from '../lib/navbar.svelte';
	import Footer from '../lib/footer.svelte';

  </script>
  
  <div class="min-h-screen bg-white flex-col items-center">
	<Navbar />
	<slot />
	<Footer />
</div>