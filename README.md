<h3>SdkBonusApi - sdk-class for loyalty_api_v106 from funidst.org</h3>

<b>1.Installation.</b>

1.1. composer.json file:

{<br>
    "require": {<br>
        "php":">=5.3.0",<br>
        "bonusapi/sdkapi": "dev-master"<br>
    },<br>
    "prefer-stable": true,<br>
    "minimum-stability": "dev"<br>
}

1.2. composer install

<b>2.Basic usage.</b>

require_once 'vendor/autoload.php';

use SdkBonusApi\SdkBonusApi;

$bonusapi = new SdkBonusApi();

$arr['numberapi'] = '1'; 
$arr['postparamstring'] = 'TID=777/IDUser=55'; 

$bonusapi->requestApi($arr);
