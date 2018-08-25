<template>
    <div class="w-100 h-100 bg-dark">
        <div class="container h-100">
            <div class="row h-100 justify-content-center align-items-center">
                <div class="card col-4 text-center justify-content-center">
                    <div class="card-body">
                        <h5 class="card-title">Login</h5>
                        <form class="card-text">
                            <div class="form-group">
                                <label class="bmd-label-floating">Email address</label>
                                <input type="email" class="form-control">
                            </div>
                            <div class="form-group">
                                <label class="bmd-label-floating">Password</label>
                                <input type="password" class="form-control">
                            </div>
                            <router-link class="btn btn-dark"
                                         style="margin-right: 1em;"
                                         to="/">
                                Back
                            </router-link>
                            <button class="btn btn-dark btn-raised">Submit</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'login',
};
</script>

<style scoped>
</style>
