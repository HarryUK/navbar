## php-nav

### Installation:
1. Put `navbar.php` into the folder where you plan to include it.
2. Add `<link rel="stylesheet" href="https://cdn.harry.ml/php-nav/v1/php-nav-css.css">` to the head tag.
3. After the body tag of your PHP document add: 
```php
    <?php
        include "navbar.php";
    ?>
   ```
4. Congrats! You have installed `php-nav`
---

### How to use`php-nav`:
1. Set a header:
```php
    // Navbar Header
    $navH1 = "Header";
```
2. Set the amount of links you want to `true` (I want 3 for this example), So I would do:
```php
    $navbarLink1 = true;
    $navbarLink2 = true;
    $navbarLink3 = true;
    $navbarLink4 = false;
```
3. Set the text and location for your active navbar links: 
```php
    // Link 1
    $navbarLink1href = "https://example.com/1";
    $navbarLink1text = "Example 1";

    // Link 2
    $navbarLink2href = "https://example.com/2";
    $navbarLink2text = "Example 2";

    // Link 3
    $navbarLink3href = "https://example.com/3";
    $navbarLink3text = "Example 3";
```
4. Now once you've done that put anything else you want on your page in a `div` container with the class `php-nav-container`, in example:
```html
    <div class="php-nav-container">
        <h1>PHP Navbar</h1>
        <p>An example of PHP Navbar</p>
    </div>
```
 5.That's it :smiley:, enjoy your fully responsive and fast navbar.
 
![Navbar Example](img/example.png)
view this example live at: https://php-nav.harry.ml

---
**Important Information**
Version: `0.1`
Status: `Stable`
