<template>
  <div>
    <b-container class="extra-info-container">
        <b-row>
            <b-col>
                <h2 class="extra-info-header">Partners</h2>
                <img :src="techAlleyLogo" alt="Tech Alley Logo">
            </b-col>
            <b-col>
                <h2 class="extra-info-header">Fine Print</h2>
                <p>The Code for Vegas Foundation is a Nevada Nonprofit Corporation, Nevada Business ID NV20222489556, formed on 16 June 2022. As of August 2022, our form 1023 filing with the IRS for 501(c)(3) public charity determination is in progress. During the determination process, <a href="https://techalley.org/">Tech Alley</a> is acting as our Fiscal Sponsor for purposes of accepting tax-deducible donations on behalf of Code for Vegas Foundation, in order to support our continued developments.</p>
                <p>The Code for Vegas Foundation logo is an original design by Justin Pecayo.</p>
                <p>This Code for Vegas Foundation website will always be a work in progress. Ideally it will evolve into a properly accessible portal useful for interacting with this foundation and its endeavors. Over time, as more projects are deployed for use, this website and other related Foundation websites will likely make use of them to demonstrate our progress.</p>
                <p>Website content is published Copyright(c) 2022 by Code for Vegas Foundation. Logos and other creative works included on this website are used with permission with copyrights held by respective owners.</p>
            </b-col>
        </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
    data() {
        return {
            techAlleyLogo: require("../assets/TechAlleyLogo.png")
        }
    }

}
</script>

<style>

.extra-info-container {
    color: #fff;
}

.extra-info-header {
    padding: 30px 0px 10px 0px;
}

</style>