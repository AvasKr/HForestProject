### getWarp [Warp|null]

```php
\skh6075\SmartWarp\SmartWarp::getInstance ()->getWarp (string $name);
```

### addWarp [void]

```php
\skh6075\SmartWarp\SmartWarp::getInstance ()->addWarp (string $name, Position $pos);
```

### deleteWarp [void]

```php
\skh6075\SmartWarp\SmartWarp::getInstance ()->deleteWarp (string $name);
```

### getWarpInFunctions

```php
$warp = SmartWarp::getInstance ()->getWarp (string $name);
```

### warp [void]

```php
$warp->warp (Player $player, bool $useOption = true);
```

### getOptions [array]

```php
$warp->getOptions ();
```

### hasOption [bool]

```php
$warp->hasOption (string $option);
```

### getOption [mixed]

```php
$warp->getOption ();
```

### setOption [void]

```php
$warp->setOption (string $option, array $value = []);
```
