## Laravel Starter

### Getting Started With Local Development

#### Setup And Start
```bash
$ cd docker
# and
$ docker-compose up
# or 
$ docker-compose up -d
```

#### Seed Initial Data
```bash
$ docker-compose exec app php artisan migrate --seed
```

#### Usage
* visit [http://localhost:8080](http://localhost:8080)
* login with email: `admin@paper.com` and password `secret`

### Documentation
* [Laravel documentation](https://laravel.com/docs)
* [Admin Dashboard](https://paper-dashboard-laravel.creative-tim.com/docs/getting-started/laravel-setup.html)

## License
The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
