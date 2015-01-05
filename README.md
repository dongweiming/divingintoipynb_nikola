divingintoipynb_nikola
======================

[WIP]a nikola blog that use ipython notebook format

Install sample
-----

    cd ~
    git clone https://github.com/getnikola/nikola
    git clone https://github.com/dongweiming/diving_into_ipynb
    cd nikola
    python setup.py install
    cd
    nikola init nikola_blog
    cd nikola_blog
    nikola install_theme zen-ipython
    nikola new_post -f ipynb -i ~/diving_into_ipynb/python_2/highchart.ipynb
    nikola new_post -f ipynb -i ~/diving_into_ipynb/python_2/nbconvert.ipynb
    # modify *.meta
    e posts/nbconvert.meta
    e posts/highchart.meta
    # modify end
    nikola build
    nikola serve
    nikola github_deploy
