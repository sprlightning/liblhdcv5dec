# liblhdcv5dec
liblhdcv5dec for ESP-IDF.

具备完整的源文件和头文件，均移植于[AOSP](https://github.com/sprlightning/liblhdc-collections/tree/main/AOSP)，使用LHDCV5协商后，可听到正弦波生成的标准音；其中lhdcv5_util_dec.c仅具备模拟解码的能力，仅供参考，用真正的LHDCV5解码算法替换其中的正弦波（模拟解码）部分可实现完整的LHDCV5音频Sink。

更多关于LHDC的内容详见[liblhdc-collections](https://github.com/sprlightning/liblhdc-collections)，本仓库的使用详见[ESP-IDF/bluedroid](https://github.com/sprlightning/liblhdc-collections/tree/main/ESP-IDF/bluedroid)。

## 本仓库目录说明
	```c
	│  CMakeLists.txt
	│  LICENSE
	│  README.md
	│  release_note
	│
	├─inc
	│      lhdcv5BT_dec.h
	│
	├─include
	│      lhdcv5_util_dec.h
	│
	└─src
			lhdcv5BT_dec.c
			lhdcv5_util_dec.
	```
