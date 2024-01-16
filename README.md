
# HDEV SMS GATEWAY FOR UGANDA TELCO

### HDEV SMS. MIT license.

Use from a PHP script:


# INitiate sms
```php
include 'sms_parse.php';

//SEND SMS

hdev_sms_ug::api_id("Your Api ID");
hdev_sms_ug::api_key("Your Api Key");
$msg = hdev_sms_ug::send("SENDER ID","TELL","MESSAGE");

var_dump($msg);//to get sms server response
```


*All of our response are objects for example to access the status in response you use
```php
	$status = $result->status;
```
