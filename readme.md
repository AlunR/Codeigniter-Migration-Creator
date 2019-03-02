# Bootstrap Migrations for Codeigniter v3

This CI library provides a simple way to bring datastructures into Codeigniter to get you started migrating a legacy project.

## Usage

In your Codeigniter app simply setup your database connection then:

```php
$this->load->libary('BootstrapMigrations');
$version = '001';
$this->BootstrapMigrations->create_migration($version);
```

And the library will output a file to the /application/migrations folder named "001_BootstrapMigrations.php" ready for use with the built-in Codeigniter migrations class (https://www.codeigniter.com/user_guide/libraries/migration.html).

## Contributing

If you find a bug or have a feature request  open up an issue and I'll see if I can help.