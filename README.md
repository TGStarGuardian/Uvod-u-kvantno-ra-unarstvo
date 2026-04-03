# Uvod-u-kvantno-računarstvo
Osnove kvantnog računarstva, zajedno sa primerima i implementacijama glavnih algoritama u Q# programskom jeziku.


# Instalacija

1. instalirajte pip3 i Python3, ako već nemate instalirano

2. napravite virtualno okruženje (virtual environment) - pratite uputstva na sledećem [linku](https://docs.python.org/3/library/venv.html)

3. u folderu u kom ste kreirali virtualno okruženje pokrenite:

source bin/activate

Sada se nalazite u virtualnom okruženju u kojem ćete instalirati pakete.

4. instalirajte Q# i JupyterLab

python -m pip install qsharp azure-quantum

python -m pip install ipykernel ipympl jupyterlab

pip3 install jupyter

5. da biste mogli kvizove da pokrećete, instalirajte jupyterquiz

pip3 install jupyterquiz


# Pokretanje

1. uđite u virtualno okruženje kao u koraku 3. u instalaciji.

2. u terminalu pokrenite

jupyter notebook

Dalje možete i sami.

# Adijabatsko računarstvo

Notebook-ovi u folderu `Adijabatsko računarstvo/` koriste D-Wave Ocean SDK biblioteke. Da biste ih pokrenuli, instalirajte sledeće pakete:

```
pip install dimod
pip install dwave-neal
pip install dwave-networkx
pip install matplotlib
pip install numpy
pip install scipy
pip install networkx
```

Ili sve odjednom:

```
pip install dimod dwave-neal dwave-networkx matplotlib numpy scipy networkx pyqubo
```

- **dimod** — definisanje QUBO/BQM modela i tačan rešavač (`ExactSolver`)
- **dwave-neal** — klasični simulovano žarenje (`SimulatedAnnealingSampler`)
- **dwave-networkx** — grafovski algoritmi za QUBO (nezavisni skup, maksimalni rez, vertex cover)
- **pyqubo** — simbolička formulacija QUBO/Izing problema, automatska kompilacija u BQM
- **matplotlib / numpy / scipy** — vizualizacija i numeričke simulacije
- **networkx** — kreiranje i manipulacija grafovima

> Napomena: za pokretanje na stvarnom D-Wave kvantnom hardveru potreban je nalog na [D-Wave Leap](https://cloud.dwavesys.com/leap/) platformi i instalacija `dwave-system` paketa.

# Slike

Slike kvantnih kola su preuzete sa [Wikipedia članka](https://en.wikipedia.org/wiki/Quantum_logic_gate). Slika kvantne Furijeove transformacije za n = 2 je moja, napravljena pomoću alata na sledećem [linku](https://algassert.com/quirk).
