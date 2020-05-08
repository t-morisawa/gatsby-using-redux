# gatsby-using-redux
Gatsby製サイトの中でReduxアプリケーションを動作させるサンプル

 - https://github.com/gatsbyjs/gatsby/tree/master/examples/using-redux
 - https://t-morisawa.github.io/gatsby-using-redux/public/

# 元のREADME

## Redux

https://using-redux.gatsbyjs.org/

Gatsby example site that shows use of redux.

## Overview

To use redux in a Gatsby site you'll need to hook in to two of Gatsby's
extension points.

Once in `wrapRootElement` which runs during Gatsby's server rendering process,
and once in `wrapRootElement` which is part of Gatsby's browser APIs.

Check out [`./gatsby-ssr.js`](./gatsby-ssr.js) and
[`./gatsby-browser.js`](./gatsby-browser.js) to see how this is implemented in
this example.
