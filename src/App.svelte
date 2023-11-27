<script>
  import Header from './components/Header.svelte';
  import Home from './pages/Home.svelte';
  import Cats from './pages/Cats.svelte';
  import Dogs from './pages/Dogs.svelte';
  import Fish from './pages/Fish.svelte';
  import Contact from './pages/Contact.svelte';
  import {Route} from 'tinro'; 
</script>

<Header />
<main>
  <Route path="/"><Home /></Route>
  <Route path="/cats"><Cats /></Route>
  <Route path="/dogs"><Dogs /></Route>
  <Route path="/fish"><Fish /></Route>
  <Route path="/contact"><Contact /></Route>
</main>
<div class="text-center">
  <p class="lead">&copy;2023 Paradigm Pet Professionals</p>
</div>