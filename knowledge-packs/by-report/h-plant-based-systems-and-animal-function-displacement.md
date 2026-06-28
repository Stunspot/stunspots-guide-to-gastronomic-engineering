# H. Plant-Based Systems and Animal-Function Displacement

## **1. Paradigm Formalization: Plant-Based Formulation as Functional Displacement**

The formulation of plant-based culinary systems within the GastroBot control architecture is formalized as an optimization problem of structural and physicochemical displacement. Plant-based formulation is not a process of 1:1 ingredient substitution; rather, it is a problem of reverse-engineering missing physical behaviors. In standard operation, animal-derived proteins and fats dictate the physical limits of the food matrix. The displacement of these materials removes highly specialized, evolutionary-optimized functional behaviors: the anisotropic fibrous bite and water retention of myofibrillar muscle tissue; the interfacial emulsification and thermo-irreversible foam coagulation of egg proteins; the pH-buffering capacity of the casein micelle and the distinct melting curve of milkfat; the thermoreversible gelation and extensional viscosity of collagen and gelatin; and the complex temporal release of meat-derived savory persistence.

To map these losses directly onto system parameters, this volume binds plant-derived or fermentation-derived replacement mechanisms to fundamental control variables. The dietary axes—encompassing vegan, vegetarian, plant-based, plant-forward, flexitarian, dairy-free, egg-free, meatless, animal-free, and whole-food plant-based operating modes—are treated as exclusionary constraint vectors applied to a shared control language. This mapping relies strictly on thermodynamic and rheological parameters: temperature ($T$), time ($t$), water activity ($A_w$), pH, ionic strength ($I$), shear stress ($\tau$), phase state transitions, emulsion architecture, gelation mechanics, particulate suspension, and sensory engineering.

By anchoring the response in reusable physicochemical primitives, the system maximizes compositional coverage at inference time. When the constraint compiler excludes an animal ingredient, the system dynamically routes the deficit to an engineered plant-based architectural substitute, ensuring that this volume interoperates cleanly and deterministically with the existing GastroBot knowledge base.

## **2. The Constraint Compiler Layer: Mapping Plant-Based Operating Modes**

To eliminate ambiguity during live inference, user intent is routed through a Constraint Compiler Layer. This layer maps broad dietary terminology directly onto explicit physicochemical constraint vectors and formulation primitives. Allowances and restrictions are mathematically absolute within the compiler, ensuring that retrieval operations access the correct sub-routines without relying on probabilistic guesswork.

| Operating Mode | Constraint Vector & Exclusions | Allowed Structural Primitives | High-Risk Failure Zones | Retrieval Synonyms |
| :---- | :---- | :---- | :---- | :---- |
| **Vegan** | Exclude all animal-derived inputs ($\sum M_{animal} = 0$). Replace meat, dairy, egg, and gelatin functions globally. | Plant proteins, plant fats, hydrocolloids, ferments, mycelium, aquafaba, particulate systems. | Emulsion collapse, rubbery gels, lipoxygenase off-notes, severe phase separation. | Vegan, animal-free, 100% plant-based, meatless. |
| **Vegetarian** | **$\sum M_{meat} = 0$**. Dairy and egg proteins permitted by specific sub-classification (lacto/ovo parameters). | Plant matrices, dairy proteins (casein/whey), egg lipids/proteins, hydrocolloids. | Texture deficits in meat analogues, browning deficits due to myoglobin absence. | Veg, meat-free, vegetarian, lacto-ovo. |
| **Dairy-Free** | **$\sum M_{dairy} = 0$**. Exclude milkfat, casein micelle buffering, lactose, whey fractions. | Plant fats, plant proteins, starch-fat hybrids, nut/seed emulsions, oat milk, cashew cream. | Thin extensional viscosity, acid-fragility, lack of buffering, poor cheese melt dynamics. | Non-dairy, vegan cheese, plant yogurt, oat milk, dairy alternative. |
| **Egg-Free** | **$\sum M_{egg} = 0$**. Exclude ovalbumin, conalbumin, egg yolk lecithin, and cholesterol. | Aquafaba, flax/chia mucilage, soy/chickpea isolate slurries, starch-hydrocolloid networks. | Collapsed foam structures, weak thermal setting, broken kinetic emulsions. | Vegan baking, egg replacer, aquafaba meringue, vegan mayonnaise. |
| **Whole-Food Plant-Based** | **$\sum M_{animal} = 0$**. Minimize refined isolates ($I_{isolate} \to 0$) and extracted fractionated oils. | Native plant matrices, intact legumes, grains, tubers, nuts, seeds, unrefined ferments. | High particulate instability, poor cohesion, highly variable rheological behavior. | WFPB, whole-food, oil-free vegan, unrefined plant-based. |
| **Plant-Forward / Flexitarian** | Plant matrix dominant ($V_{plant} > V_{animal}$). Selective animal reinforcement allowed for structural doping. | Transferable plant structures, hybrid matrices, selective meat/dairy functional doping. | Flavor masking conflicts, differential cooking shrinkage, phase mismatch during heating. | Flexitarian, plant-forward, blended meat, reduced meat. |

## **3. Default Substitution Graphs**

When animal-derived ingredients are removed from the system, the loss of function generates a cascade of predictable structural deficits. The following default substitution graphs map the lost physical behavior to its corresponding plant-system replacement path, bridging the gap between ingredient exclusion and functional recovery.1

| Lost Function & Origin | Structural Consequence of Removal | Plant-Based Replacement Mapping | Control Notes |
| :---- | :---- | :---- | :---- |
| **Meat removed** (Muscle tissue) | Loss of anisotropic fibrous network, immediate water release upon compression, Maillard browning deficit. | Plant protein fibers (HME/shear-cell), seitan (gluten network), mycelial structures, dispersed fat droplets, hydrocolloid binders. | Burger juiciness is a dispersed-phase problem. Require  $T_d$ manipulation for disulfide cross-linking. |
| **Egg removed** (Albumen/Yolk) | Rapid coalescence of O/W systems, rapid foam drainage, lack of structural rigidity post-thermal processing. | Aquafaba (saponin-protein-polysaccharide synergy), soy/chickpea slurry, flax mucilage, starch-protein weak gels. | Egg removal creates three simultaneous failures: emulsion, foam, and set. Replace functions categorically. |
| **Cream removed** (Milkfat/Casein) | Thin rheology, high vulnerability to acid splitting, rapid flavor volatilization, poor freeze-thaw stability. | Cashew cream, oat/soy particle-stabilized continuous phases, coconut cream, starch-fat systems. | Plant milk is an emulsion before it is a beverage. Requires extreme mechanical shear for homogenization. |
| **Cheese removed** (Casein network) | Loss of thermo-reversible flow, rubbery texture at high heat, absence of casein-fat matrix stretch. | Starch-hydrocolloid fat gels, fermented nut pastes, acid-balanced emulsion gels. | Tune solid fat content (SFC) and amylose ratio to achieve  $\tan \delta \ge 1$ at $80^\circ C$ for elastic melt. |
| **Stock/Gelatin removed** (Collagen) | Watery mouthfeel, lack of extensional viscosity, absence of cling, no reduction resonance. | Mushroom beta-glucan systems, seaweed hydrocolloids (agar/carrageenan), allium reductions, pectin. | Match extensional flow mechanics. Stoichiometric ratios of $\kappa$-carrageenan and locust bean gum required. |

## **4. Phase-State Framing**

To ensure the algorithmic routing of solutions operates strictly on physical parameters rather than culinary semantics, the phase identity of each high-value food class is explicitly stated. By embedding Phase-State Framing throughout the architecture, the model bypasses ambiguous culinary terms and addresses the foundational physics of the matrix.

The architecture defines the following primary plant-based systems:

* The **plant milk** system is strictly defined as an oil-in-water (O/W) emulsion combined with suspended colloidal solids.3  
* The **vegan mayonnaise** system is a kinetically stabilized highly concentrated O/W emulsion operating without egg lecithin, relying instead on particulate Pickering stabilization or plant-protein interfacial layers.4  
* The **tofu** matrix is a protein coagulum functioning as a weak hydrogel, precipitated via multivalent cations or acid-set mechanics.6  
* The **tempeh** system is a fermented particulate solid matrix bound by fungal mycelium.  
* The **seitan** matrix is a fully hydrated gluten viscoelastic network, heavily reliant on dense intermolecular disulfide bonding.2  
* The **plant burger** or meatless patty is a particulate solid matrix featuring a dispersed fat phase (for marbling and juiciness) and an engineered water-binding hydrocolloid system (e.g., methylcellulose).8  
* The **vegan custard** formulation is a starch-protein weak gel, exhibiting distinct shear-thinning behavior under load.10  
* The **aquafaba meringue** is a metastable foam system, heavily reliant on the synergy of low-molecular-weight proteins, polysaccharides, and saponins to arrest drainage.12  
* The **vegan cheese** matrix is engineered as an emulsion-gel or fat-crystal hydrogel hybrid, heavily dependent on the thermodynamic melting profile of its constituent lipids.13

## **5. Material Classes of Plant-Based Formulation**

Plant-based ingredients must be categorized by their techno-functional properties, dictating their behavior at the molecular and macroscopic scale. Unlike animal proteins, which are highly conserved and functional across broad physiological ranges, plant substrates possess highly variable characteristics based on botanical origin, extraction methodology, and processing history.15

### **5.1. Legume Proteins: Soy, Pea, Chickpea, Fava, and Lentil**

Legume isolates and concentrates are dominated by globulin and albumin fractions. They are amphiphilic but typically possess highly buried hydrophobic domains that require deliberate thermal, enzymatic, or mechanical unfolding to activate their functional potential.17

* **Soy Protein**: Soy represents the benchmark for plant protein functionality. It exhibits the highest water-holding capacity (WHC) among common legumes, frequently exceeding 6.3 g/g, and possesses an exceptionally robust amino acid profile.15 Soy isolates form firm, heat-induced gels and demonstrate superior phase separation dynamics during high-moisture extrusion, making them ideal for fibrous meat analogues.19  
* **Pea Protein**: Pea protein possesses a high native denaturation temperature ($T_d \approx 82-94^\circ C$), though commercial isolates often denature at lower thresholds ($\approx 72^\circ C$) due to harsh extraction histories.20 Pea isolate exhibits lower baseline solubility than soy and requires a high Least Gelation Concentration (LGC) of 12–20% to form self-supporting structures.15 Furthermore, it is highly susceptible to lipoxygenase-driven off-notes, requiring aggressive flavor suppression.22  
* **Chickpea Protein**: Chickpea extracts display exceptional interfacial activity. They exhibit the lowest LGC among commercial legumes (5–7%) and demonstrate superior foaming capacity and emulsion stability, making them unparalleled replacements for egg albumen in aerated systems.21  
* **Fava Bean Protein**: Fava bean is notable for its extremely light native color profile, making it highly valuable for dairy analogues where yellow/brown tinting is unacceptable.15 It exhibits a remarkably high gelation threshold, with thermal transitions shifting up to $124^\circ C$ depending on the pH and extraction method.23

### **5.2. Cereal and Pseudocereal Proteins: Wheat Gluten, Oat, and Rice**

* **Wheat Gluten**: Gluten provides unmatched viscoelasticity. It is unique among commercial plant proteins for possessing an isoelectric point (pI) near pH 7.0.15 The formation of dense, anisotropic disulfide-bonded networks makes gluten an essential structural component in seitan and a critical secondary binder in high-moisture extrusion, where it significantly enhances fibrous tearing.2  
* **Oat Protein**: Highly hypoallergenic and increasingly favored in dairy alternatives. Oat systems offer excellent continuous-phase viscosity due to their inherent beta-glucan content. When subjected to high-pressure homogenization, oat milk forms highly stable particle-stabilized emulsions.24  
* **Rice Protein**: While possessing a favorable amino acid profile and low allergenicity, rice protein suffers from poor native solubility and weak emulsification strength.25 It requires extensive enzymatic hydrolysis or extreme high-shear homogenization to prevent chalky precipitation in liquid matrices.26

### **5.3. Tuber Proteins and Starch Matrices**

* **Potato Protein**: Potato protein isolates demonstrate exceptionally high viscosity and storage modulus ($G'$) upon heating.15 They function as powerful foaming agents and emulsifiers, but their high reactivity requires strict thermal management; they coagulate rapidly and irreversibly if heated too quickly, leading to grainy, fractured networks.  
* **Waxy Starches**: Starches derived from corn, tapioca, and potato are critical for structuring plant-based cheeses and custards. Waxy starches, heavily dominated by amylopectin, swell rapidly and resist retrogradation, maintaining the viscous flow required to mimic melting cheese.27

### **5.4. Mycelial and Fungal Matrices**

Fungal mycelium provides a native fibrous, directional structure without the need for extreme thermomechanical texturization.29 Composites consisting of 30% mycelium (w/w) combined with pea or potato protein isolate exhibit massive increases in volumetric expansion and water-holding capacity, creating highly porous, spongy matrices that absorb fats and broths efficiently.30

### **5.5. Plant Fats and Lipids**

The physical behavior of plant-based cheeses, butters, and marbled meats is entirely dependent on the solid fat content (SFC) curve of the chosen lipid.32

* **Coconut Oil**: Ubiquitous in plant-based dairy due to its high saturated fat content, providing solidity at refrigeration temperatures. However, its melting curve is disastrously sharp, transitioning from a brittle solid to a thin liquid instantly between $20^\circ C$ and $25^\circ C$, resulting in a greasy mouthfeel and rapid phase separation.33  
* **Cocoa Butter**:  Offers a more gradual polymorphic melting curve, transitioning smoothly between $15^\circ C$ and $40^\circ C$.34  
* **Structured Oleogels**: Advanced systems utilize interesterification or the addition of plant waxes and ethyl cellulose to structure liquid unsaturated oils (like sunflower or canola) into a solid crystal network, replicating the slow-rendering behavior of animal adipose tissue.35

## **6. Animal-Function Displacement Maps**

To operate effectively, the formulation logic must bypass ingredient names and target the underlying physics of the missing animal tissue. This module dictates the direct engineering interventions required to bridge the functional gap.

### **6.1. Muscle Tissue Displacement**

* **Lost Function**: Anisotropic fibrous bite, fluid retention under compression (juiciness), precise fat marbling, and complex browning behavior driven by myoglobin.  
* **Structural Consequence**: When muscle is removed, the resulting particulate matrices lack cohesive chew. They rapidly release free water under mechanical compression (mastication), leaving a dry, powdery bolus.  
* **Direct Replacement Mechanisms**: Texturized vegetable protein (TVP), high-moisture extrusion (HME) networks, shear-cell generated Couette flow layers, and mycelial structures. To replicate marbling, emulsion-based adipose tissue analogues—encapsulated within alginate or curdlan matrices—are injected into the protein network.36  
* **Control Notes**: Burger juiciness is exclusively a dispersed-phase problem. Free liquid oil leaks instantly upon heating; fat must be compartmentalized in an emulsion gel to delay rendering until the target internal cooking temperature is reached.

### **6.2. Egg Displacement**

* **Lost Function**: Interfacial emulsification (via yolk lecithin), massive foam generation (via albumen proteins), heat-set thermo-irreversible coagulation, and glossy surface binding.  
* **Structural Consequence**: Sauces suffer rapid phase separation; cakes develop a dense, collapsed crumb; and patties lack structural rigidity upon cooling.  
* **Direct Replacement Mechanisms**: Aquafaba (for high-volume metastable foam), chickpea or soy isolate slurries (for thermal setting capability), and flax/chia mucilage systems (for continuous phase viscosity and particulate binding).  
* **Control Notes**: Egg removal creates three simultaneous failures: emulsion, foam, and set. No single plant ingredient replicates all three perfectly. While aquafaba wins foam volume, it loses the structural hold; it requires cross-linking with starches or hydrocolloids to survive thermal processing.38

### **6.3. Dairy Displacement**

* **Lost Function**: Casein micelle buffering capacity, broad milkfat mouthfeel, cultured lactic acidity, and the specific extensional viscosity of cream.  
* **Structural Consequence**: Plant-based milks undergo rapid pH drops during fermentation (acid-fragility) and suffer catastrophic syneresis in hot, acidic environments (e.g., coffee). The palate clearance is often described as "watery" or "chalky."  
* **Direct Replacement Mechanisms**: Particle-stabilized (Pickering) oat and cashew emulsions, starch-fat-protein hybrid gels, and shear-thinning continuous phases utilizing precise ratios of guar gum or xanthan gum.11  
* **Control Notes**: Dairy fat melts gradually over a broad thermal spectrum. Plant fats must be aggressively blended (e.g., coconut oil cut with high-oleic sunflower oil) to extend the melting curve and prevent abrupt, greasy phase transitions in the mouth.40

### **6.4. Gelatin and Collagen Displacement**

* **Lost Function**: Elastic body, thermoreversible gelation, glossy reduction, and profound extensional viscosity (the stock-like mouthcoating effect).  
* **Structural Consequence**: Pan sauces lack cling and runoff instantly. Plant hydrocolloid gels tend to fracture and shear abruptly rather than melting smoothly at body temperature ($37^\circ C$).  
* **Direct Replacement Mechanisms**: $\kappa$-carrageenan combined with locust bean gum (LBG), agar-agar networks, konjac glucomannan, and mushroom beta-glucan systems.  
* **Control Notes**: Match the extensional flow mechanics. Mushroom beta-glucans uniquely lower the Trouton ratio, providing an intricate interplay between shear and extensional viscosity that closely mimics the "swallowability" and rich mouthcoating of animal collagen.41

### **6.5. Butter and Cream Displacement**

* **Lost Function**: The specific slow-melt profile, optimal flavor carry, aeration capacity, and fat-phase buffering against astringency.  
* **Structural Consequence**: Products exhibit a greasy, slick mouthfeel or suffer from premature rendering and fat leakage during baking.  
* **Direct Replacement Mechanisms**: Coconut oil blended with long-chain unsaturated fats, cocoa butter, structured oil-in-water emulsion gels, and carefully hydrated nut creams.  
* **Control Notes**: Fat carries flavor, then hides it in the matrix. Highly structured plant-fat networks can sequester lipophilic aroma compounds, drastically reducing perceived flavor intensity.42 Formulations must compensate by either increasing volatile aromatic dosing or utilizing release-triggering starches.

## **7. Protein Solubility, Denaturation, and Gelation in Plant Systems**

The physical chemistry of plant proteins diverges sharply from that of animal proteins. Driven by their biological function as storage mechanisms in seeds, plant proteins fold into compact, globular structures with highly buried hydrophobic domains. This limits their native solubility and necessitates aggressive physical or chemical interventions to unfold the chains and activate their functional potential.17

### **7.1. Solubility Constraints and Isoelectric Point (pI) Mechanics**

Protein solubility is the absolute prerequisite for effective interfacial activity, dictating emulsification strength, foaming capacity, and gelation potential.15 In aqueous environments, solubility drops to an absolute minimum at the isoelectric point (pI)—the pH at which the protein carries zero net charge, leading to maximal protein-protein attraction and immediate precipitation. For the vast majority of legume proteins (pea, soy, fava, chickpea), the pI lies strictly between pH 4.5 and 5.0.43

* **Formulation Mathematics**: $\text{Solubility} \propto | \text{pH}_{system} - \text{pI} |$  
* **Heuristic Application**: Push the pH aggressively away from 4.5 to activate the protein. When formulating at pH 7.0–8.0 (mildly alkaline), electrostatic repulsion forces the protein chains apart, maximizing hydration and surface activity.45 Conversely, formulating a plant-based yogurt at pH 4.5 guarantees catastrophic loss of solubility and severe chalkiness unless heavily stabilized by protective colloids like pectin.

### **7.2. Thermal Denaturation ($T_d$) Pathways**

To initiate gelation or stabilize an emulsion, proteins must be heated above their denaturation temperature ($T_d$). This thermodynamic transition forces the globular proteins to unfold, exposing internal sulfhydryl groups and hydrophobic patches to the aqueous phase.7

* **Denaturation Thresholds**:  
  * Pea Protein Isolate: $T_d \approx 82–94^\circ C$ natively, though aggressive commercial spray-drying may lower this to $\approx 72^\circ C$.20  
  * Soy Protein Isolate: $T_d \approx 85^\circ C$.43  
  * Fava Bean Isolate: Demonstrates extreme thermal resistance, with $T_d$ transitions observed up to $124^\circ C$ depending on hydration and ionic strength.23  

* **Heuristic Application**:Protein adds structure, then threatens chalk and rubber. Exceeding the $T_d$ too rapidly without sufficient hydration causes the premature formation of insoluble, gritty aggregates. Heating must be precisely controlled to allow gradual unfolding before cross-linking occurs.

### **7.3. Gelation Concentration Bands**

Gelation is triggered during the cooling phase following thermal denaturation, or via the deliberate addition of acid or multivalent cations (e.g., $\text{Ca}^{2+}$, $\text{Mg}^{2+}$. The Least Gelation Concentration (LGC) dictates the absolute minimum percentage of protein required to form a self-supporting hydrogel.

* **LGC Thresholds**:  
  * Chickpea Protein: 5–7% (Exceptionally strong gelling agent).21  
  * Soy Protein: 8–12%.43  
  * Pea Protein: 12–20% (Requires heavy loading for structural integrity).15  
* **Heuristic Application**: If the resulting plant-based gel is excessively rubbery, the protein concentration has exceeded the optimal functional band, or the cooling gradient was too rapid. Intervene by reducing the protein load by 2-5% and introducing lipid droplets as active fillers to interrupt the matrix and restore tenderness.11

## **8. Fibrous and Particulate Architectures for Meat Analogues**

The recreation of myofibrillar architecture—the definitive characteristic of whole-muscle animal meat—relies on inducing localized, controlled phase separation between plant proteins, fats, and water under intense thermomechanical stress.

### **8.1. High-Moisture Extrusion (HME) Thermodynamics**

HME operates continuously at high moisture levels (>40%) and high temperatures ($140–180^\circ C$).46 The plant protein powder transitions into a viscoelastic polymer melt inside the twin-screw barrel, cleaving native non-covalent bonds.

The critical texturization occurs as the melt is forced into a long, temperature-controlled cooling die. The die wall rapidly cools the exterior of the melt, creating a severe viscosity gradient between the wall and the hotter, faster-moving center. This cross-sectional contraction generates intense elongational flows and tensile stresses ($\tau$). These forces physically align the unfolded polypeptide chains in the direction of the flow, promoting the formation of novel intermolecular disulfide bonds. The final extrudate emerges as an anisotropic, biphasic solid with distinct, striatable fibrous layers mimicking muscle fascicles.

### **8.2. Shear-Cell (Couette) Texturization**

Shear cell technology offers a highly controlled, batch-processed alternative to HME, utilizing concentric cylinders (Couette cell) or cone-plate geometries. Mild, well-defined rotational shear stress is applied to a hydrated protein dough while it is heated to  $140–160^\circ C$.49 Because the velocity gradient is relatively uniform across the radius of the device, it prevents the severe structural fracturing seen in twin-screw extruders.

* **Heuristic Application**: Extrusion builds rapid, thin fibers; shear cells build thick, whole-muscle blocks. Shear-cell technology is superior for replicating whole-cut matrices like steak or chicken breast, though it currently suffers from throughput limitations.17

### **8.3. Binders and Water-Holding Networks in Particulate Systems**

To bind minced TVP into cohesive burgers, meatballs, and sausages, thermo-responsive binders are required to trap the dispersed fat and water phases.

* **Methylcellulose (MC)**: The current synthetic standard. It possesses a unique inverse-gelation property—it forms a rigid gel upon heating ($>60^\circ C$) and melts back into a viscous liquid upon cooling. This perfectly mimics the firm bite of hot, cooked meat.9  
* **Clean-Label Polysaccharide Alternatives**: To remove MC from ingredient declarations, formulators utilize complex emulsion gels. A highly effective matrix utilizes cold-set fibers (e.g., psyllium husk at 2.2 wt%) combined with heat-set starches (e.g., quinoa flour). This dual-network system matches the water-holding capacity and specific mechanical energy of methylcellulose, delivering a firm bite without the synthetic label.8

## **9. Dairy-Free and Egg-Free Emulsion Systems**

The engineering of plant milks, creams, mayonnaise, and vegan cheeses requires the stabilization of oil-in-water (O/W) interfaces without the aid of casein micelles or egg yolk lecithin. These systems exist in a state of thermodynamic instability and demand rigorous structural support.

### **9.1. Kinetic Emulsion Stability and Pickering Particles**

Plant-based emulsions face severe kinetic degradation through creaming, flocculation, and coalescence. Stabilization relies on either increasing the continuous phase viscosity (via hydrocolloids) to arrest droplet mobility, or forming viscoelastic films directly at the oil-water interface.

* **Pickering Stabilization**: Advanced systems utilize insoluble plant protein aggregates (e.g., from oat or potato) or polysaccharide complexes as solid particles to armor the oil droplets. These particles adsorb to the interface, sterically hindering coalescence and providing massive resilience against mechanical stress.51  
* **Heuristic Application**: Plant milk is an emulsion before it is a beverage. Do not rely on protein solubility alone; utilize high-pressure homogenization (HPH) at >800 bar coupled with modified starch or saponins to achieve nanometer-scale droplet distributions and absolute stability.3

### **9.2. Fat-Phase Design and Vegan Cheese Mechanics**

Dairy cheese stretches and melts due to the unique phase transition of its casein-fat matrix. Vegan cheese replaces this missing biological architecture with a finely tuned emulsion-gel or fat-crystal hydrogel hybrid.13

* **The Coconut Oil Problem**:  Coconut oil is universally favored for its high solid fat content (SFC) at refrigeration temperatures. However, its melting curve is disastrously steep, transitioning from a brittle, crystalline solid to a thin liquid instantly between $20^\circ C$ and $25^\circ C$. This results in a greasy mouthfeel, oil pooling on pizzas, and a lack of authentic stretch.34  
* **Intervention Vector**: Blending coconut oil with 25% liquid unsaturated oil (e.g., sunflower or canola oil) significantly flattens the solid fat content profile, expanding the melting range.40  
* **Stretch Mechanics**:  Coupling this blended lipid phase with native waxy starch (high amylopectin) and a low-LGC plant protein (like pea isolate) modulates the retrogradation of the starch. This specific formulation achieves a rheological loss tangent ($\tan \delta = G''/G'$) $\ge 1$ at $80^\circ C$, ensuring the matrix transitions from elastic to viscous flow, yielding a stretchable, dynamically melting cheese analogue.27

## **10. Foam and Weak-Gel Systems Without Egg Whites or Casein**

Replacing the foaming properties of egg white requires the replication of low surface tension, rapid interfacial adsorption, and high film elasticity to prevent air bubble collapse.

### **10.1. Aquafaba Mechanics**

Aquafaba—the viscous processing water from cooking chickpeas or fava beans—forms highly voluminous but metastable foams.

* **Mechanism**: The foam is not stabilized by a single molecule, but by a synergistic triad: saponins (highly surface-active glycosides that drastically reduce interfacial tension), low-molecular-weight proteins (<25 kDa, enabling rapid migration to the air-water interface), and complex polysaccharides (amylose and pectin, which drastically increase the bulk viscosity of the continuous phase, physically arresting drainage).12  
* **Concentration Threshold**: Optimal stability requires concentrating the raw aquafaba by boiling and evaporation until the remaining liquid ratio reaches 50-70%. This disproportionately increases the carbohydrate content and accumulates Maillard reaction polymers, maximizing the structural integrity of the resulting foam.12  
* **Heuristic Application**: Aquafaba wins foam, then loses hold. Because aquafaba proteins lack the thermo-irreversible coagulation of ovalbumin, the foam will collapse under heat or prolonged holding. Formulators must interlock the foam by adding 0.1-0.5% xanthan gum or octenyl succinic anhydride (OSA) modified starch to physically delay drainage and lock the bubbles in place.39

### **10.2. Vegan Custards and Plant-Yogurt**

* **Custard Systems**: Vegan custards operate as starch-protein weak gels. To prevent catastrophic syneresis (weeping), formulation mathematics dictate a tight ratio of approximately 2-5% modified waxy starch coupled with 1-5% plant protein, stabilizing the continuous phase while preventing rubbery over-gelation.10  
* **Yogurt Syneresis**: Cultured plant milks lack casein to form a robust, interconnected acid-set gel. As lactic acid bacteria lower the pH toward the isoelectric point, plant proteins aggressively coagulate, contracting the network and violently expelling water (syneresis).55 To suppress this, formulators must interlock the aqueous phase using chicory root fiber, pectin, or subject the base to high-pressure processing (HPP) to force complete protein unfolding prior to fermentation.56

## **11. Flavor Engineering and Off-Note Suppression in Plant Matrices**

Plant-based ingredients natively carry volatile organic compounds that evoke "beany," "grassy," "earthy," or "chalky" perceptions. These off-notes easily exceed human detection thresholds (often as low as 5 ppb) and severely limit product acceptance. Within the GastroBot architecture, off-note suppression is treated as a primary thermodynamic and biochemical engineering problem, not as a culinary garnish.

### **11.1. Lipoxygenase (LOX) and Aldehyde Generation**

The primary mechanism responsible for "beany" off-notes is the enzymatic oxidation of polyunsaturated fatty acids (specifically linoleic and linolenic acids) by endogenous Lipoxygenase (LOX).58 This reaction yields lipid hydroperoxides, which rapidly cleave into highly volatile, odor-active aldehydes such as hexanal and pentanal.

* **Aldol Condensation Risk**: During the thermal extraction and drying of pea and soy isolates, these volatile aldehydes can undergo aldol condensation, generating previously uncharacterized $\alpha,\beta$-unsaturated aldehydes that cause severe, persistent "old soap" off-notes.22

### **11.2. Suppression Vectors**

* **Thermal Inactivation**: Flash-blanching legume substrates at precise parameters ($90^\circ C$ for exactly 30s) permanently denatures the LOX enzyme prior to milling and extraction, halting the entire hydroperoxide cascade.60  
* **Sequential Fermentation**: A powerful biological mitigation strategy involves two-stage microbial fermentation. Stage 1 utilizes *Lactiplantibacillus plantarum* to target specific aldehydes, followed by Stage 2 employing traditional yogurt cultures (*S. thermophilus*, *L. bulgaricus*). This sequence enzymatically metabolizes 95-99% of hexanal, 2-pentylfuran, and sulfurous volatiles into inert alcohols and masks them with pleasant organic acids.62  
* **Matrix Masking and Fat Partitioning**: Fat carries flavor, then hides it in the matrix. Expanding the dispersed fat phase sequesters hydrophobic off-notes, lowering their vapor pressure and delaying their release into the olfactory receptors during mastication.64

### **11.3. Umami Generation and Browning Deficits**

* **Umami Synergy**: Plant proteins fundamentally lack the savory persistence and depth of meat. To bridge this gap, formulations must supply high concentrations of free glutamic acid (via fermented soy, yeast extract, or mushroom concentrates) directly alongside 5'-ribonucleotides (IMP/AMP). This specific pairing triggers an exponential, synergistic activation of the T1R1/T1R3 umami receptors.65  
* **Maillard Browning Deficits**: Plant matrices lack reducing sugars and blood-derived myoglobin, severely stalling the Maillard browning reaction during cooking. Doping the exterior matrix with exogenous recombinant myoglobin, or precisely calculated ratios of pentose sugars (dextrose) and amino acids, ensures the development of a complex, caramelized crust without pushing the reaction into bitter charring.67

## **12. Temporal Stability and Service Windows**

Plant-based systems degrade structurally and rheologically under holding conditions at rates drastically different from animal systems. To ensure service reliability, operational logic must be explicitly constrained by time and temperature.

* **Foam Drainage Windows**: Plant-based foams undergo Ostwald ripening and gravitational drainage at accelerated rates. Unstabilized aquafaba foams will collapse 3x faster than egg white foams.39 The service window is strictly defined as *immediate plating*, unless the matrix is physically interlocked with octenyl succinic anhydride (OSA) modified starches, extending the hold time to $\le 2$ hours.54  
* **High-Heat Emulsion Splitting**: Non-dairy creams and sauces break rapidly under high-acid or high-heat holding (e.g., stirred into hot coffee or reduced in a tomato sauce). To extend the holding tolerance, formulate with saponin-stabilized emulsions to maintain a high negative $\zeta$-potential ($-60$ mV), ensuring powerful electrostatic repulsion even under extreme thermal stress.3  
* **Freeze-Thaw Instability**: Repeated freezing shreds hydrated plant protein networks via ice crystal nucleation, destroying water-holding capacity. To suppress this, engineer a dual-network: introduce Glucose Oxidase (GO) to enhance internal covalent disulfide cross-linking, paired with Tamarind Gum (TG) to provide intense external steric hindrance and bind free water.69  
* **Post-Cook Firming**: Plant burgers rapidly dry out and firm up during prolonged heat-lamp holding. Modulate this moisture loss by balancing thermo-responsive hydrocolloids (methylcellulose) to maintain rigidity at high heat, with hygroscopic starches to recapture moisture upon cooling.

## **13. Symptom-First Failure Diagnostics**

This rapid salvage module maps macroscopic failures directly to their physicochemical mechanisms, providing precise control interventions for live troubleshooting.

| Symptom | Mechanism | High-Probability Causes | Control Fix / Intervention Vector |
| :---- | :---- | :---- | :---- |
| **Broken vegan emulsion** | Rapid droplet coalescence due to low interfacial tension or electrostatic charge shielding. | Insufficient mechanical shear during mixing; pH approaching the isoelectric point (charge neutralization). | Increase homogenization pressure ($>800$ bar); dose with saponins or soy lecithin; shift pH $> 6.0$. |
| **Thin non-dairy cream sauce** | Lack of continuous phase entanglement and low effective solids concentration. | Starch under-hydration; insufficient protein concentration in the aqueous phase. | Insert oat beta-glucan or 0.1% xanthan gum; increase thermal shear to fully hydrate starches. |
| **Split cashew or oat emulsion** | Acid-induced protein coagulation and catastrophic phase separation. | Adding cold emulsion directly to a hot, highly acidic medium (e.g., coffee). | Pre-heat the emulsion; buffer the pH utilizing dipotassium phosphate or sodium citrate. |
| **Rubbery tofu or plant-protein gel** | Extreme over-aggregation of protein networks, physically contracting and pushing out water. | Exceeded optimal protein LGC band; cooling rate too fast; excessive calcium salt dosing. | Reduce protein loading (target 10-15%); introduce lipid droplets as active fillers to interrupt the continuous matrix. |
| **Weak plant burger cohesion** | Insufficient binder network to hold the texturized vegetable protein and fat phases. | Methylcellulose or psyllium absent; insufficient specific mechanical energy (SME) during mixing. | Ensure the binder is mixed well below $10^\circ C$ to hydrate properly before cooking; increase mixing duration. |
| **Dry vegan meat analogue** | Rapid free water release due to a weakly structured dispersed phase. | Liquid oil droplets pooling, migrating, and rendering out rapidly during heat application. | Pre-emulsify the fat phase before adding to TVP; utilize solid fat blends (coconut/sunflower) to delay melting. |
| **Dense egg-free bake** | Complete failure of aeration and thermal setting mechanisms. | Aquafaba drained before starch gelatinization; matrix lacking structural scaffolding protein. | Whip aquafaba to stiff peaks strictly at $25^\circ C$; add 2% pea protein isolate to structurally reinforce the crumb. |
| **Collapsed aquafaba foam** | Accelerated Ostwald ripening and gravity-driven liquid drainage. | Low bulk viscosity in the continuous phase; excessive free oil/fat present in the whipping bowl. | Concentrate raw aquafaba to 50% volume before whipping; add 0.2% xanthan gum to lock the liquid phase. |
| **Beany or grassy off-notes** | Lipoxygenase (LOX) oxidation of linoleic acid directly into volatile hexanal. | Use of raw, unblanched legume isolates; prolonged exposure to oxygen during milling. | Flash-blanch substrates (($90^\circ C$ / 30s) prior to processing; apply sequential *L. plantarum* fermentation. |
| **Chalky pea-protein matrix** | Insoluble protein aggregates failing to disperse in saliva, creating particulate friction. | Highly denatured commercial isolates used in excessive concentrations; poor initial hydration. | Hydrate fully with extreme high shear; physically coat particles with pectin; blend with soluble oat or rice proteins. |
| **Greasy nut-based batter** | Fat rendering from mechanically broken oleosomes. | Over-processing (shearing nuts until oil physically separates from the cellular matrix). | Emulsify the free oil immediately with a secondary carbohydrate; manage mixing temperatures ($<25^\circ C$). |
| **Grainy vegan cheese sauce** | Premature starch retrogradation or localized protein precipitation. | Uneven heating gradients; calcium bridging occurring with un-hydrated hydrocolloids. | Hydrate starches completely at $80^\circ C$ before introducing multivalent calcium ions or acidic components. |
| **Poor browning in meatless systems** | Absolute Maillard reaction deficit. | Total lack of reducing sugars and free amino acids in the isolate. | Add 1% dextrose or yeast extract; adjust surface pH to be slightly alkaline immediately prior to searing. |
| **Syneresis in cultured plant yogurt** | Gel matrix contraction expelling the whey/serum phase. | Low total solids; un-denatured globulins failing to cross-link prior to fermentation. | Pre-heat the base to $90^\circ C$ to fully denature globulins; add 1% chicory root fiber or pectin to bind water. |

## **14. Formulation Heuristics and Rapid Decision Rules**

To ensure rapid, inference-time routing within the GastroBot operating system, the following encoded heuristics must dictate macro-level decision-making. These principles compress complex physics into immediate diagnostic triggers:

* **“Plant-based cooking replaces functions, not ingredients.”** Define the absolute physical requirement (e.g., extensional viscosity, interfacial stability) before selecting the botanical substrate (e.g., beta-glucan, saponin).  
* **“Egg removal creates three problems at once: emulsion, foam, and set.”** Never attempt a 1:1 ingredient swap; you must build a composite system of lipids, hydrocolloids, and isolates to cover all three vectors.  
* **“Protein adds structure, then threatens chalk and rubber.”** Over-dosing plant protein isolates inevitably degrades mouthfeel through excessive particulate friction or over-gelation. Shield excess protein with hydrating polysaccharides.  
* **“Fat carries flavor, then hides it in the matrix.”** Highly structured oil-in-water emulsions and solid oleogels sequester hydrophobic off-notes, but they also delay the release of desirable aromas. Compensate by over-dosing volatile aromatics slightly.  
* **“Plant milk is an emulsion before it is a beverage.”** It is thermodynamically unstable and will separate unless mechanically sheared into nanoparticles and sterically stabilized.  
* **“Burger juiciness is a dispersed-phase problem.”** Unbound liquid oil leaks instantly under heat; structured fat emulsions (oleogels) burst slowly upon chewing, mimicking meat juice.  
* **“Fermentation adds savoriness, then shifts pH.”** The generation of umami-rich organic acids will push the system downward toward the protein's isoelectric point, threatening catastrophic emulsion stability.  
* **“Aquafaba wins foam, then loses hold.”** It provides massive aeration but requires immediate thermal setting or hydrocolloid doping to survive the service window without collapsing.  
* **“Whole-food purity trades control for variability.”** Retaining the native, unrefined plant matrix introduces extreme particulate instability and severely limits precision in rheological tuning.

## **15. Formulation-Loop Integration**

This volume seamlessly interoperates with the broader GastroBot operating system through a strict, deterministic eight-step execution loop. When tasked with a plant-based substitution, the system executes the following algorithm:

1. **Define Constraint Vectors**: Parse the user query through the Compiler Layer to establish absolute dietary exclusions (Vegan, Dairy-Free, WFPB).  
2. **Identify Phase System**: Determine the strict thermodynamic target of the desired product (e.g., O/W emulsion, metastable foam, solid particulate matrix, viscoelastic polymer melt).  
3. **Extract Missing Functions**: Map the excluded animal ingredients to their structural roles using the Default Substitution Graphs to identify exact physical deficits.  
4. **Select Replacement Primitives**: Retrieve the optimal plant proteins, fats, and hydrocolloids based on phase requirements, LGC thresholds, and off-note risks defined in the Material Classes.  
5. **Calculate Control Variables**: Apply explicit mathematics for the formulation (e.g., determining $\text{pH}_{system}$ relative to pI, calculating target solid fat content (SFC) curves for melt, and establishing hydrocolloid ratios).  
6. **Execute Processing Parameters**: Define the required mechanical and thermal inputs to force the matrix assembly (e.g., High-Pressure Homogenization rates, High-Moisture Extrusion shear rates, LOX-inactivation blanching temperatures).  
7. **Diagnose Symptom Signatures**: If the system fails in simulation or physical execution, route the macroscopic symptoms through the Failure Diagnostics module to isolate the underlying molecular mechanism.  
8. **Iterate via Adjustments**: Apply targeted intervention vectors (e.g., shift pH, alter hydrocolloid stoichiometry, increase continuous phase viscosity) to salvage and stabilize the matrix.

By anchoring plant-based formulation in these rigorous physicochemical primitives and thermodynamic realities, the GastroBot control architecture ensures deterministic, high-fidelity replication of animal-derived culinary phenomena across all plant-based operating modes.

#### **Works cited**

1. A dual polysaccharide and plant protein system for cheese analog with enhanced meltability and texture | Request PDF - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/401388524_A_dual_polysaccharide_and_plant_protein_system_for_cheese_analog_with_enhanced_meltability_and_texture](https://www.researchgate.net/publication/401388524_A_dual_polysaccharide_and_plant_protein_system_for_cheese_analog_with_enhanced_meltability_and_texture)  
2. High-Moisture Shear Processes: Molecular Changes of Wheat Gluten and Potential Plant-Based Proteins for Its Replacement - MDPI, accessed March 29, 2026, [https://www.mdpi.com/1420-3049/27/18/5855](https://www.mdpi.com/1420-3049/27/18/5855)  
3. Plant-Based Oil-in-Water Food Emulsions: Exploring the Influence of Different Formulations on Their Physicochemical Properties - MDPI, accessed March 29, 2026, [https://www.mdpi.com/2304-8158/13/4/513](https://www.mdpi.com/2304-8158/13/4/513)  
4. Physicochemical and structural properties of vegan mayonnaise prepared with peanut sprout oil and aquafaba - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12036073/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12036073/)  
5. Sensory characteristics, quality attributes, and storage stability of mayonnaise: a review | International Journal of Food Science and Technology | Oxford Academic, accessed March 29, 2026, [https://academic.oup.com/ijfst/article/60/2/vvaf148/8213835](https://academic.oup.com/ijfst/article/60/2/vvaf148/8213835)  
6. (PDF) A Comprehensive Review on Plant-Originated Versatile Gels: Mechanism, Characterization, and Applications - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/384363885_A_Comprehensive_Review_on_Plant-Originated_Versatile_Gels_Mechanism_Characterization_and_Applications](https://www.researchgate.net/publication/384363885_A_Comprehensive_Review_on_Plant-Originated_Versatile_Gels_Mechanism_Characterization_and_Applications)  
7. Plant Protein Heat-Induced Gels: Formation Mechanisms and Regulatory Strategies - MDPI, accessed March 29, 2026, [https://www.mdpi.com/2079-6412/13/11/1899](https://www.mdpi.com/2079-6412/13/11/1899)  
8. WO2022112315A1 - Binder system for a meat analogue product ..., accessed March 29, 2026, [https://patents.google.com/patent/WO2022112315A1/en](https://patents.google.com/patent/WO2022112315A1/en)  
9. Thermogelation of methylcellulose: Rheological considerations | Request PDF - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/223450093_Thermogelation_of_methylcellulose_Rheological_considerations](https://www.researchgate.net/publication/223450093_Thermogelation_of_methylcellulose_Rheological_considerations)  
10. EP0776610B1 - Process for the preparation of bake-stable custard - Google Patents, accessed March 29, 2026, [https://patents.google.com/patent/EP0776610B1/en](https://patents.google.com/patent/EP0776610B1/en)  
11. Role of proteins in the microstructure, rheology, tribology and sensory perception of plant-based custards - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/392844834_Role_of_proteins_in_the_microstructure_rheology_tribology_and_sensory_perception_of_plant-based_custards](https://www.researchgate.net/publication/392844834_Role_of_proteins_in_the_microstructure_rheology_tribology_and_sensory_perception_of_plant-based_custards)  
12. Optimizing Chickpea Cooking Water (Aquafaba): Enhancing Superior Foaming and Emulsifying Properties Through Concentration Protocols - MDPI, accessed March 29, 2026, [https://www.mdpi.com/2813-513X/3/1/3](https://www.mdpi.com/2813-513X/3/1/3)  
13. Food Emulsion Gels from Plant-Based Ingredients: Formulation, Processing, and Potential Applications - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10217108/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10217108/)  
14. Functionality and application of emulsion gels in fat replacement strategies for dairy products | Request PDF - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/384514545_Functionality_and_application_of_emulsion_gels_in_fat_replacement_strategies_for_dairy_products](https://www.researchgate.net/publication/384514545_Functionality_and_application_of_emulsion_gels_in_fat_replacement_strategies_for_dairy_products)  
15. Techno-Functional and Sensory Characterization of Commercial Plant Protein Powders, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10379337/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10379337/)  
16. Opportunities and challenges of plant proteins as functional ingredients for food production | PNAS, accessed March 29, 2026, [https://www.pnas.org/doi/10.1073/pnas.2319019121](https://www.pnas.org/doi/10.1073/pnas.2319019121)  
17. Deep dive: Plant-based meat end product formulation and manufacturing | GFI, accessed March 29, 2026, [https://gfi.org/science/the-science-of-plant-based-meat/deep-dive-plant-based-meat-end-product-formulation-and-manufacturing/](https://gfi.org/science/the-science-of-plant-based-meat/deep-dive-plant-based-meat-end-product-formulation-and-manufacturing/)  
18. Nutritional Value and Physicochemical Characteristics of Alternative Protein for Meat and Dairy—A Review - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC9654170/](https://pmc.ncbi.nlm.nih.gov/articles/PMC9654170/)  
19. Engineering Processes for Plant‐Based Meat Analogs: Current Status and Future Outlook, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12576308/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12576308/)  
20. Ingredient Functionality of Soy, Chickpea, and Pea Protein before and after Dry Heat Pretreatment and Low Moisture Extrusion - MDPI, accessed March 29, 2026, [https://www.mdpi.com/2304-8158/13/14/2168](https://www.mdpi.com/2304-8158/13/14/2168)  
21. The Comparison of Functional and Physical Properties of Commercial Pulse Proteins to Soy Protein - UMass ScholarWorks, accessed March 29, 2026, [https://scholarworks.umass.edu/bitstreams/7708a8e9-083d-483b-afbf-c5077c7d51b2/download](https://scholarworks.umass.edu/bitstreams/7708a8e9-083d-483b-afbf-c5077c7d51b2/download)  
22. Presence and impact of aldol condensation products as off-notes in plant-based protein sources | CentAUR, accessed March 29, 2026, [https://centaur.reading.ac.uk/121909/1/mayo-et-al-2025-presence-and-impact-of-aldol-condensation-products-as-off-notes-in-plant-based-protein-sources.pdf](https://centaur.reading.ac.uk/121909/1/mayo-et-al-2025-presence-and-impact-of-aldol-condensation-products-as-off-notes-in-plant-based-protein-sources.pdf)  
23. Physicochemical and Functional Properties of Membrane-Fractionated Heat-Induced Pea Protein Aggregates - Frontiers, accessed March 29, 2026, [https://www.frontiersin.org/journals/nutrition/articles/10.3389/fnut.2022.852225/full](https://www.frontiersin.org/journals/nutrition/articles/10.3389/fnut.2022.852225/full)  
24. Influence of hydrocolloids and natural emulsifier in the physical stability of UHT oat beverage - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/371249679_Influence_of_hydrocolloids_and_natural_emulsifier_in_the_physical_stability_of_UHT_oat_beverage](https://www.researchgate.net/publication/371249679_Influence_of_hydrocolloids_and_natural_emulsifier_in_the_physical_stability_of_UHT_oat_beverage)  
25. (PDF) Techno-Functional and Sensory Characterization of Commercial Plant Protein Powders - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/372643127_Techno-Functional_and_Sensory_Characterization_of_Commercial_Plant_Protein_Powders/download](https://www.researchgate.net/publication/372643127_Techno-Functional_and_Sensory_Characterization_of_Commercial_Plant_Protein_Powders/download)  
26. Study on Physicochemical Properties of Food Protein - MDPI, accessed March 29, 2026, [https://mdpi-res.com/bookfiles/book/8663/Study_on_Physicochemical_Properties_of_Food_Protein.pdf?v=1736302014](https://mdpi-res.com/bookfiles/book/8663/Study_on_Physicochemical_Properties_of_Food_Protein.pdf?v=1736302014)  
27. Methodology and development of a high-protein plant-based cheese alternative - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10660021/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10660021/)  
28. Particle filled protein-starch composites as the basis for plant-based meat analogues - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC9846454/](https://pmc.ncbi.nlm.nih.gov/articles/PMC9846454/)  
29. Potential Protein Production from Lignocellulosic Materials Using Edible Mushroom Forming Fungi | Journal of Agricultural and Food Chemistry - ACS Publications, accessed March 29, 2026, [https://pubs.acs.org/doi/10.1021/acs.jafc.2c08828](https://pubs.acs.org/doi/10.1021/acs.jafc.2c08828)  
30. Formation and Characterization of Mycelium–Potato Protein Hybrid Materials for Application in Meat Analogs or Substitutes - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11675917/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11675917/)  
31. Incorporation of Mycelium (Pleurotus eryngii) in Pea Protein Based Low Moisture Meat Analogue: Effect on Its Physicochemical, Rehydration and Structural Properties - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC9407581/](https://pmc.ncbi.nlm.nih.gov/articles/PMC9407581/)  
32. Influence of Protein Content on Plant-Based Emulsified and Crosslinked Fat Crystal Networks to Mimic Animal Fat Tissue | Request PDF - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/339937729_Influence_of_Protein_Content_on_Plant-Based_Emulsified_and_Crosslinked_Fat_Crystal_Networks_to_Mimic_Animal_Fat_Tissue](https://www.researchgate.net/publication/339937729_Influence_of_Protein_Content_on_Plant-Based_Emulsified_and_Crosslinked_Fat_Crystal_Networks_to_Mimic_Animal_Fat_Tissue)  
33. Research on animal-free fats presents un-fat-homable possibilities for meat alternatives, accessed March 29, 2026, [https://gfi.org/blog/research-on-animal-free-fats-presents-un-fat-homable-possibilities-for-meat-alternatives/](https://gfi.org/blog/research-on-animal-free-fats-presents-un-fat-homable-possibilities-for-meat-alternatives/)  
34. Comparing the Melt and Cooling Properties of Animal vs Plant-Based Fats - Rheology Lab, accessed March 29, 2026, [https://www.rheologylab.com/comparing-the-melt-and-cooling-properties-of-animal-vs-plant-based-fats/](https://www.rheologylab.com/comparing-the-melt-and-cooling-properties-of-animal-vs-plant-based-fats/)  
35. From liquid to solid: Exploring techniques, applications, and challenges of structured oils as fat replacements in food formulations - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11924905/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11924905/)  
36. Construction and Textural Properties of Plant-Based Fat Analogues Based on a Soy Protein Isolate/Sodium Alginate Complex Coacervation System - MDPI, accessed March 29, 2026, [https://www.mdpi.com/2304-8158/14/24/4355](https://www.mdpi.com/2304-8158/14/24/4355)  
37. A Plant-Based Animal Fat Analog Produced by an Emulsion Gel of Alginate and Pea Protein, accessed March 29, 2026, [https://www.mdpi.com/2310-2861/9/5/393](https://www.mdpi.com/2310-2861/9/5/393)  
38. Heat and shear stability of particle stabilised foams for application in gluten-free bread, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10497492/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10497492/)  
39. Quantifying the Foamability of Aquafaba and Egg White - Rheology Lab, accessed March 29, 2026, [https://www.rheologylab.com/quantifying-foamability-of-aquafaba-and-egg-white/](https://www.rheologylab.com/quantifying-foamability-of-aquafaba-and-egg-white/)  
40. Effect of saturated and unsaturated fat on the physical properties of plant-based cheese, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11403416/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11403416/)  
41. Rheological investigations of beta glucan functionality: Interactions with mucin | Request PDF - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/326751479_Rheological_investigations_of_beta_glucan_functionality_Interactions_with_mucin](https://www.researchgate.net/publication/326751479_Rheological_investigations_of_beta_glucan_functionality_Interactions_with_mucin)  
42. Construction and Textural Properties of Plant-Based Fat Analogues Based on a Soy Protein Isolate/Sodium Alginate Complex Coacervation System - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12732585/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12732585/)  
43. Physicochemical and textural properties of heat-induced pea protein isolate gels | Request PDF - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/222963857_Physicochemical_and_textural_properties_of_heat-induced_pea_protein_isolate_gels](https://www.researchgate.net/publication/222963857_Physicochemical_and_textural_properties_of_heat-induced_pea_protein_isolate_gels)  
44. The Current Situation of Pea Protein and Its Application in the Food Industry - MDPI, accessed March 29, 2026, [https://www.mdpi.com/1420-3049/27/16/5354](https://www.mdpi.com/1420-3049/27/16/5354)  
45. Effect of pH-shifting on the water holding capacity and gelation properties of mung bean protein isolate | Request PDF - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/376770162_Effect_of_pH-shifting_on_the_water_holding_capacity_and_gelation_properties_of_mung_bean_protein_isolate](https://www.researchgate.net/publication/376770162_Effect_of_pH-shifting_on_the_water_holding_capacity_and_gelation_properties_of_mung_bean_protein_isolate)  
46. Plant-Based Meat Analogues from Alternative Protein: A Systematic Literature Review, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC9498552/](https://pmc.ncbi.nlm.nih.gov/articles/PMC9498552/)  
47. Morphology Development and Flow Characteristics during High Moisture Extrusion of a Plant-Based Meat Analogue - MDPI, accessed March 29, 2026, [https://www.mdpi.com/2304-8158/10/8/1753](https://www.mdpi.com/2304-8158/10/8/1753)  
48. Protein–Protein Interactions during High-Moisture Extrusion for Fibrous Meat Analogues and Comparison of Protein Solubility Methods Using Different Solvent Systems | Journal of Agricultural and Food Chemistry - ACS Publications, accessed March 29, 2026, [https://pubs.acs.org/doi/10.1021/jf073343q](https://pubs.acs.org/doi/10.1021/jf073343q)  
49. Shear Cell Technology and the Role of Ingredients in Developing Fibrous Plant-Based Meat Analogs | Kinam Park, accessed March 29, 2026, [http://kinampark.com/T-Polymers/files/All%20References/Ajay%202025%2C%20Shear%20cell%20technology%20and%20the%20role%20of%20ingredients%20in%20developing%20fibrous%20plant-based%20meat%20analogs.pdf](http://kinampark.com/T-Polymers/files/All%20References/Ajay%202025%2C%20Shear%20cell%20technology%20and%20the%20role%20of%20ingredients%20in%20developing%20fibrous%20plant-based%20meat%20analogs.pdf)  
50. Application of a shear cell for the simulation of extrusion to test the structurability of raw materials, accessed March 29, 2026, [https://www.research-collection.ethz.ch/entities/publication/d0e32c6f-bd3f-457a-8f32-fc073997d19e](https://www.research-collection.ethz.ch/entities/publication/d0e32c6f-bd3f-457a-8f32-fc073997d19e)  
51. Physical stability of plant protein-stabilized food emulsions: A multiscale approach | WUR, accessed March 29, 2026, [https://www.wur.nl/en/activity/physical-stability-plant-protein-stabilized-food-emulsions-multiscale-approach](https://www.wur.nl/en/activity/physical-stability-plant-protein-stabilized-food-emulsions-multiscale-approach)  
52. (PDF) Lubrication by plant-based emulsions: Linking oil-water protein-stabilized interfacial mechanical properties to oil droplet lubrication properties - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/398407644_Lubrication_by_plant-based_emulsions_Linking_oil-water_protein-stabilized_interfacial_mechanical_properties_to_oil_droplet_lubrication_properties](https://www.researchgate.net/publication/398407644_Lubrication_by_plant-based_emulsions_Linking_oil-water_protein-stabilized_interfacial_mechanical_properties_to_oil_droplet_lubrication_properties)  
53. Advances in emulsion stability: A review on mechanisms, role of emulsifiers, and applications in food - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12311586/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12311586/)  
54. The contribution of polysaccharides to the foaming and emulsifying properties of aquafaba | Request PDF - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/401713228_The_contribution_of_polysaccharides_to_the_foaming_and_emulsifying_properties_of_aquafaba](https://www.researchgate.net/publication/401713228_The_contribution_of_polysaccharides_to_the_foaming_and_emulsifying_properties_of_aquafaba)  
55. Ways to Reduce Syneresis in Yogurt | Grande CIG Blog, accessed March 29, 2026, [https://www.grandecig.com/blog/ways-to-reduce-syneresis-in-yogurt](https://www.grandecig.com/blog/ways-to-reduce-syneresis-in-yogurt)  
56. Ingredients, Processing, and Fermentation: Addressing the Organoleptic Boundaries of Plant-Based Dairy Analogues - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC8952883/](https://pmc.ncbi.nlm.nih.gov/articles/PMC8952883/)  
57. Plant-based yogurt keeps getting better | Nutritional Outlook - Supplement, Food & Beverage Manufacturing Trends, accessed March 29, 2026, [https://www.nutritionaloutlook.com/view/plant-based-yogurt-keeps-getting-better](https://www.nutritionaloutlook.com/view/plant-based-yogurt-keeps-getting-better)  
58. Impact of the suppression of lipoxygenase and hydroperoxide lyase on the quality of the green odor in green leaves - PubMed, accessed March 29, 2026, [https://pubmed.ncbi.nlm.nih.gov/15740054/](https://pubmed.ncbi.nlm.nih.gov/15740054/)  
59. Presence and Impact of Aldol Condensation Products as Off-Notes in Plant-Based Protein Sources | Request PDF - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/389519781_Presence_and_Impact_of_Aldol_Condensation_Products_as_Off-Notes_in_Plant-Based_Protein_Sources](https://www.researchgate.net/publication/389519781_Presence_and_Impact_of_Aldol_Condensation_Products_as_Off-Notes_in_Plant-Based_Protein_Sources)  
60. Effect of Blanching on Enzyme Inactivation, Physicochemical Attributes and Antioxidant Capacity of Hot-Air Dried Pomegranate (Punica granatum L.) Arils (cv. Wonderful) - MDPI, accessed March 29, 2026, [https://www.mdpi.com/2227-9717/9/1/25](https://www.mdpi.com/2227-9717/9/1/25)  
61. Effects of Blanching Conditions on the Enzyme Inhibition and Antioxidant Loss in Rambutan (Nephelium lappaceum L.) Seeds, accessed March 29, 2026, [https://journal.pan.olsztyn.pl/pdf-200589-122730?filename=122730.pdf](https://journal.pan.olsztyn.pl/pdf-200589-122730?filename=122730.pdf)  
62. Controlling Off-Odors in Plant Proteins Using Sequential Fermentation - PMC - NIH, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12785252/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12785252/)  
63. Controlling Off-Odors in Plant Proteins Using Sequential Fermentation - PubMed, accessed March 29, 2026, [https://pubmed.ncbi.nlm.nih.gov/41517105/](https://pubmed.ncbi.nlm.nih.gov/41517105/)  
64. Application and Possible Mechanism of Microbial Fermentation and Enzyme Catalysis in Regulation of Food Flavour - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12154093/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12154093/)  
65. Comparative Analysis of Umami Substances and Potential Regulatory Genes in Six Economic Bivalves - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12732902/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12732902/)  
66. (PDF) Umami Characteristics and Taste Improvement Mechanism of Meat - ResearchGate, accessed March 29, 2026, [https://www.researchgate.net/publication/379275952_Umami_Characteristics_and_Taste_Improvement_Mechanism_of_Meat](https://www.researchgate.net/publication/379275952_Umami_Characteristics_and_Taste_Improvement_Mechanism_of_Meat)  
67. The Role of the Maillard Reaction in Plant-Based Proteins - Trilogy Flavors, accessed March 29, 2026, [https://trilogyflavors.com/the-role-of-the-maillard-reaction-in-plant-based-proteins/](https://trilogyflavors.com/the-role-of-the-maillard-reaction-in-plant-based-proteins/)  
68. Improving the Aromatic Profile of Plant-Based Meat Alternatives: Effect of Myoglobin Addition on Volatiles - PMC, accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC9265346/](https://pmc.ncbi.nlm.nih.gov/articles/PMC9265346/)  
69. Improving Freeze–Thaw Stability of High-Moisture Extruded Plant ..., accessed March 29, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12733136/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12733136/)  
70. Improving Freeze-Thaw Stability of High-Moisture Extruded Plant-Based Meat: A Synergistic Strategy Combining Glucose Oxidase, Phytase and Tamarind Gum - PubMed, accessed March 29, 2026, [https://pubmed.ncbi.nlm.nih.gov/41464975/](https://pubmed.ncbi.nlm.nih.gov/41464975/)

---