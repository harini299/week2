<!doctype html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
<title> desktop</title>
<style type="text/css">
	*{
		box-sizing: border-box;
	}
	h1 {
    text-align: center;
    font-size: 1.75em;
}

h2 {
    border: 3px solid black;
    font-size: 1.25em;
    text-align:center;
    float:right;
    padding-left: 30px;
    padding-right: 30px;
    position: relative;
    right: 10px;
    bottom: 5px;
    width: 150px;
    margin-bottom: auto;

}

p {
	text-align: center;
    margin: 10px;
    border: 4px solid black;
    background-color:gray;
    padding-top: 40px;
    padding-left: 15px;
    padding-right:15px;

}

.chicken {
    background-color:pink;
}

.beef {
    color: white;
    background-color: brown;
}

.sushi {
    background-color: sandybrown;
}


/* Simple Responsive Framework. */
.row {
  width: 100%;
}

/* Large devices only */
@media (min-width: 992px) {

  .col-lg-4 {
    float: left;
  }

  .col-lg-4 {
    width: 33.33%;
  }

}

/* Medium devices only */
@media (min-width: 768px) and (max-width: 991px) {

  .col-md-6, .col-md-12 {
    float: left;
}

  .col-md-6 {
    width: 50%;
  }

  .col-md-12 {
    width: 100%;
  }
}

/* Small devices only */
@media (max-width: 767px) {

.col-sm-12 {
    float: left;
}
.col-sm-12{
    width: 100%;
}

h2 {
    bottom: 15px;
}
}
	</style>
</head>
<body>
	<div class="row">
		<div class="col-lg-4 col-md-6">
			<h2 class="chicken">Chicken</h2>
			 <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it.</p>
         </div>
        

        <div class="col-lg-4 col-md-6">
        <h2 class="beef">Beef</h2>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it. </p>
        </div>

        <div class="col-lg-4 col-md-12">
        <h2 class="sushi">Sushi</h2>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it. </p>
         </div>
    </div>

</body>
</html>
	
