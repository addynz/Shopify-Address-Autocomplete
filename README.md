# Shopify Address Autocomplete Plugin by Addy.co.nz

https://www.addy.co.nz/

Improve your shopify checkout experience with the type-ahead-search address autocomplete plugin.

Add Address Autocomplete to Shopify in minutes.

## Get started
Create a free account to get your Addy API key: <https://www.addy.co.nz/signup>

1. Login to your Shopify Admin page.
2. Click on Online Store > Preference in the menu.
3. Under Preferences, scroll down and setup Google Analytics (use a blank code such as UA-0000-0) and click Save.
4. Under the Google Analytics account, click Add custom JavaScript.
5. Copy and paste the JavaScript below and replace 'YOUR-ADDY-API-KEY' with your API key.
6. Click Save and you're done!

```javascript
(function(d, w) {
  var s = document.createElement("SCRIPT");
  s.src = 'https://addycdn.azureedge.net/shopify/1.1.0/addycomplete.min.js?key=YOUR-ADDY-KEY';
  s.type = 'text/javascript';
  s.async = 1;
  d.body.appendChild(s);
})(document, window);
```

## Links

Official Addy site: <https://www.addy.co.nz/>

Complete Shopify Integration Documentation: <https://www.addy.co.nz/address-autocomplete-shopify-plugin>

RESTful API Documentation: <https://www.addy.co.nz/address-search-and-postcode-api>

All Documentation: <https://www.addy.co.nz/documentation>

Frequently Asked Questions: <https://www.addy.co.nz/frequently-asked-questions>

## License

The NZ-Address-Autocomplete code is released under the MIT License, 
which has the same license as awesomplete <https://github.com/LeaVerou/awesomplete>.
