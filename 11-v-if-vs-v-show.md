If we have to NOT show a lot of elements on page load. If we used v-if, it will not create the elements. So it will result in fast page load
Eg. 1000s of panel are hidden on page load and user clicks on one to reveal its body
If we have to show every panel open on load - anyway Vue needs to create all the panel-body nodes.