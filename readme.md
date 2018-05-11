# ppm.phar

This project provides PPM ([php-pm](https://github.com/php-pm/php-pm)) as a single bundled .phar file.

### Install

```
wget https://raw.githubusercontent.com/hernandev/ppm.phar/1.0.2/dist/ppm.phar
chmod +x ppm.phar
```

### Usage

The `ppm.phar` file is just a wrapper for PPM, meaning you can use `ppm.phar` exactally the same way you
would on a direct PPM install.

Example:

```
./ppm.phar start --boostrap=laravel --port=6789
```
