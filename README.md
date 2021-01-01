PSR-4-совместимая версия Типографа Муравьева с поддержкой PHP 7.3 и выше
===============
Создан на основе кода [Типографа Муравьева](http://mdash.ru/)

### Установка

```sh
composer require qortex/mdash
```

### Использование

```php
$typograph = new \Emuravjev\Mdash\Typograph();
$typograph->set_text('Текст, "к которому" применить типограф.');

// типографируем
$result = $typograph->apply();

// выводим результат
echo $result;
```
