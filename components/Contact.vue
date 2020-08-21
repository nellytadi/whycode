<template>
    <section class="contact" id="contact">
        <div class="container">
            <div class="block-title text-center">
                <h2 class="block-title__title">More enquiries? <br> <span>Contact</span> us today.</h2><!-- /.block-title__title -->
            </div><!-- /.block-title -->
            <div class="row">
                <div class="pt-4 col-lg-8 col-md-8 col-sm-12 mx-auto wow fadeInUp" style="z-index: 1;">
                    <form>
                        <div class="form-group">
                            <input type="text" class="formInput" placeholder="Name">
                        </div>
                        <div class="form-group">
                            <input type="email" class="formInput" placeholder="Email address">
                        </div>
                        <div class="form-group">
                            <textarea class="formInput" placeholder="Your message"></textarea>
                        </div>
                        <div class="form-group text-center" style="margin: 50px 0 100px;">
                            <input type="submit" value="submit" class="thm-btn contact-btn">
                        </div>
                    </form>
                </div><!-- /.col-lg-4 -->

            </div><!-- /.row -->

        </div><!-- /.container -->

    </section>
</template>

<script>
    export default {
        name: "Contact"
    }
</script>

<style scoped>

</style>
