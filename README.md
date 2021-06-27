<h1 align="center">Ourooom</h1>
<h4 align="center">Google Classroom Wannabe</h4>


![Ouroom](https://github.com/kurnyaannn/ouroom-project/blob/master/public/asset/ouroom.png?raw=true)
<h5 align="center">Illustration by Undraw</h5>

## Requirements
* PHP 7+
* NodeJS
* Composer
* Laravel

## Installation
* Edit .env file according to your needs
* Run :
```bash
$ composer update
$ php artisan classroom:setup
```

## Usage
* Creator Level (check UserSeeds for credentials)
  * Can access all feature available
* Administrator Level
  * Can access all feature except update role and notifying Creator
* Guru Level
  * Class feature
  * Assessment
* Siswa Level
  * Class feature

## Demo
Demo link: ( http://atm-classroom.herokuapp.com )
Username | Password
-------- | ---------
admin    | adminatm

*ps: In order to join a Class. The student needs to have same `Jurusan`, `Angkatan`, & `Class Token` with the chosen Class.
  
## Contributing
- Fork it ( https://github.com/kurnyaannn/ouroom-project/fork )
- Create your feature branch (`git checkout -b my-new-feature`)
- Commit your changes (`git commit -am 'Add some feature'`)
- Push to the branch (`git push origin my-new-feature`)
- Create a new Pull Request

## License
As you can see Ouroom is under MIT License

## About the Author
<a href="https://kurnyaannn.github.io">Yayang Kurnia</a>.
