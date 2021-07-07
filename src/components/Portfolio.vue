<template>
    <div class="portfolio" id="portfolio">
        <h1 class="title portfolio__title ">Portfolio</h1>
        <nav class="navmenu">
            <div class="navmenu__container portfolio__navmenu-container">
                <p @click="selected_section = 'All'" class="navmenu__element " :class="selected_section == 'All' ? 'navmenu__element_active' : ''">All</p>
                <p @click="selected_section = 'Web'" class="navmenu__element " :class="selected_section == 'Web' ? 'navmenu__element_active' : ''">Web</p>
                <p @click="selected_section = 'Apps'" class="navmenu__element " :class="selected_section == 'Apps' ? 'navmenu__element_active' : ''">Apps</p>
                <p @click="selected_section = 'Other'" class="navmenu__element " :class="selected_section == 'Other' ? 'navmenu__element_active' : ''">Other</p>
            </div>
        </nav>
        <div class="portfolio__gallery-container">
            <div class="portfolio__gallery">
                <div class="portfolio__gallery-item">
                    <img class="portfolio__gallery-photo" src="https://via.placeholder.com/538x365/eaeaea/?text=example" alt="">
                </div>
                <div class="portfolio__gallery-item">
                    <img class="portfolio__gallery-photo" src="https://via.placeholder.com/538x365/eaeaea/?text=example" alt="">
                </div>
                <div class="portfolio__gallery-item">
                    <img class="portfolio__gallery-photo" src="https://via.placeholder.com/538x365/eaeaea/?text=example" alt="">
                </div>
                <div class="portfolio__gallery-item">
                    <img class="portfolio__gallery-photo" src="https://via.placeholder.com/538x365/eaeaea/?text=example" alt="">
                </div>
                <div class="portfolio__gallery-item">
                    <img class="portfolio__gallery-photo" src="https://via.placeholder.com/538x365/eaeaea/?text=example" alt="">
                </div>
                <div class="portfolio__gallery-item">
                    <img class="portfolio__gallery-photo" src="https://via.placeholder.com/538x365/eaeaea/?text=example" alt="">
                </div>
            </div>
        </div>
        <a href="#" class="portfolio__readmore">Read more</a>
    </div>
</template>

<script>
export default {
  methods: {
    change_section () {

    }

  },
  data () {
    return {
      selected_section: 'All'
    }
  }
}
</script>
