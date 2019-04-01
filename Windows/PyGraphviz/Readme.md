*Pygraphviz* *.whl*s
--------------------

[[Github]: pygraphviz/pygraphviz - Python interface to Graphviz graph drawing package https://pygraphviz.github.io](https://github.com/pygraphviz/pygraphviz):
- Sources dwnloaded from [[PyPI]: pygraphviz - pygraphviz-1.5.zip](https://files.pythonhosted.org/packages/7e/b1/d6d849ddaf6f11036f9980d433f383d4c13d1ebcfc3cd09bc845bda7e433/pygraphviz-1.5.zip)
- Patch (file present in current dir) applied on top
    - Note that it **doesn't fix** *graphviz.i*, **only** the *SWIG* wrapper generated from it (*graphviz\_wrap.cpp*)
- Using (*cdt*, *cgraph* from) [[Graphviz]: Graph Visualization Software](https://www.graphviz.org)
    - Sources downloaded from [[GitLab]: graphviz/graphviz - (master) Graph Visualization Tools](https://gitlab.com/graphviz/graphviz):

            [cfati@cfati-5510-0:/cygdrive/e/Work/Dev/Fati/WinBuild/graphviz/src/graphviz]> git show head
            commit 89292b5945933b1501293c04894ed9cf886241be (HEAD -> master, origin/master, origin/HEAD)
            Merge: 429d43615 97811bd35
            Author: Stephen C North <scnorth@gmail.com>
            Date:   Mon Feb 4 08:09:40 2019 -0500

                Merge branch 'wasbridge/graphviz-master' into HEAD

    - Built with *Visual Studio **2015** (Community Edition)*


More details about the build process can be found at [[SO]: Installing pygraphviz on Windows 10 64-bit, Python 3.6 (@CristiFati's answer)](https://stackoverflow.com/questions/45093811/installing-pygraphviz-on-windows-10-64-bit-python-3-6/54890705#54890705).

Currently, there are *.whl*s available for *Python* (*64bit* **and** *32bit*):
- *3.5*
- *3.6*
- *3.7*
