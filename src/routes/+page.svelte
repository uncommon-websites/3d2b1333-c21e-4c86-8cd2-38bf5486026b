<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Find top candidates instantly"
	subtitle="Skip the noise. Hire the best fast."
	imageSrc="/generated/image-a-professional-hiring-manager-sits-at-a-.webp"
	centered={true}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/gitlab.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/spotify.com/w/400/h/400/logo'
	]}
/>

<Summary
<<<<<<< HEAD
	title="Signal, not noise"
	text="Stop wasting hours on resumes that lead nowhere. Our AI analyzes every applicant and surfaces the top 1% instantly—so your team can focus on interviews, not inboxes. Built for busy tech teams overwhelmed by applicants, we help you find exceptional talent without slowing down."
=======
	title="What we do"
	text="Stop wasting hours on resumes that go nowhere. Our AI-powered hiring assistant instantly analyzes large applicant pools and surfaces the top 1%—so your team can focus on interviews, not screening.

More applications don't mean better candidates. We help hiring managers at fast-growing tech companies cut through the volume and zero in on applicants with the clearest signals of success—before your competitors do."
>>>>>>> 214f5e022b562ec6dc4bacf90ff1fc5ed78a4818
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Chen",
			position: "VP of Engineering",
			company: "StreamTech",
			quote:
				"We reduced our time-to-hire from 6 weeks to 10 days while improving candidate quality by 40%. The AI immediately surfaced exceptional candidates we would have missed in traditional screening.",
			image: "/generated/image-a-professional-asian-woman-tech-executiv.webp"
		},
		{
			name: "Marcus Williams",
			position: "Head of Talent Acquisition",
			company: "Velocity Labs",
			quote:
				"This saved us $180K in the first quarter alone by eliminating wasted interviews with unqualified candidates. Our hiring accuracy went from 65% to 92% - we're finally hiring the right people fast.",
			image: "/generated/image-a-professional-black-man-in-a-hiring-lea.webp"
		},
		{
			name: "Sofia Rodriguez",
			position: "Engineering Director",
			company: "Apex Systems",
			quote:
				"Before this, 80% of my team's time was spent screening resumes. Now we focus on interviewing only the top 1% candidates. It's transformed how we build our technical teams.",
			image: "/generated/image-a-professional-latina-woman-engineering-.webp"
		}
	]}
/>

<Features
	title="Signal, not noise"
	subtitle="Stop wasting hours on resumes that go nowhere. Our AI analyzes every applicant and surfaces the top 1% instantly."
	features={[
		{
			title: "AI signal detection",
			description:
				"Our AI-native platform filters out unqualified candidates and highlights those with the clearest signals of success. Never miss your next top performer in the noise."
		},
		{
			title: "Built for high-volume recruiting",
			description:
				"Designed for fast-moving tech teams overwhelmed by applicant volume. Whether you're hiring 5 people or 500, we help you find exceptional talent without slowing down."
		},
		{
			title: "Pattern recognition that learns",
			description:
				"Unlike retrofitted hiring tools, our platform was designed from day one to zero in on what actually matters. It learns patterns, understands context, and gets smarter with every role."
		},
		{
			title: "Make faster, more confident decisions",
			description:
				"You don't need more resumes—you need clarity. Our assistant cuts through the noise and recommends the right candidates right away, so you can move fast and never second-guess."
		},
		{
			title: "Focus on interviews, not inboxes",
			description:
				"Stop spending 80% of your time screening unqualified candidates. Our AI does the heavy lifting so your team can focus on what matters most: great conversations with great people."
		},
		{
			title: "No complex setup required",
			description:
				"Get started in minutes with no training needed. Just plug into your hiring stack and let the assistant do the heavy lifting while you focus on building your team."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
