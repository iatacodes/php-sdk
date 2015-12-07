# php-sdk
PHP-SDK for IataCodes.org

Example:
```
include 'IataCodes.php';
$ic = new IataCodes();
$result = $ic->api('stats');
print_r( $result['response']);
```
