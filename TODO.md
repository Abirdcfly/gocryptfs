* More robust daemonization, add cli parameter "--sendusr1=pid"
* Add "-q" (quiet) flag
* Add test filesystem for "--masterkey" containing an "It works!" file
* Add fcntl file locking to make multiple concurrent mounts safe
 * add test case
* Add "--pwfile" parameter that reads the password from a file
 * Use that for additional test cases