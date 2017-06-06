# ToolUtils
一些常见的工具类

#如果添加该开源库

Gradle:
Step 1. 添加JitPack仓库

在当前项目的根目录下的 build.gradle 文件中添加如下内容:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}Copy
Step 2. 添加项目依赖

	dependencies {
	        compile 'com.github.zsj1225:ToolUtils:v1.0.1'
	}
