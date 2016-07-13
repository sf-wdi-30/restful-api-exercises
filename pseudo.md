What I need to get:

Pseudo Code

GET ALL ICE CREAM = "/icecream"

GET ICE CREAM BY FLAVORS = "/icecream/:flavors"

GET ALL ICE CREAM CATEGORIES = "/categories"

GET FRUITY = "/categories/:fruity"

GET GLUTEN FREE = "/categories/:glutenfree"

GET CHUNKY = "/categories/:chunky"

GET ALL CATEGORIES BY FLAVOR OF ICE CREAM = "/categories/:flavors/icecream"

GET FRUITY ICE CREAM FLAVOR = "/categories/:fruity/icecream/:flavors"

GET GLUTEN ICE CREAM FLAVOR = "/categories/:glutenfree/icecream/:flavors"

GET CHUNKY ICE CREAM FLAVOR = "/categories/:chunky/icecream/:flavors"

To add a new flavor:

POST NEW FLAVOR = "/api/flavors"

//"/api/icecream/:flavors" not sure if this is correct
