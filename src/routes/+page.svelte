<script lang="ts">
	import Header from "$lib/components/Header.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import TransformationSection from "$lib/components/TransformationSection.svelte";
	import WorkflowsSection from "$lib/components/WorkflowsSection.svelte";
	import TrustedData from "$lib/components/TrustedData.svelte";
	import FeaturesGrid from "$lib/components/FeaturesGrid.svelte";
	import SecuritySection from "$lib/components/SecuritySection.svelte";
	import TestimonialSection from "$lib/components/TestimonialSection.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<main class="min-h-screen bg-white font-sans text-gray-900 selection:bg-gray-900 selection:text-white">
	<Header />
	<Hero />
	<TransformationSection />
	<WorkflowsSection />
	<TrustedData />
	<FeaturesGrid />
	<SecuritySection />
	<TestimonialSection />
	<Footer />
</main>

