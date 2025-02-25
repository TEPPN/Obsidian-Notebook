#programming

---
# What is PHP?

PHP (Hypertext Preprocessor) is a widely-used open-source scripting language primarily used for web development. It is executed on the server, allowing developers to create dynamic content and interact with databases.

# Why Use PHP?

- Open-source and free
- Cross-platform compatibility (Windows, Linux, macOS)
- Integrates well with [[HTML]] and databases like [[MySQL]]
- Supports [[Object-Oriented Programming]] (OOP)
- Large community and extensive documentation

# Setting Up PHP Environment

To run PHP, you need a local development environment. Some popular choices include:

- **XAMPP** (Windows, macOS, Linux) – Includes Apache, MySQL, PHP, and phpMyAdmin
- **MAMP** (macOS, Windows) – Provides Apache, MySQL, and PHP
- **WAMP** (Windows) – Windows alternative to XAMPP
- **LAMP** (Linux) – Linux-based alternative

# Installing  XAMPP (Recommended for Beginners)

1. Download XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).
2. Install and start the Apache and MySQL modules.
3. Place your PHP files inside the `htdocs` folder (XAMPP installation directory).
4. Open your browser and go to `http://localhost/yourfile.php` to execute PHP scripts.

# PHP Syntax and Basics

## **Basic Syntax**

A PHP script starts with `<?php` and ends with `?>`.

```php
<?php
  echo "Hello, World!";
?>
```

## **PHP Tags**

- `<?php ... ?>` – Standard PHP tag (recommended)
- `<?= ... ?>` – Short tag for echoing content (must be enabled in `php.ini`)

## **Comments in PHP**

Comments help in documenting code and are ignored during execution.

```php
// This is a single-line comment
# Another single-line comment
/* This is a
   multi-line comment */
```

## **Variables and Data Types**

PHP variables start with `$` and are dynamically typed.

```php
$name = "John"; // String
$age = 25;       // Integer
$price = 10.5;   // Float
$isAdmin = true; // Boolean
```

## **Echo vs Print**

Both `echo` and `print` output text to the browser.

```php
echo "Hello World";
print "Hello World";
```

# PHP Operators and Control Structures

## **Arithmetic Operators**

```php
$x = 10;
$y = 5;
echo $x + $y; // Addition
```

## **Conditional Statements**

```php
$age = 18;
if ($age >= 18) {
  echo "You are an adult.";
} else {
  echo "You are a minor.";
}
```

## **Loops in PHP**

### **For Loop**

```php
for ($i = 1; $i <= 5; $i++) {
  echo "Number: $i";
}
```

### **While Loop**

```php
$x = 1;
while ($x <= 5) {
  echo "Number: $x";
  $x++;
}
```

# Chapter 4: Functions and Arrays

## **Defining Functions**

```php
function greet($name) {
  return "Hello, $name!";
}
echo greet("Alice");
```

## **Arrays in PHP**

```php
$fruits = array("Apple", "Banana", "Cherry");
echo $fruits[0]; // Apple
```
