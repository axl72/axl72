<style>
    .center{
        align-self: center;
    }
*,:after,:before{box-sizing:border-box}
.pull-left{float:left}
.pull-right{float:right}
.clearfix:after,.clearfix:before{content:'';display:table}
.clearfix:after{clear:both;display:block}

.author-quote-wrap .author-quote,
.author-quote-wrap .author-photo:before{
	top:0;
	left:0;
	right:0;
	bottom:0;
	position:absolute;
}

.author-quote-wrap{
	color:#fff;
	width:100%;
	overflow:hidden;
	max-width:560px;
	min-height:390px;
	margin:50px auto 0;
	background:#17a0ff;
	position:relative;
	box-shadow:0 16px 28px 0 rgba(0,0,0,.22),0 25px 55px 0 rgba(0,0,0,.21);
}
.author-quote-wrap .author-quote{
	display:none;
}
.author-quote-wrap .toggle-quote{
	display:none;
}
.author-quote-wrap .toggle-quote:checked + .author-quote{
	display:block;
}
.author-quote-wrap .author-quote a{
	color:inherit;
	text-decoration:none;
}
.author-quote-wrap .author-photo,
.author-quote-wrap .quote-content{
	height:100%;
	position:relative;
}
.author-quote-wrap .author-photo{
	width:140px;
	background-size:cover;
	background-position:center;
	background-repeat:no-repeat;
	quotes:'\201C''\201D''\2018''\2019';
}
.author-quote-wrap .author-photo.photo-a{
	background-image:url(https://raw.githubusercontent.com/khadkamhn/day-007-author-quote/master/img/author-1.jpg);
}
.author-quote-wrap .author-photo.photo-b{
	background-image:url(https://raw.githubusercontent.com/khadkamhn/day-007-author-quote/master/img/author-2.jpg);
}
.author-quote-wrap .author-photo.photo-c{
	background-image:url(https://raw.githubusercontent.com/khadkamhn/day-007-author-quote/master/img/author-3.jpg);
}
.author-quote-wrap .author-photo.photo-d{
	background-image:url(https://raw.githubusercontent.com/khadkamhn/day-007-author-quote/master/img/author-4.jpg);
}
.author-quote-wrap .author-photo.photo-e{
	background-image:url(https://raw.githubusercontent.com/khadkamhn/day-007-author-quote/master/img/author-5.jpg);
}
.author-quote-wrap .author-photo:before{
	content:'';
	background:rgba(22,160,255,.5);
}
.author-quote-wrap .author-photo:after{
	top:15px;
	left:60px;
	font-size:72px;
	line-height:72px;
	position:absolute;
	font-family:serif;
	content:open-quote;
}
.author-quote-wrap .author-photo .navigate{
	left:15px;
	z-index:10;
	right:15px;
	bottom:15px;
	position:absolute;
	text-align:center;
}
.author-quote-wrap .author-photo .navigate .label{
	width:15px;
	height:30px;
	cursor:pointer;
	position:relative;
	display:inline-block;
}
.author-quote-wrap .author-photo .navigate .label.left{
	left:-30px;
}
.author-quote-wrap .author-photo .navigate .label.right{
	right:-30px;
}
.author-quote-wrap .author-photo .navigate .label.disabled{
	cursor:not-allowed;
}
.author-quote-wrap .author-photo .navigate .label:before,
.author-quote-wrap .author-photo .navigate .label:after{
	content:'';
	height:2px;
	width:15px;
	background:#ccc;
	position:absolute;
}
.author-quote-wrap .author-photo .navigate .label:before{
	top:62%;
}
.author-quote-wrap .author-photo .navigate .label:after{
	bottom:62%;
}
.author-quote-wrap .author-photo .navigate .label.left:before,
.author-quote-wrap .author-photo .navigate .label.right:after{
	transform:rotate(45deg);
}
.author-quote-wrap .author-photo .navigate .label.right:before,
.author-quote-wrap .author-photo .navigate .label.left:after{
	transform:rotate(-45deg);
}
.author-quote-wrap .author-photo .navigate .label.left:before,
.author-quote-wrap .author-photo .navigate .label.left:after{
	left:0;
}
.author-quote-wrap .author-photo .navigate .label.right:before,
.author-quote-wrap .author-photo .navigate .label.right:after{
	right:0;
}
.author-quote-wrap .author-photo .navigate .label.disabled:before,
.author-quote-wrap .author-photo .navigate .label.disabled:after,
.author-quote-wrap .author-photo .navigate .label.disabled:hover:before,
.author-quote-wrap .author-photo .navigate .label.disabled:hover:after{
	background:#bbb;
}
.author-quote-wrap .author-photo .navigate .label:hover:before,
.author-quote-wrap .author-photo .navigate .label:hover:after{
	background:#fff;
}

.author-quote-wrap .quote-content{
	padding:15px;
	width:calc(560px - 140px);
}
.quote-content .quote-like{
	font-size:12px;
	font-weight:400;
	padding:4px 8px;
	border-radius:15px;
	display:inline-block;
	background:rgba(0,0,0,.2);
}
.quote-content .quote-like .love{
    width:18px;
    height:10px;
    position:relative;
	display:inline-block;
}
.quote-content .quote-like .love:before,
.quote-content .quote-like .love:after {
    top:0;
    left:7px;
    content:'';
    width:7px;
    height:12px;
    background:#fff;
    position:absolute;
	transform:rotate(-45deg);
	transform-origin:0 100%;
    border-radius:20px 20px 0 0;
}
.quote-content .quote-like .love:after {
    left:0;
	transform:rotate(45deg);
	transform-origin :100% 100%;
}

.quote-content .quote-text,
.quote-content .quote-author{
	text-transform:uppercase;
}
.quote-content .quote-text{
	font-size:48px;
	font-weight:900;
	line-height:55px;
}
.quote-content .quote-author{
	bottom:15px;
	font-size:14px;
	font-weight:500;
	position:absolute;
}
.quote-content .quote-author:before{
	content:'- ';
}
</style>

<div>
    <img src="https://media.giphy.com/media/UqxVRm1IaaIGk/giphy.gif"/>
    <h1> I'm axl</h1>
    <h3 class=center>
        La peor parte del infierno no son las llamas, sino no poder encontrar un debugger
    </h3>
   
</div>


<div class="author-quote-wrap">
	<input class="toggle-quote" type="radio" id="AQ-1" name="quote" checked>
	<div class="author-quote">
		<div class="pull-left author-photo photo-a animated bounceInLeft">
			<div class="navigate">
				<label class="label left" for="AQ-5">&nbsp;</label>
				<label class="label right" for="AQ-2">&nbsp;</label>
			</div>
		</div>
		<div class="pull-right quote-content">
			<div class="clearfix animated zoomIn"><div class="quote-like pull-right"><span class="love"></span> 423</div></div>
			<div class="quote-text animated rotateInDownRight">Don't You<br>Think That<br>If I Were<br>Wrong,<br>I'd Know It?</div>
			<div class="quote-author animated lightSpeedIn">Sheldon Cooper</div>
		</div>
	</div>
	<input class="toggle-quote" type="radio" id="AQ-2" name="quote">
	<div class="author-quote">
		<div class="pull-left author-photo photo-b animated bounceInLeft">
			<div class="navigate">
				<label class="label left" for="AQ-1">&nbsp;</label>
				<label class="label right" for="AQ-3">&nbsp;</label>
			</div>
		</div>
		<div class="pull-right quote-content">
			<div class="clearfix animated zoomIn"><div class="quote-like pull-right"><span class="love"></span> 512</div></div>
			<div class="quote-text animated zoomInDown">My Goal Was<br>To Prove<br>To My Family<br>I wasn't a dummy</div>
			<div class="quote-author animated lightSpeedIn">Ronalda Colen</div>
		</div>
	</div>
	<input class="toggle-quote" type="radio" id="AQ-3" name="quote">
	<div class="author-quote">
		<div class="pull-left author-photo photo-c animated bounceInLeft">
			<div class="navigate">
				<label class="label left" for="AQ-2">&nbsp;</label>
				<label class="label right" for="AQ-4">&nbsp;</label>
			</div>
		</div>
		<div class="pull-right quote-content">
			<div class="clearfix animated zoomIn"><div class="quote-like pull-right"><span class="love"></span> 618</div></div>
			<div class="quote-text animated bounceInRight">Smart-Phones.<br>Who Cares?<br>Smart-Phones.<br>I Only Have<br>Dummy Phones</div>
			<div class="quote-author animated lightSpeedIn">Don Rickles</div>
		</div>
	</div>
	<input class="toggle-quote" type="radio" id="AQ-4" name="quote">
	<div class="author-quote">
		<div class="pull-left author-photo photo-d animated bounceInLeft">
			<div class="navigate">
				<label class="label left" for="AQ-3">&nbsp;</label>
				<label class="label right" for="AQ-5">&nbsp;</label>
			</div>
		</div>
		<div class="pull-right quote-content">
			<div class="clearfix animated zoomIn"><div class="quote-like pull-right"><span class="love"></span> 741</div></div>
			<div class="quote-text animated lightSpeedIn">Design<br>Means<br>Being Good<br>Not Just<br>Looking Good</div>
			<div class="quote-author animated lightSpeedIn">Jacquie Dermody</div>
		</div>
	</div>
	<input class="toggle-quote" type="radio" id="AQ-5" name="quote">
	<div class="author-quote">
		<div class="pull-left author-photo photo-e animated bounceInLeft">
			<div class="navigate">
				<label class="label left" for="AQ-4">&nbsp;</label>
				<label class="label right" for="AQ-1">&nbsp;</label>
			</div>
		</div>
		<div class="pull-right quote-content">
			<div class="clearfix animated zoomIn"><div class="quote-like pull-right"><span class="love"></span> 824</div></div>
			<div class="quote-text animated flipInX">Design<br>Is<br>Thinking<br>Made<br>Visible</div>
			<div class="quote-author animated lightSpeedIn">Mohan Khadka</div>
		</div>
	</div>
</div>
<div>
    <a href="https://brokenlink.com" target="_blank"> 
        <img src="https://img.shields.io/website?down_message=Click%20Me%20%F0%9F%8D%91&style=for-the-badge&up_color=skyblue&up_message=Go%20to%20My%20WebSite&url=https%3A%2F%2Fbrokenlink.com"/>
    </a>
</div>

---

<div>
<h1>Sobre mí</h1>
Nada interesnte
</div>

---
<div>

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=axl72&theme=bear&border_radius=4.7&locale=es&date_format=M%20j%5B%2C%20Y%5D&background=B6C7DD)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=axl72&layout=compact&exclude_repo=obsidian-notes&hide=html)](https://github.com/anuraghazra/github-readme-stats)




</div>