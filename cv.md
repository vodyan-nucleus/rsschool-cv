# My CV

### Contact Info:
**Yauheni Vadzianovich**
**Email:** vodyanovich01@icloud.com
**Discord:** VODYAN#4473

### Skills:
* Swift
* UIKit
* SQL
* Core Data
* Git

### Code examples:
```swift
func updateHistory () {
        for child in children {
            if let child = child as? UpdateLabelTextDelegate {
            child.updateLabelText(text: "\(history)")
            }
        }
 }
 
 protocol UpdateLabelTextDelegate {
   func updateLabelText(text: String)
 }
 
 extension ChildViewController: UpdateLabelTextDelegate {
     func updateLabelText(text: String) {
         self.text = text
         guard let labelHistory = labelHistory else { return }
         UIView.transition(with: labelHistory, duration: 0.25, options: .transitionCrossDissolve, animations: {
             labelHistory.text! = text
         }, completion: nil)
         labelHistory.adjustFontSizeToFit(minimumFontSize: 15, maximumFontSize: 30)
     }
 }
 ```
 
 ### Experience:
 
 I developed Realt Agency App using Core Data and Firebase. It was my coursework for university. Also I am developing Caclculator App with history and scintific functions now.
 
 ### Education:
 
 Belarusian State University of Informatics and Radioelectronics 
 Internetional House English Courses
 
 ### Language:
 * English (B1)
 * Polish (B1)
