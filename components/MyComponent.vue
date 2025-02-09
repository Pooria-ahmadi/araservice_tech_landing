<template>
  <div>
    <div class="columns mx-0 is-justify-content-center mt-5 is-hidden-tablet is-hidden-desktop">
      <div class="column has-text-centered bg-33335b border-r-12px my-3">
        <div class="is-flex is-justify-content-space-between is-align-items-center my-4" v-for="( data, index) in table" :key="index">
          <p class="color-AEABD8 is-size-7">
            {{ data.title }}
          </p>
          <p class="has-text-white is-size-7">
            {{ data.subtitle }}
          </p>
        </div>
      </div>
    </div>
    <div class="columns mx-0 is-justify-content-center mt-5 is-hidden-tablet is-hidden-desktop">
      <div class="column has-text-centered bg-33335b border-r-12px my-3">
        <div class="is-flex is-justify-content-space-between is-align-items-center my-4" v-for="( data, index) in table" :key="index">
          <p class="color-AEABD8 is-size-7">
            {{ data.title }}
          </p>
          <p class="has-text-white is-size-7">
            {{ data.subtitle }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      table: [
        { title: 'نام و نام خانوادگی', subtitle:'پوریا احمدی' },
        { title: 'شماره کارت', subtitle:'123456' },
        { title: 'مبلغ', subtitle:'50,000  تومان' },
        { title: 'تاریخ', subtitle:'12 آذر 1403' },
        { title: 'ساعت', subtitle:'13:56' },
        { title: 'نام تریمنال', subtitle:'ایرانمال 1' },

      ],
    }
  }
}
</script>