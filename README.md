This is a template for product cards for an online store.

Learnings:
    I transitioned the opacity of the button rather than the color to optimise performance.
    I found that there was unpredictable behaviour when transitioning the opacity of the button. The ::before element background color would interfere with the opacity transition. Changing to a different color fixed the problem but certain colors such as black, white or red would not work.