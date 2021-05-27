html
		head
		link rel=stylesheet href=Chart.css
		script type=textjavascript src=jquery-3.5.1.jsscript
		script src=httpscdnjs.cloudflare.comajaxlibsChart.js2.8.0Chart.min.jsscript
		head
    body
		canvas id=myChartcanvas
		script
			var randomScalingFactor = function() {
				return Math.round(Math.random()  100);
			};
			var ctx = document.getElementById('myChart').getContext('2d');
			var randomScalingFactor = function() {
				return Math.round(Math.random()  100);
			};
		var myPieChart = new Chart(ctx, {
		type 'pie',
		data {
		
		datasets [{
			data [
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
				randomScalingFactor(),
			],
		
			backgroundColor [
				'red',
				'orange',
				'yellow',
				'coral',
				'lightblue',
				'black',
				'purple',
				'pink',
				'blue',
				'brown',
				'khaki',
				'green'
			],
		
			label 'Colors'
		}],
			labels [
				'red',
				'orange',
				'yellow',
				'coral',
				'lightblue',
				'black',
				'purple',
				'pink',
				'blue',
				'brown',
				'khaki',
				'green'
			]
		},
		options {}
	});
   
		script
	body
html
