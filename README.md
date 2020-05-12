## fangx/hyperf-cookie

> Enhanced cookie function in hyperf

## install

```bash
composer require fangx/hyperf-cookie
```

## usage

```php
<?php
namespace App\Services;

use Hyperf\Di\Annotation\Inject;

class Demo
{
  /**
   * @Inject
   * @var \Fangx\Cookie\Contracts\QueueingFactory
   */
  protected $cookie;
  
  public function demo()
  {
    //
  }
}
```
