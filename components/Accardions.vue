<template>
  <!-- ACCORDIONS -->
  <section id="accordions">
    <div class="container">
      <h2 class="title">Lorem ipsum dolor sit.</h2>

      <div v-for="(item, idx) in items" :key="idx" class="accordion">
        <div class="accordion-head">
          <h4>{{item.title}}</h4>
          <span :class="{'accordion-active': active == idx}" @click="activate(idx)">
            <svg
              width="24px"
              height="24px"
              viewBox="0 0 24 24"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
            >
              <g
                stroke="none"
                stroke-width="2px"
                fill="none"
                fill-rule="evenodd"
                stroke-linecap="square"
              >
                <g transform="translate(1.000000, 1.000000)" stroke="currentColor">
                  <path d="M0,11 L22,11" />
                  <path d="M11,0 L11,22" />
                </g>
              </g>
            </svg>
          </span>
        </div>
        <div class="accordion-panel" :style="{height: active == idx?'auto':0}">
          <div class="accordion-content">{{ item.desc }}</div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      active: null,
      items: [
        {
          title: 'Lorem ipsum dolor sit amet consectetur adipisicing.',
          desc: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam asperiores beatae, nostrum labore doloribus similique modi esse iure quos eaque dolorum consequatur enim dolor vitae ex nesciunt tempore adipisci aliquid! Lorem ipsum dolor sit amet consectetur, adipisicing elit.Molestiae aut necessitatibus facilis dolor laboriosam distinctio atque libero asperiores cum et dolorum harum, in excepturi, maxime fuga officia nulla repellendus molestias. Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque voluptatum sequi tenetur dignissimos obcaecati, assumenda nemo voluptate iusto quisquam laudantium veniam magnam officiis illum aut esse cupiditate necessitatibus. Voluptas, quo.'
        },
        {
          title: 'Lorem ipsum dolor sit amet consectetur adipisicing.',
          desc: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam asperiores beatae, nostrum labore doloribus similique modi esse iure quos eaque dolorum consequatur enim dolor vitae ex nesciunt tempore adipisci aliquid! Lorem ipsum dolor sit amet consectetur, adipisicing elit.Molestiae aut necessitatibus facilis dolor laboriosam distinctio atque libero asperiores cum et dolorum harum, in excepturi, maxime fuga officia nulla repellendus molestias. Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque voluptatum sequi tenetur dignissimos obcaecati, assumenda nemo voluptate iusto quisquam laudantium veniam magnam officiis illum aut esse cupiditate necessitatibus. Voluptas, quo.'
        },
        {
          title: 'Lorem ipsum dolor sit amet consectetur adipisicing.',
          desc: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam asperiores beatae, nostrum labore doloribus similique modi esse iure quos eaque dolorum consequatur enim dolor vitae ex nesciunt tempore adipisci aliquid! Lorem ipsum dolor sit amet consectetur, adipisicing elit.Molestiae aut necessitatibus facilis dolor laboriosam distinctio atque libero asperiores cum et dolorum harum, in excepturi, maxime fuga officia nulla repellendus molestias. Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque voluptatum sequi tenetur dignissimos obcaecati, assumenda nemo voluptate iusto quisquam laudantium veniam magnam officiis illum aut esse cupiditate necessitatibus. Voluptas, quo.'
        }
      ]
    }
  },
  methods: {
    activate(idx) {
      if (idx === this.active) {
        this.active = null
      } else {
        this.active = idx
      }
    }
  }
}
</script>

<style>
</style>