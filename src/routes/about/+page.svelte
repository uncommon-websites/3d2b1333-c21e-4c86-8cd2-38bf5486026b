<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Signal over noise",
			description: "We believe the best talent shouldn't be buried under volume. Our AI cuts through the noise to spotlight exceptional candidates instantly."
		},
		{
			title: "Speed without compromise",
			description: "Fast hiring decisions don't mean sacrificing quality. We help teams identify top 1% talent in minutes, not weeks."
		},
		{
			title: "AI-native precision",
			description: "Built from the ground up for hiring, our technology understands talent patterns that traditional systems miss."
		},
		{
			title: "Human-centered outcomes",
			description: "Technology amplifies human judgment. We create tools that make hiring managers more effective, not obsolete."
		}
	];
</script>

<SecondaryHero
	title="Find brilliance in the noise"
	subtitle="AI that spots top talent instantly"
	imageSrc="/generated/image-a-modern-tech-team-collaborating-in-a-br.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Hiring managers know the pain all too well—hundreds of applications, most of them unqualified. Days lost in resume reviews. Promising candidates buried under noise. It's a system that rewards volume over quality, and it's costing teams their most valuable resource: time. Even worse, great talent often slips through the cracks before anyone ever sees them.",
		"We built something different. Our AI-native platform is designed from the ground up to recognize the subtle signals that separate top performers from the crowd. Unlike retrofitted systems that layer AI on legacy workflows, our technology focuses exclusively on hiring patterns. It analyzes every applicant with precision, highlighting the top 1% without the manual effort. What used to take a full hiring cycle now takes minutes—with better outcomes.",
		"Today, we help high-growth teams transform the way they hire. Imagine reviewing 500 applications and seeing your strongest candidates first—before your competitors do. Our mission is simple: speed without compromise, quality without question. As we scale to capture the $240B recruitment market, we're helping the most ambitious companies find exceptional people—efficiently, confidently, and without the noise."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and Investors sections removed - no founder information or confirmed investors available -->

<!-- CTA Section -->
<CallToAction
	title="Ready to hire smarter?"
	subtitle="Find your next top performer"
	description="Join forward-thinking companies already using AI to transform their hiring process. Stop losing great candidates in the noise—start spotting exceptional talent instantly."
	imageSrc="/generated/image-a-professional-hiring-manager-sits-at-a-.webp"
/>
