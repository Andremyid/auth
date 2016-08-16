# auth
The Andremyid Auth package.

## Installation

* Add the following to your `Composer JSON` file
```
"andremyid/auth": "~0.0"
```
* Run Composer
```
$ composer update
```
* Add the following to 'Andremyid/Framework-Core' => 'ServiceProvider'
```
Andremyid\Auth\AuthServiceProvider
```
* Run the migration

```
// first, optional
$ composer dump-autoload
// and then
$ php andre migrate
```
## Usage

### Extending
