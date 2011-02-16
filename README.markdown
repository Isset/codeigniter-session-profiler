# CodeIgniter-Session-Profiler

 * Adds session data to the profiler in CodeIgniter 2.0
 * Adds a table row for each item of session data with the key and value
 * Shows both CI session data and custom session data

Note: I did not write the original implementation, I just adapted it
for CodeIgniter >= 2.0 . You can find the implementation for CodeIgniter < 2.0 [here][http://codeigniter.com/forums/viewthread/60066/]

## Requirements

* Codeigniter (Reactor) >= 2.0

### Installation

Drop the libraries/MY_Profiler.php file into your application/libraries folder. 
If you did not change the MY_ prefix, it should autoload. If you did change the MY_ prefix
you'll have to rename both the file and the class to reflect this change.

## License

This library is licensed under the MIT license, a copy of this license can be found in
the file "LICENSE".

## Contact

Bug reports can be submitted to the bugtracker provided by GitHub. If you happen to have
any questions or just want to say hi feel free to send an Email to github@isset.nl.
