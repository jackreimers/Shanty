<script>
	import Hero from '$lib/components/layout/hero.svelte';
	import Container from '$lib/components/layout/container.svelte';
	import Accordian from '$lib/components/elements/accordian.svelte';
</script>

<svelte:head>
	<title>Bunbury Sea Shanty Festival | FAQ</title>
</svelte:head>

<Hero>
	<div slot="content">
		<p class="mb-4 text-2xl font-bold lg:text-4xl">Frequently Asked Questions</p>
		<p class="max-w-prose">
			Fermentum dui faucibus in ornare quam viverra orci. Non diam phasellus vestibulum lorem
			sed risus ultricies tristique nulla.
		</p>
	</div>
</Hero>

<Container>
	<h2 class="mb-4 text-2xl font-semibold">Entertainers</h2>
	<div class="mb-12 flex w-full flex-col gap-4">
		<Accordian>
			<p slot="title">How can I apply to perform at the Bunbury Shanty Music Festival?</p>
			<p slot="content">
				Ahoy there, matey! We're thrilled to have you interested in performing at our
				festival. To apply, simply fill out the contact form.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Is the festival open to all types of shanty music?</p>
			<p slot="content">
				Absolutely! We love to celebrate the diversity of shanty music. Whether you perform
				traditional maritime shanties, modern interpretations, or even fusion genres, we
				welcome it all. If it's got that sea-faring spirit, we want to hear it!
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Do I need to have prior experience performing shanty music to apply?</p>
			<p slot="content">
				Avast ye! While prior experience with shanty music is always a plus, we encourage
				musicians of all levels to apply. Passion and enthusiasm for shanties are what truly
				matters. So, if you're ready to rock the boat, don't hesitate to apply!
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">How are performers selected for the festival?</p>
			<p slot="content">
				Arrr! Our crew of experienced curators listens to every application and evaluates
				each performer based on their unique style, talent, and suitability for the
				festival. We strive to create a diverse and engaging lineup that captivates our
				audience.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Will I get paid for my performance?</p>
			<p slot="content">
				Shiver me timbers, we believe in fair compensation! While we can't disclose specific
				details here, rest assured that selected performers will receive compensation for
				their performances. We value your talent and want to support you.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Can I sell merchandise at the festival?</p>
			<p slot="content">
				Aye, matey! We encourage performers to bring their merchandise and set up a booth at
				our festival. It's a great opportunity to showcase your CDs, merchandise, and other
				swag to our enthusiastic audience. Aye, aye, business-savvy buccaneer!
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Are there any specific technical requirements for performers?</p>
			<p slot="content">
				Avast ye, we've got your back! Our festival provides a basic sound system and stage
				equipment. However, if you have specific technical requirements, please let us know
				in your application. We'll do our best to accommodate your needs.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Can I request a specific performance time or day?</p>
			<p slot="content">
				Yarrr! We'll certainly take your preferences into consideration, but scheduling can
				be a bit like navigating stormy seas. We'll communicate with you to determine the
				best performance times and days based on the overall festival schedule.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">
				Can I bring my band or additional musicians to accompany my performance?
			</p>
			<p slot="content">
				Absolutely! The more, the merrier! If you have a band or additional musicians you'd
				like to perform with, please let us know in your application. We'll work with you to
				ensure a seamless and harmonious performance.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">How can I contact the festival organizers for further questions?</p>
			<p slot="content">
				Yo ho ho! If you have any further questions, feel free to reach out to our friendly
				festival organisers by emailing entertainer@bunburyshantyfest.au. We're here to help
				and provide all the information you need to make your performance a success!
			</p>
		</Accordian>
	</div>

	<h2 class="mb-4 text-2xl font-semibold">Volunteers</h2>
	<div class="mb-12 flex w-full flex-col gap-4">
		<Accordian>
			<p slot="title">What is this question?</p>
		</Accordian>
		<Accordian>
			<p slot="title">What about this question?</p>
		</Accordian>
	</div>

	<h2 class="mb-4 text-2xl font-semibold">Sponsors</h2>
	<div class="mb-12 flex w-full flex-col gap-4">
		<Accordian>
			<p slot="title">What is this question?</p>
		</Accordian>
		<Accordian>
			<p slot="title">What about this question?</p>
		</Accordian>
	</div>
</Container>
