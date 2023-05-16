# rf-loan-widget
refinn loan calculator widget


Installation

<script>
        (function (w, d, s, o, f, js, fjs) {
            w[o] = w[o] || function () { (w[o].q = w[o].q || []).push(arguments) };
            js = d.createElement(s), fjs = d.getElementsByTagName(s)[0];
            js.id = o; js.src = f; js.async = 1; fjs.parentNode.insertBefore(js, fjs);
        }(window, document, 'script', 'loancalculator_widget', './rf-loan-widget.js'));
        loancalculator_widget('init', {}, 'refinn-loan-calculator-widget', 'price');
    </script>

loancalculator_widget('init', {}, <id>, <price>)
to init widget need to config like this
the id value is mandatory
the price value is optional

refinn-loan-calculator-widget = div id that will render widget
price = id of value to point to reference when what to auto detect price if not to specific can use empty string eg. loancalculator_widget('init', {}, 'refinn-loan-calculator-widget', '');