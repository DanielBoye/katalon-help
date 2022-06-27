# Common lines used in Katalon. 
---

To verify if some element is visible on the webpage. Commonly used to check if you are on the right page when you clicked a button 

`WebUI.verifyElementVisible()`

---

To interact or click on an element/button

`WebUI.click()`

---

To send keyboard inputs, used for adding in passwords or writing text into a search field

`WebUI.sendKeys()`

Remember to add a `, GlobalVariable.xxx` to add in your text from a variable. 

---

To check if you are on the right website with checking the title

`WebUI.verifyMatch(WebUI.getWindowTitle(), 'xxx', false)`

---

Often used together 

```
WebUI.verifyElementVisible()

WebUI.click()
```
