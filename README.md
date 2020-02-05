## Install

```bash
$ npm install --save gatsby-plugin-snowplow-tracker
# or
$ yarn add gatsby-plugin-snowplow-tracker
```

## Usage
```javascript
{
  resolve: "gatsby-plugin-snowplow-tracker",
  options: {
    snippetHost: "//d1fc8wv8zag5ca.cloudfront.net",
    snippetVersion: "2.10.2",
    namespace: "myCollector",
    collectorUri: "collector-url.example.com",
    config: {
      appId: "myAppId"
    }
  }
}
```
