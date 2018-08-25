<template>
    <div class="w-100 h-100 bg-dark">
        <div class="container h-100">
            <div class="row h-100 justify-content-center align-items-center">
                <div class="card col-4 text-center justify-content-center">
                    <div class="card-body">
                        <h5 class="card-title">Couple List</h5>
                        <p class="card-text">
                            A bucket list for couples;
                            <br>
                            create, edit, or view yours
                        </p>
                        <router-link class="btn btn-dark btn-raised" to="/login">
                            Get Started
                        </router-link>
                        <br>
                        <a href="https://itunes.apple.com/us/app/couple-list/id1310979486?ls=1&mt=8">
                            <img src="@/assets/download_iOS.svg"
                                 alt="Download on the App Store"
                                 height="50"
                                 width="100">
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'home',
};
</script>
