# country_helper
Its a CodeIgniter helper library. It helps you get all country list.

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
  
  # Usage
  
  1. Download country_helper.php file and add it in application/helper/ folder.
  2. Load the helper file autoload.php or in a particular controller.(Your wish)
   ```
   $this->load->helper('country'); // Don't add helper and .php extension.
   ```
  3. Call the above methods to get country information.
