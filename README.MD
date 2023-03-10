
# FlyCore_Alioth_Docker

An android `kernel` for XiaoMi `Alioth` devices with native `docker` feature.



### Usage:
Prepare your `prebuilts`

then edit the `build.sh` (for arm64 platform is `build.aarch.sh`).

```
./build.sh
```

or
```
./build.aarch.sh
```

Finally, `adb sideload xxx.zip` for flash kernel and enjoy it!

[Docker on Android](https://gist.github.com/tomxi1997/f1f8692342e57272d7aa8a1e9829c978)

### Prebuilts:
#### For X86：
aarch64-linux-android-4.9:
```
https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-4.9/+/refs/heads/android-arm64-deadpool-4.9-android13-tv
```

clang-r445002:
```
https://gitlab.com/Alioth-Project/clang-r445002
```

arm-linux-androideabi-4.9:
```
https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/+/refs/heads/master
```


#### For arm64：
```
https://github.com/llvm/llvm-project/releases/tag/llvmorg-14.0.6
```




# Linux kernel


There are several guides for kernel developers and users. These guides can
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.  The formatted documentation can also be read online at:

    https://www.kernel.org/doc/html/latest/

There are various text files in the Documentation/ subdirectory,
several of them using the Restructured Text markup notation.
See Documentation/00-INDEX for a list of what is contained in each file.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.
