# CORS Fix Proxy

Welcome to the CORS Fix Proxy! This tool helps you bypass Cross-Origin Resource Sharing (CORS) restrictions by acting as a proxy. Here's how you can use it:


## Deploy on vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Kshitij033/uncorsa)


## Usage Example

To use the CORS Fix Proxy, you simply need to prefix the URL you want to access with the proxy URL.

```js
fetch("https://[your-instance].vercel.app/?url=https://[target-url].com/anything")
```
In this example, https://[your-instance].vercel.app/ is the proxy URL, and https://[target-url].com/anything is the target URL you want to access.