# Showcase
<!--{h1:.massive-header.-with-tagline}-->

> All screenshots while using Skyline


<div class="screenshots-grid">
	<div class="grid-sizer"></div>
    <div class="grid-item">
    	<img data-action="zoom" src="images/screenshots/1.jpg">
    </div>
    <div class="grid-item">
    	<img data-action="zoom" src="images/screenshots/2.jpg">
    </div>
    <div class="grid-item">
    	<img data-action="zoom" src="images/screenshots/3.jpg">
    </div>
    <div class="grid-item">
    	<img data-action="zoom" src="images/screenshots/4.jpg">
    </div>
    <div class="grid-item">
    	<img data-action="zoom" src="images/screenshots/5.jpg">
    </div>
    <div class="grid-item grid-item-wide">
    	<img data-action="zoom" src="images/screenshots/6.jpg">
    </div>
    <div class="grid-item grid-item-wide">
    	<img data-action="zoom" src="images/screenshots/7.jpg">
    </div>
    <div class="grid-item">
    	<img data-action="zoom" src="images/screenshots/8.jpg">
    </div>
    <div class="grid-item">
    	<img data-action="zoom" src="images/screenshots/9.jpg">
    </div>
    <div class="grid-item">
        <img data-action="zoom" src="images/screenshots/10.jpg">
    </div>
    <div class="grid-item">
        <img data-action="zoom" src="images/screenshots/11.jpg">
    </div>
    <div class="grid-item">
    </div>
</div>

<script type="text/javascript">
	var $grid = $('.screenshots-grid').masonry({
	  // set itemSelector so .grid-sizer is not used in layout
	  itemSelector: '.grid-item',
	  // use element for option
	  columnWidth: '.grid-sizer',
	  percentPosition: true
	});
	$grid.imagesLoaded().progress( function() {
	  $grid.masonry('layout');
	});
</script>