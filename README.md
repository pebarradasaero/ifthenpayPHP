# ifthenpayPHP
[IfthenPay](https://ifthenpay.com/) Ifthenpay Classes for PHP.

## Install

```bash
$ composer require pebarradasaero/ifthenpay
```

## Usage

```php
use pebarradasaero\IfthenPay\Helpers\Multibanco;

class XPTO {
    public function process_payment() {
        $reference = Multibanco::generateReference( $ent_id, $subent_id, $order_id, $order_value );
    }
}
```

