<template>
  <div>
    <!--______________________________ NAVBAR _____________________________________-->
    <b-navbar toggleable="lg" type="light" variant="" class="custom-navbar-color" >

      <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

      <b-navbar-brand href="#">
        <img src="https://placekitten.com/g/30/30" alt="BV">
        AverPoint
      </b-navbar-brand>

      <b-collapse is-nav id="nav_collapse">

        <b-navbar-nav class="nav-bar ml-auto text-center" style="padding: 0 0 0 50px;" >
          <b-nav-item class="active" href="#">Home</b-nav-item>
          <b-nav-item href="#">Portfolio</b-nav-item>
          <b-nav-item href="#">Create</b-nav-item>
          <b-nav-item href="#">About</b-nav-item>
        </b-navbar-nav>

        <b-navbar-nav class="ml-auto text-center">
          <b-nav-form @submit.prevent class="custom-form-navbar" >
            <div class="custom-search" >
              <i class="fa fa-search twenty-min-ago" style="font-size:16px; transform: translateY(23%);" ></i>
            <b-form-input size="sm" class="mr-sm-2 custom-search-field" type="text" placeholder="Search..."/>
            </div>
          </b-nav-form>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav right class="ml-auto text-center" style="padding: 0px 70px 0px 0px;">
          <b-nav-item class="navbar-right-content" >
            <div class="float-left" >
              <img src="https://placekitten.com/g/30/30" alt="BV">
              <b-badge pill append variant="primary badge-pos">14</b-badge>| &nbsp;
              <!-- <img src="../../public/bell.png" width="29px" height="29px" alt="bell">             -->
              <i class="fa fa-bell-o" aria-hidden="true" style="font-size: 17px;"></i>
            </div>
          </b-nav-item>
        </b-navbar-nav>

      </b-collapse>
    </b-navbar>
    <!--______________________________ NAVBAR CLOSE________________________________--> 

    <!-- _____________________________ MAIN CONTAINER _____________________________-->

    <b-container class="bv-example-row" fluid>
        <b-row >
          <!-- ______________LEFT NAVBAR __________-->
            <b-col sm="3" class="left-nav-border" > <br>
              <b-container class="bv-example-row">
                <b-row>
                    <b-col sm="12"> <span class="custom-featured-topics" > Featured topics</span><br><br>
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
                    <b-col sm="12"> <span class="custom-top-tags" >Top tags</span>
                      <br>
                      <b-link href="#" class="btn-link" >Trump</b-link> &nbsp;
                      <b-link href="#" class="btn-link" >Europe</b-link> &nbsp;
                      <b-link href="#" class="btn-link" >Hyperloop</b-link>                      
                      <hr>
                    </b-col>
                </b-row>
                <b-row>
                    <b-col sm="12"> <span class="custom-top-authors" > Top authors </span> <br> <br>
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
                  <b-card no-body title=""
                          header-tag="header"
                          footer-tag="footer">
                      <h6 slot="header"
                          class="mb-0 card-header-padding"> <span class="color-blue" > Point </span>&nbsp;
                          <span class="twenty-min-ago" >
                            20 mins ago
                            <i class="fa fa-globe" aria-hidden="true"></i>
                          </span>
                          <span class="float-right">
                            <img src="https://placekitten.com/g/30/30" alt="BV">
                            <b-badge pill append variant="primary badge-pos">14</b-badge>John Stewart
                          </span>
                      </h6>
                      <!-- <em slot="footer">
                       <b-container class="bv-example-row" >
                       <b-row >
                         <b-col lg="6" >
                           <b-button variant="primary btn-custom-width">
                              <i class="fa fa-thumbs-up" aria-hidden="true"></i>
                              23 Supported <span class="custom-font-size">123 points</span> &nbsp;
                              <i class="fa fa-plus" aria-hidden="true"></i>
                            </b-button>
                         </b-col>

                         <b-col lg="6" >
                           <b-button variant="primary btn-custom-width">
                              <i class="fa fa-thumbs-down" aria-hidden="true"></i>
                              12 Oppose <span class="custom-font-size">409 points</span> &nbsp;
                              <i class="fa fa-plus" aria-hidden="true"></i>
                            </b-button>
                         </b-col>
                       </b-row>
                       
                       </b-container>
                       
                      </em> -->
                     <b-card-body>
                       <h4 class="custom-title-padding" >I am John and think Jane makes a good Point in this Tweet:</h4>
                        <p class="card-text border-round">
                              <b-form-textarea id="textarea1"
                                              class="custom-input-field"
                                              v-model="text"
                                              placeholder="Enter something"
                                              :rows="2"
                                              :max-rows="6">
                              </b-form-textarea> 
                          <img src="https://placekitten.com/g/30/30" alt="BV">
                          <b-badge pill append variant="primary badge-pos">5</b-badge> Jane Baldwin
                        </p>
                     
                      <b-link href="#" class="btn-link" >City</b-link> &nbsp;
                      <b-link href="#" class="btn-link" >Infrastructure</b-link> &nbsp;
                      <b-link href="#" class="btn-link" >Trump</b-link> 
                      </b-card-body>
                      <img class="custom-img" src="../../public/buildings.jpg" alt="BV">
                      <b-card-body>
                        <b-button-group>
                          <button class="btn-link-normal" > <i class="fa fa-plus" aria-hidden="true"></i> Add</button>
                          <button class="btn-link-normal" > <i class="fa fa-share-alt" aria-hidden="true"></i> Share</button>
                          <button class="btn-link-normal" > <i class="fa fa-user-plus" aria-hidden="true"></i> Invite</button>
                        </b-button-group>
                        <button class="btn-link-normal float-right" > <img class="glyphicons custom-style-upload" src="../../public/upload.png" width="10px" height="10px"> Publish</button>
                      </b-card-body>
                  </b-card>
            <!-- ________________________________butttons herer ______________________________-->
            <b-container class="bv-example-row" style="padding:20px 0 0 0;">
                       <b-row no-guttersS>
                         <b-col lg="6">
                           <b-button variant="primary btn-custom-width">
                              <i class="fa fa-thumbs-up" aria-hidden="true"></i>
                              23 Supported <span class="custom-font-size">123 points</span> &nbsp;
                              <i class="fa fa-plus" aria-hidden="true"></i>
                            </b-button>
                         </b-col>

                         <b-col lg="6">
                           <b-button variant="primary btn-custom-width right_button"  >
                              <i class="fa fa-thumbs-down" aria-hidden="true"></i>
                              12 Oppose <span class="custom-font-size">409 points</span> &nbsp;
                              <i class="fa fa-plus" aria-hidden="true"></i>
                            </b-button>
                         </b-col>
                       </b-row>
                       
              </b-container>
            <!-- ________________________________butttons herer close__________________________ -->
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
  name: "Home",
  data: function() {
    return {
      text:
        "I am Jane and am stating an opinion on Twitter. Feel free to highlight and Point this on AverPoint!"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* ________________________________CSS CUSTOM STYLES___________________________________ */
img {
  border-radius: 50%;
}
.nav-bar a {
  padding: 2em 0;
}
.nav-bar li {
  border-bottom: 3px solid transparent;
}
.nav-bar li:hover {
  border-bottom: 3px solid blue;
}

.nav-bar li.active {
  border-bottom: 3px solid blue;
}
.custom-search {
  display: inline-flex;
  border: 1px solid gray;
  border-radius: 11px;
  padding: 0 13px;
  width: 190px;
  background: #fafdfe;
}
.custom-form-navbar {
  display: block;
}
.custom-featured-topics {
  font-size: 19px;
  font-weight: 600;
}
.custom-top-tags {
  font-size: 18px;
  line-height: 3;
}
.custom-style-upload {
  bottom: 1px;
  position: relative;
}
.custom-title-padding {
  padding: 15px 0;
}
.custom-top-authors {
  font-size: 18px;
}
.custom-search-field:focus,
.custom-search-field {
  border: none;
  color: #495057;
  background-color: #fafdfe;
  border-color: rgba(248, 249, 250, 0);
  outline: 0;
  -webkit-box-shadow: none;
  box-shadow: 0 0 0 0.2rem rgba(248, 249, 250, 0);
}
.custom-input-field:focus,
.custom-input-field {
  border: none;
  color: #495057;
  background-color: #fff;
  border-color: rgba(248, 249, 250, 0);
  outline: 0;
  -webkit-box-shadow: none;
  box-shadow: 0 0 0 0.2rem rgba(248, 249, 250, 0);
}
.left-nav-border {
  border-right: 1px solid lightgray;
  padding-right: 0;
}
.custom-word-wrap {
  word-wrap: break-word;
}
.badge-pos {
  vertical-align: bottom;
  position: relative;
  right: 12px;
  top: 3px;
  border: 1px solid white;
  font-size: 8px;
}
.card-header-padding {
  padding-top: 10px;
  padding-bottom: 13px;
}
.color-blue {
  color: #2b90ce;
  font-weight: 1000;
}
.twenty-min-ago {
  color: lightgray;
}
.custom-font-size {
  font-size: 12px;
}
.custom-a {
  color: dodgerblue;
  line-height: 34px;
}
.custom-a-black {
  color: black;
  padding: 0 9px;
}
.custom-navbar-color {
  border-bottom: 1px solid lightgray;
  padding: 0;
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
  margin-left: 4em;
}
.navbar-right-content {
  /* margin-right: 3em; */
  margin: 0 auto;
  margin: 0 !important;
}
.color-ghostwhite {
  background: #f8f8f8;
}
.btn-link {
  display: inline-block;
  margin: 10px 0px;
  border: 1px solid lightgray;
  padding: 2px 10px;
  border-radius: 35px;
  color: gray;
  font-size: 13px;
}
.btn-link-normal {
  border: none;
  background: none;
  color: lightgray;
}
.float-right {
  float: right;
}
.border-round {
  border-radius: 8px;
  border: 1px solid lightgray;
  padding: 15px 15px;
}
.glyphicons {
  border-radius: 0;
}
.btn-custom-width {
  width: 100%;
  margin-bottom: 10px;
}
.right_button {
  float: right;
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
