## Laravel Starter

### Getting Started With Local Development

#### Preliminary
* copy the file `.env.example` to `env`
```bash
$ composer install
```

#### Setup And Start Docker
```bash
$ cd docker
$ docker-compose up -d
```

#### Generate Random Key For environment
```bash
$ docker-compose exec app php artisan key:generate
```

#### Seed Initial Data
```bash
$ docker-compose exec app php artisan migrate --seed
```

#### Usage
* visit [http://localhost:8080](http://localhost:8080)
* login with email: `admin@paper.com` and password `secret`

#### Stop Docker
```bash
$ docker-compose stop
```

### Documentation
* [Laravel documentation](https://laravel.com/docs)
* [Admin Dashboard](https://paper-dashboard-laravel.creative-tim.com/docs/getting-started/laravel-setup.html)

## License
The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
