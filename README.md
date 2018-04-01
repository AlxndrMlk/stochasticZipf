# Zipf's distribution from stochastic process

A Python 3 replication of Zipf's Law slope generated using stochastic process based on Suzuki et al., 2005.

  **Zipf's Law** states that *"given some corpus of natural language utterances, the frequency of any word is inversely proportional to its rank in the frequency table"* (https://en.wikipedia.org/wiki/Zipf%27s_law)
  
  The law is named after American linguist and philologist who studied statistical occurrences in different languages **George Kingsley Zipf**. Zipf *"theorised that the distribution of word use was due to tendency to communicate efficiently with least effort"* (https://en.wikipedia.org/wiki/Principle_of_least_effort). 
  
  It's also worth noting that the most efficient structure for communication is the one where *"the shortest sequences are the most frequent, and the longest sequences occur with the least frequency"* (McCowan et al., 2005)

## Some history

<img src="https://secure.vetmed.ucdavis.edu/public/utilities/getbase64Image.cfm?mivid=14652" width=100px/>
Brenda McCowan

<br>


  **Zipf's Law** became famous when **Brenda McCowan** (McCowan et al., 1999) and her team applied it to study bottlenose **dolphin communication** and to compare it to humans.
  
### Dolphins and extraterrestrial intelligence

 From then on a debate started if and how **Zipf's Law** can be useful in context of discovering underlying structure of unknown communication systems. The law has been used not only to study **dolphins** but also in search for **extraterrestrial intelligence** (https://www.seti.org/seti-institute/animal-communication-information-theory-and-seti)

<br>
<img src="http://www.industrytap.com/wp-content/uploads/2016/10/seti-e1476134762199.jpg" width=500px/>
<br>

### The debate continues

Some authors propose that *"Zipf's law is required by symbolic systems"* or even that it is *"a hallmark of symbolic reference and not a meaningless feature"* (Cancho & Solé, 2003). Others argue that *"even a simple stochastic mechanism, such as a die-rolling trial, satisfies Zipf's law"* (Suzuki et al., 2005).

This notebook replicates the procedure (Die-rolling example) form Suzuki et al. (2005).

Although a stochastic process can produce **Zipf's slope** (Suzuki et al., 2005), McCowan et al. (2005) propose that **Zipf's Law** can be useful in differential context:

*"McCowan et al. (1999, 2002) agree that the Zipf slope is linguistically shallow. Zipf statistic is linguistically shallow because it tells us nothing about the relationship between signals in a repertoire (e.g. the higher-order entropies). But this fact has no bearing on its utility as a comparative tool at the repertoire (i.e. first-order approximation to the entropy) level"* (McCowan et al., 2005)

What if we apply Zipf's slope to study typical vs **atypical language acquisition** in human children? Would it help us learn something new?


## References

* Cancho, R. F. i., & Sole, R. V. (2003). Least effort and the origins of scaling in human language. Proceedings of the National Academy of Sciences, 100(3), 788–791. https://doi.org/10.1073/pnas.0335980100

* Li, W. (1992). Random Texts Exhibit Zipfs-Law-Like Word Frequency Distribution. IEEE Transactions on Information Theory, 38(6), 1842–1845. https://doi.org/10.1109/18.165464

* McCowan, B., Doyle, L. R., Jenkins, J. M., & Hanser, S. F. (2005). The appropriate use of Zipf’s law in animal communication studies. Animal Behaviour, 69(1), F1–F7. https://doi.org/10.1016/j.anbehav.2004.09.002

* McCowan, B., Hanser, S. F., & Doyle, L. R. (1999). Quantitative tools for comparing animal communication systems: Information theory applied to bottlenose dolphin whistle repertoires. Animal Behaviour, 57(2), 409–419. https://doi.org/10.1006/anbe.1998.1000

* Suzuki, R., Buck, J. R., & Tyack, P. L. (2005). The use of Zipf’s law in animal communication analysis. Animal Behaviour, 69(1), F9–F17. https://doi.org/10.1016/j.anbehav.2004.08.004

* Zipf, G. K. (1949). Human Behavior and the Principle of Least Effort. Addisson-Wesley Press, Cambridge, 6(3), 573.





