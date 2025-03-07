<template>
    <div>
        <head>
            <title>Dev Edmonton Society</title>
        </head>
        <div
            class="relative py-8 bg-white overflow-hidden max-w-7xl mx-auto sm:px-4"
        >
            <div
                class="relative mx-8 sm:mx-12 pb-8 lg:my-4 lg:grid lg:grid-cols-2 lg:gap-8 lg:items-center"
            >
                <div class="relative">
                    <h3
                        class="text-3xl leading-8 font-extrabold text-gray-900 tracking-tight sm:text-3xl sm:leading-9"
                    >
                        Dev Edmonton Society
                    </h3>
                    <h4
                        class="text-lg leading-8 font-bold text-gray-900 tracking-tight sm:text-lg sm:leading-9"
                    >
                        Fostering a stronger software development community in
                        Edmonton.
                    </h4>
                    <p class="mt-3 text-lg leading-7 text-gray-500">
                        We are made up of people who believe that an impactful,
                        diverse, and collaborative developer community enriches
                        us all. We realize this vision by sharing knowledge and
                        ideas, understanding the community and its needs,
                        promoting events and initiatives, and supporting
                        technology meetups and organizations.
                    </p>
                </div>

                <div class="mt-10 -mx-4 relative lg:mt-0">
                    <div class="slack-content relative p-4 text-center">
                        <a href="#about-our-slack">
                            <p class="text-xl text-brand-primary">
                                Learn more about our Slack!
                            </p>
                            <img
                                class="w-64 m-auto"
                                src="/img/logos/Slack_RGB.svg"
                                alt="slack logo"
                            />
                        </a>
                        <a href="#about-our-slack">
                            <VButton appearance="inverted"
                                >About Our Slack</VButton
                            >
                        </a>
                    </div>
                </div>
            </div>
        </div>

        <div
            class="relative bg-grey-000 pt-8 -mt-8 pb-16 px-4 sm:px-6 lg:pt-12 lg:px-8"
        >
            <a id="what-we-do" href="/#what-we-do" class="anchor"></a>
            <div class="absolute inset-0">
                <div class="h-1/3 sm:h-2/3"></div>
            </div>
            <div class="relative max-w-7xl mx-auto">
                <div class="text-center">
                    <h2
                        class="text-3xl leading-9 tracking-tight font-extrabold text-gray-900 sm:text-4xl sm:leading-10"
                    >
                        What We Do
                    </h2>
                </div>
                <div
                    class="mt-12 grid gap-5 max-w-lg mx-auto lg:grid-cols-3 lg:max-w-none"
                >
                    <div
                        class="flex flex-col rounded-lg shadow-lg overflow-hidden"
                    >
                        <div class="flex-shrink-0">
                            <NuxtImg
                                class="h-48 w-full object-cover"
                                alt="Group of people posing together at a past event"
                                src="/homepage/meetups-and-events.jpg"
                            />
                        </div>
                        <div
                            class="flex-1 bg-white p-6 flex flex-col justify-between"
                        >
                            <div class="flex-1">
                                <div class="block">
                                    <h3
                                        class="mt-2 text-xl leading-7 font-semibold text-gray-900"
                                    >
                                        Support Meetups & Events
                                    </h3>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        If you're a technology meetup or event
                                        organizers, we've got your back!
                                    </p>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        From online streaming tools, equipment
                                        and training, to event support,
                                        organizer training, and venues we're
                                        here to help developers run awesome
                                        events about the tools they love;
                                        without having to start from scratch on
                                        their own.
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div
                        class="flex flex-col rounded-lg shadow-lg overflow-hidden"
                    >
                        <div class="flex-shrink-0">
                            <NuxtImg
                                class="h-48 w-full object-cover"
                                alt="Group of people posing together at a past event"
                                src="/homepage/connect-community.jpg"
                            />
                        </div>
                        <div
                            class="flex-1 bg-white p-6 flex flex-col justify-between"
                        >
                            <div class="flex-1">
                                <div class="block">
                                    <h3
                                        class="mt-2 text-xl leading-7 font-semibold text-gray-900"
                                    >
                                        Connect Community
                                    </h3>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        Technology changes faster everyday, and
                                        a great technology community needs to
                                        stay connected if we want to keep us.
                                    </p>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        Through our active Slack, mailing list,
                                        events, and online outreach we provide
                                        many ways for the Edmonton technology
                                        community to come together.
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div
                        class="flex flex-col rounded-lg shadow-lg overflow-hidden"
                    >
                        <div class="flex-shrink-0">
                            <NuxtImg
                                class="h-48 w-full object-cover"
                                alt="Group of people posing together at a past event"
                                src="/homepage/provide-a-platform.jpg"
                            />
                        </div>
                        <div
                            class="flex-1 bg-white p-6 flex flex-col justify-between"
                        >
                            <div class="flex-1">
                                <div class="block">
                                    <h3
                                        class="mt-2 text-xl leading-7 font-semibold text-gray-900"
                                    >
                                        Provide A Platform
                                    </h3>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        Beyond just connecting meetup and event
                                        orgranizers with great online and
                                        in-person venues and resources we
                                        provide access to a variety of supports
                                        to help local technologists build the
                                        community they want to see, wherever
                                        that may be. Share your ideas on our
                                        Slack!
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <SlackSection />

        <div
            class="relative bg-grey-000 pt-8 -mt-8 pb-16 px-4 sm:px-6 lg:pt-12 lg:px-8"
        >
            <a id="get-involved" href="/#get-involved" class="anchor"></a>
            <div class="absolute inset-0">
                <div class="h-1/3 sm:h-2/3"></div>
            </div>
            <div class="relative max-w-7xl mx-auto">
                <div class="text-center">
                    <h2
                        class="text-3xl leading-9 tracking-tight font-extrabold text-gray-900 sm:text-4xl sm:leading-10"
                    >
                        Get Involved
                    </h2>
                </div>
                <div
                    class="mt-12 grid gap-5 max-w-lg mx-auto lg:grid-cols-3 lg:max-w-none"
                >
                    <div
                        class="flex flex-col rounded-lg shadow-lg overflow-hidden"
                    >
                        <div class="flex-shrink-0">
                            <NuxtImg
                                class="h-48 w-full object-cover"
                                src="/homepage/get-involved-dev.jpg"
                                alt="Developer sitting at a computer looking at code"
                            />
                        </div>
                        <div
                            class="flex-1 bg-white p-6 flex flex-col justify-between"
                        >
                            <div class="flex-1 flex flex-col">
                                <div class="block flex-grow">
                                    <h3
                                        class="mt-2 text-xl leading-7 font-semibold text-gray-900"
                                    >
                                        As A Developer
                                    </h3>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        There so many ways to get involved in
                                        the Edmonton developer community!
                                    </p>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        <a
                                            class="text-brand-primary"
                                            href="https://join.slack.com/t/devedmonton/shared_invite/zt-1hqylgb8i-pKr5nUmRwOJwdLHVce0rXg"
                                            >Get started by joining our Slack</a
                                        >
                                        and make sure to say hello in our
                                        <code>#introductions</code> channel
                                        where one of our friendly community
                                        members will help you find your way.
                                    </p>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        If you are interested in becoming more
                                        involved (like borrowing our equiment or
                                        voting on community decisions) then
                                        <NuxtLink
                                            to="/become_a_member"
                                            class="text-brand-primary"
                                        >
                                            find more information about becoming
                                            a member here.
                                        </NuxtLink>
                                        You do not need to be a member to come
                                        to events or participate in the slack!
                                    </p>
                                </div>
                                <div class="flex justify-center mt-4">
                                    <a
                                        href="https://join.slack.com/t/devedmonton/shared_invite/zt-1hqylgb8i-pKr5nUmRwOJwdLHVce0rXg"
                                    >
                                        <VButton appearance="inverted"
                                            >Join Slack</VButton
                                        >
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div
                        class="flex flex-col rounded-lg shadow-lg overflow-hidden"
                    >
                        <div class="flex-shrink-0">
                            <NuxtImg
                                class="h-48 w-full object-cover"
                                src="/homepage/get-involved-meetups.png"
                                alt="Developer sitting at a computer looking at code"
                            />
                        </div>
                        <div
                            class="flex-1 bg-white p-6 flex flex-col justify-between"
                        >
                            <div class="flex-1 flex flex-col">
                                <div class="block flex-grow">
                                    <h3
                                        class="mt-2 text-xl leading-7 font-semibold text-gray-900"
                                    >
                                        As An Event Organizer
                                    </h3>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        If you're like us you're probably a
                                        developer keen to start a meetup or
                                        organize an event for your favourite
                                        language or technologies. We've been
                                        there, and want to help!
                                    </p>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        Whether it's sharing best practices,
                                        streaming and recording resources,
                                        fundraising, or just lending a friendly
                                        ear we want to share the lessons we've
                                        learned and let you focus on running
                                        successful and engaging events!
                                    </p>
                                </div>
                                <div class="flex justify-center mt-4">
                                    <a
                                        class="m-auto"
                                        href="mailto:board@devedmonton.com?subject=I'm%20interested%20in%20help%20organizing%20an%20Edmonton%20technology%20event"
                                        target="_blank"
                                        rel="noopener noreferrer"
                                    >
                                        <VButton appearance="inverted"
                                            >Organize An Event</VButton
                                        >
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div
                        class="flex flex-col rounded-lg shadow-lg overflow-hidden"
                    >
                        <div class="flex-shrink-0">
                            <img
                                class="h-48 w-full object-cover"
                                src="https://images.unsplash.com/photo-1492724441997-5dc865305da7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1650&q=80"
                                alt="Simple desk set up"
                            />
                        </div>
                        <div
                            class="flex-1 bg-white p-6 flex flex-col justify-between"
                        >
                            <div class="flex-1 flex flex-col">
                                <div class="block flex-grow">
                                    <h3
                                        class="mt-2 text-xl leading-7 font-semibold text-gray-900"
                                    >
                                        As A Business
                                    </h3>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        Whether you're a growing startup or an
                                        established player the Dev Edmonton
                                        Society can help your understand the
                                        tools and technologies shaping your
                                        business.
                                    </p>
                                    <p
                                        class="mt-3 text-base leading-6 text-gray-500"
                                    >
                                        Supporting and growning the Edmonton
                                        tech community takes many shapes, from
                                        simple financial donations to direct
                                        engagemenent by providing speakers,
                                        venues, resources and donations of
                                        employee time. We want to help your
                                        business grow and find a community of
                                        technologists passionate about the tools
                                        you need to succeed!
                                    </p>
                                </div>
                                <div class="flex justify-center mt-4">
                                    <a
                                        href="mailto:board@devedmonton.com?subject=Supporting%20Dev%20Edmonton%20Society"
                                        target="_blank"
                                        rel="noopener noreferrer"
                                    >
                                        <VButton appearance="inverted"
                                            >Support Local Tech</VButton
                                        >
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <MeetupsSection />
        <EventsSectionSummary :card-limit="5" />
        <ResourcesSectionSummary :card-limit="5" />
        <SignupForm />
    </div>
</template>

<script>
import SignupForm from "../components/SignupForm";
import VButton from "../components/VButton.vue";
import EventsSectionSummary from "../components/EventsSectionSummary.vue";
import MeetupsSection from "../components/MeetupsSection.vue";
import ResourcesSectionSummary from "../components/ResourcesSectionSummary.vue";

export default {
    components: {
        VButton,
        SignupForm,
        MeetupsSection,
        EventsSectionSummary,
        ResourcesSectionSummary,
    },
};
</script>

<style>
.title {
    display: block;
    font-family:
        "Quicksand",
        "Source Sans Pro",
        -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        Roboto,
        "Helvetica Neue",
        Arial,
        sans-serif;
    font-size: 100px;
    font-weight: 300;
    color: #35495e;
    letter-spacing: 1px;
}

.subtitle {
    padding-bottom: 15px;
    font-size: 42px;
    font-weight: 300;
    color: #526488;
    word-spacing: 5px;
}

.links {
    padding-top: 15px;
}
</style>
