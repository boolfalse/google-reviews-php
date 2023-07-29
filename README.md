
## Google Reviews PHP


### About:

- This is a simple PHP script to get Google Reviews from Google Maps API and display them on your website.



#### Installation:

- Enable *Google Maps JS* and *Google Places* API services from [GCP](https://console.cloud.google.com/apis/dashboard)

- Get Google Place ID from [Place ID Finder](https://developers.google.com/maps/documentation/javascript/examples/places-placeid-finder).

- Get Google API Key from [here](https://developers.google.com/maps/documentation/javascript/get-api-key).

- Set appropriate credentials in the "config.php" like this:
```php
<?php

return [
    'google_place_id' => "***",
    'google_api_key' => "***",
];
```

- Set *schema.json* file like this:
```json
{
  "@context": "https://schema.org",
  "@type": "SportswearStore",
  "name": "Nike The Grove",
  "url": "https://nike.com/",
  "logo": "https://c.static-nike.com/a/images/w_1920,c_limit/bzl2wmsfh7kgdkufrrjq/image.jpg",
  "image": "https://c.static-nike.com/a/images/w_1920,c_limit/bzl2wmsfh7kgdkufrrjq/image.jpg",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "189 The Grove Dr Space Q-30",
    "addressLocality": "Los Angeles",
    "addressRegion": "CA",
    "postalCode": "90036",
    "addressCountry": "US",
    "telephone": "+13239370168"
  },
  "priceRange": "$$$"
}
```



#### Sources:

- [Google Rich Results](https://search.google.com/test/rich-results)
- Google Rich Results [Testing Tool](https://search.google.com/test/rich-results)
- Google Structured Data [Testing Tool](https://developers.google.com/search/docs/advanced/structured-data)
- Example [repo](https://github.com/mikeott/google-reviews)


- [Useful Schema Markup for the Finance Industry](https://salience.co.uk/insight/magazine/schema-for-finance-sites/#financialservice)
- [How finance marketers can use schema to boost SEO](https://www.thedubs.com/how-finance-marketers-can-use-schema-to-boost-their-seo/)



#### Author:

- [BoolFalse](https://boolfalse.com/)
