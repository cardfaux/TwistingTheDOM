## Attributes

`const range = document.querySelector('input[type="range"]')`
`range.getAttribute('max)`
_will give u the max value for the range input element_
`range.getAttribute('type')`
_will give you range_

_This is how we get the attributes_
_We can also Set The Attributes_

`range.setAttribute('min', '-500')`
_This will change the value of the min value to -500_

`range.setAttribute('type', 'radio')`
_This will change it from a range to a radio button_

# Finding Parent/Children/Siblings

`const firstLi = document.querySelector('li')`
`console.dir(firstLi)`
_will have a node (property) called parentElement that is the ul_
`li.parentElement`
_will give us that ul_
`li.parentElement.parentElement`
_Will give us the body_
_HTMLelement has no parent element_

`const ul = document.querySelector('ul')`
`ul.children`

_will give us back an array like structure of the li children_

`ul.children[0]`

_will give us the first li_

`ul.children[0].innerText`

_will give us the innerText of it_
