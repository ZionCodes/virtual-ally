<script>
	import Hero from "$lib/Hero.svelte";
	import Benefits from "../lib/Benefits.svelte";
	import Cta from "../lib/CTA.svelte";
	import Faq from "../lib/Faq.svelte";
	import Features from "../lib/Features.svelte";
	import Operation from "../lib/Operation.svelte";
	import Pricing from "../lib/Pricing.svelte";
	import Services from "../lib/Services.svelte";
	import Testimonial from "../lib/Testimonial.svelte";
	import SvelteSeo from "svelte-seo";

</script>

<SvelteSeo
title="Virtual Ally | Tech-Savvy Virtual Assistant for Entrepreneurs"
description="Boost your productivity with our tech-savvy virtual assistant services. Expert support in email management, digital marketing, project management, and more."
canonical="https://www.virtualally.pro/"
keywords="virtual assistant, tech-savvy VA, email management, calendar optimization, social media management, project management, digital marketing, automation, CRM, entrepreneur support"
openGraph={{
title: "Virtual Ally | Tech-Savvy Virtual Assistant for Entrepreneurs",
description:
"Elevate your business with personalized, tech-savvy virtual assistance. From email management to automation setup, we've got you covered.",
image: "/default.svg",
url: "https://www.virtualally.pro/",
type: "website",
site_name: "Virtual Ally",
}}
twitter={{
card: "summary_large_image",
site: "@virtualallypro",
title: "Virtual Ally | Tech-Savvy Virtual Assistant for Entrepreneurs",
description:
"Boost your productivity with our tech-savvy virtual assistant services. Expert support in email management, digital marketing, project management, and more.",
image: "/default.svg",
}}
facebook={{
appId: "1234567890",
}}
/>


<Hero />
<Features />
<Testimonial />
<Operation />
<Benefits />
<Services />
<Pricing />
<Faq />
<Cta />