# Shopify Address Finder Plugin by Addy.co.nz

https://www.addy.co.nz/

Boost conversions and improve order delivery when you integrate Addy's address checking and validation services into your Shopify checkout forms. Find, validate and capture accurate customer addresses at the point of order.

![Shopify Address Autocomplete](https://github.com/addynz/Shopify-Address-Autocomplete/blob/master/shopifyaddressautocomplete.gif)

Addy's service uses intelligent fuzzy matching for addresses (See: https://www.addy.co.nz/address-finder-fuzzy-matching). This means that if a typo, invalid suburb or partially correct address is entered, customers can still find the right delivery or billing address because the addresses are validated against actual delivery point data from official address sources, including the New Zealand Postal Address File (PAF).

## Benefits

- Reduce friction and increase conversion rates with a fast checkout process 
- Create a delightful checkout experience for repeated business
- Deliver to the right address, the first time
- Verify and validate address details in real-time

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

## Prices
Addy's Shopify plugin is free of charge; download and install it at no cost.  Just setup an account with Addy to get your 1,500 free completed address lookups per month.  If you require additional address transactions, simply pay as you go. See: https://www.addy.co.nz/pricing

## Links

Official Addy site: <https://www.addy.co.nz/>

Complete Shopify Integration Documentation: <https://www.addy.co.nz/address-autocomplete-shopify-plugin>

RESTful Address Finder API Documentation: <https://www.addy.co.nz/address-finder-and-postcode-api>

All Documentation: <https://www.addy.co.nz/documentation>

Frequently Asked Questions: <https://www.addy.co.nz/frequently-asked-questions>

## License

The NZ-Address-Autocomplete code is released under the MIT License, 
which has the same license as awesomplete <https://github.com/LeaVerou/awesomplete>.
