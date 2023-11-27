<svelte:head>
    <title>Paradigm Pet Professionals</title>
    <meta name="description" content="Paradigm Pet Professionals - evidence-based pet care advice for every pet lover.">
</svelte:head>
<script>
  import ContactForm from "../components/ContactForm.svelte";

</script>
<div class="px-4 py-5 my-4 text-center" style="background-image:url('/hero.jpg');background-size:cover;background-repeat:no-repeat;background-position:center;box-shadow: inset 0 0 0 1000px rgba(255,255,255,.7);border-bottom:2px black solid;">
    <h1 class="display-5 fw-bold text-body-emphasis">Paradigm Pet Professionals</h1>
    <div class="col-lg-6 mx-auto">
      <h2 class="lead mb-2">At Paradigm Pet Professionals, our mission is to offer resources to help you care for your furry, scaly, feathery, and slimy loved ones.</h2>
      <h3>Learn how to care for:</h3>
      <div class="d-grid gap-2 d-sm-flex justify-content-sm-center">
        <a href="/cats" class="btn btn-primary btn-lg px-4">Cats</a>
        <a href="/dogs" class="btn btn-primary btn-lg px-4 mx-4">Dogs</a>
        <a href="/fish" class="btn btn-primary btn-lg px-4">Fish</a>
      </div>
    </div>
</div>
<div class="container text-center mb-4">
  <h2 class="display-6 fw-bold text-body-emphasis">Pets are nature's gift to humanity</h2>
  <p class="lead">It has been scientifically proven that opening our homes and hearts to a pet increases our longevity and improves our overall quality of life as well as the lives of our pets.</p>
  <p class="lead">Our pet experts—or “Pexperts”—have been working with pet owners and professionals alike for the past twelve years. They offer one-on-one consultations with current and prospective pet owners as well as group presentations designed for veterinary, pet shelter, and pet breeding professionals.</p>
  <p class="lead">Looking for basic pet care advice for the most common type of pets? Need additional help determining which type of pet is right for you and your family? We will work with you and provide tailored evidence-based pet care to ensure lifelong health and wellness of your new companion.</p>
</div>
<div class="container text-center mb-4">
  <h2 class="display-6 fw-bold text-body-emphasis">Looking for your new best friend?</h2>
  <p class="lead">The following organizations can help you find and adopt the perfect companion:</p>
  <ul class="mb-4 lead" style="list-style:none;">
    <li>General Adoption Resources: <a href="https://theshelterpetproject.org/" target="_blank">https://theshelterpetproject.org/</a></li>
    <li>ASPCA: <a href="https://www.aspca.org/" target="_blank">https://www.aspca.org/</a></li>
    <li>Fish Rescue: <a href="https://www.sterlingshelter.org/humane-society/koi-fish-rescue/" target="_blank">https://www.sterlingshelter.org/humane-society/koi-fish-rescue/</a></li>
    <li>Snake Rescue: <a href="https://savethesnakes.org/snakerescuecall/" target="_blank">https://savethesnakes.org/snakerescuecall/</a></li>
    <li>Bird Rescue: <a href="https://ftlob.rescuegroups.org/" target="_blank">https://ftlob.rescuegroups.org/</a></li>
  </ul>
  <p class="lead">We are also happy to help you navigate the adoption process! We will guide you through each step in the process from determining which type of pet is best suited for your family and home environment, to completing the necessary paperwork, to bringing your new loved one home. Please fill out our contact form to request a consultation. We will contact you within 48 hours to schedule a consultation. All fields are required.</p>
</div>
<div class="container">
    <ContactForm />
</div>