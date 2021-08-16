<template>
  <div class="parent">
    <div style="padding-top: 130px">
        <div class="d-flex justify-content-between">
            <div class="width-49 d-flex">
                <div style="width: 35%">
                    <div class="pl-3">
                        <ul>
                            <li>About Us</li>
                            <li>Product</li>
                            <li>New Product</li>
                            <li>Application</li>
                            <li>Contact Us</li>
                            <li>News</li>
                        </ul>
                    </div>
                </div>
                <div style="width: 65%">
                    <div class="area-map">
                        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1862.1913175834259!2d105.78293045820371!3d21.017370496501215!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3135ab54ef80077d%3A0x1c375dcb13b05376!2zS2VhbmduYW0sIE3hu4UgVHLDrCwgVOG7qyBMacOqbSwgSGFub2ksIFZpZXRuYW0!5e0!3m2!1sen!2s!4v1628826008895!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                    </div>
                </div>
            </div>
            <div class="width-49">
                <p class="font-24">SHAKO Co., Ltd.</p>
                <p>No. 392, Sec. 2, Wanshou Rd., Guishan Dist., Taoyuan City 333019, Taiwan (R.O.C.)</p>
                <p>TEL: 886 3-319xxxx</p>
                <p>FAX: 886 3-31xxxxx</p>
                <p>G-mail: </p>
            </div>
        </div>
        <div class="d-flex justify-content-between">
            <div>
                <span>You are the <span>234234234</span> visitor</span>
            </div>
            <div>
                <div>
                    <p>
                        <i class="fas fa-clock"></i>
                        Online: <span>2</span>
                    </p>
                </div>
                <div>
                    <p>
                        <i class="fas fa-calendar-week"></i>
                        Day: <span>8</span>
                    </p>
                </div>
                <div>
                    <p>
                        <i class="fas fa-calendar"></i>
                        Week: <span>88</span>
                    </p>
                </div>
                <div>
                    <p>
                        <i class="fas fa-user-alt"></i>
                        Visiter: <span>223</span>
                    </p>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
 
}
</script>

<style lang="scss" scoped>
.parent {
    margin: -8% 0 0;
    vertical-align: top;
    background: #fff url('http://u643678.webmienphi.vn/userfiles/img/643678/footer_bg.png') left top repeat-x;
}
ul {
    padding: 0;
    list-style: none;
    li {
        list-style: none;
        padding: 0 !important;
        height: 30px;
    }
}
 
.width-49 {
    width: 49%;
}
.area-map {
    display: flex;
    flex-wrap: wrap;
    height: 180px;
    overflow: hidden;
}
p {
    margin-bottom: 0;
}
</style>