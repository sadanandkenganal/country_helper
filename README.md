# country_helper
Its a CodeIgniter helper library. It helps you get all the countries.

#There are three useful components on this page:

1. Get all the coutrnies.
  ```
  $country_arr = getCountryByCode(NULL);
  ```
2. Get country name by its CODE.
  ```
  $country_name = getCountryByCode('IN');
  ```
3. Get country details like Countryname, City and Country Code(By IP Address).
  ```
  $country_details_arr = getCountryNameByIp();
  ```
