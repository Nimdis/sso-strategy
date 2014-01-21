Opauth-SSO
=============
[Opauth](https://github.com/opauth/opauth) strategy for [sso.tusur.ru](http://sso.tusur.ru/) authentication.

Getting started
----------------
1. Install SSO-strategy:
   ```bash
   cd path_to_opauth/Strategy
   git clone https://github.com/Nimdis/sso-strategy.git SSO
   ```

2. Configure SSO-strategy with at least `Client ID` and `Client Secret`.

3. Direct user to `http://path_to_opauth/sso` to authenticate

Strategy configuration
----------------------

Required parameters:

```php
<?php
    'SSO' => array(
      'client_id' => 'your_client_id',
      'client_secret' => 'your_client_secret'
    )
)
```

License
---------
SSO-strategy is MIT Licensed  
Copyright © 2014 OpenTeam (https://github.com/openteam), Sergei Toroshchin (https://github.com/Nimdis)

