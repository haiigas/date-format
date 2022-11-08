## Helper CodeIgniter 3

> Indonesian Date Format

How to use:
- Save the tanggal_helper.php file in the application/helpers folder.
- Call tanggal_helper.php in the autoload.php. Find the script and change it as below.<br>
```
$autoload['helper'] = array('tanggal');
```
- Now call the format_indo function in the helper into the view. as an example:<br>
```
<?php echo format_indo(date('Y-m-d H:i:s'));?>
```
Then the output is generated like this:
```
22 Agustus 2020 22:36:00
```
Full article can be <a href="https://www.teknowebapp.com/post/membuat-format-tanggal-indonesia-di-codeigniter.html">read here</a>.
