<template>
    <div class="container">
        <div class="row links-row">
            <div class="col">
                <div class="row"><p class="title">{{ "Company" }}</p></div>
                <div class="row"><a class="footer-links" href="#">{{ "About us" }}</a></div>
                <div class="row"><a class="footer-links" href="#">{{ "Contact" }}</a></div>
                <div class="row"><a class="footer-links" href="#">{{ "Pricing" }}</a></div>
                <div class="row"><a class="footer-links" href="#">{{ "FAQ" }}</a></div>
            </div>
            <div class="col">
                <div class="row"><p class="title">{{ "Features" }}</p></div>
                <div class="row"><a class="footer-links" href="#">{{ "Feature 1" }}</a></div>
                <div class="row"><a class="footer-links" href="#">{{ "Feature 2" }}</a></div>
                <div class="row"><a class="footer-links" href="#">{{ "Feature 3" }}</a></div>
                <div class="row"><a class="footer-links" href="#">{{ "Feature 4" }}</a></div>
            </div>
            <div class="col">
                <div class="row"><p class="title">{{ "Blog" }}</p></div>
                <div class="row"><a class="footer-links" href="#">{{ "Relab" }}</a></div>
                <div class="row"><a class="footer-links" href="#">{{ "Product" }}</a></div>
                <div class="row"><a class="footer-links" href="#">{{ "Property Collective" }}</a></div>
                <div class="row"><a class="footer-links" href="#">{{ "Customer Stories" }}</a></div>
            </div>
        </div>
        <div class="row mb-5">
            <div class="col d-flex bottom-row">
                <a class="terms-link" href="#">{{ "Terms" }}</a>
                <a class="terms-link" href="#">{{ "Privacy" }}</a>
                <img src="/images/copyright.svg" height="12px"/>
            </div>
            <div class="col-auto">
                <a class="socials" href="#">
                    <img src="/images/facebook.svg" alt="" width="26" height="26">
                </a>
                <a class="socials" href="#">
                    <img src="/images/instagram.svg" alt="" width="26" height="26">
                </a>
                <a class="socials" href="#">
                    <img src="/images/linkedin.svg" alt="" width="26" height="26">
                </a>
                <a class="socials" href="#">
                    <img src="/images/twitter.svg" alt="" width="26" height="26">
                </a>
                <a class="socials" href="#">
                    <img src="/images/youtube.svg" alt="" width="26" height="26">
                </a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style scoped>
.title {
    font-weight: bold;
}
a.footer-links {
    color: #32302E;
    text-decoration: none;
}
a:hover {
    color: black;
}
a.terms-link {
    color: black;
    padding-right: 1rem;
}
.links-row {
    margin-bottom: 5rem;
}
.bottom-row {
    align-items: center;
}
.socials {
    padding: 0.6rem;
}
</style>