It's a demo for showing how to import package in go.

In main.go, we wanna import a func in test.go, then we need to import `[moduleName]/dir/dir2/dir3/.../[the folder contains the file you want to import]`. Then use `[packageName].[functionName]()` to invoke. Note that the exported function name must be initial with a capital letter.