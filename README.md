#Chrome Money Printer

Currency Generation Engine for Chrome - To Use with Chrome's Packaged apps.

##How this works

You simply add `money.js` file to your chrome web app as shown below. After that you can start printing money that passes even the most stringent of counterfeit tests, directly from within chrome

##Example

~~~html

<!doctype html>
<html>
  <head>
		<script type="text/javascript" src='money.js'></script>
		<script type="text/javascript">

			var money = require('money');
			money.setCurrency('USD');
			money.setAmount(100);
			money.setQuantity(42);
			money.print();

		</script>
	</head>
</html>

~~~

##So, where is magical `money.js`

Yes. it is not not there yet. But this is how it should be. 

**Why don't you just click on the fork button?**

[Parody](https://github.com/arunoda/chrome-node)

