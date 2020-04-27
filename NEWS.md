# anomalize 0.2.0.9000

__Bug Fixes__

* Fix issue with sign error in GESD Method (Issue #46).

# anomalize 0.2.0

* `clean_anomalies()` - A new function to simplify cleaning anomalies by replacing with trend and seasonal components. This is useful in preparing data for forecasting. 

* `tidyr` v1.0.0 and `tibbletime` v0.1.3 compatability - Improvements to incorporate the upgraded `tidyr` package. 

# anomalize 0.1.1

* [Issue #2](https://github.com/business-science/anomalize/issues/2): Bugfixes for various `ggplot2` issues in `plot_anomalies()`. Solves "Error in FUN(X[[i]], ...) : object '.group' not found".
* [Issue #6](https://github.com/business-science/anomalize/issues/6): Bugfixes for invalid unary operator error in `plot_anomaly_decomposition()`. Solves "Error in -x : invalid argument to unary operator".


# anomalize 0.1.0

* Added a `NEWS.md` file to track changes to the package.