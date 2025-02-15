<template>
    <div class="w-900px mx-auto">
        <div class="bg-img-cover-login br-15px mx-auto mt-100px-mb-60px">
            <div class="form-container px-6 py-6 mx-2">
                <form>

                    <div class="has-text-centered">
                        <img src="login.png" alt="">
                    </div>

                    <div class="field mt-5">
                        <div class="control">
                            <input class="input br-15px mt-4 py-5" type="text" placeholder="نام کاربری" />
                        </div>
                    </div>

                    <div class="field">
                        <div class="control">
                            <input class="input br-15px mt-4 py-5" type="text" placeholder="رمز عبور" />
                        </div>
                    </div>
                    <p class="color-blue-dark is-size-7 my-5">
                        رمز عبور خود را فراموش کرده اید؟
                    </p>

                    <div class="field has-text-centered">
                        <button class="button bg-blue-dark has-text-white br-15px is-fullwidth py-5">ورود</button>
                    </div>
                </form>
            </div>
        </div>

    </div>
</template>
<script>
export default {
    layout: 'login',
}
</script>