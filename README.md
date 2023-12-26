# reactphp-framwork-single

## install

```
composer require reactphp-framwork/single -vvv
```

## usage

```
<?php

class ProcessManager 
{
    use \Reactphp\Framework\Single\Single;
}

ProcessManager::instance()->foo();

ProcessManager::instance('custome_key')->foo();

```

## License

MIT