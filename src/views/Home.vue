<template>
  <div class="home">
    <Bigfeatures/>
    <Features/>
    <Screenshots/>
    <Price/>
    <Contact/>
    <div class="overlay overlay-hugeinc">
        <button type="button" class="overlay-close">Close</button>
        <nav>
        <ul>
            <li class="hideit"><a href="#header">Home</a></li>
            <li class="hideit"><a href="#bigfeatures">Feature</a></li>
            <li class="hideit"><a href="#speciality">Speciality</a></li>
            <li class="hideit"><a href="#gallery">Gallery</a></li>
            <li class="hideit"><a href="#testimonial">Testimonial</a></li>
            <li class="hideit"><a href="#team">Team</a></li>
            <li class="hideit"><a href="#contact">Contact Us</a></li>
        </ul>
        </nav>
    </div>
  </div>
</template>

<script>
import Bigfeatures from '@/components/Bigfeatures.vue'
import Contact from '@/components/Contact.vue'
import Features from '@/components/Features.vue'
import Price from '@/components/Price.vue'
import Screenshots from '@/components/Screenshots.vue'

export default {
  name: 'Home',
  components: {
    Bigfeatures,
    Contact,
    Features,
    Price,
    Screenshots
  }
}
</script>
