# tandem-tutorial-samples

### Executive summary

The site https://rw-community.org/ contains the tutorials on testing and debugging a typical redwood application (chosen to be [Redwood tutorial app](https://github.com/redwoodjs/redwood-tutorial#redwood-tutorial-app)). The files that need testing and debugging are in various other than main) branches of [tandem tutorial samples](https://github.com/adriatic/tandem-tutorial-samples) site.

---

This repository contains the clone of the [Redwood Tutorial App](https://github.com/redwoodjs/redwood-tutorial) `Redwood blog` as the final state of that app **after the first four chapters** (before the [Intermission chapter](https://redwoodjs.com/docs/tutorial/intermission)) (note the work `clone` rathen than `fork`, to avoid any unneeded interactions).

This (tandem-tutorial-samples) collection "lives" in **main** branch of [this repository](https://github.com/adriatic/tandem-tutorial-samples). It is the only non-modified version of the tutorial which is used to verify the correct functioning of the coomplete development environment.

In order to getting this application up and running, the following commands need to be executed first:
```
git clone https://github.com/adriatic/tandem-tutorial-samples
cd tandem-tutorial-samples
yarn install
yarn rw prisma migrate dev
yarn rw dev
```

All other branches (expect a lot of them) have at least one artificially created bug, needed for the readers / app developers) to practice testing and debuggin. The README.md in branches other than main explains the details of the testing and debugging needed in that branch of that tutorial chapter.

<p align="center">
<img width="400" alt="image" src="https://user-images.githubusercontent.com/2712405/165872785-5332e5d8-8b43-4f35-b18f-42a7f42ae7c5.png"/>
<br/>
<b>Testing and debugging section of tandem app</b>
</p>
<br/>

The README in each branch other than this (which is in the main branch) will document the testing and debugging strategy as well as the solution (how the bug in this version of the tutorial is found and fixed).

---


