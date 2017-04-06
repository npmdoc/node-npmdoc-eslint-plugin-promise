# api documentation for  [eslint-plugin-promise (v3.5.0)](https://github.com/xjamundx/eslint-plugin-promise#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-eslint-plugin-promise.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eslint-plugin-promise) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eslint-plugin-promise.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eslint-plugin-promise)
#### Enforce best practices for JavaScript promises

[![NPM](https://nodei.co/npm/eslint-plugin-promise.png?downloads=true)](https://www.npmjs.com/package/eslint-plugin-promise)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-promise/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-eslint-plugin-promise_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-promise/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eslint-plugin-promise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eslint-plugin-promise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "jden",
        "email": "jason@denizac.org"
    },
    "bugs": {
        "url": "https://github.com/xjamundx/eslint-plugin-promise/issues"
    },
    "dependencies": {},
    "description": "Enforce best practices for JavaScript promises",
    "devDependencies": {
        "eslint": "^3.0",
        "mocha": "^2.3.4",
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "78fbb6ffe047201627569e85a6c5373af2a68fca",
        "tarball": "https://registry.npmjs.org/eslint-plugin-promise/-/eslint-plugin-promise-3.5.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "cf01cd13145a450e568885e8c5182fff501a4700",
    "homepage": "https://github.com/xjamundx/eslint-plugin-promise#readme",
    "keywords": [
        "eslint",
        "eslintplugin",
        "eslint-plugin",
        "promise",
        "promises"
    ],
    "license": "ISC",
    "maintainers": [
        {
            "name": "xjamundx",
            "email": "jamund@gmail.com"
        }
    ],
    "name": "eslint-plugin-promise",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/xjamundx/eslint-plugin-promise.git"
    },
    "scripts": {
        "pretest": "standard",
        "test": "mocha test"
    },
    "version": "3.5.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eslint-plugin-promise](#apidoc.module.eslint-plugin-promise)
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.</span>configs
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.</span>rules
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.</span>rules.always-return
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.</span>rules.catch-or-return
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.</span>rules.no-native
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.</span>rules.no-return-wrap
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.</span>rules.param-names
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.</span>rulesConfig

#### [module eslint-plugin-promise.rules](#apidoc.module.eslint-plugin-promise.rules)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>avoid-new (context)](#apidoc.element.eslint-plugin-promise.rules.avoid-new)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>no-callback-in-promise (context)](#apidoc.element.eslint-plugin-promise.rules.no-callback-in-promise)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>no-nesting (context)](#apidoc.element.eslint-plugin-promise.rules.no-nesting)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>no-promise-in-callback (context)](#apidoc.element.eslint-plugin-promise.rules.no-promise-in-callback)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>prefer-await-to-callbacks (context)](#apidoc.element.eslint-plugin-promise.rules.prefer-await-to-callbacks)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>prefer-await-to-then (context)](#apidoc.element.eslint-plugin-promise.rules.prefer-await-to-then)
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>always-return
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>catch-or-return
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>no-native
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>no-return-wrap
1.  object <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>param-names

#### [module eslint-plugin-promise.rules.always-return](#apidoc.module.eslint-plugin-promise.rules.always-return)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.always-return.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.always-return.create)

#### [module eslint-plugin-promise.rules.catch-or-return](#apidoc.module.eslint-plugin-promise.rules.catch-or-return)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.catch-or-return.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.catch-or-return.create)

#### [module eslint-plugin-promise.rules.no-native](#apidoc.module.eslint-plugin-promise.rules.no-native)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.no-native.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.no-native.create)

#### [module eslint-plugin-promise.rules.no-return-wrap](#apidoc.module.eslint-plugin-promise.rules.no-return-wrap)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.no-return-wrap.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.no-return-wrap.create)

#### [module eslint-plugin-promise.rules.param-names](#apidoc.module.eslint-plugin-promise.rules.param-names)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.param-names.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.param-names.create)



# <a name="apidoc.module.eslint-plugin-promise"></a>[module eslint-plugin-promise](#apidoc.module.eslint-plugin-promise)



# <a name="apidoc.module.eslint-plugin-promise.rules"></a>[module eslint-plugin-promise.rules](#apidoc.module.eslint-plugin-promise.rules)

#### <a name="apidoc.element.eslint-plugin-promise.rules.avoid-new"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>avoid-new (context)](#apidoc.element.eslint-plugin-promise.rules.avoid-new)
- description and source-code
```javascript
avoid-new = function (context) {
  return {
    NewExpression: function (node) {
      if (node.callee.name === 'Promise') {
        context.report(node, 'Avoid creating new promises.')
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-promise.rules.no-callback-in-promise"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>no-callback-in-promise (context)](#apidoc.element.eslint-plugin-promise.rules.no-callback-in-promise)
- description and source-code
```javascript
no-callback-in-promise = function (context) {
  return {
    CallExpression: function (node) {
      if (!isCallback(node)) {
        // in general we send you packing if you're not a callback
        // but we also need to watch out for whatever.then(cb)
        if (hasPromiseCallback(node)) {
          var name = node.arguments && node.arguments[0] && node.arguments[0].name
          if (name === 'callback' || name === 'cb' || name === 'next' || name === 'done') {
            context.report(node.arguments[0], 'Avoid calling back inside of a promise.')
          }
        }
        return
      }
      if (context.getAncestors().some(isInsidePromise)) {
        context.report(node, 'Avoid calling back inside of a promise.')
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-promise.rules.no-nesting"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>no-nesting (context)](#apidoc.element.eslint-plugin-promise.rules.no-nesting)
- description and source-code
```javascript
no-nesting = function (context) {
  return {
    CallExpression: function (node) {
      if (!hasPromiseCallback(node)) return
      if (context.getAncestors().some(isInsidePromise)) {
        context.report(node, 'Avoid nesting promises.')
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-promise.rules.no-promise-in-callback"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>no-promise-in-callback (context)](#apidoc.element.eslint-plugin-promise.rules.no-promise-in-callback)
- description and source-code
```javascript
no-promise-in-callback = function (context) {
  return {
    CallExpression: function (node) {
      if (!isPromise(node)) return

      // if i'm returning the promise, it's probably not really a callback
      // function, and I should be okay....
      if (node.parent.type === 'ReturnStatement') return

      // what about if the parent is an ArrowFunctionExpression
      // would that imply an implicit return?

      if (context.getAncestors().some(isInsideCallback)) {
        context.report(node.callee, 'Avoid using promises inside of callbacks.')
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-promise.rules.prefer-await-to-callbacks"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>prefer-await-to-callbacks (context)](#apidoc.element.eslint-plugin-promise.rules.prefer-await-to-callbacks)
- description and source-code
```javascript
prefer-await-to-callbacks = function (context) {
  function checkLastParamsForCallback (node) {
    var len = node.params.length - 1
    var lastParam = node.params[len]
    if (lastParam && (lastParam.name === 'callback' || lastParam.name === 'cb')) {
      context.report(lastParam, errorMessage)
    }
  }
  function isInsideYieldOrAwait () {
    return context.getAncestors().some(function (parent) {
      return parent.type === 'AwaitExpression' || parent.type === 'YieldExpression'
    })
  }
  return {
    CallExpression: function (node) {
      // callbacks aren't allowed
      if (node.callee.name === 'cb' || node.callee.name === 'callback') {
        context.report(node, errorMessage)
        return
      }

      // thennables aren't allowed either
      var args = node.arguments
      var num = args.length - 1
      var arg = num > -1 && node.arguments && node.arguments[num]
      if (arg && arg.type === 'FunctionExpression' || arg.type === 'ArrowFunctionExpression') {
        if (arg.params && arg.params[0] && arg.params[0].name === 'err') {
          if (!isInsideYieldOrAwait()) {
            context.report(arg, errorMessage)
          }
        }
      }
    },
    FunctionDeclaration: checkLastParamsForCallback,
    FunctionExpression: checkLastParamsForCallback,
    ArrowFunctionExpression: checkLastParamsForCallback
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-promise.rules.prefer-await-to-then"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.</span>prefer-await-to-then (context)](#apidoc.element.eslint-plugin-promise.rules.prefer-await-to-then)
- description and source-code
```javascript
prefer-await-to-then = function (context) {
  return {
    MemberExpression: function (node) {
      // you can then() if you are inside of a yield or await
      if (context.getAncestors().some(function (parent) {
        return parent.type === 'AwaitExpression' || parent.type === 'YieldExpression'
      })) {
        return
      }

      // if you're a then expression then you're probably a promise
      if (node.property && node.property.name === 'then') {
        context.report(node.property, 'Prefer await to then().')
      }
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-promise.rules.always-return"></a>[module eslint-plugin-promise.rules.always-return](#apidoc.module.eslint-plugin-promise.rules.always-return)

#### <a name="apidoc.element.eslint-plugin-promise.rules.always-return.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.always-return.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.always-return.create)
- description and source-code
```javascript
create = function (context) {
  // funcInfoStack is a stack representing the stack of currently executing
  //   functions
  // funcInfoStack[i].branchIDStack is a stack representing the currently
  //   executing branches ("codePathSegment"s) within the given function
  // funcInfoStack[i].branchInfoMap is an object representing information
  //   about all branches within the given function
  // funcInfoStack[i].branchInfoMap[j].good is a boolean representing whether
  //   the given branch explictly 'return's or 'throw's. It starts as 'false'
  //   for every branch and is updated to 'true' if a 'return' or 'throw'
  //   statement is found
  // funcInfoStack[i].branchInfoMap[j].loc is a eslint SourceLocation object
  //   for the given branch
  // example:
  //   funcInfoStack = [ { branchIDStack: [ 's1_1' ],
  //       branchInfoMap:
  //        { s1_1:
  //           { good: false,
  //             loc: <loc> } } },
  //     { branchIDStack: ['s2_1', 's2_4'],
  //       branchInfoMap:
  //        { s2_1:
  //           { good: false,
  //             loc: <loc> },
  //          s2_2:
  //           { good: true,
  //             loc: <loc> },
  //          s2_4:
  //           { good: false,
  //             loc: <loc> } } } ]
  var funcInfoStack = []

  function markCurrentBranchAsGood () {
    var funcInfo = peek(funcInfoStack)
    var currentBranchID = peek(funcInfo.branchIDStack)
    if (funcInfo.branchInfoMap[currentBranchID]) {
      funcInfo.branchInfoMap[currentBranchID].good = true
    }
    // else unreachable code
  }

  return {
    ReturnStatement: markCurrentBranchAsGood,
    ThrowStatement: markCurrentBranchAsGood,

    onCodePathSegmentStart: function (segment, node) {
      var funcInfo = peek(funcInfoStack)
      funcInfo.branchIDStack.push(segment.id)
      funcInfo.branchInfoMap[segment.id] = {good: false, node: node}
    },

    onCodePathSegmentEnd: function (segment, node) {
      var funcInfo = peek(funcInfoStack)
      funcInfo.branchIDStack.pop()
    },

    onCodePathStart: function (path, node) {
      funcInfoStack.push({
        branchIDStack: [],
        branchInfoMap: {}
      })
    },

    onCodePathEnd: function (path, node) {
      var funcInfo = funcInfoStack.pop()

      if (!isInlineThenFunctionExpression(node)) {
        return
      }

      path.finalSegments.forEach((segment) => {
        var id = segment.id
        var branch = funcInfo.branchInfoMap[id]
        if (!branch.good) {
          if (hasParentReturnStatement(branch.node)) {
            return
          }

          // check shortcircuit syntax like 'x && x()' and 'y || x()''
          var prevSegments = segment.prevSegments
          for (var ii = prevSegments.length - 1; ii >= 0; --ii) {
            var prevSegment = prevSegments[ii]
            if (funcInfo.branchInfoMap[prevSegment.id].good) return
          }

          context.report({
            message: 'Each then() should return a value or throw',
            node: branch.node
          })
        }
      })
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-promise.rules.catch-or-return"></a>[module eslint-plugin-promise.rules.catch-or-return](#apidoc.module.eslint-plugin-promise.rules.catch-or-return)

#### <a name="apidoc.element.eslint-plugin-promise.rules.catch-or-return.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.catch-or-return.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.catch-or-return.create)
- description and source-code
```javascript
create = function (context) {
  var options = context.options[0] || {}
  var allowThen = options.allowThen
  var terminationMethod = options.terminationMethod || 'catch'

  if (typeof terminationMethod === 'string') {
    terminationMethod = [terminationMethod]
  }

  return {
    ExpressionStatement: function (node) {
      if (!isPromise(node.expression)) {
        return
      }

      // somePromise.then(a, b)
      if (allowThen &&
        node.expression.type === 'CallExpression' &&
        node.expression.callee.type === 'MemberExpression' &&
        node.expression.callee.property.name === 'then' &&
        node.expression.arguments.length === 2
      ) {
        return
      }

      // somePromise.catch()
      if (node.expression.type === 'CallExpression' &&
        node.expression.callee.type === 'MemberExpression' &&
        terminationMethod.indexOf(node.expression.callee.property.name) !== -1
      ) {
        return
      }
      context.report(node, 'Expected ' + terminationMethod + '() or return')
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-promise.rules.no-native"></a>[module eslint-plugin-promise.rules.no-native](#apidoc.module.eslint-plugin-promise.rules.no-native)

#### <a name="apidoc.element.eslint-plugin-promise.rules.no-native.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.no-native.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.no-native.create)
- description and source-code
```javascript
create = function (context) {
  var MESSAGE = '"function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.no-native.</span>create" is not defined.'

<span class="apidocCodeCommentSpan">  /**
   * Checks for and reports reassigned constants
   *
   * @param {Scope} scope - an escope Scope object
   * @returns {void}
   * @private
   */
</span>  return {
    'Program:exit': function () {
      var scope = context.getScope()

      scope.implicit.left.forEach(function (ref) {
        if (ref.identifier.name !== 'Promise') {
          return
        }

        if (!isDeclared(scope, ref)) {
          context.report(ref.identifier, MESSAGE, { name: ref.identifier.name })
        }
      })
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-promise.rules.no-return-wrap"></a>[module eslint-plugin-promise.rules.no-return-wrap](#apidoc.module.eslint-plugin-promise.rules.no-return-wrap)

#### <a name="apidoc.element.eslint-plugin-promise.rules.no-return-wrap.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.no-return-wrap.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.no-return-wrap.create)
- description and source-code
```javascript
create = function (context) {
  return {
    ReturnStatement: function (node) {
      if (isInPromise(context)) {
        if (node.argument) {
          if (node.argument.type === 'CallExpression') {
            if (node.argument.callee.type === 'MemberExpression') {
              if (node.argument.callee.object.name === 'Promise') {
                if (node.argument.callee.property.name === 'resolve') {
                  context.report(node, resolveMessage)
                } else if (node.argument.callee.property.name === 'reject') {
                  context.report(node, rejectMessage)
                }
              }
            }
          }
        }
      }
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-promise.rules.param-names"></a>[module eslint-plugin-promise.rules.param-names](#apidoc.module.eslint-plugin-promise.rules.param-names)

#### <a name="apidoc.element.eslint-plugin-promise.rules.param-names.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-promise.rules.param-names.</span>create (context)](#apidoc.element.eslint-plugin-promise.rules.param-names.create)
- description and source-code
```javascript
create = function (context) {
  return {
    NewExpression: function (node) {
      if (node.callee.name === 'Promise' && node.arguments.length === 1) {
        var params = node.arguments[0].params

        if (!params || !params.length) { return }

        if (params[0].name !== 'resolve') {
          return context.report(node, 'Promise constructor parameters must be named resolve, reject')
        }

        if (params[1] && params[1].name !== 'reject') {
          return context.report(node, 'Promise constructor parameters must be named resolve, reject')
        }
      }
    }
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
