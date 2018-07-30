# 0.3.0

* Prevent errors from being raised if they match a filter

# 0.2.1 [June 23, 2018]

* Added `filter_levels` option for filtering by log level (closes #4)
* Fixed Travis CI build

# 0.2.0 [Feb 17, 2018]

* Stop using threads, it's a fool's errand. We now output logs at the end of each test
* Update colors
* Drop dependencies on net-http-persistent + selenium-webdriver

# 0.1.2 [Feb 16, 2018]

* Use a new instance with each spec example to avoid issues with code reloading

# 0.1.1 [Feb 16, 2018]

* Added better multi-line formatting for "\n" literals

# 0.1.0 [Feb 16, 2018]

* First release!
