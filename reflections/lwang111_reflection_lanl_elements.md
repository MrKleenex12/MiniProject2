# Reflection: lanl_elements

ELEMENTS is a finite element library from Los Alamos that other LANL codes, like Fierro, are built on. It depends on another LANL library called MATAR. Its timeline is declining with 3 gaps of at least three months, and it tends to get attention only when the codes around it need something.

The longest gap was 6 months, from January to June 2024. It was moderately hard to interpret, because the commits before it are mostly "updated matar submodule" and merges. There were no issues filed around the gap either. What the commits do show is that ELEMENTS was mostly being kept in sync with MATAR rather than developed on its own.

The recovery backs this up. The first commit after the gap is "updated matar version (for updated Kokkos)," which means a dependency changed and ELEMENTS had to follow. The bigger recovery came from a new person, Jacob Moore, who made 76 of the 90 commits after the gap and led a v2 refactor. The project is Active, and recent commits add boundary surface sets "to be used in fierro." This means ELEMENTS moves when its users move.
