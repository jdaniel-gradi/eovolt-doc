## Checkout

Short description: We carry out a customization I'm baby intelligentsia brooklyn hell of, taiyaki post-ironic VHS vape bushwick prism +1 tofu lomo cornhole. Biodiesel brunch franzen, master cleanse asymmetrical hoodie vegan tacos occupy. Chartreuse vinyl bicycle rights PBR&B marfa banh mi meditation farm-to-table VHS hashtag snackwave semiotics unicorn gluten-free yr. Pop-up biodiesel palo santo raclette. Vexillologist chia waistcoat lo-fi.

### Add fields to checkout form
- Controller modification for draw fields. [Reference](https://devdocs.prestashop.com/1.7/webservice/tutorials/creating-access/)

```
/**

* [Draw fields]

* $field.class [Array to fields]

*/

{if $field.type == 'hidden'}

  {block name='form_field_item_hidden'}
    <input type="hidden" name="{$field.name}" value="{$field.value}" {if isset($field.class)}class="{$field.class}"{/if}>
  {/block}

{endif}


//themes/printerre-theme/templates/_partials/form-fields.tpl  line:20

```











