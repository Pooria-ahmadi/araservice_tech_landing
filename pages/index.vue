<template>
  <div>
    <div class="background-header-index">
      <div class="top-135px-right-25px has-text-centered w-295px is-hidden-mobile">
        <h1 class=" is-size-3-desktop is-size-5-mobile color-blue-dark has-text-weight-bold">
          تعمیرات سریع و مطمئن<br>
          خانه‌تان را به ما بسپارید!
        </h1>
        <p class=" is-size-7 mt-6 has-text-gray">
          تعمیرات سریع و مطمئن در دستان شماست! با ما به راحتی مشکلات خود را حل کنید. از مشاوره تا انجام خدمات، همه چیز
          به صورت آنلاین و در کمترین زمان ممکن
        </p>
        <p class=" mt-2 font-bold-number">
          تعمیرات لوازم خانگی، و تجهیزات صنعتی با کیفیت بالا و قیمت مناسب
        </p>
        <NuxtLink to="/login" class="button bg-blue-dark br-15px px-5 mt-5 w-145px">
          <div class="is-align-items-center is-flex">
            <p class="has-text-white ml-3">
              ورود
            </p>
            <img src="left white.png" alt="">
          </div>
        </NuxtLink>
      </div>
    </div>
    <div class="has-text-centered is-hidden-mobile">
      <img src="image 14.png" alt="">
    </div>
    <div class="has-text-centered is-hidden-desktop is-hidden-tablet">
      <img src="Frame 146.png" alt="">
    </div>


    <div class="w-900px mx-auto mt-5 ">
      <div class="columns mx-2 is-centered mt-6">
        <div class="column  has-text-centered">
          <p class="color-blue-dark  font-bold-number is-size-3-desktop  is-size-5-mobile">
            خدمات آنلاین تعمیرات حرفه‌ای
          </p>

          <p class=" mt-5 mb-3">
            اپلیکیشن‌های خدمات تعمیرات آنلاین پلتفرم‌هایی هستند که به کاربران این امکان را می‌دهند تا به راحتی و تنها با
            چند کلیک، نیازهای تعمیراتی خود را برطرف کنند.

          </p>
          <p>
            این اپلیکیشن‌ها معمولاً شامل دسته‌بندی‌های مختلفی از جمله تعمیر لوازم خانگی، خودرو، الکترونیک و حتی خدمات
            ساختمانی هستند. کاربران می‌توانند با انتخاب نوع خدمت مورد نظر، اطلاعات مربوط به تکنسین‌ها یا متخصصان را
            مشاهده
            کرده و با آن‌ها ارتباط برقرار کنند.
          </p>
          <button class="button bg-blue-dark br-15px  mt-5 w-164px">
            <div class="is-align-items-center is-flex">
              <p class="has-text-white ml-3">
                نصب اپلیکیشن‌
              </p>
              <img src="left white.png" alt="">
            </div>
          </button>
        </div>
      </div>
    </div>
    <servicedesktop />
    <servicemobile />
    <div class="w-900px mx-auto ">
      <div class="columns mx-0 is-centered mt-5">
        <div class="column is-9 has-text-centered">
          <p>
            بهبود تجربه مشتری، افزایش رضایت کاربران و در نهایت رشد اقتصادی در این حوزه شود. همچنین، با توجه به نیازهای
            روزافزون جامعه به خدمات سریع و قابل اعتماد، این اپلیکیشن‌ها می‌توانند به عنوان یک پل ارتباطی مؤثر بین
            ارائه‌دهندگان خدمات و مصرف‌کنندگان عمل کنند و به ایجاد شفافیت و اعتماد در بازار کمک نمایند.
          </p>
          <p class="mt-5">
            در نتیجه، توسعه این پلتفرم‌ها نه تنها به نفع کاربران خواهد بود بلکه می‌تواند فرصت‌های شغلی جدیدی نیز ایجاد
            کند و
            به رونق کسب‌وکارهای کوچک و متوسط کمک کند.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import servicedesktop from "@/components/servicedesktop.vue";
import servicemobile from "@/components/servicemobile.vue";

export default {
  components: {
    servicedesktop,
    servicemobile,
  },
};
</script>