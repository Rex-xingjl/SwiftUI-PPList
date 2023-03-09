# SwiftUI-PPList

可在iOS13+版本使用的带刷新功能的List（已在百万用户的项目中使用）

Available in iOS13+, refreshable List （using in a million-user APP）

# How to use

block style

```swift

PPList(isRefreshing: $viewModel.model.isRefershing) {
    contentBody // any
} refreshAction: { completion in
    refreshFunction(completion)
}

```

async style

```swift

PPList(isRefreshing: $manager.model.isRefershing) {
   content
} asyncRefreshAction: {
    await asyncRefreshFuction()
}

```

# Sight
![screenRecord](https://user-images.githubusercontent.com/18180671/223914779-6fd4e144-e519-443c-ad39-2f3ab7bdae8f.gif)

https://user-images.githubusercontent.com/18180671/223914857-adbf01a4-2f40-4fe7-bde6-9f0b18959b8d.mov



