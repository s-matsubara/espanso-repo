A simple package to enable espanso to use Badge created during pr-review.  
It works by replacing keywords like `:must` with ![must-badge](https://img.shields.io/badge/review-must-critical.svg).  
More details below.

### Installation

Install the package with:

```
espanso install review-badge --git https://github.com/s-matsubara/espanso-repo --external
```

### Usage

| Keyword  | Emoji                                                                |
|----------|----------------------------------------------------------------------|
| `:must`  | ![must-badge](https://img.shields.io/badge/review-must-critical.svg) |
| `:want`  | ![want-badge](https://img.shields.io/badge/review-want-blue)         |
| `:nits`  | ![nits-badge](https://img.shields.io/badge/review-nits-orange.svg)   |
| `:typo`  | ![typo-badge](https://img.shields.io/badge/review-typo-orange.svg)   |
| `:ask`   | ![ask-badge](https://img.shields.io/badge/review-ask-yellow.svg)     |
| `:imo`   | ![imo-badge](https://img.shields.io/badge/review-imo-green.svg)      |
| `:next`  | ![next-badge](https://img.shields.io/badge/review-next-skyblue.svg)  |
| `:good`  | ![good-badge](https://img.shields.io/badge/review-good-success.svg)  |
| `:memo`  | ![memo-badge](https://img.shields.io/badge/review-memo-lightgrey)    |
