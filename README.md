## Threejs PrePare
![initial](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbDR0cV%2FbtranzNbwBZ%2FdKNPm9XCwdYPkIf9plOm90%2Fimg.png)

### Npm Version Update
```bash
 npm install -g npm@8.8.0
```

### Project setup Threejs Module Download
```bash
npm install --save three
```

### Project setup Threejs Module Local Download
```bash
https://github.com/mrdoob/three.js/archive/master.zip
```

### Threejs CDN Latest Version Check
```bash
https://cdn.skypack.dev/three
```

### Use CDN
```bash
//head tag in HTML//
<script async src="https://unpkg.com/es-module-shims@1.3.6/dist/es-module-shims.js"></script>
<script type="importmap">
  {
    "imports": {
      "three": "https://unpkg.com/three@<version>/build/three.module.js"
    }
  }
</script>

//start SCRIPT src//
<script src="" type="module">
  import * as THREE from 'three';
</script>
```