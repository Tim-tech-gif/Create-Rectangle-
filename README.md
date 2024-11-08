# Create-Rectangle-
struct Rectangle {     x: i32,     y: i32,     width: i32,     height: i32, }  impl Rectangle {     fn area(&amp;self) -> i32 {         self.width * self.height     }      // Функція для знаходження площі перекриття     fn intersection_area(&amp;self, other: &amp;Rectangle) -> i32 {         
