# Govini_Entity_Match
Tech Assesment

Thank you for this opportunity. I first tried to create an algorithm from scratch using an idea that mapped each char a-z 0-1 in the selected features to a dictionary that would hold the frequency of those characters. then I would run the Euclidean distance of that frequency sequence to all those in that the same block. Returning the matching record with the smallest distance. However, this method was unsuccessful in both speed and accuracy. Then I researched existing packages in python and found “recordlinkage” package. This package uses the blocks created and determines the set of possible pairs, then uses the jarowinkler distance to return matches within a certain threshold. 

