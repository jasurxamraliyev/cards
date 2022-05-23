<template>
  <div>
    <card-1/><br>
    <card/><br>
    <EssentialLink/><br>
    <Card2/><br>
    <Card3/>
    <Card4/>

    <div class="q-mt-xl"></div>
  </div>
</template>

<script>
import card from '../components/card.vue';
import Card1 from '../components/card1.vue';
import EssentialLink from 'src/components/EssentialLink.vue';
import Card2 from '../components/card2.vue';
import Card3 from '../components/card3.vue';
import Card4 from 'src/components/card4.vue';
export default {
  components: { card, Card1, EssentialLink, Card2, Card3, Card4 },
  component:{card}
}
</script>

<style>

</style>
