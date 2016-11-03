# Pickrr-Prestashop order placing plugin

##### Step 1: First go to the backend of your admin panel and go to advance parameter -> Webservice and add new web service api key then give all view permissions and save it and after that check "Enable PrestaShop's webservice" and 'Enable CGI mode for PHP" and again click on save button 

##### Step 2: Then go to the root directory of the project and scroll to "/www/html/prestashop/admin/themes/default/template/controllers/orders/helpers/view.tpl" open view.tpl and go to line 124 and find the div  class="well hidden-print" and after first anchor tag paste the below given code




```javascript
<a target="_blank" class="btn btn-success" href="https://pickrr.herokuapp.com/prestashop/order/{$order->id}">
     <i class="icon-truck"></i>
		{l s='place to pickrr'}
</a>
&nbsp;
```

##### Step 3: After that whenever you open order detail page you will find "place to pickrr" button in your backend

##### Step 4: After that send your webservices api key to harish@pickrr.com or info@pickrr.com

##### Step 5: Detailed Description is given in demo video https://youtu.be/pATbxVOOOwk
