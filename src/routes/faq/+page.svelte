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
		<p class="header text-2xl font-bold lg:text-4xl">Frequently Asked Questions</p>
	</div>
</Hero>

<Container>
	<h2 class="header mb-4 text-3xl font-semibold">Entertainers</h2>
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

	<h2 class="header mb-4 text-3xl font-semibold">Sponsors</h2>
	<div class="mb-12 flex w-full flex-col gap-4">
		<Accordian>
			<p slot="title">What is the Bunbury Shanty Music Festival?</p>
			<p slot="content">
				The Bunbury Shanty Music Festival is an annual event held in Bunbury, Western
				Australia, celebrating the history and culture of sea shanties. It brings together
				talented musicians, enthusiasts, and the local community for a weekend of vibrant
				performances and maritime festivities.
			</p>
		</Accordian>
		<!-- TODO: Gmail email address in below question -->
		<Accordian>
			<p slot="title">How can I become a sponsor of the Bunbury Shanty Music Festival?</p>
			<p slot="content">
				We appreciate your interest in sponsoring our festival! Please reach out to our
				sponsorship team complete the contact form or by emailing
				bunburyshantyfestival@gmail.com. They will provide you with more details about the
				available sponsorship opportunities and benefits.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">
				What are the benefits of sponsoring the Bunbury Shanty Music Festival?
			</p>
			<p slot="content">
				As a sponsor, you'll gain valuable exposure to a diverse audience of sea shanty
				enthusiasts and music lovers. Your brand will be prominently displayed throughout
				the festival grounds, and you'll have the opportunity to engage with attendees
				through various promotional activities. Additionally, you'll be supporting and
				contributing to the cultural heritage of sea shanties.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Are there different sponsorship packages available?</p>
			<p slot="content">
				Yes, we offer various sponsorship packages tailored to meet the unique needs and
				budgets of our sponsors. Our sponsorship team will work closely with you to
				determine the best package that aligns with your goals and objectives.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Can I promote my products/services during the festival?</p>
			<p slot="content">
				Absolutely! Depending on your sponsorship package, you may have the opportunity to
				set up a booth or display area to showcase your products/services. This allows you
				to directly engage with festival attendees and promote your brand in a lively and
				festive atmosphere.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">
				Can I have my company logo featured in festival promotional materials?
			</p>
			<p slot="content">
				Yes, as a sponsor, your company logo will be prominently displayed on our festival
				website, social media platforms, and select promotional materials. This provides
				valuable exposure to our audience and helps build brand recognition.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Can I sponsor a specific musical act or stage?</p>
			<p slot="content">
				Yes, we offer sponsorship opportunities for individual musical acts or stages. This
				allows you to align your brand with specific performances that resonate with your
				target audience. Contact our sponsorship team to discuss the available options.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Are there any exclusive sponsorship opportunities?</p>
			<p slot="content">
				Yes, we have limited exclusive sponsorship opportunities available. These provide
				maximum visibility and recognition for your brand throughout the festival. Please
				inquire with our sponsorship team for more details.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">How can I measure the impact of my sponsorship?</p>
			<p slot="content">
				We provide post-event reports that outline the reach and engagement of the festival,
				including attendance numbers, social media metrics, and media coverage. This will
				help you measure the impact of your sponsorship and evaluate the return on your
				investment.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">
				Who can I contact for further information or to discuss sponsorship options?
			</p>
			<p slot="content">
				For more information or to discuss sponsorship opportunities, please contact our
				sponsorship team at bunburyshantyfestival@gmail.com. They will be happy to assist
				you and provide all the necessary details. Please note that the answers provided
				here are fictional and should be tailored to fit the specific details and
				requirements of the Bunbury Shanty Music Festival.
			</p>
		</Accordian>
	</div>

	<h2 class="header mb-4 text-3xl font-semibold">Volunteers</h2>
	<div class="mb-12 flex w-full flex-col gap-4">
		<Accordian>
			<p slot="title">How can I become a volunteer for the Bunbury Shanty Music Festival?</p>
			<p slot="content">
				Yarrr! We'd be thrilled to have you join our crew! To become a volunteer, simply
				visit our festival website and fill out the volunteer contact form. We'll be in
				touch with further details and to discuss your role.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">What are the requirements to volunteer?</p>
			<p slot="content">
				Ahoy, matey! We welcome volunteers of all backgrounds and ages (18 and above).
				Whether you're a seasoned sailor or a landlubber with a passion for shanties, as
				long as you have enthusiasm and a positive attitude, you're good to go!
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">What kind of tasks will I be assigned as a volunteer?</p>
			<p slot="content">
				Avast ye! As a volunteer, you'll assist with various tasks such as setting up
				stages, helping with artist logistics, handing out festival programs, guiding
				attendees, and much more. We'll find a role that matches your skills and interests.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Will I get any training or guidance as a volunteer?</p>
			<p slot="content">
				Aye, aye! We've got your back. Before the festival, we'll provide a comprehensive
				orientation to familiarize you with your role and responsibilities. There will also
				be experienced volunteers and coordinators available throughout the festival to
				guide and support you.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Will I have time to enjoy the festival as a volunteer?</p>
			<p slot="content">
				Fear not, me hearties! We want you to have a jolly good time too. While
				volunteering, you'll have designated breaks and shifts that allow you to enjoy the
				festival. However, keep in mind that your assigned responsibilities should be your
				top priority during your shift.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Are there any perks for volunteers?</p>
			<p slot="content">
				Shiver me timbers, there are indeed! As a token of our appreciation, volunteers will
				receive a festival t-shirt, and free tickets to the festival.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Can I choose my shift timings?</p>
			<p slot="content">
				Arrr! We'll do our best to accommodate your preferences, but please understand that
				scheduling volunteers can be quite a puzzle. We'll communicate with you to determine
				the most suitable shift timings based on your availability.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">What if I can no longer volunteer after signing up?</p>
			<p slot="content">
				Avast ye, unforeseen circumstances happen! If you can no longer volunteer, please
				let us know as soon as possible by contacting our volunteer coordinator. We
				understand that life can be unpredictable, and we'll appreciate your timely
				communication.
			</p>
		</Accordian>
		<!-- TODO: Gmail email address in below question -->
		<Accordian>
			<p slot="title">How can I contact the volunteer coordinator for further questions?</p>
			<p slot="content">
				Yo ho ho! If you have any more questions, feel free to reach out to our friendly
				volunteer coordinator by emailing bunburyshantyfestival@gmail.com. They'll be
				delighted to assist you and provide all the information you need.
			</p>
		</Accordian>
		<Accordian>
			<p slot="title">Can I bring my friends to volunteer with me?</p>
			<p slot="content">
				Absolutely! The more, the merrier! If you have friends who are interested in
				volunteering, encourage them to apply too. Just make sure they fill out their own
				application forms so we can assign them appropriate roles.
			</p>
		</Accordian>
	</div>
</Container>
