<template>
<div class="footer">
        <center><img src="../assets/img/logo.png" alt="" class="mt-5"></center>
        <center><small>Your Partner Room Design</small></center> 
        <br>
        <div class="foot">
            <div >
                <a class="nav-link text-dark" href=""><b>Overview</b></a>
                <a class="nav-link text-dark" href="">Shipping</a>
                <a class="nav-link text-dark" href="">Refund</a>
                <a class="nav-link text-dark" href="">Promotion</a>
            </div>
            <div>
                <a class="nav-link text-dark" href=""><b>Company</b></a>
                <a class="nav-link text-dark" href="">About</a>
                <a class="nav-link text-dark" href="">Career</a>
                <a class="nav-link text-dark" href="">Contact Us</a>
            </div>
            <div>
                <a class="nav-link text-dark" href=""><b>Explore</b></a>
                <a class="nav-link text-dark" href="">Term & Condition</a>
                <a class="nav-link text-dark" href="">Privacy Police</a>
                <a class="nav-link text-dark" href="">For Developer</a>
            </div>
            <div>
                <p><b>Special Letter</b></p>
                <div class="input-group mb-2">
                        <input 
                        type="text" 
                        class="form-control"
                        placeholder="Your Email Address" 
                        aria-describedby="basic-addon2"
                        id="valnama">
                        <div class="input-group-append">
                          <button type="submit" class="btn" id="btnsubmit"><img src="../assets/img/tele-icon.png" alt="" class="input-group-text" id="basic-addon2" style="background-color: pink;"></button>
                        </div>
                    </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'footerComponent'

}
</script>

<style scoped>
.footer{
    background-color: blanchedalmond;
    margin-top: 5%;
}
.footer .foot{
    display: flex;
    justify-content: space-around;
}

</style>