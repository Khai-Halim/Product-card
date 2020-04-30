This is a template for product cards for an online store.

Learnings:
    CSS bug?:
    Adding a z-index to the btn caused the element to go behind the ::after element even though it had a higher index and position: relative. !important did not work either.
    The only solution found was to remove the z-index on the parent. 
    I decided to transition color instead of fading to an element behind.