# HPC-Komondor-Alphafold-Project
Using the HPC Komondor for Alphafold Project

README (English)
	1.	This repository contains a code pipeline that generates and evaluates structural models for IL-8 variants.
	2.	The script first runs monomer and multimer predictions on each variant to produce fresh 3D structures (PDB files).
	3.	It then computes approximate binding energies between the new variants and the original IL-8 sequence.
	4.	Multiple rounds of mutation are performed, and each round’s top variants (based on calculated energies) proceed to the next stage.
	5.	The pipeline therefore demonstrates how sequence mutations can influence potential binding interactions and overall protein stability.
	6.	All predicted structures are saved in variant-specific directories, with files named such as ranked_0.pdb or ranked_1.pdb.
	7.	The project can be adapted to other protein systems by supplying a new reference sequence and adjusting the script parameters.
	8.	For further details on running the code and interpreting the outputs, please refer to the commented sections within the script and the logs produced in each results directory.

⸻

README (Hungarian)
	1.	Ez a repository egy olyan kódrendszert tartalmaz, amely IL-8 variánsok szerkezeti modelljeit hozza létre és értékeli ki.
	2.	A script először monomer és multimer predikciókat futtat minden variánson, így új, független 3D-struktúrákat (PDB fájlokat) generál.
	3.	Ezt követően kiszámolja a hozzávetőleges kötési energiákat az új variánsok és az eredeti IL-8 szekvencia között.
	4.	Több mutációs kört alkalmaz, és minden körben a legjobb eredményt adó variánsok jutnak tovább a következő szakaszba.
	5.	A folyamat így bemutatja, hogy a szekvencia megváltoztatása miként befolyásolja a lehetséges kölcsönhatásokat és a fehérje stabilitását.
	6.	Minden predikált szerkezet egyedi, variánsspecifikus mappákban kerül elmentésre, például ranked_0.pdb vagy ranked_1.pdb néven.
	7.	A projekt más fehérjerendszerekre is adaptálható, ha egy új referencia-szekvenciát adunk meg, és a script paramétereit ennek megfelelően módosítjuk.
	8.	A kód futtatásával és az eredmények értelmezésével kapcsolatban további információ a script kommentjeiből, illetve az egyes eredménymappákban található naplófájlokból nyerhető.
