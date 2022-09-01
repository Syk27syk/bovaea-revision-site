<template>
    <div>
        <!--
        <div id="BOVAEA part 1">
            <div class="flex flex-row">
                <h3><NuxtLink to="">BOVAEA Part 1</NuxtLInk></h3>
                <button @click="toggleIsHidden">
                    <svg
                        class="-mr-1 ml-2 h-5 w-5"
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                        aria-hidden="true">
                        <path
                            fill-rule="evenodd"
                            d="M5.23 7.21a.75.75 0 011.06.02L10 11.168l3.71-3.938a.75.75 0 111.08 1.04l-4.25 4.5a.75.75 0 01-1.08 0l-4.25-4.5a.75.75 0 01.02-1.06z"
                            clip-rule="evenodd"
                        />
                     </svg>
                </button>
            </div>
            <div v-show="isHidden" id="dropdown1" class="grid grid-rows-6">
                <ul
                    <li v-for="(name, link) in bovaea1list"
                        :key={{ name }}
                        :value={{ link }}
                    >
                    </li>
                </ul>
            </div>
        </div>
        <div id="BOVAEA part 2">
            <NuxtLink to=""> Estate Agency Law &#40;Professional Practice&#41;</NuxtLink>
            <NuxtLink to=""> Land Economics </NuxtLink>
            <NuxtLink to=""> Principles of Valuation </NuxtLink>
            <NuxtLink to=""> Laws Relating to Property </NuxtLink>
            <NuxtLink to=""> Real Estate Agency Practice </NuxtLink>
            <NuxtLink to=""> Building Technology Part II </NuxtLink>
        </div>
        <div id="Provisional Estate Agent Test of Professional Competence">
            <p>to be completed</p>
        </div>
        <div id="digital marketing resources">
            <NuxtLink to=""> Social media marketing </NuxtLink>
            <NuxtLink to =""> Search engine optimization </NuxtLink>
            <NuxtLink to=""> Graphic design </NuxtLink>
        </div>
        <div id="sales">
            <p> basic sales cycle </p>
            <p> negotiation for sales and marketing </p>
            <p> persuasion skills for sales and marketing </p>
            <p> territory management </p>
            <p> pre-call planning and research </p>
            <p> discovery </p>
            <p> sales prospecting </p>
            <p> handling objections </p>
            <p> closing skills </p>
            <p> post-closing </p>
            <p> sales networks </p>
        </div>
        <div id="analytics for sales and marketing">
            <p> metrics for sales and marketing </p>
        </div>
        <div id="real estate investment and finance">
            <p> urban economics </p>
            <p> applying the economist's toolkit on real estate markets </p>
            <p> real estate cycles </p>
            <p> pricing characteristics of properties - hedonic modelling </p>
            <p> fundamentals of valuation finance </p>
            <p> mortgages </p>
            <p> fundamentals in real estate investments </p>
            <p> sustainability in real estate </p>
        </div>
        <div id="real estate research">
            <p> real estate research </p>
        </div>
        <div id="property development">
            <p> property development </p>
        </div>
        <div id="property management">
            <p> property management </p>
        </div>
        <div id="property valuation">
            <p> property valuation </p>
        </div>
        <div id="real estate by category of property">
            <p> residential </p>
            <p> commercial </p>
            <p> industrial </p>
            <p> vacant land </p>
        </div>
        <div id="malaysian real estate">
            <p>market outlook, data and trends"</p>
            <div id="by category of property">
                <p> residential </p>
                <p> commercial </p>
                <p> industrial </p>
                <p> vacant land </p>
            </div>
            <p> investors </p>
            <p> homebuyers </p>
            <p> rental </p>
            <p>resource list</p>
        </div>
        <div id="international real estate">
            <p> tax issues</p>
            <p> customs, laws and religion</p>
            <p> currency and exchange rates </p>
            <p> market conditions </p>
            <p> strategies for international real estate </p>
            <p> negotiation in international real estate </p>
            <p> marketing in internatioanl real estate </p>
            <p> investment performance in international real estate </p>
            <p> geography in international real estate </p>
            <div id="international real estate by region">
                <p> Asia Pacific </p>
                <p> Europe </p>
                <p> Eastern Europe </p>
                <p> Australiasia </p>
                <p> North America </p>
                <p> South America </p>
            </div>
        </div>
        <div id="financial planning for real estate investment">
            <p> financial planning </p>
        </div>
        <div id="proptech101">
            <p> visualizing properties </p>
            <p> tech for developers and construction </p>
            <p> tech for property search </p>
            <p> property transactions/tech-enabled brokerage </p>
            <p> property management </p>
            <p> tech for marketing </p>
            <p> tech for asset utilization - lease/rent </p>
            <p> valuation and analytics </p>
            <p> data in real estate </p>
            <p> IoT in real estate </p>
            <p> crowdfunding for investment </p>
            <p> proptech companies to note </p>
            <p> resources </p>
        </div>
        -->
    </div>
</template>

<script>
export default {
  data () {
    return {
      isHidden: true,
    }
  },
  methods: {
    toggleIsHidden (isHidden) {
      console.log('I am running');
      if (isHidden === true) {
        isHidden = false;
      } else {
        isHidden = true;
      }
    }
  }
}
</script>
