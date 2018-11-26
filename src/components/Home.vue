<template>
  <div>
    <!--______________________________ NAVBAR _____________________________________-->
    <b-navbar toggleable="lg" type="light" variant="" >

      <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

      <b-navbar-brand href="#">
        <img src="https://placekitten.com/g/30/30" alt="BV">
        AverPoint
      </b-navbar-brand>

      <b-collapse is-nav id="nav_collapse">

        <b-navbar-nav class="ml-auto text-center" >
          <b-nav-item href="#">Home</b-nav-item>
          <b-nav-item href="#">Portfolio</b-nav-item>
          <b-nav-item href="#">Create</b-nav-item>
          <b-nav-item href="#">About</b-nav-item>
        </b-navbar-nav>

        <b-navbar-nav class="ml-auto" >
          <b-nav-form @submit.prevent >
            <b-form-input size="sm" class="mr-sm-2" type="text" placeholder="Search"/>
          </b-nav-form>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto text-center">

          <b-nav-item right class="navbar-right-content" >
            <div class="float-left" >
              <img src="https://placekitten.com/g/30/30" alt="BV">
              <b-badge pill append variant="primary">6</b-badge>
            </div> &nbsp; | &nbsp;
            <img src="../../public/bell.png" width="29px" height="29px" alt="bell">            
          </b-nav-item>
        </b-navbar-nav>

      </b-collapse>
    </b-navbar>
    <!--______________________________ NAVBAR CLOSE________________________________--> 

    <!-- _____________________________ MAIN CONTAINER _____________________________-->

    <b-container class="bv-example-row" fluid>
        <b-row>
          <!-- ______________LEFT NAVBAR __________-->
            <b-col sm="3"> <br>
              <b-container class="bv-example-row">
                <b-row>
                    <b-col sm="12"> <b> Featured topics </b><br><br>
                      <b-link class="custom-a" href="#">Obama care</b-link> <br>
                      <b-link class="custom-a" href="#">Space X</b-link> <br>
                      <b-link class="custom-a" href="#">iPhone X</b-link> <br>
                    </b-col>
                </b-row>
                <b-row>
                    <b-col sm="12">
                      <hr>
                      <b-link class="custom-a-black" href="#">Recently</b-link> &nbsp;
                      <b-link class="custom-a-black" href="#">Active</b-link> &nbsp;
                      <b-link class="custom-a-black" href="#">Most viewed</b-link> 
                      <hr>
                    </b-col>
                </b-row>
                <b-row>
                    <b-col sm="12">Top tags
                      <br>
                      <b-link href="#" class="btn-link" >Trump</b-link> &nbsp;
                      <b-link href="#" class="btn-link" >Europe</b-link> &nbsp;
                      <b-link href="#" class="btn-link" >Hyperloop</b-link>                      
                      <hr>
                    </b-col>
                </b-row>
                <b-row>
                    <b-col sm="12">Top authors <br> <br>
                     <b-row>
                       <b-col >
                         <img src="https://placekitten.com/g/30/30" alt="BV"> Marc Baldwin
                         <span class="float-right">
                           <b-link class="custom-a" href="#">in GQ</b-link>
                         </span>
                       </b-col>
                     </b-row> 
                     <!-- second row -->
                     <br>
                     <b-row>
                       <b-col >
                         <img src="https://placekitten.com/g/30/30" alt="BV"> Marc Baldwin
                         <span class="float-right">
                           <b-link class="custom-a" href="#">in GQ</b-link>
                         </span>
                       </b-col>
                     </b-row>                     
                    </b-col> 
                </b-row> <hr>
                <b-row>
                    <b-col sm="12">From friends
                    </b-col>
                </b-row>
                
              </b-container>

            </b-col>
          <!-- ____________LEFT NAVBAR CLOSE______-->
            <!-- ___________CARD _________-->
            <b-col sm="9" class="color-ghostwhite">
             <b-row class="justify-content-md-center custom-padding-top">
               <b-col sm="9">
                  <b-card title="I am John and think Jane makes a good Point in this Tweet:"
                          header-tag="header"
                          footer-tag="footer">
                      <h6 slot="header"
                          class="mb-0"> <span class="color-blue" > Point </span>&nbsp;
                          <span>20 min ago</span>
                          <span class="float-right">
                            <img src="https://placekitten.com/g/30/30" alt="BV">
                            <b-badge pill append variant="primary">6</b-badge>
                            John Stewart
                          </span>
                      </h6>
                      <em slot="footer">
                       <!-- custom button -->
                       <b-container class="bv-example-row" >
                       <b-row >
                         <b-col sm="6" >
                           <b-button variant="primary btn-custom-width">
                              <img class="custom-img-thumbsup img-flip" src="../../public/thumbsup.png" alt="BV" width="15px" height="15px" >
                              23 Supported <span class="custom-font-size">123 points</span> +
                            </b-button>
                         </b-col>
                       <!-- second btn -->
                         <b-col sm="6" >
                           <b-button variant="primary btn-custom-width">
                              <img class="custom-img-thumbsup img-flip" src="../../public/thumbsup.png" alt="BV" width="15px" height="15px" >
                              12 Oppose <span class="custom-font-size">409 points</span> +
                            </b-button>
                         </b-col>
                       </b-row>
                       
                       </b-container>
                       
                       <!-- custom button close -->
                      </em>
                      <p class="card-text border-round">
                        I am Jane and am stating an opinion on Twitter. Feel free to highlight
                        and Point this on AverPoint! <br> <br>
                        <img src="https://placekitten.com/g/30/30" alt="BV">
                        <b-badge pill append variant="primary">6</b-badge> Jane Baldwin
                      </p>
                      <b-link href="#" class="btn-link" >City</b-link> &nbsp;
                      <b-link href="#" class="btn-link" >Infrastructure</b-link> &nbsp;
                      <b-link href="#" class="btn-link" >Trump</b-link> 
                      <img class="custom-img" src="../../public/buildings.jpg" alt="BV">
                      <br><br>
                      <b-button-group>
                        <button class="btn-link-normal" > <img class="glyphicons" src="../../public/add.png" width="10px" height="10px"> Add</button>
                        <button class="btn-link-normal" > <img class="glyphicons" src="../../public/share.png" width="10px" height="10px">Share</button>
                        <button class="btn-link-normal" > <img class="glyphicons" src="../../public/invite.png" width="10px" height="10px"> Invite</button>
                      </b-button-group>
                      <button class="btn-link-normal float-right" > <img class="glyphicons" src="../../public/publish.png" width="10px" height="10px"> Publish</button>
                  </b-card>
               </b-col>
             </b-row>
            </b-col>
            <!-- _________CARD CLOSE ______-->
        </b-row>
        
    </b-container>

    <!-- _____________________________ MAIN CONTAINER CLOSE________________________-->
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* ________________________________CSS CUSTOM STYLES___________________________________ */
img {
  border-radius: 50%;
}
.custom-word-wrap {
  word-wrap: break-word;
}
.badge-pos {
  position: absolute;
  bottom: 21px;
  right: 7.5%;
}
.color-blue {
  color: blue;
  font-weight: 900;
}
.custom-font-size {
  font-size: 12px;
}
.custom-a {
  color: blue;
}
.custom-a-black {
  color: black;
}
.custom-navbar-color {
  border-bottom: 1px solid lightgray;
  height: 80px;
}
.custom-img {
  border-radius: 0;
  width: 100%;
}
.custom-img-thumbsup {
  border-radius: 0;
}
.img-flip {
  -webkit-transform: scaleY(-1);
  transform: scaleY(-1);
}
.navbar-brand {
  margin-left: 3em;
}
.navbar-right-content {
  margin-right: 3em;
}
.color-ghostwhite {
  background: #f8f8f8;
}
.btn-link {
  display: inline-block;
  margin: 10px 0px;
  border: 1px solid gray;
  padding: 2px 10px;
  border-radius: 35px;
  color: gray;
}
.btn-link-normal {
  border: none;
  background: none;
  color: gray;
}
.float-right {
  float: right;
}
.border-round {
  border-radius: 8px;
  border: 1px solid gray;
  padding: 18px 18px;
}
.glyphicons {
  border-radius: 0;
}
.btn-custom-width {
  width: 100%;
}
.custom-padding-top {
  padding-top: 65px;
}
header,
footer {
  background: white;
}

/* ________________________________CSS CUSTOM STYLES CLOSE_____________________________ */

/* _________________________________CUSTOM MEDIA QUERY _________________________________*/
@media (min-width: 576px) {
  .form-inline .form-control {
    display: inline-block;
    width: 100%;
    vertical-align: middle;
  }
}
/* _________________________________CUSTOM MEDIA QUERY CLOSE____________________________*/
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
