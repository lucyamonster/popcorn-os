# caramel interpreter notes

- strawberry caramel
    parser / lexer
    https://craftinginterpreters.com/a-map-of-the-territory.html#scanning
- blueberry caramel
    intermediate
    https://craftinginterpreters.com/a-map-of-the-territory.html#intermediate-representations
- raspberry and blackberry caramel
    runs the code on the honey kernel or on another os


I would like to have straberry and blueberry be in a crate that is loaded into raspberry or blackberry.
So that that code isn't duplicated and only the execute step has to be written twice.

I think that an import can just be handled as running the imported 