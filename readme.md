# Faker Provider Animals

[![Monthly Downloads](https://poser.pugx.org/edwindayot/faker-provider-animals/d/monthly.png)](https://packagist.org/packages/edwindayot/faker-provider-animals) [![Build Status](https://travis-ci.org/EdwinDayot/Faker-Provider-Animals.svg?branch=master)](https://travis-ci.org/EdwinDayot/Faker-Provider-Animals)

Please use as described [here](https://github.com/fzaninotto/Faker#faker-internals-understanding-providers)

## Install

### Add repository to composer.json

```json
..
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/WedgeSama/Faker-Provider-Animals.git"
        }
    ],
...
```

### Require lib.
```shell
composer require --dev edwindayot/faker-provider-animals
```

## Use with Symfony

Create a new file at `config/services_dev.yaml` with the code bellow inside:

```yaml
services:
    _defaults:
        autowire: true
        autoconfigure: true

    FakerProviderAnimals\Animals: ~

```

## Functions availables

```
animal()     // 'Cat'
```
