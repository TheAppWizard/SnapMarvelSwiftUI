# SnapMarvelSwiftUI
This project can be used for implementation of Movie Application  with help of SwiftUI



## ScrollView Concept
```
ScrollView(.horizontal) {
    HStack(spacing: 20) {
        ForEach(0..<10) {
            Text("Item \($0)")
                .foregroundColor(.white)
                .font(.largeTitle)
                .frame(width: 200, height: 200)
                .background(Color.red)
        }
    }
}
```
