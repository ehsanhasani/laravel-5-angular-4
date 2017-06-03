# laravel 5.4 with angular 4 start project

## Installation:

```
composer install
npm install
```
Create `.env` file (can be based on `.env.example`
```
php artisan key:generate
```

## Building

```
npm run dev
```

## Watching

```
npm run watch
```

## Server

```
php artisan serve
```

## To include component template to the component use following code:
```ts
'template': require('./app.component.html'),
```


## To include component style to the component use following code:
```ts
'styles': [`${require('./app.component.scss')}`]
```
