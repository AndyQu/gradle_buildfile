# gradle_buildfile
1. 只包含一个文件:build.gralde。只包含了一个生成wrapper的task。
2. 使用方通过git拿到这个文件后，可以先生成wrapper，然后通过执行某个task，来下载相应的gradle distribution。
3. 目前，我在一个docker中使用这个文件预生成gradle distribution，以构建所需的image。
