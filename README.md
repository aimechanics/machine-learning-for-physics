## Machine Learning for Physics

```text


%%%%%%%%%%=*++++++    -%%%%%%%%%%*----:         +%%%%%%=+-:                                                          ::::::+%%%%%%%%%%%%%%%%%%%+     
%%%%%%%%%%%=*+++++++++%%%%%%%%%%%*--------:     +%%%%%%=+---                                  .**=%%%%%%%%%      ::::::::::+%%%%%%%%%%%%%%%%%%%%%%   
%%%%%%%%%%%=*++++++++*%%%%%%%%%%%*--------:     +%%%%%%=+---                                .***=%%%%%%%%%%     :::::::::::+%%%%%%%%%%%%%%%%%%%%%%%% 
%%%%%%%%%%%%**+++++++%%%%%%%%%%%%*--------:     +%%%%%%=+---                               +**=%%%%%%%%%%%%     :::::::::::+%%%%%%%         +%%%%%%%*
%%%%%%+%%%%%=*++++++*%%%%%.%%%%%%*--------:     +%%%%%%=+---                              ***=%%%%%=+%%%%%%     :::::::::::+%%%%%%%......::...%%%%%%%
%%%%%%+*%%%%%**+++++%%%%%+.%%%%%%*--------:     +%%%%%%=+---                             ***=%%%%%::+%%%%%%     :::::::::::+%%%%%%%::::::::::-%%%%%%%
%%%%%%++%%%%%%*+++++%%%%% .%%%%%%*--------:     +%%%%%%=+---                           -***=%%%%%:::=%%%%%%     :::::::::::+%%%%%%%*******====%%%%%%%
%%%%%%++*%%%%%**+++%%%%%+:.%%%%%%*--------:     +%%%%%%=+---                          ***=%%%%%%::::=%%%%%%     :::::::::::+%%%%%%%@@@@@@@%%%%%%%%%% 
%%%%%%++-%%%%%%*++*%%%%%:..%%%%%%*--------:     +%%%%%%=+---                         ***=%%%%%=:::::=%%%%%%     :::::::::::+%%%%%%%%%%%%%%%%%%%%%%%  
%%%%%%=+-+%%%%%*++%%%%%=: .%%%%%%*--------:     +%%%%%%=+---                        ***=%%%%%::::::-=%%%%%%     :::::::::::+%%%%%%%%%%%%%%%%%%%%%*   
%%%%%%=+--%%%%%=+*%%%%%:. .%%%%%%*--------:     +%%%%%%=+---                        ::+%%%%%%%%%%%%%=%%%%%%%%%* :::::::::::+%%%%%%%%%%%%%%%==-       
%%%%%%=---*%%%%%*%%%%%=:. *%%%%%%*--------:     +%%%%%%=+---                        ::+%%%%%%%%%%%%%%%%%%%%%%%* :::::::::::+%%%%%%%                  
%%%%%%=----%%%%%%%%%%%-.  *%%%%%%*--------:     +%%%%%%=+-%%%%%%%%%%%%%%%           ::+%%%%%%%%%%%%%%%%%%%%%%%* :::::::::::+%%%%%%%                  
%%%%%%=-+--*%%%%%%%%%=:.  *%%%%%%*--------:     +%%%%%%%%%%%%%%%%%%%%%%=-                     ::::::%%%%%%%     :::::::::::+%%%%%%%                  
%%%%%%=-+---%%%%%%%%%+.   *%%%%%%*--------:     +%%%%%%%%%%%%%%%%%%%%%%=-                     ::::::%%%%%%%     :::::::::::+%%%%%%%                  
%%%%%%=++---*%%%%%%%%-.   =%%%%%%*-------       +%%%%%%%%%%%%%%%%%%%%%%=-                      :::::%%%%%%%       .::::::::+%%%%%%%                  
------+++--: --------:.   +------+--:           -------------------------                         ::-------             :::+-------
 
 Machine    Learning     for    Physics

```

**M2 MSIAM — Université Grenoble Alpes**
**Academic year 2026/2027**


### Teaching team

- Vincent Acary
- Michael Arbel
- Filippo Masi
- Henri Leroy

### Course format

- 3 ECTS, 18 hours
- Lectures and hands-on sessions

### Scope

The course focuses on:

- physics-informed learning;
- operator learning;
- structured models and differentiable solvers;
- comparison with classical numerical methods.

A recurring question throughout the course is how machine learning can complement numerical methods for modelling and solving physical problems.

### Prerequisites

Required background:

- probability and statistics at Master 1 level.

Useful background:

- linear algebra and multivariable calculus;
- numerical methods and optimization;
- ordinary and partial differential equations;
- Python programming and basic machine learning.

### Repository structure

```text
machine-learning-for-physics/
├── README.md
├── requirements.txt
├── slides/
├── hands-on/
└── project/
```

- `slides/`: lecture slides.
- `hands-on/`: notebooks, scripts, and supporting files for practical sessions.
- `project/`: project statements.
- `requirements.txt`: common Python dependencies used in the hands-on sessions.

### Slides

| # | Topic | Material |
|---:|---|---|
| 01 | Introduction | [PDF](slides/01_Introduction.pdf) |
| 02 | Neural networks, optimization, and automatic differentiation | [PDF](slides/02_Neural-networks_optim_autodiff.pdf) |

### Python environment

A minimal environment can be created with

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
