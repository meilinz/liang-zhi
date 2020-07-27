# liang-zhi
Reference Game Experiment (Local in-lab version)

Open a terminal and navigate to the directory (e.g., listA)
```sh
$ cd ~/Experiments/liang-zhi/speaker/listA
```
Activate the python environment for the experiment to run locally
```sh
$ source activate picture-naming-local
```
Enter psiturk
```sh
$ psiturk
```
Turn on the psiturk server
```sh
$ server on
```
Generate a randomized link for a participant; need to do this for every participant
```sh
$ debug
```
Then, open the link using Chrome. It should open a tab automatically. 

**Remember to check if `localhost` is in the address bar of the Chrome Browser**

## Citation

If you use this experiment framework in your academic work, please cite the paper that this experiment was built on. 

Zhan, M., & Levy, R. (2019). Availability-Based Production Predicts Speakers’ Real-time Choices of Mandarin Classifiers. In Proceedings of the Annual Conference of the Cognitive Science Society (pp.1268-1274).

Link to the paper: https://cogsci.mindmodeling.org/2019/papers/0231/0231.pdf

BibTex

```
@inproceedings{zhan-levy:2019-availability,
  year = {2019},
  title = {Availability-Based Production Predicts Speakers’ Real-time Choices of Mandarin Classifiers},
  pages = {1268–1274},
  booktitle = {Proceedings of the 41st Annual Meeting of the Cognitive Science Society},
  author = {Zhan, Meilin and Levy, Roger P.}
}
```
