<template>
    <div class="container-scroller">
        <div class="container-fluid page-body-wrapper full-page-wrapper">
            <div class="content-wrapper d-flex align-items-center auth register-bg-1 theme-one">
                <div class="row w-100 mx-auto">
                    <div class="col-lg-4 mx-auto">
                        <h2 class="text-center mb-4">Register</h2>
                        <div class="auto-form-wrapper">
                            <form action="register">
                                <div class="form-group">
                                    <div class="input-group">
                                        <input type="text" class="form-control" placeholder="Username">
                                        <div class="input-group-append">
                                            <span class="input-group-text"><i class="icon-check"></i></span>
                                        </div>
                                    </div>
                                </div>
                                <div class="form-group">
                                    <div class="input-group">
                                        <input type="password" class="form-control" placeholder="Password">
                                        <div class="input-group-append">
                                            <span class="input-group-text"><i class="icon-check"></i></span>
                                        </div>
                                    </div>
                                </div>
                                <div class="form-group">
                                    <div class="input-group">
                                        <input type="password" class="form-control" placeholder="Confirm Password">
                                        <div class="input-group-append">
                                            <span class="input-group-text"><i class="icon-check"></i></span>
                                        </div>
                                    </div>
                                </div>
                                <br />
                                <div class="form-group">
                                    <button class="btn btn-primary submit-btn btn-block">Register</button>
                                </div>
                                <div class="text-block text-center my-3">
                                    <span class="text-small font-weight-semibold">Already have and account ?</span>
                                    <router-link to="/login"><a class="text-small">Login</a></router-link>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
            <!-- content-wrapper ends -->
        </div>
        <!-- page-body-wrapper ends -->
    </div>
</template>
