Having an issue where steal isn’t looking inside the node_modules folder.
When I open test/test.html, I get this error:
```
Error: Error loading "steal-qunit" at http://localhost:3996/steal-qunit.js
Error loading "steal-qunit" from "test/test" at http://localhost:3996/test/test.js
```

### Solution:
_semver_ version in package.json wasn't correct.
