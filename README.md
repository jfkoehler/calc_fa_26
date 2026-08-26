# LMTH 2040 — Calculus: A Multidisciplinary Approach

**Eugene Lang College of Liberal Arts, The New School**  
**Fall 2026**  
Mondays & Wednesdays, 12:00–1:40 PM

> **Integration → Differentiation → Differential Equations → Higher Dimensions & PDEs**

This repository contains materials for **LMTH 2040: Calculus — A Multidisciplinary Approach**, a liberal-arts calculus course at Eugene Lang College.

The course approaches calculus as both a mathematical practice and a historical and cultural object. Rather than treating calculus as a fixed collection of techniques, we investigate how mathematical ideas emerge from problems involving **measurement, motion, infinity, accumulation, prediction, optimization, representation, and change**.

The Fall 2026 course places these ideas in conversation with the **history and sociology of science, art and visual culture, computation, mathematical modeling, and artificial intelligence**.

Students work simultaneously with mathematical problems, historical primary sources, Jupyter notebooks, data, images, models, and readings in the humanities and social sciences.

---

## Course Architecture

The semester follows a broadly historical progression through four mathematical units, each containing two modules.

### Unit I — Integration

**Module 1 — Measurement, Exhaustion & Infinity**

- area and quadrature
- Archimedes
- exhaustion and approximation
- geometric series
- Cavalieri and indivisibles
- infinity and the continuum
- Riemann sums
- computational approximation

**Module 2 — Integration, Probability & Data**

- definite integrals
- accumulation functions
- the Fundamental Theorem of Calculus
- probability densities
- expectation
- Lorenz curves and the Gini coefficient
- quantification and social measurement

---

### Unit II — Differentiation

**Module 3 — Motion, Tangency & the Derivative**

- secant and tangent problems
- instantaneous change
- Leibniz and differential notation
- numerical and graphical differentiation
- derivative rules
- composition and the chain rule
- motion studies and scientific images

**Module 4 — Optimization, Networks & Learning**

- extrema
- optimization
- objective functions
- Newton's method
- regression
- loss functions
- perceptrons
- gradient-based learning
- backpropagation

---

### Unit III — Differential Equations

**Module 5 — Dynamics, Prediction & Simulation**

- rates and differential equations
- slope fields
- Euler's method
- numerical simulation
- growth and population models
- nonlinear dynamics
- assumptions and model validation

**Module 6 — Feedback, Control & Intelligence**

- equilibrium
- stability
- feedback
- dynamical systems
- cybernetics
- control
- historical models of machine intelligence

---

### Unit IV — Higher Dimensions & PDEs

**Module 7 — Surfaces, Fields & Partial Differential Equations**

- functions of several variables
- surfaces
- partial derivatives
- directional change
- gradients
- vector fields
- vibrating strings
- wave and diffusion equations

**Module 8 — Images, Representation & Generative AI**

- images as numerical objects
- high-dimensional spaces
- vectors and embeddings
- machine vision
- classification
- diffusion
- generative models
- mathematical and cultural representations of AI

---

## Why Begin with Integration?

Most contemporary calculus courses begin with limits and derivatives.

This course begins instead with problems of **measurement and accumulation**.

The choice is partly historical. Problems involving areas, volumes, exhaustion, and infinite processes long predate the systematic differential calculus of Newton and Leibniz.

It is also pedagogical.

Following Otto Toeplitz's idea of a **genetic approach**, we ask students to encounter mathematical concepts through some of the problems and practices from which they developed rather than beginning exclusively with their later formal organization.

The course is not intended to reproduce history chronologically. Historical development instead provides a way of asking why mathematical concepts were invented, what problems they solved, and what alternative forms they might have taken.

---

## Mathematics + History + Culture

Historical and cultural material is not treated as an appendix to the mathematics.

Students encounter primary mathematical and scientific sources alongside work in the history and sociology of science, philosophy, art, and cultural studies.

Recurring authors and sources include:

- Archimedes
- Bonaventura Cavalieri
- Isaac Barrow
- Gottfried Wilhelm Leibniz
- Otto Toeplitz
- Michel Serres
- Gilles Deleuze & Félix Guattari
- Theodore Porter
- Lorraine Daston & Peter Galison
- Eadweard Muybridge
- Étienne-Jules Marey
- Frank Rosenblatt
- David Rumelhart, Geoffrey Hinton & Ronald Williams
- Naomi Oreskes, Kristin Shrader-Frechette & Kenneth Belitz
- Norbert Wiener
- Andrew Pickering
- d'Alembert, Euler & Bernoulli
- Gaspard Monge
- Geoffrey Bowker & Susan Leigh Star
- Trevor Paglen
- Kate Crawford

Historical primary sources are drawn in part from Dirk J. Struik's
*A Source Book in Mathematics, 1200–1800*, with David Eugene Smith's
*A Source Book in Mathematics* serving as an additional resource.

---

## Reading as Mathematical Practice

Readings are organized around three recurring questions:

### READ

What is the author actually claiming, constructing, or trying to accomplish?

### CONNECT

What happens when we place the text beside the mathematics, computation, model, dataset, or image we are studying?

### QUESTION

Where should we challenge, test, complicate, or refuse the author's account?

Students are not expected simply to accept theoretical interpretations of mathematics. A reading by Serres or Deleuze and Guattari, for example, becomes something that mathematical practice itself can help us evaluate.

See [`readings.tex`](readings.tex) for the working reader.

---

## Computation

Computation is integrated throughout the course using **Python and Jupyter notebooks**.

Students use computation to experiment with mathematical ideas rather than merely automate calculations.

Representative notebook investigations include:

```text
polygonal approximation and exhaustion
        ↓
Riemann sums and numerical integration
        ↓
probability distributions
        ↓
Lorenz curves and Gini coefficients
        ↓
motion and numerical differentiation
        ↓
optimization landscapes
        ↓
perceptrons
        ↓
backpropagation
        ↓
Euler's method
        ↓
dynamical systems and feedback
        ↓
surfaces and gradients
        ↓
numerical PDEs
        ↓
images, embeddings and diffusion
```

One goal of the Fall 2026 redesign is to audit the existing notebooks in this repository and elsewhere and classify them as:

**KEEP** — already fits the redesigned course  
**REWORK** — strong mathematical core but needs a new context or structure  
**REMOVE** — no longer earns its place in the course  
**ADD** — a new notebook or studio is needed

---

## Calculus + AI

Artificial intelligence appears in this course primarily as a **historical, mathematical, and cultural problem**, not as an isolated application unit.

Students trace a mathematical path from

\[
\text{slope}
\rightarrow
\text{extrema}
\rightarrow
\text{optimization}
\rightarrow
\text{loss}
\rightarrow
\text{parameter updates}
\rightarrow
\text{learning}.
\]

Primary sources allow students to investigate changing meanings of terms such as **neuron**, **learning**, **representation**, and **intelligence**.

The course moves from Rosenblatt's perceptron to backpropagation and eventually to high-dimensional representations and generative models.

At the same time, readings in history, STS, and cultural studies ask what disappears when AI is represented exclusively as mathematics and software.

---

## Images and Visual Culture

Images are both mathematical objects and objects of study.

Students may work with historical motion studies by Muybridge and Marey to construct numerical descriptions of motion:

\[
\text{body}
\rightarrow
\text{image}
\rightarrow
\text{measurement}
\rightarrow
\text{data}
\rightarrow
\text{function}
\rightarrow
\text{derivative}.
\]

Later, the process is reconsidered in the context of machine vision:

\[
\text{image}
\rightarrow
\text{pixels}
\rightarrow
\text{numbers}
\rightarrow
\text{features}
\rightarrow
\text{embedding}
\rightarrow
\text{classification}.
\]

This allows questions about scientific seeing, objectivity, representation, and machine vision to develop alongside the calculus.

---

## Calculus Colloquium

Students regularly contribute to a **Calculus Colloquium**.

Rather than simply reporting on a reading, students place an additional mathematical problem, historical source, technical paper, artwork, dataset, or theoretical text into conversation with the mathematics currently being studied.

A typical contribution includes:

- approximately **3 pages of mathematical/critical writing**, prepared in LaTeX;
- approximately **5 presentation slides**;
- a short in-class presentation and discussion.

Possible sources range from Archimedes, Lucretius, Newton, Leibniz, Euler, Fourier, Turing, Shannon, McCulloch & Pitts, Wiener, Rosenblatt, and historical mathematical sourcebooks to cybernetic art, ImageNet, neural networks, transformers, and diffusion models.

---

## Projects

The current redesign anticipates three larger project arcs.

### Project I — Measure Something

Students investigate a problem involving accumulation, approximation, integration, probability, or quantification.

The project asks not only how something can be measured, but what assumptions make that measurement possible.

### Project II — Make Something Change / Learn

Students construct and analyze a mathematical system involving differentiation, optimization, loss, learning, or prediction.

Possible projects include regression models, optimization systems, perceptrons, motion studies, or related computational investigations.

### Final Project — Calculus in the World

Students develop a more independent mathematical investigation involving differential equations, fields, higher-dimensional mathematics, images, modeling, AI, or another approved topic.

The final project combines mathematical work with historical, cultural, scientific, artistic, or social interpretation.

---

## Repository Structure

The repository is currently being reorganized for Fall 2026. The intended structure is approximately:

```text
calcbook/
│
├── README.md
│
├── syllabus/
│   ├── syllabus.tex
│   ├── readings.tex
│   ├── references.bib
│   ├── langcalc.sty
│   └── assets/
│
├── notebooks/
│   ├── 01-integration/
│   ├── 02-differentiation/
│   ├── 03-differential-equations/
│   └── 04-higher-dimensions/
│
├── colloquium/
│
├── projects/
│
└── resources/
```

This structure is provisional and will evolve as the existing notebook collection is audited.

---

## Building the Syllabus

The syllabus and reader are written in LaTeX using BibLaTeX and Biber.

A typical build is:

```bash
pdflatex syllabus.tex
biber syllabus
pdflatex syllabus.tex
pdflatex syllabus.tex
```

The course bibliography lives in:

```text
references.bib
```

and the reader can be included from the main syllabus with:

```latex
\input{readings}
```

---

## Fall 2026 Redesign Status

This repository is currently under active development.

### Current priorities

- [x] Establish four-unit / eight-module course architecture
- [x] Develop core historical and cultural reader
- [x] Integrate primary mathematical and AI sources
- [x] Establish Fall 2026 working calendar
- [ ] Finalize reading excerpts and page ranges
- [ ] Audit existing Jupyter notebooks
- [ ] Create KEEP / REWORK / REMOVE / ADD notebook map
- [ ] Reorganize notebook directory around the new modules
- [ ] Develop new motion / visual culture notebook
- [ ] Develop perceptron and backpropagation notebooks
- [ ] Develop differential-equations / feedback notebooks
- [ ] Develop surfaces / PDE notebook
- [ ] Develop image / embedding / diffusion notebooks
- [ ] Finalize Calculus Colloquium assignment
- [ ] Finalize project sequence and rubrics
- [ ] Complete Fall 2026 syllabus

---

## Course Development

This repository preserves materials from earlier versions of LMTH 2040 while documenting the redesign of the course for Fall 2026.

The aim is not to replace a conventional calculus course with a course *about* calculus.

The aim is to teach substantial calculus while asking broader questions:

**Where do mathematical ideas come from?**

**What becomes visible when the world is represented mathematically?**

**What becomes invisible?**

**How do mathematical techniques migrate between physics, economics, images, computation, and artificial intelligence?**

**What does it mean to model change?**