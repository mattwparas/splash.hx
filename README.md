# splash.hx

Splash screen for helix, using Steel.

## Installation

```shell
forge pkg install --git https://github.com/mattwparas/splash.hx.git
````

## Usage

```scheme
(require "splash-hx/splash.scm")

;; Add this to your init.scm
(when (equal? (command-line) '("hx"))
  (show-splash))
```
