<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Innovation",
			description: "Constantly challenging the status quo to create better solutions."
		},
		{
			title: "Integrity",
			description: "Building trust through transparent actions and honest communication."
		},
		{
			title: "Impact",
			description: "Measuring our success by the positive change we create for our clients."
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
<Culture {values} generating />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	generating
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	generating
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	generating
	title="Ready to collaborate?"
	subtitle="Let's create something amazing"
	description="Join the companies already leveraging our expertise to transform their digital presence and achieve their business goals."
/>
