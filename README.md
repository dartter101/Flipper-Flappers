# Flipper-Flappers:    *Find Your Flipper*[https://www.kaggle.com/competitions/happy-whale-and-dolphin](Link Goes Here)
The problem to be solved is the identification of dolphins' individuals using their identifying marks on their back and fins, much like how fingerprint comparisons use the loops, whorls, and arches of a fingerprint. The process will compare identifying marks between several different photos to determine if the dolphin in the photo is one that has already been recorded or a new previously unidentified dolphin.Dolphins are important in determining the health of the ocean by serving as bioindicators for us. By identifying the individual dolphins we can gain information about the state and status of the ocean climates, as well as help preserve their species, and better understand how to maintain the oceans of our world. Readings we will need to examine will be articles and documents on distinguishing Identifier marks for dolphins so that we have a better idea of how to help the program “look” for important information. Additional readings will be on CART and to help determine how to best utilize its properties to obtain our goal of identifying individuals. Further readings will be on classification itself so we understand the best ways to utilize its characteristics of classification to construct a model capable of identifying if the dolphin was a previously existing one. Most data is provided by our kaggle project we selected, a series of pictures to train our program on as well as pictures to test with. Additional data will be information we look up on identifying factors, beyond simply scars, spots and shape of fins. The learning style we will be using is Classification and regression trees (CART), the goal is to feed the function with the input data (x), where x is the image of a dolphin, and output data (y), where y is id of the dolphin in that image and if the dolphin does not yet have an id a new temporary id is assigned. so when we have new data, we can predict the value of one or more outcomes and draw conclusions from it. We will be attempting to classify distinct features of dolphins such as spots and scars. Our output will be a dictionary with keys being the dolphin identification number and the values being an array containing the images related to that dolphin, where unmatched images will be given a new identification using classification.
