<template>
  <div class="home">
   <div class='container-fluid' >
						
						<div class='v-align' >
							<div class='inner' >
								<div class='intro-text' >
									<h1> Hi<i class="fa-sharp fa-regular fa-face-smile fa-beat"></i> I'm Nontobeko </h1>
    					<p>
										Full stack Developer
									</p>
									<div class='intro-btns' >		
										<a href='https://www.canva.com/design/DAFgcb3O8a8/-JeIQ1I_L58Ey_vkX2SWVA/edit?utm_content=DAFgcb3O8a8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton' class='btn-custom section-toggle' target="_blank_" >
											Download Cv
										</a>	
									</div>
								</div>
							</div>
						</div>
					</div>
  </div>
</template>

<script>


export default {
  name: 'HomeView',
  components: {
   
  }
}
</script>
<style scoped>
.home{
  padding-top:6rem;
  min-height:100vh;
}
.intro-text{
	padding-top:200px;
	text-align:center;
}
.intro-text > h1{
	margin:0;
	color:#202020;
	text-transform:uppercase;
	font-weight:900;
	letter-spacing:8px;
	font-size:78px;
}
.intro-text > p{
	font-size:18px;
	color:rgba(0,0,0,.3);
	color:rgba(255,255,255,.8);
	margin-top:15px;
	margin-bottom:0;
	font-weight:300;
	font-style:italic;
	letter-spacing:2px;
}
.intro-text > .intro-btns{
	margin-top:45px;
}
.intro-text > .intro-btns > .btn-custom{
	margin:0 15px;
}
a.btn-custom{
	color:#FFF;
	text-decoration:none;
}
.btn-custom{
	color:#FFF;
	letter-spacing:4px;
	text-transform:uppercase;
	text-decoration:none;
	text-align:center;
	font-size:11px;
	font-weight:400;
	display:inline-block;
	*display:inline;
	*zoom:1;
	line-height:1em;
	padding:17px 32px;
	position:relative;
	z-index:5;
	background:transparent;
	border:none;
}
.btn-custom:after{
	content: ' ';
	position:absolute;
	top:0;
	left:-10px;
	right:-10px;
	bottom:0;
	-webkit-transform:rotate(-4deg);
	-moz-transform:rotate(-4deg);
	-ms-transform:rotate(-4deg);
	-o-transform:rotate(-4deg);
	transform:rotate(-4deg);
	z-index:-1;
	opacity:0;
	visibility:hidden;
	background:rgba(0,0,0,.3);
	-webkit-transition:all .3s cubic-bezier(.785,.135,.15,.86);
	-moz-transition:all .3s cubic-bezier(.785,.135,.15,.86);
	transition:all .3s cubic-bezier(.785,.135,.15,.86);
}
.btn-custom:before{
	content: ' ';
	position:absolute;
	top:0;
	left:0;
	right:0;
	bottom:0;
	z-index:2;
	border:solid 1px #FFF;
	border-color:rgba(255,255,255,.8);
}
.btn-custom:hover:after{
	opacity:1;
	visibility:visible;
}
.btn-custom.btn-color:after{
	background:#303F9F;
}
.btn-custom.btn-color:hover:after{
	opacity:.4;
}
.btn-custom.btn-color{
	color:#202020;
}
.btn-custom.btn-color > span:before,
.btn-custom.btn-color > span:after{
	background:rgba(0,0,0,.2);
}
.btn-custom.btn-color:before{
	border-color:rgba(0,0,0,.2);
}
@media only screen and (max-width: 600px) {
.home{
	width: 100%;
	overflow-x: hidden;
}
.intro-text{
	position: relative;
	text-align: center;
  font-size:12px;
}}

</style>
