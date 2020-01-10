* **child_process**: doc deprecate ChildProcess.\_channel (cjihrig) [#26982](https://github.com/nodejs/node/pull/26982)
* **deps**: update nghttp2 to 1.37.0 (gengjiawen) [#26990](https://github.com/nodejs/node/pull/26990)
* **dns**:
  * make dns.promises enumerable (cjihrig) [#26592](https://github.com/nodejs/node/pull/26592)
  * remove dns.promises experimental warning (cjihrig) [#26592](https://github.com/nodejs/node/pull/26592)
* console:
    * make console.table() use colored inspect (TSUYUSATO Kitsune) #20510
    * The console.timeLog() method has been implemented. #21312
    * console.countReset() will emit a warning if the timer being
	reset does not exist. #21649
