# RefreshRecyclerView
## fork by "https://github.com/llxdaxia/RecyclerView"

### 做了几个更新
1、关闭log日志显示，增加了adapter的onItemClickListener

2、修改了footer显示，改为 "没有更多了"

### 添加依赖
```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

```
    dependencies {
    	        compile 'com.github.adzcsx2:RecyclerView:c072d015f6'
    	}
```

<img src="screenshot/RecyclerAdapter.png" width="270" height="480"/>
<img src="screenshot/MultiTypeAdapter.png" width="270" height="480"/>
