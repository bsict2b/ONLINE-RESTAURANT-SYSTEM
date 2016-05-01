<?php
function formatMoney($number, $fractional=false) {
		if ($fractional) {
			$number = sprintf('%.2f', $number);
		}
		while (true) {
			$replaced = preg_replace('/(-?\d+)(\d\d\d)/', '$1,$2', $number);
			if ($replaced != $number) {
				$number = $replaced;
			} else {
				break;
			}
		}
		return $number;
	}
?>

<!DOCTYPE HTML>
<html>
  <head>
	  <title>BON APPETITE</title>
	  <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
	  <link href="web/css/style.css" rel="stylesheet" type="text/css"  media="all" />
	  <link href='http://fonts.googleapis.com/css?family=Open+Sans' rel='stylesheet' type='text/css'>
      
      <link rel="icon" type="image/png" href="images/favicon.png" />
<link href="css/style.css" media="screen" rel="stylesheet" type="text/css" />

<link href="admin/src/facebox.css" media="screen" rel="stylesheet" type="text/css" />
<script src="admin/lib/jquery.js" type="text/javascript"></script>
<script src="admin/src/facebox.js" type="text/javascript"></script>
<script type="text/javascript">
  jQuery(document).ready(function($) {
    $('a[rel*=facebox]').facebox({
      loadingImage : 'admin/src/loading.gif',
      closeImage   : 'admin/src/closelabel.png'
    })
  })
</script>
    
  
  
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
  <link href="web/css/style.css" rel="stylesheet" type="text/css"  media="all" />
  <link href='http://fonts.googleapis.com/css?family=Open+Sans' rel='stylesheet' type='text/css'>
  <link href="web/css/slider.css" rel="stylesheet" type="text/css"  media="all" />
  <script type="text/javascript" src="web/js/jquery.min.js"></script> 
  <script type="text/javascript" src="web/js/jquery.easing.1.3.js"></script> 
  <script type="text/javascript" src="web/js/camera.min.js"></script>
  <script type="text/javascript" src="web/js/jquery.lightbox.js"></script> 
  <link rel="stylesheet" type="text/css" href="web/css/lightbox.css" media="screen" />
	  <script type="text/javascript">
		  $(function() {
			$('.gallery a').lightBox();
		  });
	  </script>
	 <script type="text/javascript">
			   jQuery(function(){
				jQuery('#camera_wrap_1').camera({
					pagination: false,
				});
			});
	 </script>
      
 </head>
	<body>
	<!----start-header----->
	 <div class="header">
	     <div class="wrap">
			<div class="top-header">
				<div class="logo">
					<a href="index.html"><img src="web/images/logo1.png" title="logo" /></a>
				</div>
				<div class="social-icons">
					<ul>
						<li><a href="#"><img src="web/images/facebook.png" title="facebook" /></a></li>
						<li><a href="#"><img src="web/images/twitter.png" title="twitter" /></a></li>
						<li><a href="#"><img src="web/images/google.png" title="google pluse" /></a></li>
					</ul>
				</div>
				<div class="clear"> </div>
			</div>
			
			<div class="top-nav">
				<div class="top-nav-left">
					<ul>
						<li><a href="index.html">Home</a></li>
						<li><a href="about.html">About</a></li>
                        <li class="active"><a href="menu.html">Menu</a></li>
						<li><a href="services.html">Services</a></li>
					
						<li><a href="contact.html">Contact</a></li>
						<div class="clear"> </div>
					</ul>
				</div>
				<div class="top-nav-right">
					<form>
						<input type="text"><input type="submit" value="" />
					</form>
				</div>
				<div class="clear"> </div>
			</div>
		
		</div>
	</div>

        
		 <div id="about" style="overflow: scroll; height: 390px;">
								
								<ul class="price-list p2">
									<strong style="font-size: 18px;">Specialty</strong>
									<?php
										include('connect.php');
										$id='specialty';
										$result = $db->prepare("SELECT * FROM menu WHERE mcat= :mmm");
										$result->bindParam(':mmm', $id);
										$result->execute();
										for($i=0; $row = $result->fetch(); $i++){
									?>n
									<li><span>Php <?php $dsds=$row['price'];
									echo formatMoney($dsds, true);
									?></span><a rel="facebox" href="menudetails.php?id=<?php echo $row['id']; ?>"><?php echo $row['name']; ?></a></li>
									<?php
										}
									?>
								</ul>
								<ul class="price-list p2">
									<strong style="font-size: 18px;">Lunch and Dinner</strong>
									<br><strong style="font-size: 12px; font-style:italic;">( Combo 250 - 1 soup/3 main course/1 salad/1 desert/rice/soft drinks )</strong>
									<br><strong style="font-size: 12px; font-style:italic;">( Combo 315 - 1 soup/4 main course/1 salad/1 desert/rice/soft drinks )</strong>
									<br><strong style="font-size: 12px; font-style:italic;">( Combo 400 - 1 soup/4 main course/2 salad/2 desert/rice/soft drinks )</strong>
									<?php
										$id='lunch_and_dinner';
										$result = $db->prepare("SELECT * FROM menu WHERE mcat= :mmm");
										$result->bindParam(':mmm', $id);
										$result->execute();
										for($i=0; $row = $result->fetch(); $i++){
									?>
									<li><span><?php echo $row['price']; ?></span><a rel="facebox" href="menudetails.php?id=<?php echo $row['id']; ?>"><?php echo $row['name']; ?></a></li>
									<?php
										}
									?>
								</ul>
								<ul class="price-list p2">
									<strong style="font-size: 18px;">Merienda</strong>
									<br><strong style="font-size: 12px; font-style:italic;">( Combo 285 - 2 pasta/2 meat/3 bread/2 dessert/softdrinks )</strong>
									<?php
										$id='merienda';
										$result = $db->prepare("SELECT * FROM menu WHERE mcat= :mmm");
										$result->bindParam(':mmm', $id);
										$result->execute();
										for($i=0; $row = $result->fetch(); $i++){
									?>
									<li><span><?php echo $row['price']; ?></span><a rel="facebox" href="menudetails.php?id=<?php echo $row['id']; ?>"><?php echo $row['name']; ?></a></li>
									<?php
										}
									?>
								</ul>
							</div>
	
	
		
	<div class="copy-right">
		<div class="top-to-page">
						<a href="#top" class="scroll"> </a>
						<div class="clear"> </div>
					</div>
		<p><a href="bonappetite.com/"> Copyright @ www.bonappetite.com</a></p>

	</div>
		
	</body>
</html>

