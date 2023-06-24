
# rf-loan-widget

  

refinn loan calculator widget

  

## Installation

  

```

<script>

(function (w, d, s, o, f, js, fjs) {

w[o] = w[o] || function () { (w[o].q = w[o].q || []).push(arguments) };

js = d.createElement(s), fjs = d.getElementsByTagName(s)[0];

js.id = o; js.src = f; js.async = 1; fjs.parentNode.insertBefore(js, fjs);

}(window, document, 'script', 'loancalculator_widget', './rf-loan-widget.js'));

  
  

loancalculator_widget('init', {}, 'refinn-loan-calculator-widget', 'price', 2, '', '', 'prod');

loancalculator_widget_2('init', {}, 'refinn-loan-calculator-widget-2', '', 5, '', '', 'dev');

</script>

```

  

<b>loancalculator_widget('init', {}, id, price, promotions per page, affiliateid, utm, environment) to init widget need to config like this</b>

id value is mandatory<br/>

price value is optional<br/>

promotions per page are mandatory<br/>

affiliateid for affiliate model can set = ''<br/>

utm for tracking can set = ''

environment is mandatory
can set dev and prod
it will affect refinn redirect url


refinn-loan-calculator-widget = div id that will render widget <br/>

price = id of value to point to reference when what to auto detect price if not to specific can use empty string eg. <br/>

loancalculator_widget('init', {}, 'refinn-loan-calculator-widget', ''); <br/><br/>

  

Note: Can see example source code in index.html file