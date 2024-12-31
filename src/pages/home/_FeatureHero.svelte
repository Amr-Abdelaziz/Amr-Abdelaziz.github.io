<script>
  import { Section, HeroHeader } from "flowbite-svelte-blocks";
  import { Button, DeviceMockup } from "flowbite-svelte";
  import { ArrowRightOutline } from "flowbite-svelte-icons";
  import ParallaxDevices from "./_ParallaxDevices.svelte";
</script>
<!-- Reference: https://flowbite-svelte-blocks.vercel.app/marketing/hero -->
<Section name="heroVisual">
  <div class="mr-auto place-self-center lg:col-span-7">
    <HeroHeader h1Class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl dark:text-white" pClass="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-400">
      <svelte:fragment slot="h1">
        <p>
          <span class="p">
            AI<br/>
            Automation<br/>
        </span>
      </p>
      </svelte:fragment>
      <svelte:fragment slot="paragraph">
        <div class="block">
          <p>
            <span class="font-bold">AI DEVELOPMENT</span>

              <span><br/>I craft intelligent solutions tailored for health and wellness startups, including custom chatbots, AI tools, and seamless integrations.
                         I offer drive growth, optimize processes, and enhance communication, elevating your business and amplifying your impact on people's lives.
          </span>
          <br/>
          </p>
          &nbsp;
          <p>
          <span>
            <span class="font-bold">LEAD GENERATION</span>
              <br/>My AI-powered lead generation solutions are designed specifically for health and wellness startups.
               By leveraging custom chatbots and personalized integrations,
                I streamline your lead acquisition and management processes, allowing you to focus on what truly matters – helping more people achieve their health goals.
          </span>
          <br/>
          </p>
          &nbsp;
          <p>
          <span >
            <span class="font-bold">CRM AUTOMATION</span>
              <br/>Optimize your client relationships with our CRM solutions. I automate and streamline your lead management journey,
               ensuring both efficiency and a personal touch. This allows your health or wellness startup to concentrate on delivering exceptional services while nurturing strong client connections.
          </span>
          </p>
          &nbsp;
          <p>
            <span class="font-bold">My mission</span> <span>is to elevate your health and wellness business</span>
      
          <span >I am a unique blend of tech experts and health enthusiasts, with over 15 years of combined experience in fintech, startups, design agencies, and the wellness sector.</span>
          <span >This dual expertise allows me to create automation solutions that truly understand and address the specific needs of health and wellness businesses.</span>
          <span >I help you automate your workflows to increase productivity, regain control of your time, and amplify your impact on people's health and wellbeing.</span>
          <span class="font-bold">By partnering with me, you can focus on what matters most – growing your business and transforming lives.</span>
          </p>
          &nbsp;
          <p>
            <span class="font-bold">Say Goodbye To:</span>
          </p>
          <div id="list01" class="list">
              <ul>
                  <li>
                      <p>Potential clients lost due to slow follow-ups</p>
                  </li>
                  <li>
                      <p>Wasted hours chasing unqualified leads</p>
                  </li>
                  <li>
                      <p>Repetitive tasks that drain your energy</p>
                  </li>
              </ul>
          </div>
          &nbsp;
          <p>
            <span class="font-bold">Say Hello To:</span>
          </p>
          <div id="list02" class="list">
              <ul>
                  <li>
                      <p>More qualified leads in the health and wellness space</p>
                  </li>
                  <li>
                      <p>Higher conversion rates for your programs and services</p>
                  </li>
                  <li>
                      <p>Reduced admin hours, giving you more time for customers</p>
                  </li>
                  <li>
                      <p>Innovative AI solutions that set you apart in the wellness industry</p>
                  </li>
              </ul>
          </div>
      </div>
         
       
      </svelte:fragment>
  </HeroHeader>
  </div>
  <div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
    <img src="/images/zurich_and_seattle_1.png" alt="mockup" object-fit="cover" layout="fill"/>
  </div>
</Section>

