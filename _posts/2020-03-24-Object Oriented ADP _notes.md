# Object Oriented - Analysis, Design, Programming

Source :
https://www.linkedin.com/learning/programming-foundations-object-oriented-design-3/inheritance?u=76811570

## Objects

1. Basically Objects have
   - Identity
   - Attributes
   - Behaviors

    Note : Attributes are also sometime called as
    Fields, States, Properties, Characteristics, Variables etc depending on the domain one is in, say in biology it makes sense for an animal object attributes called as characteristics to states or variables.

    Similarly, Behaviors are called as Methods, Functions etc.

- **Identity** makes
  - One object different from its own object.
    - eg: say, one mug can be full, other can be empty, they both come under object mug. But each have their own characteristics.

  - One object different from other types of object.
    - eg: say, a mug object is completely different from a person object.

- **Attributes**
  - Are characteristics an object will commonly have.
    - eg: say, A mug may have common states like filled, empty, half etc. representing the current status of mug capacity.
- **An Object or Behavior ?**
  - Ask yourself, In future - Do you need multiple instances of this set of behaviors. if yes try object oriented approach else other approaches. 
  - To figure out if something is an object or behavior, A simple test might be to figure out if its a name ? in sense make 'the test'.

    It makes sense to say

        the Person, 
        the Mug
        etc

    Its doesn't makes sense to say

        the ringing,
        the climbing
        etc 

    ringing, climbing are verbs and they are **behaviors** while person, mug are nouns they are **objects**



<!-- #### Visual Gist -->

![Visual Gist]({{ site.url }}/assets/images/posts/Object_Oriented_ADP_notes/Objects_classes_visual_gist.png)

## Classes
