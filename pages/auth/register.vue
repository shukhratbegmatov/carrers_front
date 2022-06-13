<template>
    <section class="section_bg m-0 login-form">
        <Navbar></Navbar>
        <div class="login_forms">
             <div class="form_f">
            <form class="login-register">
                    <div class="grid-x">
                            <div class="small-4 cell">
                                <h1 class="login-register__header">Register</h1>
                            </div>
                            <div class="small-8 cell flex-end link-forms">
                                <NuxtLink to="/auth/login">Login</NuxtLink>
                            </div>
                            <div class="small-12 cell">
                                <div class="">
                                    <input type="text" value="" placeholder="Email" name="email">
                                </div>
                            </div>
                            <div class="small-12 cell">
                                <div class="">
                                    <input type="text" value="" placeholder="Name" name="email">
                                </div>
                            </div>
                            <div class="small-12 cell">
                                <div class="">
                                    <input type="password" value="" placeholder="password" name="password">
                                </div>
                            </div>
                            <div class="small-12 cell">
                                <div class="">
                                    <input type="password" value="" placeholder="Password confirmation" name="password">
                                </div>
                            </div>
                    </div>
                    <div class="small-6 cell flex-end mar-bot-10">
                         <button class="button button--green before-fade-in fade-in">
                            Next
                        </button>
                    </div>
            </form>
        </div>
        </div>
        <Footer class="m-0"></Footer>
    </section>
</template>