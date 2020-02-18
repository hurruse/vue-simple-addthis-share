# Simple AddThis share component for vue


[![release version](https://img.shields.io/github/v/release/hinex/vue-simple-addthis-share.svg)](https://github.com/hinex/vue-simple-addthis-share/releases) [![npm version](https://badge.fury.io/js/vue-simple-addthis-share.svg)](https://badge.fury.io/js/vue-simple-addthis-share) [![](https://data.jsdelivr.com/v1/package/npm/vue-simple-addthis-share/badge?style=rounded)](https://www.jsdelivr.com/package/npm/vue-simple-addthis-share) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/hinex/vue-simple-addthis-share/blob/master/LICENSE) [![dependences](https://david-dm.org/hinex/vue-simple-addthis-share.svg)](https://david-dm.org/hinex/vue-simple-addthis-share) [![devDependences](https://david-dm.org/hinex/vue-simple-addthis-share/dev-status.svg)](https://david-dm.org/hinex/vue-simple-addthis-share?type=dev)

Solves the problem with navigating through pages and URLs. Without extra shit. Just install and use.

### Install

```bash
npm install vue-simple-addthis-share --save
```

### Usage

```html
<script>
  import AddThis from 'vue-simple-addthis-share'
    
  export default {
    name: "AwesomeComponent",
    components: {
      AddThis,
    }
  }
</script>
```

#### Template area:

```html
<template>
  <AddThis publicId="ra-somehash" />
</template>
```

#### Custom props

You can pass AddThis attributes like a pros for title, media etc ([AddThis props documentation](https://www.addthis.com/academy/setting-the-url-title-to-share/)).

```html
<template>
  <AddThis 
    publicId="ra-somehash" 
    data-url="THE URL"
    data-title="THE TITLE"
    data-description="THE DESCRIPTION"
    data-media="THE IMAGE"
  />
</template>
```
