# journal
#### Journal about new things learned

## 9/7
### Visual studio code
- find none ASCII char
    - [^\u0000-\u007F]
- debug
    - launch.json
```json
{
    "version": "0.2.0",
    "configurations": [
        {
            "type": "node",
            "request": "launch",
            "name": "Launch via NPM",
            "runtimeExecutable": "npm",
            "runtimeArgs": [
                "run-script",
                "redux"
            ],
            "port": 9229
        }
    ]
}
```
- debug
    - npm
```json
{
    "redux": "babel-node --inspect-brk=9229 test-redux.js --presets es2015,stage-2"
}
```

