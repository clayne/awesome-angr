# Awesome angr [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of resources/tools and analyses for the [angr](https://github.com/angr) binary analysis framework.
This page does not only collect links and external resources, but its meant to be an harbour to release any non-official extensions/tool/utils that can be useful when working with angr.

## ExplorationTechniques 📁

A collection of exploration techniques written by the community

* *SimgrViz*: an exploration technique that collects information regarding the states generated by the SimulationManager and creates a graph that can be later visualized to debug the analyses (.dot file). 

## Documentation :book:
* [docs.angr.op](https://docs.angr.io/) - Official angr general documentatoin website.
* [angr.io](http://angr.io/api-doc/angr.html) - Official angr API documentation.

## Projects :rocket:

List of academic/not-acadamic projects based on angr which code is open source.

* [Heaphopper](https://github.com/angr/heaphopper) - Apply symbolic execution to automatically verify security properties of most common heap libraries.
* [angr-cli](https://github.com/fmagin/angr-cli) - Command line interface for angr a la peda/GEF/pwndbg.
* [Syml](https://github.com/ucsb-seclab/syml) - Use ML to prioritize exploration of promising vulnerable paths.
* [Angrop](https://github.com/angr/angrop) - Generate ropchains using angr and symbolic execution.
* [Angr-management](https://github.com/angr/angr-management) - GUI for angr.
* [Mechaphish](https://github.com/mechaphish) - AEG system for CGC.
* [angr-static-analysis-for-vuzzer64](https://github.com/ash09/angr-static-analysis-for-vuzzer64) - angr-based static analysis module for Vuzzer.
* [FirmXRay-angr](https://github.com/ucsb-seclab/monolithic-firmware-collection/tree/master/utils/firmxray) - An angr version of the base address detection analysis implemented in [FirmXRay](https://github.com/OSUSecLab/FirmXRay).

## Blogposts :newspaper:
* [angr-blog](https://angr.io/) - Official angr blog.
* [A reaching definition engine for binary analysis built-in in angr.](https://degrigis.github.io/posts/angr_rd/) - A walk-through of the ReachingDefinition analysis built-in in angr.
* [shellphish-phrack](http://phrack.org/papers/cyber_grand_shellphish.html) - Phrack article on [Mechaphish](https://github.com/mechaphish), the AEG system based on angr that got 3rd place at the CGC.

## Papers :page_with_curl:

Here a collection of papers which used or whose project is based on the angr framework.

| Year       | Paper     | 
| :------------- | :----------: | 
| 2021 | [SoK: All You Ever Wanted to Know About x86/x64 Binary Disassembly But Were Afraid to Ask](https://www.portokalidis.net/files/sok86disas_oakland21.pdf)
| 2021 | [SyML: Guiding Symbolic Execution Toward Vulnerable States Through Pattern Learning](https://conand.me/publications/ruaro-syml-2021.pdf)
| 2021 | [DIANE: Identifying Fuzzing Triggers in Apps to Generate Under-constrained Inputs for IoT Devices](https://conand.me/publications/redini-diane-2021.pdf)
| 2021 | [Boosting symbolic execution via constraint solving time prediction (experience paper)](https://dl.acm.org/doi/10.1145/3460319.3464813)
| 2020 | [Symbion: Interleaving Symbolic with Concrete Execution](https://sites.cs.ucsb.edu/~vigna/publications/2020_CNS_Symbion.pdf) |
| 2020 | [KARONTE: Detecting Insecure Multi-binary Interactions in Embedded Firmware](https://www.badnack.it/static/papers/University/karonte.pdf) | 
| 2020 | [Device-agnostic Firmware Execution is Possible: A Concolic Execution Approach for Peripheral Emulation](https://dl.acm.org/doi/10.1145/3427228.3427280) |
| 2020 | [KOOBE: Towards Facilitating Exploit Generation of Kernel Out-Of-Bounds Write Vulnerabilities](https://www.usenix.org/system/files/sec20summer_chen-weiteng_prepub.pdf)
| 2019 | [BinTrimmer: Towards Static Binary Debloating Through Abstract Interpretation](https://sites.cs.ucsb.edu/~chris/research/doc/dimva19_bintrimmer.pdf)
| 2019 | [Sleak: Automating Address Space Layout Derandomization](https://par.nsf.gov/servlets/purl/10155109)
| 2018 | [HeapHopper: Bringing Bounded Model Checking to Heap Implementation Security](https://sites.cs.ucsb.edu/~chris/research/doc/usenix18_heaphopper.pdf)
| 2017 | [Your Exploit is Mine: Automatic Shellcode Transplant for Remote Exploits](https://www.ieee-security.org/TC/SP2017/papers/579.pdf)
| 2017 | [BOOMERANG: Exploiting the Semantic Gap in Trusted Execution Environments](https://sites.cs.ucsb.edu/~vigna/publications/2017_NDSS_Boomerang.pdf)
| 2017 | [Ramblr: Making Reassembly Great Again](https://sefcom.asu.edu/publications/ramblr-making-reassembly-great-again-ndss2017.pdf)
| 2017 | [BootStomp: On the Security of Bootloaders in Mobile Devices](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-redini.pdf) |
| 2017 | [Piston: Uncooperative Remote Runtime Patching](https://sefcom.asu.edu/publications/piston-uncooperative-remote-runtime-patching-acsac2017.pdf)
| 2016 | [SoK: (State of) The Art of War: Offensive Techniques in Binary Analysis](https://sites.cs.ucsb.edu/~vigna/publications/2016_SP_angrSoK.pdf)
| 2016 | [Driller: Augmenting Fuzzing Through Selective Symbolic Execution](https://sites.cs.ucsb.edu/~chris/research/doc/ndss16_driller.pdf)
| 2015 | [Firmalice - Automatic Detection of Authentication Bypass Vulnerabilities in Binary Firmware](https://sites.cs.ucsb.edu/~chris/research/doc/ndss15_firmalice.pdf) |



