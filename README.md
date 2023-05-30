# Xpath-syntax
Syntax for Xpath for automation using c#
xpath syntax	Reason	using by there
//tagname[@attribute='value']	Find an element using XPath	IWebElement element 
//*[@id='element_id']	Find an element by ID using XPath	IWebElement elementById
//*[@class='element_class']	Find an element by class name using XPath	IWebElement elementByClass
//*[text()='Element Text']	Find an element by text using XPath	IWebElement elementByText
//*[contains(text(),'Partial Text')]	Find an element by partial text using XPath	IWebElement elementByPartialText
//tagname[@attribute='value'])[index]	Find an element by index using XPath	IWebElement elementByIndex
//tagname[@attribute1='value1' and @attribute2='value2']	Find an element by multiple attributes using XPath	IWebElement elementByMultipleAttributes
//parent/tagname[@attribute='value']	Find an element by parent-child relationship using XPath	IWebElement elementByParentChild
//tagname[@attribute='value']/preceding-sibling::sibling_tagname	Find an element by preceding-sibling relationship using XPath	IWebElement elementByPrecedingSibling
//tagname[@attribute='value']/following-sibling::sibling_tagname	Find an element by following-sibling relationship using XPath	IWebElement elementByFollowingSibling
//tagname[@attribute='value']	Find multiple elements using XPath	IReadOnlyCollection<IWebElement> elements
![image](https://github.com/Mayuravetri1/Xpath-syntax/assets/132995954/36ff7de8-a30e-4340-82cb-a2710a327c69)
