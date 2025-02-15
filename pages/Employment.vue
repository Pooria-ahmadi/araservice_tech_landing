<template>
    <div class="w-900px mx-auto">
        <div class="bg-img-cover br-2px-solid br-15px py-6 px-5 mx-auto mt-100px-mb-60px">
            <p class="has-text-centered font-bold-number is-size-5 color-blue-dark">
                فرم استخدام تعمیرکاران
            </p>

            <div class="columns mx-0 mt-6">
                <div class="column  has-text-justified">
                    <p class="font-bold-number is-size-6 color-blue-dark">نام و نام خانوادگی</p>
                    <input class="input br-15px mt-2" type="text" placeholder="نام " />
                    <input class="input br-15px mt-4" type="text" placeholder="نام خانوادگی" />
                </div>
                <div class="column  has-text-justified">
                    <p class="font-bold-number is-size-6 color-blue-dark">شماره تلفن و ایمیل</p>
                    <input class="input br-15px mt-2" type="text" placeholder="شماره تلفن " />
                    <input class="input br-15px mt-4" type="text" placeholder="ایمیل" />
                </div>
                <div class="column  has-text-justified">
                    <p class="font-bold-number is-size-6 color-blue-dark">کد ملی و تاریخ تولد</p>
                    <input class="input br-15px mt-2" type="text" placeholder="کد ملی " />
                    <input class="input br-15px mt-4" type="text" placeholder="تاریخ تولد" />
                </div>
            </div>
            <div class="columns mx-0 is-vcentered">
                <div class="column  has-text-justified">
                    <p class="font-bold-number is-size-6 color-blue-dark"> آدرس</p>
                    <input class="input br-15px mt-2" type="text" placeholder="آدرس " />

                </div>
                <div class="column  has-text-justified is-align-self-flex-end">
                    <input class="input br-15px " type="text" placeholder=" کد پستی " />
                </div>
                <div class="column  has-text-justified">
                    <p class="font-bold-number is-size-6 color-blue-dark">وضعیت تاهل</p>
                    <div class="columns is-mobile">
                        <div class="column">
                            <div class="control has-icons-left has-icons-right  mt-2">
                                <input class="input br-15px" type="text" placeholder="مجرد" />
                                <span class="icon is-small is-left ml-5">
                                    <img src="Check Circle.png" alt="">
                                </span>
                                <span class="icon is-small is-right">
                                    <img src="Toilet Sign People.png" alt="">
                                </span>
                            </div>
                        </div>
                        <div class="column">
                            <div class="control has-icons-left has-icons-right  mt-2">
                                <input class="input br-15px" type="text" placeholder="متاهل " />
                                <span class="icon is-small is-right">
                                    <img src="Toilet Sign People2.png" alt="">
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="columns mx-0">
                <div class="column is-4">
                    <input class="input br-15px " type="text" placeholder=" شهر " />

                </div>
                <div class="column">
                    <input class="input br-15px " type="text" placeholder=" نشانی " />
                </div>
            </div>
            <div class="columns mx-0 mt-6 is-vcentered">
                <div class="column  has-text-justified">
                    <p class="font-bold-number is-size-6 color-blue-dark">تخصص</p>
                    <input class="input br-15px mt-2" type="text" placeholder="تخصص " />
                    <input class="input br-15px mt-4" type="text" placeholder="سابقه کاری" />
                </div>
                <div class="column  has-text-justified is-align-self-flex-end">
                    <input class="input br-15px height-100px" type="text" placeholder="شماره تلفن " />
                </div>
                <div class="column  has-text-justified">
                    <p class="font-bold-number is-size-6 color-blue-dark">رزومه کاری خود را در قالب یک فایل آپلود کنید
                    </p>
                    <div class="control has-icons-left has-icons-right  mt-2">
                        <input class="input br-15px" type="text" placeholder="آپلود رزومه" />
                        <span class="icon is-small is-left ml-5">
                            <img src="Document Uploads.png" alt="">
                        </span>
                    </div>
                </div>
            </div>
            <p class="has-text-gray">
                با تشکر، این فرم مورد بررسی قرار گرفته و نتیجه از طریق پیامک و ایمیل به شما ارسال میگردد.
            </p>
            <div class="columns mx-0 is-centered">
                <div class="column is-4 has-text-centered">
                    <button class="button bg-blue-dark br-15px mt-5 w-100">
                        <p class="has-text-white">
                            ثبت
                        </p>
                    </button>
                </div>
            </div>

        </div>
    </div>
</template>